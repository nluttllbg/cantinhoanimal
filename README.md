# Cantinho Animal Pet Shop — site institucional

Site de página única (HTML5 + Tailwind CSS via CDN + JavaScript vanilla) para o
**Cantinho Animal Pet Shop**, em Cuiabá - MT.

## Como visualizar

Abra o arquivo `index.html` no navegador (duplo clique) ou use um servidor local:

```powershell
npx.cmd -y serve .
```

## Dados reais utilizados (fontes públicas)

| Dado | Valor | Fonte |
|---|---|---|
| Nome | Cantinho Animal Pet Shop | Google Maps (link fornecido) |
| Endereço | Av. Gen. Mello, 2955 — Jardim Califórnia, Cuiabá - MT, CEP 78065-800 | Instagram oficial + CNPJ |
| Coordenadas | -15.6247914, -56.0765448 | Link do Google Maps fornecido |
| Telefone | (65) 3634-4265 | Instagram/Facebook oficiais |
| WhatsApp | (65) 99675-5244 | Link da bio do Instagram oficial |
| Nota no Google | 4,0 (5 avaliações) | Diretório Petboop (dados do Google, 2026) |
| Avaliações | Mauro Brito (5★) e FGS Eventos (5★) | Google, via Petboop |
| Instagram | @cantinhoanimalcuiaba | Perfil oficial |
| Facebook | /cantinhoanimalcuia | Perfil oficial |
| Serviços | Pet shop, banho e tosa, consultório veterinário, entrega em domicílio, ração a granel, medicamentos veterinários | Instagram oficial + CNAE da empresa |
| Logo e fotos | Conteúdo publicado no perfil oficial do Instagram | Instagram oficial |

## Pontos que o proprietário deve confirmar

1. **Horário de funcionamento** — não está publicado de forma acessível nas fontes
   consultadas. O site direciona para consulta no WhatsApp/Google. Recomenda-se
   atualizar o perfil do Google e substituir o texto por uma tabela de horários.
2. **Fotos do espaço/equipe** — o Google Maps não permite extração de fotos sem API
   key. Foram usadas apenas imagens reais do perfil oficial no Instagram (nenhuma
   imagem de IA ou banco genérico). Se houver fotos da fachada/interior, basta
   colocá-las em `images/` e substituir as referências.
3. **Contagem de avaliações** — a nota 4,0/5 avaliações vem de diretório público e
   pode estar defasada em relação ao perfil atual do Google.

## Estrutura

```
cantinho-animal/
├── index.html      # site completo (Tailwind CDN + JS)
└── images/         # logo e fotos reais do perfil oficial
```
