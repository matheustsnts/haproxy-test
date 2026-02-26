# HAProxy Load Balancer com Docker Compose 🚀

Este projeto implementa um balanceador de carga utilizando **HAProxy** para distribuir o tráfego entre quatro instâncias de uma aplicação web (Rosa, Vermelho, Verde e Azul).

## 🏗️ Estrutura do Docker Compose
A solução utiliza a imagem [mmumshad/simple-webapp-color](https://hub.docker.com) para demonstrar visualmente o balanceamento de carga através de cores.

### Serviços:
- **HAProxy**: Porta 80 (Entrada principal).
- **WebApps**: 4 containers rodando em instâncias isoladas com cores distintas.

## 🚀 Como Executar

1. **Subir os containers:**
   ```bash
   docker-compose up -d
   ```

2. **Acessar a aplicação:**
   Abra o navegador em [http://localhost](http://localhost). A cada atualização, o HAProxy direcionará você para uma instância de cor diferente.

## 🛠️ Tecnologias
- [Docker](https://www.docker.com)
- [HAProxy Official Image](https://hub.docker.com)
- [Git](https://git-scm.com)

---
