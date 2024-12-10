# Econecta 🌍  
**Facilitando a gestão de resíduos sólidos com tecnologia, sustentabilidade e inovação.**

---

## 🚀 Sobre o Projeto  
O **Econecta** é um sistema inovador que conecta descartantes de resíduos sólidos a coletores, promovendo práticas sustentáveis e eficientes. Utilizamos tecnologias avançadas, como blockchain e inteligência artificial, para oferecer transparência, rastreabilidade e uma experiência otimizada para os usuários.

---

## Funcionalidades
### 1. Otimização de Rotas
- Utiliza a API do Google Maps em conjunto com algoritmos de otimização para calcular as melhores rotas baseadas nas demandas aceitas pelos coletores.

### 2. Previsão de Demanda
- Analisa o histórico de transações para prever picos de demandas em épocas específicas, ajudando na alocação eficiente de recursos.

### 3. Chatbot de Atendimento
- Oferece suporte 24/7 para responder perguntas frequentes e auxiliar os usuários.

### 4. Sistema de Recomendação
- Identifica clientes próximos às rotas agendadas, enviando lembretes para que organizem e realizem o descarte.

### 5. Rastreamento por Blockchain
- Garante transparência e segurança no registro das transações e no acompanhamento do ciclo de vida dos resíduos.

---

## 🛠️ Tecnologias Utilizadas  

### **Backend**  
#### **Java com Spring Boot**  
- Framework robusto para criar APIs RESTful.  
- Gerenciamento de dependências facilitado com Maven.  
- Camadas organizadas para controle, serviço e repositório.  
- **Principais funcionalidades**:  
  - Endpoints para cadastro, atualização e rastreamento de demandas.  
  - Integração com blockchain e serviços do Google Cloud.  

#### **MySQL**  
- Banco de dados relacional para armazenar informações de usuários, demandas e resíduos.  
- Design eficiente com normalização para evitar redundâncias.  
- **Vantagens**:  
  - Alta confiabilidade e suporte a grandes volumes de dados.  
  - Fácil integração com JPA/Hibernate no Spring Boot.  

#### **Hyperledger Fabric**  
- Plataforma blockchain para rastreabilidade das demandas.  
- Permite criar redes privadas de blockchain, garantindo segurança e transparência.  
- **Funcionalidades implementadas**:  
  - Registro de cada transação de demanda no blockchain.  
  - Rastreamento imutável para todas as partes envolvidas.  

### **Frontend**  
#### **Jetpack Compose (Kotlin)**  
- Framework moderno e declarativo para criar a interface do aplicativo móvel.  
- **Principais características**:  
  - Interface rica e responsiva.  
  - Facilita a reutilização de componentes como botões, listas e telas.  
- **Por que escolhemos Kotlin?**  
  - Integração nativa com o Android.  
  - Sintaxe concisa e mais segura.  

### **Inteligência Artificial (IA)**  
#### **Google Cloud AI**  
- Ferramentas da Google Cloud usadas para implementar funcionalidades de IA:  
  - **Chatbot de atendimento**:  
    - Respostas automatizadas 24/7.  
    - Treinado para responder dúvidas frequentes sobre descarte de resíduos.  
  - **Previsão de demandas**:  
    - Análise do histórico de demandas para prever picos em certas épocas.  

### **APIs Externas**  
#### **Google Maps Platform**  
- Integração com a API Directions para otimização de rotas.  
- Cálculo de rotas baseado na localização dos descartantes e dos coletores.  
- Reduz o consumo de combustível e o tempo de coleta.  

---

## 🌐 Como Executar  

### Pré-requisitos  
1. **Java 17** ou superior instalado.  
2. **Kotlin** configurado para o desenvolvimento do aplicativo.  
3. **Docker** para executar o Hyperledger Fabric.  
4. Conta no **Google Cloud** para configurar as APIs.  

### Passos  
1. Clone o repositório:  
   ```bash  
   git clone https://github.com/seuusuario/econecta.git  
