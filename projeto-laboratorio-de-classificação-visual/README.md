# 👁️ Treinando IA para Aprender com Imagens: Análise de Viés e Visão Computacional

## 📝 Descrição do Projeto
Este projeto foi desenvolvido com o objetivo de explorar os conceitos práticos de visão computacional, classificação de imagens e mitigação de vieses em algoritmos de Inteligência Artificial. Utilizando a plataforma **Teachable Machine (by Google)**, foi construído e treinado um modelo supervisionado capaz de classificar expressões faciais em tempo real, dividindo-as entre duas categorias distintas: "Não está sorrindo" e "Está sorrindo".

Mais do que a execução técnica, o experimento propõe uma reflexão aprofundada sobre como a seleção restrita de dados impacta a generalização do modelo e perpetua comportamentos discriminatórios ou ineficazes no software final.

## 🔗 Link do Projeto
O modelo treinado e a interface de testes podem ser acessados publicamente através do link:
* [Teachable Machine Model](https://teachablemachine.withgoogle.com/models/z_POtsF5G/)

## 🚀 Tecnologias e Ferramentas Utilizadas
* **Plataforma de ML:** Teachable Machine (Google)
* **Ambiente de Execução:** Web / Visão Computacional Baseada em Câmera (Webcam)
* **Conceitos Chave:** Classificação Supervisionada, Viés de Dados (Bias), Abordagem Human-in-the-loop.

---

## 🧠 Análise Crítica e Aprendizados

### ⚖️ Mecanismo do Viés
A seleção restrita ou homogênea de dados de treinamento vai além de causar um simples erro técnico momentâneo. Ela embute uma ideologia e uma visão limitada diretamente no código fonte. Quando isso ocorre, o algoritmo passa a validar e aprender apenas os padrões apresentados, tendendo a ignorar ou classificar incorretamente qualquer variação externa. Como consequência, o sistema passa a tratar a diversidade natural das experiências humanas como se fossem um "erro" ou uma "exceção".

### ⚠️ Consequência Social no Software
Modelos enviesados geram falhas críticas de consistência em produção. Variações simples no ambiente operacional — como o nível de luminosidade (ambientes mais claros ou mais escuros) — alteram diretamente o resultado preditivo das classes de imagem. Esse tipo de comportamento instável quebra a confiabilidade do produto, deixando o usuário desconfiado, frustrado e inseguro quanto à eficácia do ecossistema de software.

### 🛠️ Ação Mitigatória: Human-in-the-loop
Para sanar e prevenir esses desvios em sistemas de produção, adota-se a abordagem estratégica de **Human-in-the-loop (Humanos no Ciclo)**. Isso envolve:
* Estabelecer auditorias e revisões constantes das amostras de dados coletadas.
* Implementar uma validação humana rigorosa sobre os resultados preditivos das IAs.
* Manter equipes dedicadas a rastrear, identificar e corrigir ativamente as anomalias e erros do classificador.

Esta governança técnica garante um ganho substancial na qualidade e precisão do algoritmo, estruturando um sistema robusto que funciona de forma justa e consistente.

## 👥 Autores do Projeto
* **Felipe Henrique Duranes Rodrigues** — RGM: 48139181
* **Vitor da Silva Bonilha** — RGM: 48123005

---
[⬅️ Voltar ao início](https://github.com/seu-usuario/Tecnologia-Heimirich)
