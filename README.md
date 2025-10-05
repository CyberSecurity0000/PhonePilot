# PhonePilot 🚦

![Aviso](https://img.shields.io/badge/Usage-Educational%20Only-red)

**PhonePilot** — automação educacional para descoberta de contatos em páginas web (scraper).  
**Uso:** fins educacionais e testes autorizados apenas. Não usar para spam, marketing ou invasão de privacidade.

---

## Conteúdo deste arquivo (tudo em 1 só)
- Instalação (virtualenv + requirements)
- Geração do script `phone_pilot.py` (here-doc)
- Comandos para gerar `requirements.txt` e `LEGAL.md` (se necessário)
- Execução e exemplos
- Aviso legal / LEGAL

---

## 1) Instalação rápida

Recomendado: criar virtualenv e instalar dependências.

```bash
# criar e ativar venv (Linux/macOS)
python3 -m venv venv
source venv/bin/activate

# Windows (PowerShell)
# python -m venv venv
# .\venv\Scripts\Activate.ps1

# instalar dependências (se você já tem requirements.txt)
pip install -r requirements.txt
