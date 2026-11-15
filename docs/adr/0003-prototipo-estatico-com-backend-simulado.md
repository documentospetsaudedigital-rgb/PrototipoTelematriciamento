# Protótipo estático com backend simulado no navegador

O protótipo não tem servidor nem API. Ele é um site estático publicado no GitHub Pages, e o "backend" é um módulo de repositório em memória, alimentado por dados sintéticos e persistido no `localStorage`, com um botão para restaurar os dados de demonstração. Assim os profissionais de saúde abrem um link sem instalar nada, e os monitores não gastam a pequena cota de IA com infraestrutura. O custo é que nada é compartilhado entre navegadores: cada pessoa vê o próprio estado. Também não validamos contrato de API nem autorização no servidor (RNF03), e isso fica para a implementação real.

## Opções consideradas

- MSW interceptando HTTP fictício: deixaria a API desenhada, mas com mais setup.
- json-server local: impediria a publicação estática.
