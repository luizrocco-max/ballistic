# Balística CBC T200 / T200 Light

Dashboard estático (HTML único, sem dependências, funciona offline e instalável como app) que estima alcance máximo, trajetória, velocidade e energia por bago dos cartuchos CBC Competition 12/70 — T200, T200 Light, C25 e Voo Hélice — com integração numérica do bago isolado em atmosfera, altura de disparo, desnível de terreno, vento e modelo de arrasto ajustáveis. Cada elemento tem um botão "?" com explicação e os números da configuração atual; um botão busca as condições reais do local (altitude, temperatura, pressão e vento) pela internet. A seção "Hélice / FAN 32" aplica o modelo à modalidade de hélice (posto a 27 m FEDECAT ou 26 m FITASC), estimando com um modelo de rosada gaussiana calibrada pelo choke quantos bagos atingem o testigo e a zona central, a energia por bago e a probabilidade de atingir o número mínimo de impactos.

## Cartuchos

| Cartucho | Código CBC | Carga | V0 | Chumbo |
|---|---|---|---|---|
| T200 7½ | 10001277 | 32 g | 400 m/s | 2,38 mm |
| T200 Light 7½ | 10001290 | 32 g | 370 m/s | 2,38 mm |
| T200 Light 8 | 10001283 | 32 g | 370 m/s | 2,29 mm |
| C25 7½ | 10002180 | 28 g | 405 m/s | 2,38 mm |
| C25 8 | 10001299 | 28 g | 405 m/s | 2,29 mm |
| Voo Hélice 7½ | 10030421 | 32 g | 415 m/s | 2,38 mm |
| Voo Hélice 8 | 10028790 | 32 g | 415 m/s | 2,29 mm |

## Fontes

- Catálogo CBC 2026/2027, linha Competition (velocidades na boca do cano, provete de 30"). Diâmetro do chumbo 7½ conforme tabela CBC; nº 8 adotado em 2,29 mm (padrão americano, não listado no catálogo).
- Loth, E. et al. (2021), coeficiente de arrasto de esfera em função do número de Mach.
- Regulamentos: FEDECAT (Reglamento Internacional FAN 32), FITASC (International Rules Helices ZZ 2026); percentuais de choke típicos (40/50/60/65/70% em 76 cm a 36,6 m).
- Open-Meteo (previsão e geocodificação) para as condições do local, consultado apenas quando o usuário pede.

## Limitações principais

- Bago isolado, esfera lisa, sem interação da rosada, sem rotação, sem vento lateral, vento uniforme com a altura, terreno tratado como degrau, sem ricochete.
- V0 do catálogo (provete de 30"); canos mais curtos, lotes e temperatura da munição alteram a velocidade real.
- Condições do local vêm de previsão meteorológica (vento a 10 m) e de um modelo de elevação, não de medição no estande.
- A lista completa está no próprio painel, em "Entenda o modelo → Observações e limitações".

## Aviso

Os valores são uma estimativa de engenharia, não um limite de contenção. Zonas de exclusão e barreiras devem seguir as normas do Exército/PF e da CBTE, com margem muito acima destes números.
