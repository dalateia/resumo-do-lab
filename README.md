# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

### Modelos de responsabilidade compartilhada. (Tipos de arquitetura)

Os modelos são baseados em quantas responsabilidades o serviço de nuvem terá de acordo com o serviço prestado. No caso de SaaS, praticamente tudo é gerenciado pela nuvem, e na outra extremidade, On-premises, todo o serviço é de responsabilidade da organização.

1. **SaaS** - Alta responsabilidade (Software as a Service)
2. PaaS - Média responsabilidade (Platform as a Service)
3. IaaS - Baixa responsabilidade (Infrastructure as a Service)
4. On-premises - Nenhuma responsabilidade

### Modelos de nuvem

- Nuvem privada: Serviço de nuvem da própria organização. Permite controle total, mas tem custo alto.
- Nuvem pública: Serviços como Azure,AWS e GCP. Alta disponibilidade e custo acessível.
- Nuvem híbrida: Modelo flexível e interconectado a nuvens, publica e privada.
- Multinuvem: Modelo com várias nuvens públicas (duas ou mais)

### Azure Arc

Plataforma de serviços de gerenciamento híbrido, on-premises e multinuvem da Azure. 

### **Solução VMware no Azure**

A Solução VMware no Azure permite executar suas cargas de trabalho do VMware no Azure com integração e escalabilidade total.

### Como descrever o modelo baseado em consumo

- CapEx (Despesas de capital): despesa inicial, geralmente de gasto único. (Reformas, veículo empresarial, um novo datacenter,etc)
- OpEx (Despesas operacionais): despesa recorrente, relacionado a gastos com serviços ou produtos. (Aluguel, assinaturas, internet, etc)

# **Sobre os benefícios da alta disponibilidade e da escalabilidade na nuvem**

### Alta disponibilidade

Diferenças entre SLAs 99% e 99,99% de Uptime

- Uptime - Tempo online
- Downtime - Tempo offline

### Escalabilidade

Capacidade de ajustar recursos sob demanda.

### Dimensionamento Vertical

Vertical aumenta o poder de processamento da mesma máquina.
Vertical aumenta recurso em um único nó.

### Dimensionamento Horizontal

Horizontal aumenta a quantidade de máquinas executando a mesma função.
Horizontal aumenta o número de nós no ambiente.

# Sobre **os benefícios da confiabilidade e da previsibilidade na nuvem**

## Microsoft Azure Well-Architected Framework

- Confiabilidade
- Previsibilidade
- Desempenho
- Custo

# Sobre **os benefícios da segurança e da governança na nuvem**

A computação em nuvem facilita governança e conformidade ao aplicar padrões corporativos automaticamente, auditar recursos e manter sistemas atualizados com patches e políticas de segurança. Dependendo do modelo (IaaS, PaaS ou SaaS), o nível de gerenciamento pode variar entre controle total ou automação. Além disso, provedores de nuvem oferecem infraestrutura mais preparada para lidar com ameaças como ataques DDoS.

# Sobre **os benefícios da capacidade de gerenciamento na nuvem**

Existem dois tipos de capacidade de gerenciamento: 

- **Gerenciamento da nuvem**: administração direta dos recursos em nuvem, permitindo escalar automaticamente, implantar via templates, monitorar integridade e gerar alertas baseados em métricas.
- **Gerenciamento na nuvem**: formas de administrar o ambiente e os recursos, utilizando ferramentas como portal web, linha de comando, APIs ou PowerShell.
