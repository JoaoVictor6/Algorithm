Round Robin é uma técnica para o balanceamento de carga que distribui eficientemente o tráfego entre vários servidores ou recursos de rede. Além disso, no contexto do gerenciamento de DNS, essa tecnologia pode ser usada para distribuir solicitações de usuários entre vários servidores IP. Iremos focar na criação deesse algoritmo e tentar aplica-lo em algum exemplo.

# Especificidades
- é um dos algoritmos mais simples e mais antigos
- Imune a starvation
	__starvation__ significa inanaição. é um problema que ocorre quando um processo nunca é executado. Bem comum em programação concorrente
- Usados em sistemas multi-tarefas

Essa abordagem existe para evitar sobrecarga de uma única porta de comunicação, basicamente __"balanceamos"__ a carga distribuindo para todos os serviços.
No contexto de servidor DNS, o Round Robin pode ser usado como uma forma simples de distribuir solicitações entre vários servidores.
Nesse caso, o servidor DNS responde ás solicitações de resolução de nomes fornecend
### Roadmap
