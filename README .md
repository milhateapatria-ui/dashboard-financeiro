# Controle de Gastos da Empresa

Dashboard de gastos feito com um único arquivo HTML (`index.html`), sem instalação e sem servidor.

## O que ele controla

- Combustível (gasolina, etanol, diesel), hospedagem, alimentação, pedágios, multas e mercado
- Peças Ranger e peças quadriciclo
- Escritório (folhas, tinta de impressão, fichário, serviços de administração)
- Contas fixas: aluguel de prédio, energia, água, faxineira e internet
- Cartão usado em cada compra, com limite e fatura do mês

## Contas fixas e avisos no WhatsApp

1. Em **Configurações**, informe o número do WhatsApp que recebe os avisos (com DDD).
2. Em **Contas fixas**, cadastre cada conta com o dia do vencimento e quantos dias antes quer ser avisado.
3. Quando uma conta estiver perto de vencer ou atrasada, aparece um aviso no topo do dashboard e um contador no menu.
4. O botão do WhatsApp abre a conversa com a mensagem pronta. Basta tocar em enviar.
5. Ao pagar, use o botão **Pagar**: o lançamento já vem preenchido e a conta passa para o mês seguinte.

O envio é feito por você, ao tocar no botão. Mensagens automáticas, sem abrir o dashboard, precisam de um serviço externo (API do WhatsApp).

## Como usar

1. Abra o `index.html` no navegador.
2. Cadastre os cartões em **Cartões > + Novo cartão**.
3. Registre cada compra em **+ Novo lançamento**.

Os dados ficam salvos no navegador (localStorage). Use **Configurações > Salvar backup** para guardar uma cópia.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie os arquivos `index.html` e `README.md`.
2. Vá em **Settings > Pages**.
3. Em **Branch**, escolha `main` e a pasta `/ (root)`, e clique em **Save**.
4. O endereço aparece em alguns minutos: `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

Importante: os dados ficam no navegador de cada pessoa. Quem abrir o link verá o dashboard vazio e só enxergará o que lançar naquele aparelho.
