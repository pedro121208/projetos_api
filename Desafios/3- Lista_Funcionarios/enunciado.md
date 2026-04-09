# 👥 Desafio 3: Lista de Funcionários (Random User)

Simulação de um sistema corporativo real. Vai receber um JSON muito rico e profundo em detalhes, precisando de navegar por vários níveis (Objetos dentro de Objetos) para extrair o que precisa.

**A sua missão:**
1. Consulte a API: `https://randomuser.me/api/?results=6` (O parâmetro final define que queremos 6 pessoas).
2. Para cada pessoa gerada, construa um painel na interface que mostre:
   - A fotografia grande (`picture.large`)
   - O Nome Completo (É preciso juntar `name.first` + `name.last`)
   - O País (`location.country`)
   - O Email (`email`) usar href "#" para o clique não chamar nenhum aplicativo.
3. Preste muita atenção à estrutura do JSON recebido. O array principal fica dentro da propriedade `results`.