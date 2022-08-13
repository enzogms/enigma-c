
<h1 align="center"><img src="https://raw.githubusercontent.com/abrahamcalf/programming-languages-logos/master/src/c/c_256x256.png" alt="drawing" width="200"/> <br> 1º Trabalho Prático – Enigma  
</h1>


Dada uma configuração inicial, a máquina de criptografia alemã Enigma, da Segunda Guerra Mundial, substituía cada letra digitada no teclado por alguma outra letra. A substituição era bastante complexa, mas a máquina tinha uma vulnerabilidade: uma letra nunca seria substituída por ela mesma! Essa vulnerabilidade foi explorada por Alan Turing, que trabalhou na criptoanálise da Enigma durante a guerra. O objetivo era encontrar a configuração inicial da máquina usando a suposição de que a mensagem continha uma certa expressão usual da comunicação, como por exemplo a palavra ARMADA. Essas expressões eram chamadas de cribs. Se a mensagem cifrada era, por exemplo, FDMLCRDMRALF, o trabalho de testar as possíveis configurações da máquina era simplificado porque a palavra ARMADA, se estivesse nessa mensagem cifrada, só poderia estar em duas posições, ilustradas na tabela abaixo com uma seta. As demais cinco posições não poderiam corresponder ao crib ARMADA porque ao menos uma letra do crib, sublinhada na tabela abaixo, casa com sua correspondente na mensagem cifrada; como a Enigma nunca substituiria uma letra por ela própria, essas cinco posições poderiam ser descartadas nos testes.
<p align="center">
   <img src="https://user-images.githubusercontent.com/90652800/184500775-b04c4060-d4aa-429b-af47-dee108a0d4ac.png"/>
   <br>
   <img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=GREEN&style=for-the-badge"/>
   <br>
   
</p>


## 📥 Entrada
A primeira linha da entrada contém a mensagem cifrada, que é uma sequência de, pelo menos, uma letra e no máximo 104 letras. A segunda linha da entrada contém o crib, que é uma sequência de, pelo menos, uma letra e no máximo o mesmo número de letras da mensagem. Apenas as 26 letras maiúsculas, sem acentuação, aparecem na mensagem e no crib.


## 📤 Saída
Imprima uma linha contendo um inteiro, indicando o número de posições possíveis para o crib na mensagem cifrada.

**Exemplo**:

