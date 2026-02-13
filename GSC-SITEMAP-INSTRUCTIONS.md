# Instructions pour soumettre le sitemap à Google Search Console

## ✅ Vérifications effectuées

- Sitemap accessible : https://tonsitewebpro.com/sitemap.xml ✅
- Format XML valide ✅
- Content-Type correct (application/xml) ✅
- Référencé dans robots.txt ✅
- Toutes les URLs testées et accessibles (200 OK) ✅

## 📝 Comment soumettre le sitemap dans GSC

### Méthode 1 : Soumettre via l'interface GSC (RECOMMANDÉE)

1. Aller sur https://search.google.com/search-console
2. Sélectionner la propriété **tonsitewebpro.com**
3. Dans le menu de gauche, cliquer sur **Sitemaps**
4. Dans le champ "Ajouter un sitemap", entrer : **sitemap.xml**
5. Cliquer sur **ENVOYER**

### Méthode 2 : URLs alternatives à essayer

Si la première ne fonctionne pas, essayer ces variations :

- `https://tonsitewebpro.com/sitemap.xml` (URL complète)
- `sitemap.xml` (URL relative)
- `/sitemap.xml` (chemin absolu)

### Méthode 3 : Vérifier la propriété GSC

Assurez-vous que la propriété dans GSC correspond exactement au domaine :
- Si la propriété GSC est pour **www.tonsitewebpro.com**, il faudra peut-être ajouter cette version aussi
- Si la propriété GSC est pour **tonsitewebpro.com** (sans www), c'est correct ✅

## 🔍 Diagnostic des erreurs possibles

### "Sitemap introuvable" ou "Erreur 404"

**Cause probable :** Mauvais format d'URL dans GSC

**Solution :**
1. Vérifier que vous utilisez juste `sitemap.xml` (sans https://)
2. Ou essayer avec l'URL complète : `https://tonsitewebpro.com/sitemap.xml`

### "Le sitemap contient des erreurs"

**Cause probable :** GSC n'a pas encore crawlé la nouvelle version

**Solution :**
1. Attendre 24-48h que Google recrawle
2. Ou demander une inspection d'URL dans GSC pour robots.txt

### "Propriété non vérifiée"

**Cause probable :** La propriété GSC n'est pas vérifiée

**Solution :**
1. Vérifier la propriété avec l'une des méthodes disponibles
2. Puis réessayer de soumettre le sitemap

## 📊 Après la soumission

Une fois soumis, GSC affichera :
- **En attente** : Google va crawler le sitemap
- **Succès** : X URLs découvertes (devrait être ~32 URLs)
- Délai habituel : 24-72 heures pour le premier crawl

## 🔄 Mise à jour du sitemap

Chaque fois que le sitemap est modifié :
1. GSC détectera automatiquement les changements via robots.txt
2. Ou vous pouvez "Retester le sitemap" dans l'interface GSC

## 📞 Problème persistant ?

Si après 48h le sitemap n'est toujours pas reconnu :
1. Vérifier dans GSC > Paramètres > Propriétés que l'URL correspond
2. Vérifier dans GSC > Couverture s'il y a des erreurs de crawl
3. Inspecter l'URL du robots.txt pour forcer un recrawl

---

Date de création : 2026-02-13
