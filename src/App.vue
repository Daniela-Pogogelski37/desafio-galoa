<template>

    <div class="flex flex-col md:flex-row">

        <div class="flex flex-row justify-between  items-center h-12 m-2 md:hidden">
            <a href="#">
                <div class="flex flex-row items-center box-language justify-center">
                <img src="public/lng-img.svg" alt="language" />
                <div class="ml-1 mr-1 text-gray-dark font-quicksand text-sm w-10-5">PT, BR</div>
                    <img src="public/dropdown.svg" alt="dropdown arrow" height="4" width="6" />
                </div>
            </a>
            <div class="flex flex-col text-right text-gray-dark font-quicksand">
                <div class="text-sm">Bem vindo!</div>
                <div class="mt-1 text-xs">alguem12@galoascience.com</div>
            </div>
            <a href="#" class="">
                <div class="relative flex items-center">
                    <img class="rounded-full w-10 h-10" src="public/foto.png" />
                    <div class="absolute -top-1 right-0 h-4 w-4 my-1 rounded-full z-2 bg-badge flex place-content-center">
                        <span class="text-white -mt-1">2</span>
                    </div>
                </div>
            </a>
        </div>

        <div id="side-menu" class="mb-8 flex flex-col z-10 md:mb-0 h-screen box-side-menu">
            <div class="grid grid-cols-1 place-content-center w-full side-menu-title">
                <span class="w-full text-center text-3xl text-white font-roboto-700">SLACA 2019</span>
            </div>
            <div class="flex w-full place-content-center">
                <img src="public/img-01.png" />
            </div>
            <div class="flex flex-col divide-y-2 font-quicksand text-menu">
                <div class="place-content-center flex flex-col h-8">
                    <a href="#" class="ml-8">Apresentação</a>
                </div>
                <div class="h-8 place-content-center flex flex-col">
                    <a href="#" class="ml-8">Comitês</a>
                </div>
                <div class="h-8 place-content-center flex flex-col">
                    <a href="#" class="ml-8">Autores</a>
                </div>
                <div class="h-8 place-content-center flex flex-col">
                    <a href="#" class="ml-8">Eixos temáticos</a>
                </div>
                <div class="h-8 flex bg-color-orange">
                    <div class="lbar-menu inline h-full">&nbsp;</div>
                    <a href="#" class="mt-1 ml-8">Trabalhos</a>    
                </div>
                <div class="h-8 place-content-center flex flex-col">
                    <a href="#" class="ml-8">Contato</a>
                </div>
                <div></div>
            </div>
        </div>

        <div class="-mt-32 md:-mt-0 md:overflow-auto md:relative flex flex-col w-full h-screen z-0">

            <div id="header" class="bg-color-orange flex flex-col md:flex-row justify-between">

                <div class="m-2 md:m-0 md:ml-9 font-roboto text-color-01">
                    <div class="mt-1.5 text-header-01">Anais do Simpósio Latino Americano de Ciências de Alimentos</div>
                    <div class="mt-0.5 text-header-02">Anais do 13º Simpósio Latino Americano de Ciência de Alimentos</div>
                    <div class="-mt-1 text-header-01">ISSN: 1234-5678</div>
                </div>

                <div class="mr-9 mb-3 flex flex-col md:flex-row place-content-center items-center hidden md:flex">
                    <a href="#" class="md:mt-3">
                        <div class="flex flex-row items-center mr-20 box-language justify-center">
                        <img src="public/lng-img.svg" alt="language" />
                        <div class="ml-1 mr-1 text-gray-dark font-quicksand text-sm w-10-5">PT, BR</div>
                            <img src="public/dropdown.svg" alt="dropdown arrow" height="4" width="6" />
                        </div>
                    </a>
                    <div class="md:mr-4 md:mt-3 flex flex-col text-right text-gray-dark font-quicksand">
                        <div class="text-sm">Bem vindo!</div>
                        <div class="mt-1 text-xs">alguem12@galoascience.com</div>
                    </div>
                    <a href="#" class="md:mt-3">
                        <div class="relative flex items-center">
                            <img class="rounded-full" src="public/foto.png" width="48" height="30" />
                            <div class="absolute -mt-1 top-0 right-0 h-5 w-5 my-1 rounded-full z-2 bg-badge flex place-content-center">
                                <span class="text-white -mt-0.5">2</span>
                            </div>
                        </div>
                    </a>
                </div>

            </div>
    
            <div id="content" class="mt-8 m-2 md:mt-0 md:m-0 md:ml-10 flex flex-col place-items-start z-0">
                <div class="flex flex-col md:flex-row justify-between w-full md:mt-6">
                    <div class="ml-4 md:ml-0 text-center md:text-left text-orange font-roboto-900 text-sm md:text-2xl w-video-box">
                        Análise sensorial de preparações funcionais desenvolvidas para escolares entre 09 e 15 anos, do município de Campinas/SP 
                    </div>
                    <div class="mt-8 md:mt-0 flex flex-col mr-10 w-full md:w-auto">
                        <div class="flex flex-row gap-6 md:gap-2 items-center place-content-center">
                            <button class="w-32 h-12 md:h-8 btn-orange text-white flex items-center justify-center gap-2">
                                <i class="fa fa-download" aria-hidden="true"></i>
                                <span class="font-roboto-500 text-base">Download</span>
                            </button>
                            <button class="w-12 md:w-11 h-12 md:h-8 btn-orange text-white flex items-center justify-center">
                                <i class="fas fa-star"></i>
                            </button>
                            <button class="w-12 md:w-11 h-12 md:h-8 btn-orange text-white flex items-center justify-center">
                                <img src="public/doi.svg">
                            </button>    
                        </div>
                        <div class="mt-4 md:mt-0 font-roboto-500 text-orange text-base flex items-center place-content-center h-full">
                            <a href="#" class="mt-3">COMO CITAR ESSE TRABALHO?</a>
                        </div>
                    </div>
                </div>
                <div class="flex flex-col md:flex-row justify-between w-full mt-6 items-center">
                    <div class="w-video-box h-video-box">
                        <iframe class="w-full h-full" src="https://www.youtube.com/embed/tgbNymZ7vqY">
                        </iframe>
                    </div>
                    <div class="box-details w-80 mt-8 md:mt-0 md:mr-10">
                        <div class="box-details-top bg-color-orange flex items-center">
                            <span class="ml-4 text-color-02 text-lg font-roboto-500">Detalhes</span>
                        </div>
                        <div class="overflow-auto box-content-details text-gray-dark2 font-quicksand m-4">
                            <div class="text-sm">
                                <p>Tipo de Apresentação: <span class="font-bold">Pôster</span></p>
                                <p>Eixo temático: <span class="font-bold">Alimentação e saúde (AS)</span></p>
                                <p>Palavras-chaves: <span class="font-bold">Alimentos funcionais, alimentação escolar.</span></p>
                            </div>
                            <div class="mt-8 text-base">
                                <p><span class="font-bold">Autores:</span></p>
                                <p>Galileo Galilei<sup>1</sup></p>
                                <p>Berta Lange de Morretes<sup>2</sup></p>
                                <p>Isaac Newton<sup>3</sup></p>
                                <p>Cesar Lattes<sup>1</sup></p>
                                <p>Stephen Hawking<sup>4</sup></p>
                            </div>
                            <div class="mt-12 text-sm">                            
                                <p><sup>1</sup>Universidade Estadual de Campinas</p>
                                <p><sup>2</sup>Universidade de São Paulo</p>
                                <p><sup>3</sup>Instituto Nacional de Pesquisas Espaciais</p>
                                <p><sup>4</sup>Universidade Federal do Rio de Janeiro</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="resumo" class="mt-8 w-full flex flex-col items-center">
                    <div class="box-generic-full w-80 md:w-auto md:mr-10">
                        <div class="box-generic-full-top bg-color-orange flex items-center">
                            <span class="ml-4 text-color-02 text-lg font-roboto-500">Resumo</span>
                        </div>
                        <div class="text-gray-dark2 text-sm font-quicksand m-4">
                            <span id="descricao-less-hdnl">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus vitae turpis auctor, mollis felis ut, commodo turpis. Phasellus felis mauris, egestas eget cursus et, iaculis quis lacus. Fusce auctor eros sed magna ultricies gravida. Etiam aliquam dictum nisl, vel aliquet enim accumsan sit amet. Donec finibus nisi tellus, ut viverra lorem vestibulum ut.  Phasellus condimentum orci id leo condimentum lobortis et non lorem. Sed id nisl metus. Quisque sollicitudin ligula in sapien scelerisque, ac gravida eros vestibulum Phasellus condimentum orci id leo condimentum lobortis et non lorem. Sed id nisl metus. Quisque sollicitudin ligula in sapien scelerisque, ac gravida eros vestibulum.  Etiam aliquam dictum nisl, vel aliquet enim accumsan sit ametl accumsant... 
                            </span>
                            <a id="descricao-more" href="javascript:void(0);" onclick="document.getElementById('descricao-less-hdnl').style.display='none';document.getElementById('descricao-more-hdnl').style.display='block';document.getElementById('descricao-more').style.display='none';" class="text-orange font-bold">ver mais</a>
                            <span id="descricao-more-hdnl" class="hidden">
                                <p class="mt-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus vitae turpis auctor, mollis felis ut, commodo turpis. Phasellus felis mauris, egestas eget cursus et, iaculis quis lacus. Fusce auctor eros sed magna ultricies gravida. Etiam aliquam dictum nisl, vel aliquet enim accumsan sit amet. Donec finibus nisi tellus, ut viverra lorem vestibulum ut. Phasellus condimentum orci id leo condimentum lobortis et non lorem. Sed id nisl metus. Quisque sollicitudin ligula in sapien scelerisque, ac gravida eros vestibulum.</p>
                                <p class="mt-4">Fusce vitae luctus dui. Donec id euismod mauris, in volutpat urna. Proin dapibus consequat feugiat. Proin dictum justo arcu, quis vestibulum augue lacinia quis. Sed dignissim dui nulla, ut faucibus mauris sodales id. Aliquam erat volutpat. Maecenas dolor enim, tincidunt id elit non, suscipit interdum turpis. Etiam finibus urna libero, eget interdum eros volutpat ullamcorper. Pellentesque et pretium lorem. Aenean interdum quis diam ac porttitor. Cras nec ipsum pulvinar, pharetra libero non, ornare enim. Etiam in laoreet odio.</p>                                
                                <p class="mt-4">Nam eget tristique elit, at fermentum tellus. Mauris scelerisque ligula id eleifend feugiat. Donec eleifend vehicula sem nec dapibus. Integer scelerisque neque dui, in lacinia erat molestie eu. Phasellus maximus dui eget lacus porta tempor. Ut ex nibh, dignissim quis purus semper, efficitur facilisis turpis. Praesent blandit elementum ultricies. Aliquam sit amet enim sit amet nulla pulvinar lobortis consectetur non odio. Phasellus at lacus hendrerit, vulputate nisi sit amet, viverra mauris. Etiam eu scelerisque orci. Quisque sagittis, mi vitae pharetra iaculis, orci elit eleifend massa, eu posuere mauris odio id odio. Morbi eu libero luctus, consectetur lorem vel, interdum sapien. Aenean in porta arcu. Maecenas eu maximus massa.</p>
                                <p class="mt-4">Praesent velit dolor, dignissim sed quam ac, efficitur porta justo. Pellentesque porta pharetra felis ut hendrerit. Nulla facilisi. Aliquam erat volutpat. Nunc sit amet faucibus quam. Maecenas dapibus luctus dolor at viverra. Duis nec fringilla libero. Duis risus nibh, viverra ac orci nec, iaculis dictum sem. Aliquam at malesuada arcu. Aliquam erat volutpat. Donec varius ipsum purus, ut vehicula purus placerat vitae. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p> 
                            </span>
                        </div>
                    </div>
                </div>
                <div id="discussoes" class="mt-8 w-full flex flex-col items-center md:items-stretch">
                    <div class="box-generic-full w-80 md:w-auto md:mr-10">
                        <div class="box-generic-full-top bg-color-orange flex items-center">
                            <span class="ml-4 text-color-02 text-lg font-roboto-500">Discussões</span>
                        </div>
                        <div class="flex flex-col items-center">

                            <div id="box-topic-st-01" class="w-full flex flex-col items-center">
                                <span class="w-full text-center text-lg text-orange font-roboto-700 mt-5">
                                    Compartilhe suas ideias ou dúvidas com os autores!
                                </span>
                                <div class="flex flex-row justify-center md:justify-between w-120 gap-4 md:gap-20 mt-8">
                                    <img src="public/icone1.svg">
                                    <img src="public/icone2.svg">
                                    <img src="public/icone3.svg">
                                </div>
                                <div class="p-8 text-gray-dark3 text-center font-quicksand text-sm mt-5">
                                    <p>Sabia que o maior estímulo no desenvolvimento científico e cultural é a curiosidade?</p>
                                    <p>Deixe seus questionamentos ou sugestões para o autor!</p>
                                </div>

                                <div class="grid grid-cols-1 divide-y-2 w-full p-4 place-content-center z-5">
                                    <div></div>
                                    <div></div>
                                </div>

                                <button class="p-2 gap-2 items-center flex flex-row text-base btn-orange text-white -mt-10 z-10" onclick="document.getElementById('box-topic-st-01').classList.add('hidden');document.getElementById('box-topic-st-02').classList.remove('hidden');">
                                    <i class="ml-2 fas fa-plus"></i>
                                    <span class="mr-2 font-quicksand-700">criar tópico</span>
                                </button>    
    
                            </div>

                            <div id="box-topic-st-02" class="w-full flex flex-col items-center -mt-8 hidden">
                                <span class="p-8 text-gray-dark2 text-center font-quicksand text-sm mt-5">
                                        Tem uma dúvida ou sugestão? Compartilhe seu feedback com os autores!
                                </span>
                                <div class="flex flex-col w-full px-4 -mt-4">
                                    <div class="w-full text-left text-lg text-orange font-roboto-700 mt-5">
                                        Assunto
                                    </div>    
                                    <input type="text" placeholder="Defina um tópico sucinto para notificar os autores..." class="px-4 txt-input w-full text-gray-dark3 font-quicksand" />
                                </div>
                                <div class="flex flex-col place-content-start w-full px-4">
                                    <div class="w-full text-left text-lg text-orange font-roboto-700 mt-5">
                                        Conte&uacute;do
                                    </div>    
                                    <textarea class="p-4 html-input w-full text-gray-dark3 font-quicksand"></textarea>                                    
                                    <div class="w-full html-input-menu flex flex-row justify-between">
                                        <div class="flex flex-row items-center ml-8 gap-4">
                                            <a href="#"><img src="public/bold-btn.svg" width="13" height="10" /></a>
                                            <a href="#"><img src="public/italic-btn.svg" width="15" height="10" /></a>
                                        </div>
                                        <button class="btn-send-form-topic h-full font-quicksand-700 text-white px-2 md:px-20"  onclick="document.getElementById('box-topic-st-02').classList.add('hidden');document.getElementById('box-topic-st-03').classList.remove('hidden');">Enviar</button>
                                    </div>
                                </div>

                                <div class="grid grid-cols-1 divide-y-2 w-full p-4 place-content-center z-5">
                                    <div></div>
                                    <div></div>
                                </div>
                            </div>

                            <div id="box-topic-st-03" class="w-full flex flex-col items-center hidden">
                                <span class="w-full text-center text-lg text-orange font-roboto-700 mt-5">
                                    Seu tópico foi enviado com sucesso! :D
                                </span>
                                <div class="px-8 py-4 text-gray-dark3 text-center font-quicksand text-sm">
                                    <p>Agradecemos por sua contribuição, uma notificação será enviada ao seu email assim que seu tópico for respondido!</p>
                                </div>
                                <span class="w-full text-center text-orange font-quicksand-500-2 text-sm mt-8 underline mb-12">
                                    <a href="#">Descubra outros trabalhos!</a>
                                </span>

                                <div class="grid grid-cols-1 divide-y-2 w-full p-4 place-content-center z-5">
                                    <div></div>
                                    <div></div>
                                </div>

                                <button class="p-2 gap-2 items-center flex flex-row text-base btn-orange text-white -mt-10 z-10" onclick="document.getElementById('box-topic-st-03').classList.add('hidden');document.getElementById('box-topic-st-02').classList.remove('hidden');document.getElementById('box-topic-st-02').classList.remove('block');">
                                    <span class="mr-2 px-12 font-15 font-quicksand-700">criar novo tópico</span>
                                </button>    

                                <div class="relative md:mb-0 mb-6 p-4 w-full z-5">
                                    <div class="absolute z-10 px-4 w-full h-full">
                                        <div class="flex flex-col place-content-center items-center w-full h-full pr-8 pb-2 gap-2">
                                            <i class="fas fa-check-double text-gray-1"></i>
                                            <span class="font-quicksand-700 text-sm text-gray-1 md:text-base">Aguardando feedback dos autores</span>
                                            <span class="w-full text-center text-orange font-quicksand-500-2 text-sm mt-4 underline mb-12">
                                                <a href="#">Editar tópico</a>
                                            </span>            
                                        </div>
                                    </div>
                                    <div class="box-topic-blur w-full flex flex-col p-4">
                                        <span class="text-orange  font-quicksand-700">Assunto da pergunta aparece aqui</span>
                                        <span class="text-gray-dark2 font-quicksand-500">Carlos Henrique Santos</span>
                                        <span class="text-gray-dark3 font-quicksand mt-2 hidden md:block">Comecinho da pergunta aparece aqui resente relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo...</span>
                                    </div>    
                                </div>
    
                            </div>

                            <div class="mt-4 md:mt-0 p-4 w-full cursor-pointer">
                                <div class="box-topic w-full flex flex-col p-4">
                                    <span class="text-orange  font-quicksand-700">Assunto da pergunta aparece aqui</span>
                                    <span class="text-gray-dark2 font-quicksand-500">Carlos Henrique Santos</span>
                                    <span class="text-gray-dark3 font-quicksand mb-6 mt-2 hidden md:block">Comecinho da pergunta aparece aqui resente relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo...</span>
                                    <div class="flex flex-row items-end gap-4 h-full">
                                        <a href="#">
                                            <i class="text-orange fas fa-1x fa-ellipsis-v"></i>
                                        </a>
                                        <button class="w-7 h-5 btn-orange text-white flex items-center justify-center">
                                            <i class="fas fa-heart"></i>
                                        </button>
                                        <span class="text-gray-dark4 font-segoe-ui">1 like</span>
                                        <span class="text-gray-dark4 font-segoe-ui">1 resposta</span>
                                    </div>
                                </div>    
                            </div>
                            <div id="box-exp-topic-st-01" class="cursor-pointer md:mb-0 mb-6 p-4 w-full" onclick="document.getElementById('box-exp-topic-st-01').classList.add('hidden');document.getElementById('box-exp-topic-st-02').classList.remove('hidden');document.getElementById('box-exp-topic-st-02').classList.remove('block');">
                                <div class="box-topic w-full flex flex-col p-4">
                                    <span class="text-orange  font-quicksand-700">Assunto da pergunta aparece aqui</span>
                                    <span class="text-gray-dark2 font-quicksand-500">Carlos Henrique Santos</span>
                                    <span class="text-gray-dark3 font-quicksand mt-2 mb-6 hidden md:block">Comecinho da pergunta aparece aqui resente relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo...</span>
                                    <div class="flex flex-row items-end gap-4 h-full">
                                        <a href="#">
                                            <i class="text-orange fas fa-1x fa-ellipsis-v"></i>
                                        </a>
                                        <button class="w-7 h-5 btn-orange text-white flex items-center justify-center">
                                            <i class="fas fa-heart"></i>
                                        </button>
                                        <span class="text-gray-dark4 font-segoe-ui">1 like</span>
                                        <span class="text-gray-dark4 font-segoe-ui">1 resposta</span>
                                    </div>
                                </div>    
                            </div>

                            <div id="box-exp-topic-st-02" class="cursor-pointer p-4 md:mb-0 mb-6 w-full hidden" onclick="document.getElementById('box-exp-topic-st-02').classList.add('hidden');document.getElementById('box-exp-topic-st-01').classList.remove('hidden');document.getElementById('box-exp-topic-st-01').classList.remove('block');">

                                <div class="box-topic-exp md:mb-0 mb-6 w-full">
                                    <div class="box-comment-exp w-full flex flex-col p-4">
                                        <span class="text-orange  font-quicksand-700">Assunto da pergunta aparece aqui</span>
                                        <span class="text-gray-dark2 font-quicksand-700 text-sm">Carlos Henrique Santos</span>
                                        <span class="text-gray-dark3 font-quicksand mt-2  mb-6">
                                            Comecinho da pergunta aparece aqui resente relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo resente relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo?
                                        </span>
                                        <div class="flex flex-row items-end gap-4 h-full">
                                            <a href="#">
                                                <i class="text-orange fas fa-1x fa-ellipsis-v"></i>
                                            </a>
                                            <button class="w-7 h-5 btn-orange text-white flex items-center justify-center">
                                                <i class="fas fa-heart"></i>
                                            </button>
                                            <span class="text-gray-dark4 font-segoe-ui">1 like</span>
                                            <span class="text-gray-dark4 font-segoe-ui">1 resposta</span>
                                        </div>
                                    </div>    
                                    <div class="relative box-comment w-full flex flex-col p-4">
                                        <div class="absolute top-0 right-0 mr-10 mt-4 flex flex-row gap-10">
                                            <span class="text-base text-orange font-quicksand-700">Autor</span>
                                            <i class="fas fa-1x fa-check-double text-orange"></i>
                                        </div>
                                        <span class="text-gray-dark2 font-quicksand-700 text-sm">Adriano da Silva</span>
                                        <span class="text-gray-dark3 pr-14 font-quicksand mt-2">
                                            <p>Resposta do autor é aqui. Relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo resente relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo.</p>
                                        </span>
                                    </div>    
                                    <div class="box-comment-reply w-full flex flex-col p-4">
                                        <span class="text-gray-dark2 font-quicksand-700 text-sm">Carlos Henrique Santos</span>
                                        <span class="text-gray-dark3 font-quicksand mt-2">
                                            <p>Consegui entender melhor agora! Parece que a variação da análise da dimensão e impacto de processo formativo situado impacto de processo formativo.</p>
                                            <p>&nbsp;</p>
                                            <p>Obrigada pela resposta, muito interessante o seu trabalho!</p>
                                        </span>
                                    </div>    
                                    <div class="relative box-comment w-full flex flex-col p-4">
                                        <div class="absolute top-0 right-0 mr-10 mt-4 flex flex-row gap-10">
                                            <span class="text-base text-orange font-quicksand-700">Coautor</span>
                                            <i class="fas fa-1x fa-check-double text-orange"></i>
                                        </div>
                                        <span class="text-gray-dark2 font-quicksand-700 text-sm">Carmila Ferreira Andrade</span>
                                        <span class="text-gray-dark3 pr-14 font-quicksand mt-2">
                                            <p>Também ínteressante lembrar que o relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo resente relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo.</p>
                                            <p>&nbsp;</p>
                                            <p>Situado impacto de processo formativo processo resente relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo.</p>
                                        </span>
                                    </div>    
                                    <div class="relative box-comment w-full flex flex-col p-4">
                                        <div class="absolute top-0 right-0 mr-10 mt-4 flex flex-row gap-10">
                                            <span class="text-base text-orange font-quicksand-700">Coautor</span>
                                            <i class="fas fa-1x fa-check-double text-orange"></i>
                                        </div>
                                        <span class="text-gray-dark2 font-quicksand-700 text-sm">Ana Carolina</span>
                                        <span class="text-gray-dark3 pr-14 font-quicksand mt-2">
                                            <p>Resposta do autor é aqui. Relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo resente relato inscreve-se no campo da análise da dimensão e impacto de processo formativo situado impacto de processo formativo processo.</p>
                                        </span>
                                    </div>    

                                </div>
    
                            </div>

                        </div>
                    </div>
                </div>
            </div>
    
            <div id="footer" class="mt-12 text-orange">
                <img src="public/img-footer.png">
            </div>
    
        </div>

    </div>

