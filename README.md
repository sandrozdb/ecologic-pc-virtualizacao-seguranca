<p align="center"><img src="assets/cover.svg" alt="Ecologic PC — Virtualização e Segurança" width="100%"></p>

# Ecologic PC — Casemod com Virtualização e Segurança

Projeto acadêmico que integrou reaproveitamento de hardware, virtualização, redes de computadores e práticas introdutórias de segurança em um ambiente controlado.

## Problema

O estudo de infraestrutura, sistemas operacionais e segurança exige um ambiente em que configurações e testes possam ser realizados sem afetar máquinas ou redes externas.

## Objetivo

Construir um computador customizado e utilizá-lo como base para um laboratório virtualizado, permitindo experimentar sistemas operacionais, conectividade e administração de redes com isolamento.

## Solução desenvolvida

O computador físico recebeu o VirtualBox e ambientes Windows e Kali Linux. As máquinas virtuais formaram uma rede de testes controlada para exercícios de comunicação, configuração e observação do ambiente.

```mermaid
flowchart TD
    A[Ecologic PC] --> B[VirtualBox]
    B --> C[Ambiente Windows]
    B --> D[Ambiente Kali Linux]
    C <--> E[Rede virtual isolada]
    D <--> E
    E --> F[Testes controlados]
```

## Arquitetura virtualizada

![Arquitetura virtualizada genérica](assets/arquitetura-virtualizada.svg)

O diagrama utiliza nomes e endereços fictícios. Ele explica o funcionamento conceitual sem reproduzir configurações potencialmente sensíveis.

## Atividades documentadas

- montagem e organização de um computador customizado;
- criação e gerenciamento de máquinas virtuais;
- instalação e uso de Windows e Kali Linux;
- configuração de uma rede virtual de laboratório;
- verificação de conectividade entre ambientes;
- observação de serviços e fundamentos de segurança;
- administração básica de sistemas operacionais.

## Tecnologias

- VirtualBox
- Windows
- Kali Linux
- virtualização
- redes TCP/IP
- administração de sistemas
- segurança da informação

Python e SQL não são atribuídos ao projeto, pois não há confirmação de uso.

## Segurança

O repositório não contém credenciais, endereços reais, exploração de sistemas, dados de terceiros ou instruções ofensivas. Os exemplos são limitados a um laboratório autorizado e isolado.

## Organização

```text
├── assets/                         # capa e arquitetura visual
├── docs/
│   ├── ambiente-virtualizado.md
│   ├── laboratorio-seguranca.md
│   └── resultados-e-aprendizados.md
├── SECURITY.md
├── LICENSE
└── README.md
```

## Limitações

- os arquivos e registros originais de 2024 não estão disponíveis;
- versões, componentes físicos e parâmetros exatos não são declarados sem evidência;
- a arquitetura visual é uma reconstrução genérica;
- não são apresentados resultados quantitativos não medidos.

## Melhorias futuras

- recriar o laboratório em um simulador documentado;
- registrar configurações reproduzíveis e anonimizadas;
- incluir testes defensivos automatizados;
- comparar modos de rede do VirtualBox;
- monitorar recursos utilizados pelas máquinas virtuais.

## Competências desenvolvidas

Infraestrutura de TI, virtualização, redes, sistemas operacionais, documentação técnica, segurança da informação e resolução de problemas.

## Autor

**Sandro Ferreira**

[LinkedIn](https://www.linkedin.com/in/sandrozdb/) · [GitHub](https://github.com/sandrozdb)

## Licença

Distribuído sob a licença MIT. Consulte [LICENSE](LICENSE).
