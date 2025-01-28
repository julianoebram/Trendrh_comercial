import React from "react";
import Image from 'next/image';
import { Card } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { motion } from "framer-motion";


export default function BriefPresentation() {
  return (
    <div className="p-6 bg-gray-50 min-h-screen flex flex-col items-center justify-center">
      {/* Header */}
      <motion.div
        initial={{ opacity: 0, y: -50 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 0.8 }}
        className="text-center mb-8"
      >
        <h1 className="text-4xl font-bold text-gray-800">Sua empresa precisa de um BPO de RH</h1>
        <p className="text-gray-600 mt-2 text-lg">Dados que comprovam: eficiência, economia e transformação.</p>
      </motion.div>

      {/* Key Data Section */}
      <motion.div
        initial={{ opacity: 0, scale: 0.9 }}
        animate={{ opacity: 1, scale: 1 }}
        transition={{ duration: 0.8, delay: 0.2 }}
        className="grid grid-cols-1 md:grid-cols-3 gap-6"
      >
        <Card className="p-6 text-center">
          <h2 className="text-2xl font-semibold text-gray-800">35%</h2>
          <p className="text-gray-600 mt-2">Redução média de custos operacionais ao terceirizar o RH.</p>
        </Card>
        <Card className="p-6 text-center">
          <h2 className="text-2xl font-semibold text-gray-800">30%</h2>
          <p className="text-gray-600 mt-2">Aumento na retenção de talentos com gestão especializada.</p>
        </Card>
        <Card className="p-6 text-center">
          <h2 className="text-2xl font-semibold text-gray-800">95%</h2>
          <p className="text-gray-600 mt-2">Redução no risco de multas trabalhistas e fiscais.</p>
        </Card>
      </motion.div>

      {/* Call to Action */}
      <motion.div
        initial={{ opacity: 0, y: 50 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 0.8, delay: 0.4 }}
        className="mt-12 text-center"
      >
        <h2 className="text-2xl font-bold text-gray-800">Por que esperar?</h2>
        <p className="text-gray-600 mt-2">Empresas que já aderiram ao BPO de RH estão economizando milhões e liderando seus mercados.</p>
        <Button 
          className="mt-4 bg-indigo-600 text-white hover:bg-indigo-500"
          onClick={() => window.open("https://wa.me/5547991300957", "_blank")}
        >
          Entre em Contato pelo WhatsApp
        </Button>
      </motion.div>
    </div>
  );
}