</template>

<script>
</script>

<style>

.box-side-menu {
    box-shadow: 0px 0px 0px;
}

@media ( min-width: 600px ) {
    .box-side-menu {
        box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.25);
    }    
}

.side-menu-title {
    background: linear-gradient(180deg, #FFB354 0%, #EE7A3A 100%);
    height: 68px;
}

.text-menu {
    font-weight: 500;
    font-size: 15px;
    line-height: 19px;
}

.lbar-menu {
    width: 5px;
    background: linear-gradient(180deg, #FFB455 0%, #ED7839 100%);
}

.text-header-01 {
    font-size: 10px;
    line-height: 16px;
}

.text-header-02 {
    font-size: 16px;
    line-height: 18px;
}

@media ( min-width: 600px ) {

    .text-header-01 {
        font-size: 14px;
        line-height: 16px;
    }
    
    .text-header-02 {
        font-size: 22px;
        line-height: 26px;
    }
    
}

.bg-badge {
    background: #F85959;
    border-radius: 10px;
}

.box-language {
    border: 1px solid #CCCCCC;
    box-sizing: border-box;
    border-radius: 3px;
    width: 97px;
    min-height: 34px;    
}

.btn-orange {
    background: #ED7839;
    border-radius: 4px;
}

.w-video-box {
    width: 90%;
}

@media ( min-width: 600px ) {
    .w-video-box {
        width: 783px;
    }
}

.h-video-box {
    height: auto;
}

@media ( min-width: 600px ) {
    .h-video-box {
        height: 439px;
    }
}

.box-details {
    border: 1px solid #ECECEC;
    min-height: 439px;
}

.box-details-top {
    min-height: 45px;    
    border: 1px solid #ECECEC;
    box-sizing: border-box;
    border-radius: 3px 3px 0px 0px;
}

.box-content-details {
    min-height: 349px;    
}

.box-generic-full {
    border: 1px solid #ECECEC;
}

.box-generic-full-top {
    min-height: 45px;    
    border: 1px solid #ECECEC;
    box-sizing: border-box;
    border-radius: 3px 3px 0px 0px;
}

.w-10-5 {
    width: 42px;
}

.text-orange {
    color: #ED7839;
}

.text-gray-dark {
    color: #333333;
}

.text-gray-dark2 {
    color: #5C5C5C;
}

.text-gray-dark3 {
    color: #4D4D4D;
}

.text-gray-dark3 {
    color: #595959;
}

.text-gray-dark4 {
    color: #757575;    
}

.text-gray-1 {
    color: #707070;    
}


.text-color-01 {
    color: #725C5C;
}

.text-color-02 {
    color: #4E4E4E;
}

.bg-color-orange {
    background: #FDF1EB;
}

.font-roboto {
    font-family: Roboto;
    font-weight: 400;
}

.font-roboto-500 {
    font-family: Roboto;
    font-weight: 500;
}

.font-roboto-700 {
    font-family: Roboto;
    font-weight: 700;
}

.font-roboto-900 {
    font-family: Roboto;
    font-weight: 900;
}

.font-quicksand {
    font-family: Quicksand;
}

.font-quicksand-400 {
    font-family: Quicksand;
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 18px;    
}

.font-quicksand-500 {
    font-family: Quicksand;
    font-size: 12px;
    font-style: normal;
    font-weight: 500;
    line-height: 15px;
}

.font-quicksand-500-2 {
    font-family: Quicksand;
    font-style: normal;
    font-weight: 500;
}

.font-quicksand-700 {
    font-family: Quicksand;
    font-weight: 700;
    font-style: normal;
    font-weight: bold;
}

.font-15 {
    font-size: 15px;
}

.font-segoe-ui {
    font-family: Segoe UI;
    font-style: normal;
    font-weight: 350;
    font-size: 14px;
    line-height: 19px;
}

.btn-orange {
    background: linear-gradient(180deg, #FEB254 0%, #F0813D 100%);
    box-shadow: 0px 0px 2px rgba(0, 0, 0, 0.12), 0px 2px 2px rgba(0, 0, 0, 0.24);
    border-radius: 4px;
}

.box-topic {
    min-height: 148px;
    background: #FFFFFF;
    border: 1px solid #E7E7E7;
    box-sizing: border-box;
    box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.12);
    border-radius: 4px;
}

.box-topic-blur {
    min-height: 148px;
    background: #FAFAFA;
    border: 1px solid #E7E7E7;
    box-sizing: border-box;
    border-radius: 4px;
    filter:blur(2px);
}

.txt-input {
    background: #FFFFFF;
    border: 1px solid #CCCCCC;
    box-sizing: border-box;
    border-radius: 3px;
    height: 39px;
}

.html-input {
    background: #FFFFFF;
    border: 1px solid #CCCCCC;
    box-sizing: border-box;
    border-radius: 3px;
    height: 82px;
}

.html-input-menu {
    background: #EAF1F2;
    border: 1px solid #CCCCCC;
    box-sizing: border-box;
    border-radius: 0px 0px 4px 4px;
    height: 31px;
}

.btn-item-html-input {
    width: 13px;
    height: 10px;
}

.btn-send-form-topic {
    background: linear-gradient(180deg, #FEB154 0%, #F1833E 100%);
    border-radius: 0px 0px 4px 0px;
}

.box-topic-exp {
    background: #FFFFFF;
    border: 1px solid #E7E7E7;
    box-sizing: border-box;
    border-radius: 0px;
}

.box-comment {
    background: #F8F8F8;
    border: 1px solid #E7E7E7;
    box-sizing: border-box;
    border-radius: 0px;
    min-height: 131px;
}

.box-comment-reply {
    background: #FFFFFF;
    border: 1px solid #E7E7E7;
    box-sizing: border-box;
    border-radius: 0px;
    min-height: 131px;
}

.box-topic-exp {
    border: 1px solid #E7E7E7;
    box-sizing: border-box;
    box-shadow: 0px 0px 8px rgba(0, 0, 0, 0.12);
    border-radius: 4px;
}

</style>
