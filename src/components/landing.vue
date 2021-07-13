<template>
<div class="tw-bg-main">
    <div class="lg:block xl:block sm:hidden md:hidden">
      <header class="">
          <nav class="bg-transparent">
              <div class="w-11/12 mx-auto px-2 sm:px-6 lg:px-8">
                  <div class="relative flex items-center justify-between h-16">
                      <div class="flex items-center justify-center sm:items-stretch sm:justify-start mr-auto">
                          <div class="flex-shrink-0 flex items-center">
                          </div>
                          <div class="sm:block sm:ml-6">
                              <div class="flex space-x-4">
                                  <a href="#home"
                                      class="text-black font-semibold hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Home</a>

                                  <a href="#services"
                                      class="text-black font-semibold hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Serviços</a>

                                  <a href="#desenvolvimento"
                                      class="text-black font-semibold hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Desenvolvimento</a>

                                  <a href="#sobre"
                                      class="text-black font-semibold hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Sobre</a>


                                  <a href="#avaliacao"
                                      class="text-black font-semibold hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Avaliações</a>
                              </div>
                          </div>
                      </div>
                      <div class="inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
                          <button class="text-black-400 font-semibold uppercase m-4 focus:outline">
                              <a class="col-end-13 link text-black uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/login">Login</a>
                          </button>

                          <!-- Profile dropdown -->
                          <div class="ml-3">
                              <div>
                                  <button type="button"
                                      class="bg-gray-800 flex text-sm rounded-full focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-offset-gray-800 focus:ring-white"
                                      id="user-menu-button" aria-expanded="false" aria-haspopup="true">
                                      <button class="yellowground text-white p-2 uppercase rounded-md px-2">
                                          <a class="col-end-13 link text-white uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/create-account">cadastrar seu
                                            projeto </a>
                                      </button>

                                  </button>
                              </div>
                          </div>
                      </div>
                  </div>
              </div>
          </nav>
      </header>
    
      <div class="border-bottom: 50% 50% 50% 50% / 0% 0% 100% 100% ;">
          <div id="home" class="grid grid-cols-2">
              <div class="w-11/12 mt-44 ml-24">
                  <h1 class="font-baloo2 text-black text-6xl text-justify w-10/12">Bem Vindo a Fábrica de Software</h1>

                  <p class="font-official text-gray-500 text-justify mt-10"> A fábrica de software tem como o objetivo, melhorar
                      o ambiente digital de micro e pequenos
                      negócios, trazendo
                      soluções tecnológicas computacionais focadas em software
                      de forma gratuita para projetos de baixa complexidade com
                      prazo de até 30 dias.
                  </p>

                  <div class="mt-10 flex-1">
                      <button class="yellowground text-white p-2 font-bold uppercase rounded-md px-2 w-3/12">
                        <a class="col-end-13 link text-white uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/login">Login</a>
                      </button>
                      <span class="text-gray-500 mx-2">ou</span>
                      <a class="col-end-13 link text-black uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/create-account">cadastrar seu
                        projeto </a>

                  </div>
              </div>
              <div class="mt-24 ml-auto">
                  <img src="img/principal.png" alt="Imagem card">
              </div>
          </div>


          <div id="services">
              <h1 class="font-baloo2-bold text-gray-900 text-center text-4xl mb-4">O que <br>desenvolvemos ?</h1>
          </div>
          <div class="w-10/12 mx-auto flex mt-10">
                  <div class="ml-auto">
                      <img src="img/aplicativos.png">
                      <div class="w-full">
                          <h1 class="font-baloo2 text-3xl">Aplicativos</h1>
                          <p class="description font-official text-justify my-6">Aplicativos para plataformas móveis
                             trazendo flexibilidade no negócio.</p>
                                  <a target="_blank" href="https://sites.google.com/saojudas.br/exposaojudasti/projetos" class="link font-official font-extrabold">Confira aplicativos realizados na fábrica ›</a>
                      </div>
                  </div>

                  <div class="mt-12 mx-16">
                      <img src="img/sites.png">
                      <div class="w-full">
                          <h1 class="font-baloo2 text-3xl">Sites</h1>
                          <p class="description font-official text-justify my-6">Soluções em sites para que haja 
                            um fácil acesso de todos os usuários.</p>
                                  <a target="_blank" href="https://sites.google.com/saojudas.br/exposaojudasti/projetos" class="link font-official font-extrabold">Confira sites realizados na fábrica ›</a>
                      </div>
                  </div>

                  <div class="mt-16">
                      <img src="img/webservice.png">
                      <div class="w-full">
                          <h1 class="font-baloo2 text-3xl">Web Service</h1>
                          <p class="description font-official text-justify my-6">Integração de aplicações diferentes 
                            em uma plataforma, unificando serviços.</p>
                                  <a target="_blank" href="https://sites.google.com/saojudas.br/exposaojudasti/projetos" class="link font-official font-extrabold">Confira web services realizados na fábrica ›</a>
                      </div>
                  </div>
          </div>

          <div id="desenvolvimento" class="blueground mt-36">
            <div class="rodar">
                <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                    height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 100 C40 60 60 60 100 100 Z" />
                </svg>
            </div>
                <div class="flex relative">
                    <img class="relative bottom-40 ml-40" src="img/Group 34.png" alt="">
                    <div class="w-96 lg:ml-12 ">
                        <h1 class="text-2xl mb-6 font-bold text-white ">Qual o objetivo da Fábrica ?</h1>
                        <p class="text-base text-white text-justify">
                            Promover o encontro entre empresas e academia,
                            possibilitando que os alunos coloquem em prática o que estão aprendendo nas aulas assim
                            como tenham contato com projetos reais.
                        </p>
                    </div>

                </div>

                <div class="flex mr-10 -mt-96" style="margin-left: 30%">
                    <div class="w-96 ml-12 mt-30">
                        <h1 class="text-2xl mb-6 font-bold text-white ">Como propor projeto ?</h1>
                        <p class="text-base text-white text-justify">A proposta de projetos deverá ser feita dentro da plataforma, 
                          preenchendo todos os dados solicitados e descrevendo a proposta, com documentos e informações. 
                          É necessário salientar que o cliente deve estar ciente das regras propostas pela plataforma.
                        </p>
                    </div>
                    <img class="mb-80" src="img/Group-35.png" alt="">
                </div>


                <div class="flex ml-20" style="margin-top: -540px;">
                    <img class="relative mt-40" src="img/Group 36.png" alt="">
                    <div class="w-96 float-right mt-64 ml-2">
                        <h1 class="text-2xl mb-6 font-bold text-white ">Quem Desenvolve ?</h1>
                        <p class="text-base text-white text-justify">Os alunos que se cadastrarem na fabrica poderão 
                          desenvolver os projetos disponíveis na plataforma, com acompanhamento de professores, 
                          mentores e os clientes propusentes.
                        </p>
                        <!--<button class="rounded-lg  btn-color p-2 uppercase mt-4 focus:outline">
                            <a class="col-end-13 link text-white uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/create-account">cadastrar seu
                            projeto </a>
                        </button> -->
                </div>
              </div>
            <div>
              <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 100 C40 60 60 60 100 100 Z" />
              </svg>
            </div>
        </div>


          <div id="sobre" class="container mx-auto grid grid-cols-3 mt-8 mb-24">
              <div>
                  <img class="mt-56" src="img/circle_orange.png" alt="">
              </div>
              <div class="w-100">
                  <h1 class="text-center text-4xl mt-28 mb-10 font-bold">Sobre</h1>
                  <p class="text-center">O projeto é desenvolvido por alunos da Universidade São Judas Tadeu e para o
                      auxílio do
                      desenvolvimento temos professores para administrar os grupos.</p>
              </div>
              <div>
                  <img class="float-right mt-20" src="img/circle_red.png">
              </div>
          </div>

          <div class="footer yellowground mt-12 text-center">
              <div class="rodar">
                  <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                      height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                      <path d="M0 100 C40 60 60 60 100 100 Z" />
                  </svg>
              </div>

              <div class="flex mb-36">
                  <p class="font-baloo2 ml-auto font-bold text-xl mr-12">
                      Coloque seu negócio em um próximo nível, e deixe a gente te ajudar
                  </p>
                  <div class="mr-auto block">
                      <button class="font-baloo2 white text-black p-2 uppercase rounded px-2 rounded-md shadow-xl">
                          <a class="col-end-13 link text-black uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/create-account">cadastrar seu
                            projeto </a>
                      </button>
                      <p class="font-baloo2 mr-auto">
                          <a class="col-end-13 link text-white uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/login">ou Login ›</a>
                          
                      </p>
                  </div>
              </div>

              <div class="flex">
                  <img class="ml-auto mr-4" src="img/ustj-n.png" alt="">
                  <img class="mr-auto h-14 mt-3 ml-4" src="img/ustj-flex.png" alt="">
              </div>
              
              <div>
                  <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                      height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                      <path d="M0 100 C40 60 60 60 100 100 Z" />
                  </svg>
              </div>
          </div>
      </div>
    </div>

