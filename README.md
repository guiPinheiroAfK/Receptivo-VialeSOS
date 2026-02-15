# 🚐 ReceptivoPro - Intelligence for Tourism

O **ReceptivoPro** é um sistema de back-office desenvolvido para agências de turismo receptivo que buscam automatizar a operação de campo. O sistema centraliza reservas, organiza a logística de passageiros e gera manifestos de transporte de forma inteligente.

## 🛠️ Tecnologias Principais
* **Backend:** Java 21 + Spring Boot 3.3+
* **Persistência:** Spring Data JPA + PostgreSQL
* **Segurança:** Spring Security & JWT
* **Documentação:** Swagger/OpenAPI

## 🎯 Funcionalidades Chave
- **Gestão de Reservas:** Importação e lançamento de PAX com suporte multi-moeda (BRL, USD, PYG).
- **Logística Inteligente:** Agrupamento automático de passageiros por hotéis e roteiros (Pick-up).
- **Manifesto de Transporte:** Geração automática de listas para fiscalização internacional (Brasil/Paraguai/Argentina).
- **Controle de Status:** Dashboard em tempo real para monitorar embarques e serviços pendentes.
- **Módulo Financeiro:** Cálculo automático de comissões e faturamento de agências parceiras.

## 🚀 Como Executar o Projeto
1. Certifique-se de ter o **JDK 21** e o **Maven** instalados.
2. Clone o repositório:
   ```bash
   git clone https://github.com/guiPinheiroAfK/Receptivo-VialeSOS.git
3. **Execução:**
   ```bash
   mvn clean install
   mvn spring-boot:run
