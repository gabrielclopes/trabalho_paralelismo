# trabalho_paralelismo
Trabalho para a disciplina de Programação Paralela.

Objetivos:

Etapa 1)
1. Extrair a RNC do código e compilar para a arquitetura da sua máquina host.
2. Calcular o tempo de execução da RNC na sua máquina Host.
3. Gerem 1000 entradas para a RNC (100 de cada tipo, podem usar python para isso) e alterem o código para
suportar essa entrada de dados, ou seja, cada execução deve processar todas as entradas.

Etapa 2)
1. Paralelizar com Pthreads a execução da RNC para que cada inferência (detecção de padrões) execute em 1
thread.
2. Casos com pelo menos 1, 2, 3 e 4 threads (até o máximo de núcleos físicos da sua máquina host) e
verifiquem quantas inferências são feitas por segundo para cada uma das configurações.
3. Utilizar 2 compiladores: GCC (v10 ou maior) e CLANG (v10 ou maior).
