// Site web de présentation style Ankaadia
import React from "react";
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";

export default function LandingPage() {
  return (
    <main className="min-h-screen bg-gray-50 text-gray-900">
      <section className="py-20 px-6 text-center max-w-4xl mx-auto">
        <h1 className="text-4xl font-bold mb-4">MedReko – Simplifiez votre reconnaissance médicale</h1>
        <p className="text-lg mb-6">
          Une plateforme tout-en-un pour les médecins internationaux : suivez vos étapes, gérez vos documents, accédez à un accompagnement clair pour exercer en Allemagne.
        </p>
        <Button className="text-lg px-6 py-2">Commencer maintenant</Button>
      </section>

      <section className="grid gap-10 p-6 md:grid-cols-2 max-w-5xl mx-auto">
        <Card>
          <CardContent className="p-6">
            <h2 className="text-2xl font-semibold mb-2">Création de profil</h2>
            <p>Renseignez vos données : pays, spécialité, niveau de langue, land souhaité…</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-6">
            <h2 className="text-2xl font-semibold mb-2">Checklist personnalisée</h2>
            <p>Une liste claire de toutes les étapes à suivre selon votre profil : traductions, envois, examens, etc.</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-6">
            <h2 className="text-2xl font-semibold mb-2">Suivi de documents</h2>
            <p>Importez et mettez à jour vos documents traduits, diplômes, CV, attestations…</p>
          </CardContent>
        </Card>

        <Card>
          <CardContent className="p-6">
            <h2 className="text-2xl font-semibold mb-2">Accompagnement</h2>
            <p>Accès à des guides, des modèles de CV, de lettres, et à une communauté d'entraide.</p>
          </CardContent>
        </Card>
      </section>

      <footer className="bg-white mt-20 text-center py-6 border-t text-sm">
        © 2025 MedReko – Made for Doctors by Doctors
      </footer>
    </main>
  );
}
