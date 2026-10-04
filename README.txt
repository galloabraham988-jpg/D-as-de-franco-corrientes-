SAMMY — GEMINI CON FALLBACK AUTOMÁTICO

Variables de Vercel:
GEMINI_API_KEY = tu clave de Google AI Studio
GEMINI_MODEL = opcional; por defecto gemini-3.8-flash

Si Gemini devuelve alta demanda, 429, 503 o capacidad temporalmente agotada,
Sammy prueba automáticamente 3.7 Flash, 3.6 Flash y 3.5 Flash-Lite.
