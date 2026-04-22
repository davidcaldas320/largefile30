**# 🏎️ Racha Urbana em 3D - Projeto Blender

> **Status:** Versão Acadêmica Concluída ✅  
> *O projeto atende a todos os critérios avaliativos da disciplina, com foco em rigging e animação. Melhorias futuras em texturização e iluminação estão previstas para evolução do portfólio.*

[cite_start]Este projeto é uma simulação cinematográfica de um racha urbano, focada em técnicas avançadas de animação automotiva, rigging técnico e iluminação realista[cite: 4]. [cite_start]Desenvolvido como trabalho final para a disciplina de **Computação Gráfica e Realidade Virtual**, o projeto demonstra o pipeline completo de produção 3D[cite: 6, 98].

---

## 🎥 Demonstração
*(Substitua o link abaixo pelo link do seu vídeo no YouTube ou o arquivo do vídeo)*
[▶️ Assista ao vídeo da animação final aqui](SUU_LINK_AQUI)

---

## 🎯 Objetivo e Visão Geral
[cite_start]O objetivo deste projeto foi criar uma cena de drift realista inspirada na cultura pop e em jogos como *Forza Horizon 5*, explorando a física de movimento de um veículo e a criação de um ambiente urbano imersivo[cite: 23, 89].

**Foco principal do aprendizado:**
* [cite_start]**Cinemática Automotiva:** Como um carro se inclina em curvas e como as rodas reagem ao solo[cite: 58, 68].
* [cite_start]**Fotorrealismo:** Aplicação de materiais PBR e iluminação cinematográfica[cite: 30, 31, 39].

---

## 🛠️ Tecnologias e Ferramentas
[cite_start]Para alcançar esse nível de detalhe, utilizamos o que há de mais moderno no ecossistema 3D[cite: 35, 125]:

| Ferramenta | Uso no Projeto |
| :--- | :--- |
| **Blender 4.x** | [cite_start]Modelagem, Animação e Renderização [cite: 3] |
| **Cycles Engine** | [cite_start]Renderização de alta fidelidade com Ray Tracing [cite: 78] |
| **Rigacar Addon** | [cite_start]Sistema complexo de suspensão e direção do veículo [cite: 43] |
| **Quixel Bridge** | [cite_start]Texturas fotorrealistas de asfalto e calçada [cite: 40, 120] |
| **Poly Haven** | [cite_start]HDRIs para iluminação global realista [cite: 38, 119] |

---

## 🚀 O que foi desenvolvido? (Passo a Passo)

### 1. Rigging Técnico do Veículo
[cite_start]O carro utiliza o addon **Rigacar**, que automatiza comportamentos físicos reais[cite: 42, 60]:
* [cite_start]**Suspensão Independente:** O chassi inclina conforme o movimento[cite: 46].
* [cite_start]**Giro Automático:** As rodas giram proporcionalmente à velocidade e direção[cite: 44, 47].
* [cite_start]**Nomenclatura:** Seguimos o padrão técnico (ex: `wheel.fl`, `body`) para garantir a funcionalidade do rig[cite: 50, 56].

### 2. Iluminação e Ambiente
[cite_start]A cena simula uma noite urbana imersiva utilizando[cite: 38, 88]:
* [cite_start]**Emissives:** Para faróis de carros e luzes da cidade[cite: 38].
* [cite_start]**HDRI:** Para reflexos dinâmicos e precisos na pintura metálica[cite: 31, 88].
* [cite_start]**Shader Principled BSDF:** Para metais, vidros e pneus realistas[cite: 39, 40].

### 3. Câmera e Renderização
* [cite_start]**Câmera Dinâmica:** Utilizamos tomadas de perseguição e lateral para uma estética cinematográfica[cite: 75, 87].
* [cite_start]**Alta Performance:** Configurado em **60 FPS** em Full HD para fluidez máxima[cite: 76, 78].
* [cite_start]**Desafio:** O processo de renderização totalizou mais de **16 horas** para garantir a fidelidade visual[cite: 78, 113].

---

## 👥 Autores
* [cite_start]**David Teixeira Ferreira Caldas** [cite: 5]
* [cite_start]**Kaion Murilo Laurentino Rodrigues** [cite: 5]

---

## 📚 Referências
* [cite_start]Blender Manual [cite: 123]
* [cite_start]DigiCreatures (Rigacar) [cite: 124]
* [cite_start]BlenderKit, CGTrader e Quixel Bridge [cite: 121, 122]**
