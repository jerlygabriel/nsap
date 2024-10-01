<template>
  <div class = "mx-44 mt-10">
    <img src = "../public/IMG-20241001-WA0003.jpg" class = "h-[360px] mx-auto rounded-md" />
    <div class = "flex justify-center">
      <ul class="menu menu-vertical lg:menu-horizontal bg-base-200 rounded-box shadow-md mt-5">
        <li @click = "texto = 1"><a>Participe</a></li>
        <li @click = "texto = 2"><a>5ª COREPSI-TO e 12ª CNP</a></li>
        <li @click = "texto = 3"><a>Ações Mobilizadoras</a></li>
        <li @click = "texto = 4"><a>Pré Congressos</a></li>
        <li @click = "texto = 5"><a>Documentos</a></li>
        <li @click = "texto = 6"><a>Comorg</a></li>
        <li @click = "texto = 7"><a>Contato</a></li>
      </ul>
    </div>
    <div class="flex w-full flex-col">
      <div class="divider">CRP-23</div>
    </div>
    <div class = "bg-base-100 rounded-md shadow-md mb-10 p-2">
      <div v-if = "texto == 1">
        <h1 class = "text-4xl text-center font-bold p-4"> Participe </h1>
        <p>Em agosto de 2025, profissionais de Psicologia de todo o Brasil escolher&atilde;o novas chapas de representantes para os Conselhos Regionais e para o Conselho Federal de Psicologia. Por&eacute;m, antes do processo eleitoral, os Conselhos de cada Estado promovem um processo dial&oacute;gico e democr&aacute;tico,&nbsp;<strong>do qual voc&ecirc; pode fazer parte</strong>, para definir as diretrizes que orientar&atilde;o os tr&ecirc;s anos das gest&otilde;es.&nbsp;</p>
          <p>O&nbsp;<strong>5&ordm; COREPSI-PR ocorrer&aacute; em</strong><strong>&nbsp;21, 22 e 23 de mar&ccedil;o de 2025</strong>&nbsp; com o tema &ldquo;Psicologia e Democracia: A Pluriversalidade do nosso fazer&rdquo; e seus objetivos s&atilde;o:</p>
          <ul class = "p-4 list-disc">
            <li>Promover a organiza&ccedil;&atilde;o e mobiliza&ccedil;&atilde;o das pessoas Psic&oacute;logas do Tocantins, possibilitando a defini&ccedil;&atilde;o da contribui&ccedil;&atilde;o do Sistema Conselhos de Psicologia para o desenvolvimento da Psicologia como ci&ecirc;ncia e profiss&atilde;o;</li>
            <li>Garantir a participa&ccedil;&atilde;o das(os) Psic&oacute;logas(os) no processo de delibera&ccedil;&atilde;o acerca da&nbsp;a&ccedil;&otilde;es a serem desenvolvidas pelo Conselho Federal de Psicologia (CFP) e pelo&nbsp;Conselho Regional de Psicologia do Tocantins (CRP 23), favorecendo a valoriza&ccedil;&atilde;o e o&nbsp;protagonismo das(os) psic&oacute;logas(os), bem como a auto-organiza&ccedil;&atilde;o em rela&ccedil;&atilde;o &agrave;s&nbsp;etapas que precedem o Congresso Nacional da Psicologia (CNP);</li>
            <li>Apresentar propostas referentes ao tema do 12º Congresso Nacional da Psicologia&nbsp;(12&ordf; CNP), que subsidiem as diretrizes pol&iacute;ticas a serem implementadas e/ou reguladas pelo Conselho Federal de Psicologia (CFP) e Conselho Regional de&nbsp;Psicologia do Tocantins (CRP 23) para serem implementadas no pr&oacute;ximo tri&ecirc;nio;</li>
            <li>Garantir o espa&ccedil;o de articula&ccedil;&atilde;o para composi&ccedil;&atilde;o, inscri&ccedil;&atilde;o e apresenta&ccedil;&atilde;o de chapas&nbsp;que concorrer&atilde;o ao mandato do Conselho Regional de Psicologia do Estado do&nbsp;Tocantins, para a gest&atilde;o 2025-2028;</li>
            <li>Eleger as pessoas delegadas para o 12&ordm; CNP, que ser&aacute; realizado nos dias 03 a 06 de julho de 2025.</li>
          </ul>
      </div>
      <div v-if = "texto == 2">
        <h1 class = "text-4xl text-center font-bold p-4"> 12ª COREPSI-TO </h1>
        <p>Ap&oacute;s a realiza&ccedil;&atilde;o dos Pr&eacute;-COREPSIs, as propostas aprovadas em cada regi&atilde;o s&atilde;o&nbsp;sistematizadas e levadas a discuss&atilde;o pelas pessoas delegadas no 5&ordm; Congresso Regional da Psicologia do Tocantins (5&deg; COREPSI);<br>As propostas votadas em todas as etapas ser&atilde;o levadas para o 12&ordm; Congresso Nacional da&nbsp;Psicologia (12&ordm; CNP). &Eacute; tamb&eacute;m durante a 5&ordm; COREPSI que ser&atilde;o escolhidas as pessoas&nbsp;delegadas para representar o Tocantins no 12o CNP.</p>
        <p><br><strong><span style="font-size: 23px;">12&ordm; Congresso Nacional da Psicologia (CNP)</span></strong></p>
        <p><br>O processo de forma&ccedil;&atilde;o das diretrizes que orientam as gest&otilde;es regionais e federal no&nbsp;pr&oacute;ximo tri&ecirc;nio &eacute; finalizado no 12&ordm; Congresso Nacional da Psicologia (CNP), que ser&aacute;&nbsp;realizado entre os dias ----------------- 2025. Neste momento, as delega&ccedil;&otilde;es regionais votam as&nbsp;propostas e, uma vez aprovadas, elas formam o Caderno de Delibera&ccedil;&otilde;es, que fica dispon&iacute;vel&nbsp;para conhecimento da categoria.<br>As discuss&otilde;es e propostas, desde esta etapa, devem ser alinhadas ao tema do 12&ordm; Congresso Nacional da Psicologia (12&ordm; CNP): Psicologia e Democracia: A Pluriversalidade do nosso fazer. Por uma psicologia pluriversa e inclusiva!</p>
        <p>Dentro desta tem&aacute;tica, as propostas devem estar alinhadas a um dos tr&ecirc;s eixos definidos pelo regulamento do 12&ordm; CNP:</p>
        <p><br><strong>I &ndash; Eixo 01</strong> &ndash; Sistema Conselhos de Psicologia: A organiza&ccedil;&atilde;o democr&aacute;tica e a participa&ccedil;&atilde;o da categoria na consolida&ccedil;&atilde;o de um sistema pluriverso e representativo;</p>
        <p><strong>II &ndash; Eixo 2</strong> &ndash; Interlocu&ccedil;&atilde;o com a sociedade: Articula&ccedil;&otilde;es das Psicologias brasileiras para a efetiva&ccedil;&atilde;o do Estado Democr&aacute;tico de Direito na perspectiva da interseccionalidade, considerando as vulnerabilidades a partir dos diferentes marcadores sociais, tais como: quest&otilde;es &eacute;tnico-raciais, socioecon&ocirc;micas, culturais, geracionais, sexualidade e g&ecirc;nero e das pessoas com defici&ecirc;ncia;</p>
        <p><strong>III &ndash; Eixo 3</strong> &ndash; Exerc&iacute;cio Profissional: O trabalho das psicologias na consolida&ccedil;&atilde;o da democracia com responsabilidade &eacute;tica, t&eacute;cnica e pol&iacute;tica, a partir de uma perspectiva pluriversa.</p>
      </div>
      <div v-if = "texto == 3">
        <h1 class = "text-4xl text-center font-bold p-4"> Ações Mobilizadoras </h1>
        <p>A organiza&ccedil;&atilde;o do 5&deg; Congresso Regional da Psicologia do Estado do Tocantins (5º COREPSI)&nbsp;ser&aacute; de responsabilidade do IV Plen&aacute;rio do CRP 23, por meio da Comiss&atilde;o Organizadora do&nbsp;Tocantins (COMORG-TO).</p>
        <p><br>Elas ocorrer&atilde;o nas seguintes modalidades:</p>
        <p><br><strong>1. Eventos Preparat&oacute;rios: </strong>Eventos de diferentes formatos, organizados pelo CRP 23, que objetivam:</p>
        <p>articular e mobilizar amplamente profissionais da Psicologia, por meio de&nbsp;discuss&otilde;es de base, encontros tem&aacute;ticos, mesas redondas, debates on-line e outros, para a&nbsp;discuss&atilde;o da tem&aacute;tica do 5&deg; COREPSI e do 12º CNP, favorecendo a organiza&ccedil;&atilde;o da categoria&nbsp;profissional para o levantamento de quest&otilde;es profissionais, estimulando a elabora&ccedil;&atilde;o de&nbsp;propostas a serem apresentadas, apreciadas e votadas nos Pr&eacute;-congressos divulgando&nbsp;tamb&eacute;m no CNP.<br>a) Podem participar dos Eventos Preparat&oacute;rios: profissionais da Psicologia, estudantes,&nbsp;pessoas convidadas e quaisquer outras pessoas interessadas. Nos Eventos Preparat&oacute;rios n&atilde;o&nbsp;se elege delega&ccedil;&atilde;o para o 12º CNP;<br>b) As(os) estudantes de psicologia, ser&atilde;o considerados aptas(os), apenas aqueles discentes&nbsp;matriculados em cursos de gradua&ccedil;&atilde;o de psicologia autorizados ou reconhecidos pelo MEC,&nbsp;mediante apresenta&ccedil;&atilde;o de comprovante de matr&iacute;cula atualizado, correspondente ao&nbsp;semestre vigente ao evento.</p>
        <p><br><strong>2. Eventos livres:</strong> S&atilde;o as a&ccedil;&otilde;es de mobiliza&ccedil;&atilde;o propostas pela categoria, de forma aut&ocirc;noma e&nbsp;podem ser organizadas por psic&oacute;logos ou por coletivos da psicologia, associa&ccedil;&otilde;es, sindicatos&nbsp;e/ou institui&ccedil;&otilde;es p&uacute;blicas e privadas de psicologia, bem como organiza&ccedil;&otilde;es estudantis de<br>psicologia.<br>a) O cadastro do evento livre dever&aacute; ser feito por uma pessoa f&iacute;sica, sendo ela: psic&oacute;loga,&nbsp;com cadastro ativo, regular, adimplente, com inscri&ccedil;&atilde;o principal no Estado do Tocantins, que&nbsp;ser&aacute; designada para responder &agrave;s demandas, conforme organiza&ccedil;&atilde;o/orienta&ccedil;&atilde;o da COMORG-&nbsp;TO, regional e comunicado por meio do formul&aacute;rio dispon&iacute;vel no hotsite www.crp23.org.br;</p>
        <p>b) Os Eventos livres, dever&atilde;o ser realizados entre o per&iacute;odo de: 01o de setembro de 2024 a 30&nbsp;de novembro de 2024;<br>c) Todas as propostas ser&atilde;o encaminhadas &agrave; COMORG-TO, que poder&aacute; sugerir jun&ccedil;&atilde;o,&nbsp;divis&atilde;o e adequa&ccedil;&atilde;o de propostas que n&atilde;o possam ser exequ&iacute;veis em a&ccedil;&otilde;es, atividades ou&nbsp;projetos pelo 5o Plen&aacute;rio do CRP 23, preservando a vers&atilde;o anterior de todas as propostas,&nbsp;para registro hist&oacute;rico e garantia efetiva de democracia.Como realizar um evento livre:<br>1. Fa&ccedil;a o download e preencha o formul&aacute;rio &gt; <a class="text-blue-500 underline" href="https://forms.gle/wYKghkUTmV37FSHo6" target="_blank" rel="noopener">Clique Aqui</a><br>2. Assine o documento e envie para o e-mail &gt; <a class="text-blue-500 underline" href="mailto:karlamilhomemcardoso@gmail.com;" target="_blank" rel="noopener">Clique Aqui</a><br>3. Ap&oacute;s a realiza&ccedil;&atilde;o do evento, encaminhe as propostas conforme a sistematiza&ccedil;&atilde;o<br>presente neste formul&aacute;rio &gt; <a class="text-blue-500 underline" href="https://forms.gle/wYKghkUTmV37FSHo6" target="_blank" rel="noopener">Clique Aqui</a></p>
      </div>
      <div v-if = "texto == 4">
        <h1 class = "text-4xl text-center font-bold p-4"> Pré Congressos </h1>
        <p>No Tocantins, a agenda dos chamados Pr&eacute;-COREPSIs contar&aacute; com eventos virtuais de 01 de&nbsp;outubro de 2024 a 02 de fevereiro de 2025. Toda pessoa Psic&oacute;loga com registro ativo pode<br>participar de um Pr&eacute;-COREPSI, inst&acirc;ncia na qual se debateram quest&otilde;es relativas &agrave; Psicologia&nbsp;como ci&ecirc;ncia e profiss&atilde;o, e em que ocorreram as candidaturas para ser pessoa delegada no&nbsp;12o COREPSI.<br>Tamb&eacute;m podem participar estudantes de Psicologia, pessoas convidadas e pessoas&nbsp;observadoras. O direito a voz foi garantido a todas as pessoas, e o direito a voto &eacute; restrito a&nbsp;profissionais de Psicologia.<br>Nesta fase ocorrer&aacute;, concomitantemente, a elei&ccedil;&atilde;o de delega&ccedil;&atilde;o que participar&aacute; do 5o&nbsp;COREPSI e delibera&ccedil;&otilde;es sobre outras proposi&ccedil;&otilde;es de &acirc;mbito regional, a serem encaminhadas&nbsp;para o 5o COREPSI.</p>
