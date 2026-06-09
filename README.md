# Contador de Pizza Online

Um contador visual de fatias de pizza para competir com amigos! Adicione participantes, controle as fatias de cada um e veja as pizzas completas ficarem opacas enquanto novas pizzas são criadas.

## 🎮 Demonstração

[Teste online](https://kmeliuskas.github.io/Contador_de_Pizza_Online/)

## ✨ Funcionalidades

- **Múltiplos participantes**: Adicione quantas pessoas quiser ao jogo
- **Contador de fatias**: Cada participante tem seu próprio contador (1 a infinito)
- **Visualização em pizzas**: Cada pizza tem 6 fatias - quando completa, aparece opaca
- **Responsivo**: Layout adaptado para mobile, tablet e desktop
- **Limite de exibição**: Mostra até 2/3/4 pizzas por tela (dependendo do dispositivo)
- **Indicador ...**: Mostra "..." quando há mais pizzas que o limite visível

## 📱 Responsividade

| Dispositivo | Pizzas visíveis |
|-------------|-----------------|
| Mobile < 576px | 2 pizzas |
| Tablet < 768px | 2-3 pizzas |
| Desktop < 992px | 3-4 pizzas |
| Desktop > 1200px | 4 pizzas |

## 🛠️ Tecnologias

- HTML5
- CSS3 (Flexbox, Media Queries)
- JavaScript (ES6+)
- Font Awesome (ícones)
- Google Fonts (Poppins)

## 🎯 Como usar

1. Digite o nome do participante
2. Clique em "Adicionar"
3. Use +/− para controlar as fatias de cada pessoa
4. Quando completar 6 fatias, a pizza ficará opaca (pizza completa)
5. Excedentes começam uma nova pizza

## 📂 Estrutura

```
/
├── index.html
├── css/
│   └── estilo.css
├── js/
│   └── jQuery-3.7.1.js
└── img/
    ├── fatia-pizza.png
    └── fatia-pizza2.png
```

## 🤝 Contribuição

Fork o projeto, crie sua branch e abra um Pull Request.

## 👤 Autor

Matteo Kmeliuskas