# Diagnostic olfactif — démo

Module de quiz parfum à greffer sur une boutique **Shopify** (section Liquid, thème Dawn) ou **WordPress / WooCommerce** (shortcode, bloc Gutenberg ou Elementor).

Démo interactive : boutique fictive, quiz en 8 questions, profil olfactif, 3 recommandations, capture e-mail RGPD, badges de compatibilité sur la collection, données envoyées au CRM.

## Liens prêts à envoyer

Ajoutez des paramètres à l'URL de la démo pour l'adapter au prospect :

| Paramètre | Valeurs | Effet |
|---|---|---|
| `pf` | `shopify` · `woo` | Plateforme affichée |
| `ch` | `marbre` · `nuit` · `atelier` | Charte de la boutique fictive |
| `vue` | `donnees` · `offre` | Ouvre directement un onglet |
| `quiz` | `1` | Ouvre le diagnostic au chargement |
| `offre` | `0` | Masque l'onglet des tarifs |

Exemples :

- Prospect Shopify, ambiance sombre : `?pf=shopify&ch=nuit`
- Prospect WooCommerce, sans les prix : `?pf=woo&ch=atelier&offre=0`
- Montrer la donnée collectée : `?vue=donnees`

---
Développé par Monsieur.H — Les Monsieurs by Monsieur.H
