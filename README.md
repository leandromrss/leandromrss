## Sobre mim
 
```javascript
class LeandroMoraes {
    constructor() {
        this.name = "Leandro Moraes";
        this.education = "Redes de Computadores - Estácio";
        this.techStack = ["JavaScript", "HTML", "CSS",];
        this.currentFocus = "Arquitetura FrontEnd";
    }
 
    aboutMe() {
        return `
        👨‍💻 ${this.name}
        📚 ${this.education}
        💻 Stack: ${this.techStack.join(" | ")}
        🎯 Focus: ${this.currentFocus}
        ✨ Motto: "Código Limpo > Código Inteligente"
        `;
    }
}
 
const dev = new LeandroMoraes();
console.log(dev.aboutMe());
```
