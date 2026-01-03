hugo server --bind 0.0.0.0 --port 8080 --appendPort=false --liveReloadPort=443


echo "# audif-store" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/adschexp/audif-store.git
git push -u origin main





5. Consideraciones para una Tienda en Hugo
ElementoSolución RecomendadaPagosSnipcart (fácil integración con HTML) o Stripe Checkout.
InventarioArchivos de datos (data/products.toml) o un CMS decapitado (Decap CMS).
BuscadorAlgolia o Pagefind (específico para sitios estáticos).
FormulariosNetlify Forms (si usas su proxy) o Formspree.