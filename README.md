# Tiny BH · prévia para testadores

Belo Horizonte inteira em um mapa isométrico em pixel art, onde moradores e turistas descobrem lugares e empresas se apresentam.

Esta prévia cobre o **Centro-Sul de BH**: Centro, Santa Efigênia, Funcionários, Savassi, Lourdes e Serra.

## Como testar

Abra o link do GitHub Pages deste repositório e experimente:

1. Arrastar e dar zoom no mapa.
2. Buscar um lugar (ex.: "hospital", "padaria", "farmácia").
3. Filtrar por categoria.
4. Abrir a ficha de um lugar e usar "Como chegar".
5. Em "Minha casa", marcar um ponto no mapa e mudar o raio.
6. Trocar para "Bem-vindo, Turista" e ver o roteiro a pé.
7. Tocar no clima (canto superior direito) e trocar entre clima ao vivo, chuva, tempestade, dia e noite.
8. Passar o mouse pelo mapa e ver o efeito tilt-shift (desfoque nas bordas, foco onde o mouse está). Ajuste a força em ⚙ Configurações.
9. Esperar o aviãozinho (faixa "Anuncie aqui") e o helicóptero (faixa "Sua marca aqui") e clicar neles.
10. Usar os cartões dos pontos turísticos (embaixo no computador, em cima no celular).
11. Abrir ⚙ Configurações: minimapa, vida no mapa, contorno do bairro e idioma PT/EN.
12. Atalhos: `/` busca, `M` minimapa, `B` contorno do bairro, `D` tilt-shift, `T` modo turista, `0` bairro inteiro, `+` e `−` zoom, `Esc` fecha.
13. Usar o botão de compartilhar: o link guarda o ponto e o zoom exatos do mapa.
14. Abrir o **Passeio vivo**: digitar saída e chegada (lugar, rua ou "Minha casa"), marcar no mapa (ou abrir um lugar e tocar em "Passeio até aqui"), mexer nos controles de verde, ruas calmas, cafés, cultura e minutos a mais, e comparar as rotas.
15. Testar no celular.

## Envie seu retorno

Abra uma *issue* neste repositório contando o que funcionou, o que travou e o que faltou. Diga também o aparelho e o navegador.

## Observações

- O espaço publicitário do avião ainda não está à venda; o contato comercial aparece como "em breve".
- Planos "Destaque" e "Selo Bem-vindo, Turista" que aparecem em alguns lugares são simulações; nenhuma empresa é cliente.
- Lugares vêm do OpenStreetMap e podem estar incompletos ou desatualizados.
- O clima ao vivo vem do Open-Meteo (open-meteo.com), atualizado a cada 15 minutos.
- Base: Prefeitura de BH/Prodabel (edificações e ortofoto 2015, CC-BY). Lugares, ruas e limites: © OpenStreetMap contributors.

## Contato comercial

O contato que aparece no painel "Anuncie" e nas fichas ("É o seu negócio?") fica em `dados/contato.json`:

```json
{
  "whatsapp": "+55 31 99999-0000",
  "email": "comercial@tinybh.com.br",
  "instagram": "@tinybh"
}
```

Deixe vazio (`""`) o canal que não quiser mostrar. Sem nenhum canal preenchido, aparece "Contato comercial: em breve."

## Fontes e licenças

- Prédios e foto aérea: Prefeitura de Belo Horizonte / Prodabel, conjuntos "Edificação" e "Ortofoto 2015" (Creative Commons Atribuição).
- Ruas, lugares e limites: © colaboradores do OpenStreetMap (ODbL).
- Pintura em pixel art: FLUX.2 [klein] 4B (Apache 2.0).