<p>Confira a agenda preliminar dos eventos:<br>a) Encontro 1 - dia outubo de 2024 - modalidade on-line;<br>b) Encontro 2 - dia outubro/novembro de 2024 - modalidade on-line;<br>c) Encontro 3 - dia novembro de 2024 - modalidade on-line;<br>d) Encontro 4 - dia dezembro de 2024 - modalidade on-line;<br>e) Encontro 5 - dia janeiro de 2024 - modalidade on-line;<br>f) Encontro 6 - 02 fevereiro de 2024 - modalidade on-line;<br>Todos os eventos s&atilde;o abertos a qualquer pessoa profissional, estudantes e demais&nbsp;pessoas convidadas residentes no Estado do Tocantins.<br>Para a modalidade presencial, al&eacute;m das cidades nas quais o CRP TO possui sede (Palmas,&nbsp;Araguaina e Gurupi).<br>Mais detalhes a respeito da escolha das cidades estar&atilde;o dispon&iacute;veis em breve!</p>
      </div>
      <div v-if = "texto == 5">
        <h1 class = "text-4xl text-center font-bold p-4"> Documentos </h1>
        <p>Fa&ccedil;a o download de documentos importantes para a realiza&ccedil;&atilde;o do 12o CNP e do5&deg; COREPSI-TO:</p>
