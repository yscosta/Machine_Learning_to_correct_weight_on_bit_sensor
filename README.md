# ML_to_correct_weight_on_bit

<div class="alert" style="background-color:#fff; color:white; padding:0px 10px; border-radius:5px;"><h1 style='margin:15px 15px; color:#305496; font-size:40px'>Aprendizagem de máquina para ajustar os dados faltantes do sensor do peso sobre a broca</h1>
</div>

Na perfuração dos poços de petróleo são utilizados equipamentos compostos por uma sequência de tubos e uma broca em sua extremidade. Nesse conjunto é aplicado uma rotação e o peso sobre toda a estrutura, que é chamada de coluna de perfuração,  fragmenta a rocha no fundo dos poços. Esses conceitos são retratados na animação <a href="https://www.linkedin.com/posts/alison-silva-217212135_activity-6858874651595153408-szUA/?utm_source=linkedin_share&utm_medium=member_desktop_web" target="_blank" rel="noopener noreferrer">Sonda de Perfuração</a>, elaborada pela Pertroanimes com  maiores detalhes.

Sensores estão acoplados aos diversos equipamentos de perfuração para o monitoramento, porém, tais dispositivos estão suscetíveis a falhas, o que acarreta na falta de dados.

Um modelo de aprendizagem de máquina será utilizado para corrigir os dados faltantes gerados devido a deficiência do sensor do peso sobre a broca, também conhecido como Weight on BIt (WOB).

Como condição para que o algoritmo submeta os dados ao modelo, que retornará a projeção do valor, é preciso que WOB esteja nulo e as demais variáveis não. Com isso, o resultado é exposto em gráficos com a substituição do peso sobre a broca junto com a rotação (RPM) e a profundidade do poço (DEPTH), a fim de analisar se o resultado é adequado.
