Round Robin é uma técnica para o balanceamento de carga que distribui eficientemente o tráfego entre vários servidores ou recursos de rede. Além disso, no contexto do gerenciamento de DNS, essa tecnologia pode ser usada para distribuir solicitações de usuários entre vários servidores IP. Iremos focar na criação deesse algoritmo e tentar aplica-lo em algum exemplo.

## Especificidades
- é um dos algoritmos mais simples e mais antigos
- Imune a starvation
	__starvation__ significa inanaição. é um problema que ocorre quando um processo nunca é executado. Bem comum em programação concorrente
- Usados em sistemas multi-tarefas

Essa abordagem existe para evitar sobrecarga de uma única porta de comunicação, basicamente __"balanceamos"__ a carga distribuindo para todos os serviços.
No contexto de servidor DNS, o Round Robin pode ser usado como uma forma simples de distribuir solicitações entre vários servidores.
Nesse caso, o servidor DNS responde ás solicitações de resolução de nomes fornecendo uma lista rotativa de endereçõs IP associados ao mesmo nome de domínio, geralmente serão serviçoes redundantes.
![[Pasted image 20240528103108.png]]
## Casos de uso
Ok, entendemos oque seria o algoritmo Round Robin e como ele é usado em balanceamentos de carga, mas oque seria isso?
"Balanceamento de caraga" é uma técnica para otimizar a escalabilidade, confiabilidade e desempenho da aplicação. Isso se torna __muito__ útil em serviços com muito trafego.

Ao empregar o Round Robin nessas situações, é possível garantir um melhor desempenho e uma distribuição mais eficiente do trabalho, através da alocação equitativa dos recursos e requisições disponíveis.

## Vantagens
Esse algoritmo proporciona uma distribuição justa e equitativa da carga de trabalho entre os recursos disponíveis, evitando sobrecargas e subutilizações. Além disso, como dito na seção [especificidades](#especificidades), este algoritmo é bem fácil de implementar, ou seja, ele exige pouca configuração e manutenção em comparação com outros algoritmos de balanceamento mais sofisticados.

### Dicionário
- 
## Implementação
O algoritmo do Round Robin se chama __Round Robin Scheduling__ e irei me basear no seguinte artigo e outros conteudos que irei registrando aqui para implementa-lo.
- [Program for Round Robin Scheduling for the same Arrival time](https://www.geeksforgeeks.org/program-for-round-robin-scheduling-for-the-same-arrival-time/)
