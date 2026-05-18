# SecureOffice VR: Treinamento Imersivo de Cibersegurança

## 📝 Descrição do Projeto
O **SecureOffice VR** é um projeto conceitual de um ambiente educacional imersivo em Realidade Virtual desenvolvido para a plataforma Meta Quest (Android). O objetivo do projeto é treinar funcionários corporativos a identificarem ameaças de engenharia social, Phishing e falhas de segurança física no ambiente de trabalho tradicional, aumentando engajamento e retenção do aprendizado.

> **Nota de Desenvolvimento:** Devido a limitações físicas de hardware local para a execução estável do Unity Editor e renderização em tempo real do Meta XR SDK, este repositório armazena o planejamento técnico, documentação de arquitetura e especificação de engenharia do software para a atividade avaliativa da Residência em TIC 29.

---

## 🛠️ Especificações Técnicas Planejadas

* **Engine:** Unity 6000.3.9f1 LTS (Garante suporte de longo prazo e estabilidade).
* **SDK:** Meta XR All-in-One SDK (Via Package Manager).
* **Plataforma Alvo:** Android (Meta Quest 2 / Quest 3).
* **Texture Compression:** ASTC.
* **Mapeamento de Input no Editor:** XR Meta Simulator (Para testes com mouse e teclado via PC).

---

## 📂 Estrutura de Pastas Proposta para o Projeto

```text
/SecureOffice-VR-TIC29
│
├── /Assets
│   ├── /Audio         <- Clipes de som para feedback positivo/negativo.
│   ├── /Materials     <- Materiais e texturas otimizados para mobile.
│   ├── /Prefabs       <- Modelos 3D configurados com XR Grab Interactable.
│   ├── /Scenes        <- Cena principal: SecureOffice_Training.unity.
│   └── /Scripts       <- Lógica em C# para controle de pontuação e eventos.
│
├── /ProjectSettings   <- Configurações de build do Unity e mapeamento OpenXR.
└── .gitignore         <- Configurado para ignorar as pastas /Library e /Temp. 
```
### 🎯 Escopo dos Elementos Interativos (Assets de Cena)

* **Office_Desk:** Mesa de trabalho que serve de suporte para os cenários de teste.
* **Desktop_PC:** Monitor exibindo uma interface interativa de e-mail de Phishing.
* **Password_Note:** Post-it com uma senha exposta (Item coletável via *XR Grab Interactable*).
* **Secure_Bin:** Lixeira de descarte seguro que serve de gatilho para destruição de dados sensíveis.
* **Sound_Success:** Feedback sonoro tridimensional acionado ao mitigar um risco com sucesso.

---

### 🎓 Identificação

* **Estudante:** João Lucas
* **Curso:** Web 3.0 / Metaverso
* **Instituição:** Residência em TIC 29