<!-- mobile -->
<div class="xl:hidden lg:hidden md:hidden p-4">
    
    <div class="block mt-6">
        <div class="block" id="home">
            <h1 class="font-baloo2 text-black text-4xl">Bem Vindo a Fábrica de Software</h1>
            <p class="font-official text-gray-500 mt-3 text-sm text-justify"> A fábrica de software tem como o objetivo, melhorar
                o ambiente digital de micro e pequenos
                negócios, trazendo
                soluções tecnológicas computacionais focadas em software
                de forma gratuita para projetos de baixa complexidade com
                prazo de até 30 dias.
            </p>
            <div class="mt-8 flex-1">
                <button class="btn-color text-white p-2 font-bold uppercase rounded-md px-2 w-4/12">
                    <a href="https://fabrica-user-client.herokuapp.com/login" class="link font-bold text-white" target="_blank">
                        Login
                    </a>
                </button>
                <span class="text-gray-500 mx-2">ou</span>
                <a class="col-end-13 link uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/create-account">cadastrar seu
                    projeto </a>
            </div>
            <div class="mt-12 ml-auto">
                <img src="img/principal.png" alt="Imagem card">
            </div>
        </div>
        <div class="block mt-16">
            <div id="services">
                <h1 class="font-baloo2-bold text-gray-900 text-center text-2xl mb-4">O que <br>desenvolvemos ?</h1>
            </div>
            <div class="block">
                <img src="img/aplicativos.png">
                <div class="">
                    <h1 class="font-baloo2 text-2xl text-center">Aplicativos</h1>
                    <p class="description font-official my-6">Aplicativos para plataformas móveis trazendo flexibilidade no negócio.</p>
                    <p class="text-center"><a target="_blank" href="https://sites.google.com/saojudas.br/exposaojudasti/projetos" class="link font-official font-extrabold text-center">Confira aplicativos realizados na fábrica ›</a></p> 
                </div>
            </div>
            <div class="block mt-14">
                <img src="img/sites.png">
                <div class="">
                    <h1 class="font-baloo2 text-2xl text-center">Sites</h1>
                    <p class="description font-official my-6">Soluções em sites para que haja um fácil acesso de todos os usuários.</p>
                    <p class="text-center"><a target="_blank" href="https://sites.google.com/saojudas.br/exposaojudasti/projetos" class="link font-official font-extrabold text-center">Confira sites realizados na fábrica ›</a></p>
                </div>
            </div>
            <div class="block mt-14">
                <img src="img/webservice.png">
                <div class="">
                    <h1 class="font-baloo2 text-2xl text-center">Web Service</h1>
                    <p class="description font-official my-6">Integração de aplicações diferentes em uma plataforma, unificando serviços.</p>
                    <p class="text-center"><a target="_blank" href="https://sites.google.com/saojudas.br/exposaojudasti/projetos" class="link font-official font-extrabold text-center">Confira web services realizados na fábrica ›</a></p>
                </div>
            </div>
        </div>
        <div class="blueground mt-10">
            <div class="rodar">
                <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                    height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 100 C40 90 60 90 100 100 Z" />
                </svg>
            </div>

            <div class="block p-3">
                <div class="w-full">
                    <img src="img/ajuda.png" class="w-8/12 ml-auto mr-auto" alt="">
                    <h1 class="text-2xl mb-6 font-bold text-white text-center">Qual o objetivo da Fábrica?</h1>
                    <p class="text-base text-white text-justify">Promover o encontro entre empresas e academia,
                        possibilitando que os alunos coloquem em prática o que estão aprendendo nas aulas assim
                        como tenham contato com projetos reais.
                    </p>
                   <!-- <div class="text-center">
                        <button class="w-48 rounded-lg  btn-color p-2 uppercase mt-4 focus:outline">
                            Sobre
                        </button>
                    </div> -->
                </div>

                <div class="w-full mt-16">
                    <img src="img/propor-app.png" class="w-8/12 ml-auto mr-auto" alt="">
                    <h1 class="text-2xl mb-6 font-bold text-white text-center">Como propor projeto ?</h1>
                    <p class="text-base text-white text-justify">A proposta de projetos deverá ser feita dentro da plataforma, 
                        preenchendo todos os dados solicitados e descrevendo a proposta, com documentos e informações. 
                        É necessário salientar que o cliente deve estar ciente das regras propostas pela plataforma.
                    </p>
                    <!--<div class="text-center">
                        <button class="w-48 rounded-lg  btn-color p-2 uppercase mt-4 focus:outline">
                            Sobre
                        </button>
                    </div>-->
                </div>

                <div class="w-full mt-16">
                    <img src="img/img-mobile/quem-desenvolve.png" class="w-8/12 ml-auto mr-auto" alt="">
                    <h1 class="text-2xl mb-6 font-bold text-white text-center">Quem Desenvolve ?</h1>
                    <p class="text-base text-white text-justify">Os alunos que se cadastrarem na fabrica poderão desenvolver os 
                        projetos disponíveis na plataforma, com acompanhamento de professores, 
                        mentores e os clientes propusentes.
                    </p>
                    <!--<div class="text-center">
                        <button class="w-48 rounded-lg  btn-color p-2 uppercase mt-4 focus:outline">
                            Sobre
                        </button>
                    </div>-->
                </div>
            </div>

            <div>
                <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                    height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 100 C40 90 60 90 100 100 Z" />
                </svg>
            </div>
        </div>
        <div id="sobre" class="block mt-16 mx-auto mt-10">
            <div class="w-100">
                <h1 class="text-center text-4xl mb-10 font-bold">Sobre</h1>
                <p class="text-center">O projeto é desenvolvido por alunos da Universidade São Judas Tadeu e para o
                    auxílio do
                    desenvolvimento temos professores para administrar os grupos.</p>
            </div>
        </div>
        <div class="footer yellowground mt-12 text-center">
            <div class="rodar">
                <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                    height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 100 C40 90 60 90 100 100 Z" />
                </svg>
            </div>
            <div class="block mb-20 ml-auto mr-auto p-3">
                <p class="font-baloo2 ml-auto font-bold text-xl">
                    Coloque seu negócio em um próximo nível, e deixe a gente te ajudar
                </p>
                <div class="mr-auto block mt-6">
                    <button class="font-baloo2 white text-black p-2 uppercase rounded px-2 rounded-md shadow-xl">
                        <a class="col-end-13 link text-black uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/create-account">cadastrar seu
                        projeto </a>
                    </button>
                    <p class="font-baloo2 mr-auto">
                        <a class="col-end-13 link text-white uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/login">ou Login ›</a>
                    </p>

                </div>
            </div>
            <div class="block p-3">
                <img class="ml-auto mr-auto" src="img/ustj-flex.png" alt="">
                <img class="ml-auto mr-auto mt-8" src="img/ustj-n.png" alt="">
            </div>
            <div>
                <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                    height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                    <path d="M0 100 C40 90 60 90 100 100 Z" />
                </svg>
            </div>
        </div>
        <div class="">
            <h1 class="text-center">
                <a class="p-6 underline " href="">Termos de uso</a>
            </h1>
        </div>
    </div>
