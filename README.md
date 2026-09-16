# 🎭 Automação de Matrículas & Gestão de Pagamentos — Oficinas de Teatro 2026

![Make](https://img.shields.io/badge/Make-0052CC?style=for-the-badge&logo=make&logoColor=white)
![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)

Sistema automatizado de processamento de inscrições, geração de cobranças via Pix/Cartão e conciliação bancária em tempo real para oficinas culturais, desenvolvido na plataforma **Make (Integromat)** com integração direta à **API do Mercado Pago** e **Google Sheets**.

---

## 📌 Visão Geral do Projeto

O objetivo desta solução é automatizar todo o funil de matrícula de alunos, desde o preenchimento do formulário inicial até a confirmação do pagamento da taxa de inscrição, eliminando conferências manuais e reduzindo o tempo de resposta ao aluno.

O projeto é dividido em dois cenários complementares:

1. **Cenário 1 (Inscrição & Cobrança):** Captura novas respostas na planilha, gera um link de checkout dinâmico no Mercado Pago e dispara o e-mail com as instruções de pagamento.
2. **Cenário 2 (Webhook & Conciliação):** Escuta notificações instantâneas do Mercado Pago, valida a aprovação do pagamento, atualiza o status na planilha principal e envia a confirmação final com o link do grupo de avisos.

---

## 🛠️ Arquitetura do Fluxo
