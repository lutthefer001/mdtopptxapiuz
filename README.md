# markdown-reveal-pptx-api

Markdown → RevealJS HTML → PowerPoint `.pptx` converter. **Butun kod bitta `main.py` faylida.**

## Xususiyatlar

- ✅ 12 ta RevealJS theme (black, white, dracula, ...)
- ✅ 16:9 va 4:3 aspect ratio
- ✅ Xavfsiz SVG embed (XSS himoyasi)
- ✅ RevealJS fragment syntax (`<!-- .element: class="fragment" -->`)
- ✅ Code highlighting
- ✅ To'g'ridan-to'g'ri PPTX export (python-pptx)
- ✅ Vercel serverless deploy

## Tezkor Boshlash

```bash
# 1. Virtual muhit
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 2. Dependency
pip install -r requirements.txt

# 3. Ishga tushirish
python main.py

# 4. Brauzer: http://localhost:8000/docs