</div> 

    <!-- Medium -->
<div class="lg:hidden xl:hidden sm:hidden md:block p-4">
    <div class="">
        <header>
            <nav class="bg-transparent">
                <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
                    <div class="relative items-center h-16">
                        <div class="flex items-center justify-center ">
                            
                            <div class="">
                                <div class="flex space-x-4">
                                    <a href="#home"
                                        class="text-black font-semibold hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Home</a>
    
                                    <a href="#services"
                                        class="text-black font-semibold hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Serviços</a>
    
                                    <a href="#desenvolvimento"
                                        class="text-black font-semibold hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Desenvolvimento</a>
    
                                    <a href="#sobre"
                                        class="text-black font-semibold hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Sobre</a>
    
                                    <a href="#avaliacao"
                                        class="text-black font-semibold hover:bg-gray-700 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Avaliações</a>
                                </div>
                            </div>
                            <div class="inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0">
                                <button class="text-black-400 font-semibold uppercase m-4 focus:outline">
                                    <a class="col-end-13 link text-black uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/login">Login</a>
                                </button>
                                <div class="ml-3">
                                    <button class="btn-color text-white p-2 uppercase rounded px-2">
                                        <a class="col-end-13 link text-white uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/create-account">cadastrar projeto </a>
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </nav>
        </header>
    </div>

    <div class="block mt-16">
        <h1 class="font-baloo2 text-black text-4xl">Bem Vindo a Fábrica de Software</h1>
        <p class="font-official text-gray-500 mt-3 text-sm"> A fábrica de software tem como o objetivo, melhorar
            o ambiente digital de micro e pequenos
            negócios, trazendo
            soluções tecnológicas computacionais focadas em software
            de forma gratuita para projetos de baixa complexidade com
            prazo de até 30 dias.
        </p>
        <div class="mt-8 flex-1">
            <button class="btn-color text-white p-2 font-bold uppercase rounded-md px-2 w-4/12">
                <a class="col-end-13 link text-white uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/login">Login</a>
            </button>
            <span class="text-gray-500 mx-2">ou</span>
            <a class="col-end-13 link uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/create-account">cadastrar seu
                    projeto </a>
        </div>
        <div class="mt-12 ml-auto">
            <img src="img/principal.png" alt="Imagem card" class="w-auto">
        </div>
    </div>
    <div class="block mt-16">
        <div id="services">
            <h1 class="font-baloo2-bold text-gray-900 text-center text-2xl mb-4">O que <br>desenvolvemos ?</h1>
        </div>
        <div class="block">
            <img src="img/aplicativos.png" class="ml-auto mr-auto">
            <div class="text-center">
                <h1 class="font-baloo2 text-2xl text-center">Aplicativos</h1>
                <p class="description font-official my-6">Aplicativos para plataformas móveis trazendo flexibilidade no negócio.</p>
                <p class="text-center"><a target="_blank" href="https://sites.google.com/saojudas.br/exposaojudasti/projetos" class="link font-official font-extrabold text-center">Confira aplicativos realizados na fábrica ›</a></p> 
            </div>
        </div>
        <div class="block mt-14">
            <img src="img/sites.png" class="ml-auto mr-auto">
            <div class="text-center">
                <h1 class="font-baloo2 text-2xl text-center">Sites</h1>
                <p class="description font-official my-6">Soluções em sites para que haja um fácil acesso de todos os usuários.</p>
                <p class="text-center"><a target="_blank" href="https://sites.google.com/saojudas.br/exposaojudasti/projetos" class="link font-official font-extrabold text-center">Confira sites realizados na fábrica ›</a></p>
            </div>
        </div>
        <div class="block mt-14">
            <img src="img/webservice.png" class="ml-auto mr-auto">
            <div class="text-center">
                <h1 class="font-baloo2 text-2xl text-center">Web Service</h1>
                <p class="description font-official my-6">Integração de aplicações diferentes em uma plataforma, unificando serviços.</p>
                <p class="text-center"><a target="_blank" href="https://sites.google.com/saojudas.br/exposaojudasti/projetos" class="link font-official font-extrabold text-center">Confira web services realizados na fábrica ›</a></p>
            </div>
        </div>
    </div>
    <div class="blueground mt-10">
        <div class="rodar">
            <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 100 C40 90 60 90 100 100 Z" />
            </svg>
        </div>

        <div class="block p-3">
            <div class="w-full">
                <img src="img/ajuda.png" class="w-6/12 ml-auto mr-auto" alt="">
                <h1 class="text-2xl mb-6 font-bold text-white text-center">Qual o objetivo da Fábrica ?</h1>
                <p class="text-base text-white text-justify">Promover o encontro entre empresas e academia,
                    possibilitando que os alunos coloquem em prática o que estão aprendendo nas aulas assim
                    como tenham contato com projetos reais.
                </p>
            </div>

            <div class="w-full mt-16">
                <img src="img/propor-app.png" class="w-6/12 ml-auto mr-auto" alt="">
                <h1 class="text-2xl mb-6 font-bold text-white text-center">Como propor projeto ?</h1>
                <p class="text-base text-white text-justify">A proposta de projetos deverá ser feita dentro da plataforma, 
                    preenchendo todos os dados solicitados e descrevendo a proposta, com documentos e informações. 
                    É necessário salientar que o cliente deve estar ciente das regras propostas pela plataforma.
                </p>
            </div>

            <div class="w-full mt-16">
                <img src="img/quem-desenvolve.png" class="w-6/12 ml-auto mr-auto" alt="">
                <h1 class="text-2xl mb-6 font-bold text-white text-center">Quem Desenvolve ?</h1>
                <p class="text-base text-white text-justify">Os alunos que se cadastrarem na fabrica poderão desenvolver os 
                    projetos disponíveis na plataforma, com acompanhamento de professores, 
                    mentores e os clientes propusentes.
                </p>
            </div>
        </div>

        <div>
            <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 100 C40 90 60 90 100 100 Z" />
            </svg>
        </div>
    </div>
    <div id="sobre" class="block mt-16 mx-auto mt-10">
        <div class="w-100">
            <h1 class="text-center text-4xl mb-10 font-bold">Sobre</h1>
            <p class="text-center">O projeto é desenvolvido por alunos da Universidade São Judas Tadeu e para o
                auxílio do
                desenvolvimento temos professores para administrar os grupos.</p>
        </div>
    </div>
    <div class="footer yellowground mt-12 text-center">
        <div class="rodar">
            <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 100 C40 90 60 90 100 100 Z" />
            </svg>
        </div>
        <div class="block mb-36 ml-auto mr-auto p-3">
            <p class="font-baloo2 ml-auto font-bold text-xl">
                Coloque seu negócio em um próximo nível, e deixe a gente te ajudar
            </p>
            <div class="mr-auto block mt-6">
                <button class="font-baloo2 white text-black p-2 uppercase rounded px-2 rounded-md shadow-xl">
                    <a class="col-end-13 link text-black uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/create-account">cadastrar seu
                    projeto </a>
                </button>
                <p class="font-baloo2 mr-auto">
                    <a class="col-end-13 link text-white uppercase font-bold text-sm" target="_blank" href="https://fabrica-user-client.herokuapp.com/create-account">ou Login ›</a>
                    
                </p>
            </div>
        </div>
        <div class="block p-3">
            <img class="ml-auto mr-auto" src="img/ustj-flex.png" alt="">
            <img class="ml-auto mr-auto mt-8" src="img/ustj-n.png" alt="">
        </div>
        <div>
            <svg id="bigHalfCircle" fill="#FFF" xmlns="http://www.w3.org/2000/svg" version="1.1" width="100%"
                height="100" viewBox="0 0 100 100" preserveAspectRatio="none">
                <path d="M0 100 C40 90 60 90 100 100 Z" />
            </svg>
        </div>
    </div>
    <div class="">
        <h1 class="text-center">
            <a class="p-6 underline " href="">Termos de uso</a>
        </h1>
    </div>