<p><a class="text-blue-500 underline" href="https://api.crp23.org.br/arquivo/crp23.org.br/docs/4532/REGULAMENTOS%20COMORG.pdf" target="_blank" rel="noopener">Regulamento Nacional do 12o CNP</a><br><a class="text-blue-500 underline" href="https://api.crp23.org.br/arquivo/crp23.org.br/docs/4531/REGULAMENTOS%20COMORG.pdf" target="_blank" rel="noopener">Regulamento do 5o Congresso Regional da Psicologia do Tocantins (5o COREPSI)</a><br><a class="text-blue-500 underline" href="nsap" target="_blank" rel="noopener">Formul&aacute;rio para informa&ccedil;&atilde;o de A&ccedil;&otilde;es Mobilizadoras &ndash; Eventos Livres</a></p>
      </div>
      <div v-if = "texto == 6">
        <h1 class = "text-4xl text-center font-bold p-4"> Comorg </h1>
        <p>Conhe&ccedil;a a Comiss&atilde;o Organizadora Regional do 5o COREPSI-TO.</p>
        <p>Karla Milhomem Cardoso (Conselheira titular)</p>
        <p>Douglas Hermann de Sousa (Conselheira titular)</p>
        <p>Ocinarya Saraiva Lima (Psic&oacute;loga convidada)</p>
        <p>M&aacute;rcia Helena Padilha (Psic&oacute;loga fiscal)</p>
        <p>Ayala Griss Batista Cavalcante (Funcion&aacute;ria)</p>
        <p>Breno Vasco Pereira Lima (Funcion&aacute;ria)</p>
        <p>H&eacute;rika Santos Rosa (Funcion&aacute;ria)</p>
        <p>Joelene Oliveira Costa (Funcion&aacute;ria)</p>
      </div>
      <div v-if = "texto == 7">
        <h1 class = "text-4xl text-center font-bold p-4"> Contato </h1>
        <p>Se voc&ecirc; tem alguma d&uacute;vida, n&atilde;o hesite em entrar em contato conosco!<br></p>
<p>Mande um e-mail para a respons&aacute;vel pela Comiss&atilde;o Organizadora&nbsp;Regional &gt; <a class="text-blue-500 underline" href="mailto:karlamilhomemcardoso@gmail.com" target="_blank" rel="noopener">Clique Aqui</a></p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      texto: 1
    }
  }
}
</script>