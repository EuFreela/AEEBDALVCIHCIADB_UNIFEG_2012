# AEEBDALVCIHCIADB_UNIFEG_2012

### PROTÓTIPO 1
<p>Aqui se encontra o meu projeto para trabalho de conclusão de curso em ciência da computação no ano de 2012. O projeto surgiu de acordo com a especialização de quem seria o orientador. O Doutor em processamento de imagens, Dr. Fernando Versal Salina, seria o meu orientador, contudo, ele precisou sair da UNIFEG para dar aulas no IFSUL de SP. Em seu lugar, como orientador, ficou sendo Lucas Ximenes Boa Sorte.</p>

<p>Como se tratava de um trabalho científico, as justificativas para o peso do contribuiria para a ciência era a tendência dos trabalhos no UNIFEG. Discutimos e decidimos ajudar pessoas somando desenvolvimento de software + processamento de imagens. Assim surgiu este trabalho focado na minoria linguística no país.</p>

<p>Este trabalho trata-se de um protótipo. Para processamento de imagens, em especial o reconhecimento de padrões, exige especificações quanto a hardwaare e tecnicas de software a serem usadas. Entre as dificuldades e problemas encontrados é a luz para reconhecimento de padrões em tempo real. Devido a esta condição foi escolhido a técnica match template e não RNA.</p>

<p>O artigo desse sistema foi enviado com exclusividade para a SBC, onde até a Dr. em IHC duvidou que o sistema rodaria com match template alegando o estouro de memória. E de fato, isso aconteceria se eu não fizesse a otimização do que seria usado, por isso o trabalho foi gravado em ambiente preparado. Isso somente porque a luz que incide sobre o objeto não é tratada em harware mas em software.</p>

<p>Eu disponibilizei o código fonte no trabalho e demais configurações para execução do código. Desde que vc siga todas as especificações é possível que reproduza as condições necessárias para que ele execute. Além disso, este trabalho tem sido extendido ou continuado em posteriores trabalhos para stricto sensu (mestrado e doutorado) onde as condições que ele parou eu acertei em novos projetos, como a luz. Agora o trataento é com hardware o que permite o uso da aplicação em diversos ambiente. Para doutorado será reconhecimento de microexpressões faciais usado em libras.</p>

<p>O trabalho pode ser lido aqui: <a href="https://lameckfernandes.files.wordpress.com/2016/10/com12-lsfernandes.pdf">DESENVOLVIMENTO DE UM SOFTWARE PARA AUXÍLIO À EDUCAÇÃO DE DEFICIENTES AUDITIVOS: ALFABETIZAÇÃO BILÍNGUE ATRAVÉS DE MÉTODOS DE IHC E VISÃO COMPUTACIONAL</a></p>

<p>Se quiser aprender openCV, de uma maneira "bem educativa", basta entrar no meu blog: <a href="http://novos-cientistas.blogspot.com.br/2012/03/desenvolvimento-de-sistemas_07.html">OpenCv na prática</a></p>

<p>O Ms. Lucas Ximenes me disse que alguns alunos gostariam de continuar as implementações porém, encontram dificiuldades para as configurações necessárias e para conseguir um build no código. Por isso eu estou disponibilizando acesso a ele nos aquivos do git. Se quiser continuar fique a vontade. Sugiro que passe o sistema para rede neural criando os pesos que serão usados nos demais projetos.</p>
<br>

### Características que devem ser consideradas:
<o>
  <li>1. Se trata do protótipo de um sistema e não definitivamente o sistema final. A metodologia para desenvolvimento desse sistema respeita o modelo espiral a entrega de resultados por sprints de 4 semanas. Até chegar a este resultado foram 12 sprints (1 ano)</li>
  <li>2. A cada interação uma nova interface é criada. Como o problema neste protótipo é a luz, foi criado um controle sobre a imagem real para ser comparada com o template.</li>
  <li>3. LIBRAS não se limita apenas a um alfabeto datilológico, mas, nesse projeto foi a proposta para iniciar o sistema com reconhecimento de padrões. Como se trata de etapas a serem cumpridas esta fase foi de extrema importancia principalmente devido ao tempo escasso para entrega do projeto para conclusão de curso</li>
  <li>4. Para demais integrações da interface IHC se faz necessário especialistas e o uso de pessoas para testarem - por isso será realizado em outras versões. A Drª em IHC me cobrou isso</li>
  <li>5. Atualmente utilizamos os modelos baseados em IHC sendo o UX/UI os quais focam no usuário. Isso facilitaria o uso de pessoas e documentos para conclusão de algumas etapas até a intrgração direta com IHC</li>
  <li>Não existe atraso no frame para comparação com o template. O que existe é um numero reduzido de templates a serem comparados com a imagem real. Os templates foram pré-processados para otimização de leitura sem estourar a memória. Devido a esse motivo, se faz necessário que a distancia entre o ROI e a mão sejam 80% equivalentes e o mesmo para a posição. A RNA resolveria isso, mas, precisará de um computador melhor do que o qual usei para este projeto</li>
  <li>Este trablho foi inédito até a sua apresentação. O que não era necessário para um trabalho de bacharelado</li>
</o>

<br>

<p>Pois é, parece a memória não estoura (buffer over flow) Doutora</p>
<a href="https://www.youtube.com/embed/eWH9EMVnhlo"><img src="https://s13.postimg.org/pmcqguoaf/Sem_t_tulo.png" width="600" height="400"></a>