</div>
</div>

</template>

<script>
import 'alpinejs'

export default {
  name: 'Landing',
  data() {
      return {
          showMenu: false
      }
    },
  props: {
    msg: String
  },
  methods: {
      openMenu(){
        this.showMenu = true
      },
      hideMenu(){
          this.showMenu = false
      }
    },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@import '../assets/style.css';
.bottom{
    bottom: 20px;
    position: absolute !important;
}
.container {
  position: relative;
}
.text-block {
  position: absolute;
  bottom: 20px;
  right: 20px;
  background-color: black;
  color: white;
  padding-left: 20px;
  padding-right: 20px;
}
.tumb-1{
  position: relative;
}
.absolute-card{
  position: absolute;
}
.footer{
        left: 0;
        bottom: 0;
        width: 100%;
        color: white;
        text-align: center;
    }

    .font-official {
        font-family: 'Montserrat', sans-serif;
    }

    .font-baloo2 {
        font-family: 'Baloo Bhai 2', cursive;
    }

    .font-baloo2-bold {
        font-family: 'Baloo 2', cursive;
    }

    .btn-color {
        color: #fff;
        background-color: #FF9700;
    }

    .description {
        color: #9FA2B4;
    }

    .link {
        color: #299EF3;
    }

    .blueground {
        background-color: #299EF3;
    }

    .yellowground{
        background-color: #FF9700;
    }

    .white {
        background-color: #fff;
    }

    .rodar {
        transform: rotate(180deg);
    }

    .tumb-1 {
        background-image: url(../../public/img/tumb-1.png);
    }
</style>
