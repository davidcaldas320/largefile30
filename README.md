# 🏎️ Racha Urbana em 3D - Projeto Blender

> **Status:** Versão Acadêmica Concluída ✅  
> *O projeto atende a todos os critérios avaliativos da disciplina, com foco em rigging e animação. Melhorias futuras em texturização e iluminação estão previstas para evolução do portfólio.*

---

<p align="center">
</p>
<img width="782" height="872" alt="Captura de tela_22-4-2026_155243_" src="https://github.com/user-attachments/assets/8656e9a8-1183-4326-92c6-9bb1e719ffdd" />

<br><i>Render Final: Simulação de Racha Urbana em 3D</i>



Este projeto é uma simulação cinematográfica de um racha urbano, focada em técnicas avançadas de animação automotiva, rigging técnico e iluminação realista. Desenvolvido como trabalho final para a disciplina de **Computação Gráfica e Realidade Virtual**, o projeto demonstra o pipeline completo de produção 3D.

## 🎯 Objetivo e Visão Geral

O objetivo deste projeto foi criar uma cena de drift realista inspirada na cultura pop e em jogos como *Forza Horizon 5*, explorando a física de movimento de um veículo e a criação de um ambiente urbano imersivo.

**Foco principal do aprendizado:**
* **Cinemática Automotiva:** Como um carro se inclina em curvas e como as rodas reagem ao solo.
* **Fotorrealismo:** Aplicação de materiais PBR e iluminação cinematográfica.

---

## 🛠️ Tecnologias e Ferramentas

Para alcançar esse nível de detalhe, utilizamos o que há de mais moderno no ecossistema 3D:

| Ferramenta | Uso no Projeto |
| :--- | :--- |
| **Blender 4.x** | Modelagem, Animação e Renderização |
| **Cycles Engine** | Renderização de alta fidelidade com Ray Tracing |
| **Rigacar Addon** | Sistema complexo de suspensão e direção do veículo |
| **Quixel Bridge** | Texturas fotorrealistas de asfalto e calçada |
| **Poly Haven** | HDRIs para iluminação global realista |

---

## 🚀 O que foi desenvolvido? (Passo a Passo)

### 1. Rigging Técnico do Veículo
O carro utiliza o addon **Rigacar**, que automatiza comportamentos físicos reais:
* **Suspensão Independente:** O chassi inclina conforme o movimento.
* **Giro Automático:** As rodas giram proporcionalmente à velocidade e direção.
* **Nomenclatura:** Seguimos o padrão técnico (ex: `wheel.fl`, `body`) para garantir a funcionalidade do rig.

<p align="center">
  <img width="1600" height="844" alt="rigcar" src="https://github.com/user-attachments/assets/548f5e07-4fc1-4954-afbd-d2e1f49ff196" />



  <br><i>Demonstração da estrutura de Rigging e bones do veículo.</i>
</p>

### 2. Iluminação e Ambiente
A cena simula uma noite urbana imersiva utilizando:
* **Emissives:** Para faróis de carros e luzes da cidade.
* **HDRI:** Para reflexos dinâmicos e precisos na pintura metálica.
* **Shader Principled BSDF:** Para metais, vidros e pneus realistas.

<p align="center">
  <img width="1531" height="731" alt="render" src="https://github.com/user-attachments/assets/eddbc421-d1b0-46c6-8039-c7104961a908" />
  <br><i>Configuração de materiais e iluminação noturna.</i>
</p>

### 3. Câmera e Renderização
* **Câmera Dinâmica:** Utilizamos tomadas de perseguição e lateral para uma estética cinematográfica.
* **Alta Performance:** Configurado em **60 FPS** em Full HD para fluidez máxima.
* **Desafio:** O processo de renderização totalizou mais de **16 horas** para garantir a fidelidade visual.

---

## 👥 Autores
* **David Teixeira Ferreira Caldas**
* **Kaion Murilo Laurentino Rodrigues**

---

## 📚 Referências Utilizadas

* **Poly Haven** - Plataforma para assets 3D de alta qualidade, incluindo HDRIs, texturas e modelos.
* **Quixel Bridge** - Biblioteca robusta de assets 3D fotorrealistas e ferramentas para integração em projetos 3D.
* **BlenderKit** - Addon e biblioteca integrada ao Blender, oferecendo modelos, materiais e pincéis.
* **CGTrader** - Marketplace para modelos 3D, ideal para encontrar assets específicos e de alta qualidade.
* **Blender Manual** - Documentação oficial do Blender, recurso essencial para o aprendizado e solução de problemas técnicos.
* **DigiCreatures (Rigacar)** - Documentação e recursos para o addon Rigacar, facilitando o rigging de veículos no Blender.

As referências listadas foram fundamentais para a execução e aprimoramento deste projeto, fornecendo desde assets 3D de alta qualidade até o suporte técnico necessário.
