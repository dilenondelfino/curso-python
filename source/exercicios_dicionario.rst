#. Faça um dicionário com as 5 pessoas mais perto de você, tendo o nome como chave e a cor da camisa que está usando como valor.

#. Crie um dicionário vazio ``semana = {}`` e o complete com uma chave para cada dia da semana, tendo como seu valor uma lista com as aulas que você tem nesse dia (sábado e domingo recebem listas vazias, ou você tem aula?).

#. Crie um dicionário vazio ``filmes = {}``. Agora preencha-o com o nome de cinco filmes como chaves e *outros* dicionários contendo o respectivo ``vilão`` e o ``ano`` em que cada filme foi lançado como valor.

   .. only:: instructors

      Exemplo de solução:

      .. doctest::

         >>> filmes = {}
         >>> filmes["Vingadores"] = {"Vilão": "Thanos", "Ano": 2019}
         >>> filmes["O Náufrago"] = {"Vilão": "A Ilha (?)", "Ano": 2000}
         >>> filmes["E O Vento Levou"] = {"Vilão": "O vento", "Ano": 1939}
         >>> filmes
         {'Vingadores': {'Vilão': 'Thanos', 'Ano': 2019}, 'O Náufrago': {'Vilão': 'A Ilha (?)', 'Ano': 2000}, 'E O Vento Levou': {'Vilão': 'O vento', 'Ano': 1939}}