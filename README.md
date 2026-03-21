```python
class Belin7z:
    """
    Profile: Jefferson Alves
    Role: Full Stack Developer & Automation Enthusiast
    """
    def __init__(self):
        self.name: str = "Jefferson Alves"
        self.role: str = "Developer Self Bot"
        self.stack: list[str] = ["Python", "Django", "JavaScript", "PostgreSQL"]
        self.foco: str = "Sistemas de Gestão e Análise de Dados"
        self.objetivo: str = "Soluções eficientes, seguras e escaláveis"
        self.status: str = "🚀 Desenvolvendo por hobby & profissionalmente"

    def get_contact(self) -> dict:
        return {
            "Open to": ["Open Source", "Collaborations", "Freelance"],
            "Availability": "Remote / Worldwide"
        }

    def __str__(self) -> str:
        return f"🖥 {self.name} | {self.role} | {self.status}"

# Instanciando o perfil
eu = Belin7z()

if __name__ == "__main__":
    print(eu)
    # Output: 🖥 Jefferson Alves | Developer Self Bot | 🚀 Desenvolvendo por hobby & profissionalmente
```
