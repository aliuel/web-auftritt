<template>

  <div id="wrapper" class="mr-[11vw] xs:mr-[5vh]">
    <!-- margin same as banner width -->

    <div id="header"
      class="border-b-[2px] border-black pr-[3vh] h-[25vh] mt-[-2vh] flex flex-col items-end lg:pr-[20vw]">
      <h1 class="mb-[-11vh] mr-[5vh]">Ali</h1>
      <h1>Ülgen</h1>
    </div>

    <div id="main" class="flex flex-col items-center">
      <div id="introduction" class="section
        lg:border-l-[2px] ">
        <h3>01</h3>
        <h1>Sehr geehrter Herr Grünig</h1>
        <p>Diesen Sommer habe ich meine Lehre als Informatiker und die Berufsmatura erfolgreich abgeschlossen und plane
          nun meine Berufskarriere im Bereich Informatik zu beginnen. Ich sehe Ihr Stellenangebot für die
          Frontend-Entwicklerposition als eine grossartige Möglichkeit für mich, in die Welt der Informatik einzusteigen. Ich
          wünsche mir, in der Entwicklung tätig zu sein und bei fugu bietet sich mir die Gelegenheit, als Teil eines
          Teams von Spezialisten auch tatsächlich herausgefordert zu werden und meine Fähigkeiten zu erweitern.
        </p>
      </div>

      <div id="person" class="section text-right 
        lg:border-r-[2px]">
        <h3>02</h3>
        <h1>Zu meiner Person</h1>
        <p>Während meiner Ausbildungszeit wurde ich mit viel Fachwissen in verschiedenen
          Themengebieten für die Arbeitswelt der Informatik vorbereitet, wobei mich das Themengebiet der Webentwicklung
          am meisten interessiert hat. Das Full-Stack Development war für mich eine willkommene Herausforderung und das
          logische Denken hinter der Arbeit geniesse ich sehr. Ebenfalls gefällt mir die kreative Arbeit, welche hinter
          dem Umsetzen eines gelungenen GUIs steht. Mit der Zeit machte ich mich mit vielen Technologien vertraut und
          mittlerweile ist die Webentwicklung eines meiner persönlichen Interessen.
        </p>
        <p>
        </p>
        <!-- <p>Ansonsten zählt auch Fitness und mit Freunden was unternehmen zu meinen Hobbies. </p> -->
      </div>

      <div class=" lg:flex border-black lg:my-[5vh]">
        <div id="frontend" class="section lg:w-1/2 lg:mb-[10%] lg:border-x-[2px]">
          <h3>03</h3>
          <h1>Frontend</h1>
          <p class="pr-0"> Planung und Entwicklung von mehreren responsiven und interaktiven GUIs mit verschiedenen Frameworks und
            Libraries, wie Vue, Vuetify und weitere.</p>
          <div class="talents">
            <div class="bg-[#42B883]">
              <span>vue</span>
            </div>
            <div class="bg-[#38BDF8]">
              <span>Tailwind</span>
            </div>
            <div class="bg-[#CC6699]">
              <span>sass</span>
            </div>
            <div class="bg-[#1697F6]">
              <span>vuetify</span>
            </div>
            <div class="bg-[#F47933]">
              <span>html</span>
            </div>
            <div class="bg-[#008FD5]">
              <span>css</span>
            </div>
            <div class="bg-[#F99D34]">
              <span>js</span>
            </div>
          </div>
        </div>

        <div id="backend" class="section lg:w-1/2 text-right lg:self-end lg:border-x-[2px] lg:ml-[-2px]">
          <h3>04</h3>
          <h1>Backend</h1>
          <p class="pl-0"> Erfahrung in der Entwicklung von REST APIs mit Node und Express. Konzipieren und Umsetzen von komplexen
            SQL Datenbankschemas.</p>
          <div class="talents justify-end">
            <div class="bg-[#83CD29]">
              <span>node</span>
            </div>
            <div class="bg-[#313131]">
              <span>express</span>
            </div>
            <div class="bg-[#D63AFF]">
              <span>jwt</span>
            </div>
            <div class="bg-[#F29111]">
              <span>mysql</span>
            </div>
            <div class="bg-[#0F80CC]">
              <span>sqlite</span>
            </div>
            <div class="bg-[#F99D34]">
              <span>js</span>
            </div>
          </div>
        </div>
      </div>

      <div id="person" class="section border-none">
        <h3>05</h3>
        <h1>Kontakt</h1>
        <p class="pb-12">Sollten Sie noch irgendwelche Fragen haben, können Sie sich jederzeit bei mir melden.</p>
        <div class="contact flex mb-5">
          <img src="./assets/envelope.svg" alt="">
          <p>m.ali.uelgen@gmail.com</p>
        </div>
        <div class="contact flex pb-12">
          <img src="./assets/phone.svg" alt="">
          <p>078 967 66 21</p>
        </div>
      </div>

    </div>

  </div>

  <div id="banner" class="fixed py-2 right-0 top-0 border-l-[2px] border-black h-screen bg-transparent w-[11vw] 
    flex flex-col items-center justify-evenly
    xs:w-[5vh]">
    <h2 class=" font-black">Bewerbung</h2>
    <div id="socialmedia">
      <a href="https://www.linkedin.com/in/ali-%C3%BClgen-16b766219/">
        <img class="mb-6" src="./assets/linkedin.svg" alt="">
      </a>
      <a href="https://github.com/aliuel">
        <img src="./assets/github-square.svg" alt="">
      </a>
    </div>
    <h2 class=" tracking-wider">06/01/22 - Stettlen</h2>
  </div>
</template>

<script>
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;900&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;1,900&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

  * {
    font-family: 'Montserrat', sans-serif;
  }

  body {
    background-color: #F1F1F1;
  }

  h3 {
    font-family: 'Playfair Display', serif;
  }

  p {
    font-family: 'Roboto', sans-serif;
  }

  #banner h2 {
    writing-mode: vertical-rl;
    transform: scale(-1);
  }
</style>