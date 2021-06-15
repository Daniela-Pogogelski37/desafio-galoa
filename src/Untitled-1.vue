<template>
<!-- inicio esta focado na tela do celular -->
  <div class="flex flex-col md:flex-row">

        <div class="flex flex-row justify-between  items-center h-12 m-2 md:hidden">
            <a href="#">
                <div class="flex flex-row items-center box-language justify-center">
                <img src="img/lng-img.svg" alt="language" />
                <div class="ml-1 mr-1 txt-lng-box">PT, BR</div>
                    <img src="img/public/seta" alt="dropdown arrow" height="4" width="6" />
                </div>
            </a>
            <div class="flex flex-col text-right text-user-info">
                <div class="text-user-hello">Bem vindo!</div>
                <div class="mt-1 text-user-email">alguem12@galoascience.com</div>
            </div>
            <a href="#" class="">
                <div class="relative flex items-center">
                    <img class="rounded-full w-10 h-10" src="public/ela.png"/>
                    <div class="absolute -top-1 right-0 h-4 w-4 my-1 rounded-full z-2 bg-badge flex place-content-center">
                        <span class="text-white -mt-1">2</span>
                    </div>
                </div>
            </a>
        </div>

        <div id="side-menu" class="mb-8 flex flex-col z-10 md:mb-0 h-screen box-side-menu">
            <div class="grid grid-cols-1 place-content-center w-full side-menu-title">
                <span class="w-full text-center text-3xl text-white font-sans font-bold">SLACA 2019</span>
            </div>
            <div class="flex w-full place-content-center">
                <img src="public/logoslaca.png"/>
            </div>
            <div class="flex flex-col divide-y-2">
                <div class="place-content-center flex flex-col h-8">
                    <a href="#" class="ml-8 text-menu">Apresentação</a>
                </div>
                <div class="h-8 place-content-center flex flex-col">
                    <a href="#" class="ml-8 text-menu">Comitês</a>
                </div>
                <div class="h-8 place-content-center flex flex-col">
                    <a href="#" class="ml-8 text-menu">Autores</a>
                </div>
                <div class="h-8 place-content-center flex flex-col">
                    <a href="#" class="ml-8 text-menu">Eixos temáticos</a>
                </div>
                <div class="h-8 flex menu-selected">
                    <div class="lbar-menu inline h-full">&nbsp;</div>
                    <a href="#" class="mt-1 ml-8 text-menu">Trabalhos</a>    
                </div>
                <div class="h-8 place-content-center flex flex-col">
                    <a href="#" class="ml-8 text-menu">Contato</a>
                </div>
                <div></div>
            </div>
        </div>

        <div class="-mt-32 md:-mt-0 md:overflow-auto md:relative flex flex-col w-full h-screen z-0">

            <div id="header" class="page-header flex flex-col md:flex-row justify-between">

                <div class="m-2 md:m-0 md:ml-9">
                    <div class="mt-1.5 text-header text-header-01">Anais do Simpósio Latino Americano de Ciências de Alimentos</div>
                    <div class="mt-0.5 text-header text-header-02">Anais do 13º Simpósio Latino Americano de Ciência de Alimentos</div>
                    <div class="-mt-1 text-header text-header-03">ISSN: 1234-5678</div>
                </div>

                <div class="mr-9 mb-3 flex flex-col md:flex-row place-content-center items-center hidden md:flex">
                    <a href="#" class="md:mt-3">
                        <div class="flex flex-row items-center mr-20 box-language justify-center">
                        <img src="public/mundo.png" alt="language" />
                        <div class="ml-1 mr-1 txt-lng-box">PT, BR</div>
                            <img src="public/seta.png" alt="dropdown arrow" height="4" width="6" />
                        </div>
                    </a>
                    <div class="md:mr-4 md:mt-3 flex flex-col text-right text-user-info">
                        <div class="text-user-hello">Bem vindo!</div>
                        <div class="mt-1 text-user-email">alguem12@galoascience.com</div>
                    </div>
                    <a href="#" class="md:mt-3">
                        <div class="relative flex items-center">
                            <img class="rounded-full" src="public/ela.png" width="48" height="30" />
                            <div class="absolute -mt-1 top-0 right-0 h-5 w-5 my-1 rounded-full z-2 bg-badge flex place-content-center">
                                <span class="text-white -mt-0.5">2</span>
                            </div>
                        </div>
                    </a>
                </div>

            </div>
    
            <div id="content" class="mt-8 m-2 md:mt-0 md:m-0 md:ml-10 flex flex-col place-items-start z-0">
                <div class="flex flex-col md:flex-row justify-between w-full md:mt-6">
                    <div class="ml-4 md:ml-0 text-center md:text-left text-title-research text-sm md:text-2xl w-video-box">
                        Análise sensorial de preparações funcionais desenvolvidas para escolares entre 09 e 15 anos, do município de Campinas/SP 
                    </div>
                    <div class="mt-8 md:mt-0 flex flex-col mr-10 w-full md:w-auto">
                        <div class="flex flex-row gap-6 md:gap-2 items-center place-content-center">
                            <div class="w-32 h-12 md:h-8 btn-orange text-white flex items-center justify-center">
                                <a href="#" class=" flex items-center justify-center gap-2">
                                    <img src="img/lng-img.svg">
                                    <span>Download</span>
                                </a>
                            </div>
                            <div class="w-12 md:w-11 h-12 md:h-8 btn-orange text-white flex items-center justify-center">
                                <a href="#">
                                    <img src="img/lng-img.svg">
                                </a>
                            </div>
                            <div class="w-12 md:w-11 h-12 md:h-8 btn-orange text-white flex items-center justify-center">
                                <a href="#">
                                    <img src="img/doi.svg">
                                </a>
                            </div>    
                        </div>
                        <div class="mt-4 md:mt-0 text-cit text-base flex items-center place-content-center h-full">
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
                        <div class="box-details-top flex items-center">
                            <span class="ml-4 box-details-title">Detalhes</span>
                        </div>
                        <div class="overflow-auto text-content-details m-4">
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
                        <div class="box-generic-full-top flex items-center">
                            <span class="ml-4 box-details-title">Resumo</span>
                        </div>
                        <div class="box-generic-full-content m-4">
                            <span id="descricao-less-hdnl">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus vitae turpis auctor, mollis felis ut, commodo turpis. Phasellus felis mauris, egestas eget cursus et, iaculis quis lacus. Fusce auctor eros sed magna ultricies gravida. Etiam aliquam dictum nisl, vel aliquet enim accumsan sit amet. Donec finibus nisi tellus, ut viverra lorem vestibulum ut.  Phasellus condimentum orci id leo condimentum lobortis et non lorem. Sed id nisl metus. Quisque sollicitudin ligula in sapien scelerisque, ac gravida eros vestibulum Phasellus condimentum orci id leo condimentum lobortis et non lorem. Sed id nisl metus. Quisque sollicitudin ligula in sapien scelerisque, ac gravida eros vestibulum.  Etiam aliquam dictum nisl, vel aliquet enim accumsan sit ametl accumsant... 
                            </span>
                            <a id="descricao-more" href="javascript:void(0);" onclick="document.getElementById('descricao-less-hdnl').style.display='none';document.getElementById('descricao-more-hdnl').style.display='block';document.getElementById('descricao-more').style.display='none';" class="btn-more">ver mais</a>
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
                        <div class="box-generic-full-top flex items-center">
                            <span class="ml-4 box-details-title">Discussões</span>
                        </div>
                        <div class="box-generic-full-content m-4">
                            <span id="descricao-less-hdnl">
                                Lorem ipsum dolor
                            </span>
                        </div>
                    </div>
                </div>
            </div>
    
            <div id="footer" class="mt-12">
                <img src="img/img-footer.png">
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
    font-family: Quicksand;
    font-style: normal;
    font-weight: 500;
    font-size: 15px;
    line-height: 19px;
}

.menu-selected {
    background-color: #FDF1EB;
}

.lbar-menu {
    width: 5px;
    background: linear-gradient(180deg, #FFB455 0%, #ED7839 100%);
}

.page-header {
    background: #FDF1EB;
}

.text-header {
    color: #725C5C;
    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
}

.text-header-01 {
    font-size: 10px;
    line-height: 16px;
}

.text-header-02 {
    font-size: 16px;
    line-height: 18px;
}

.text-header-03 {
    font-size: 10px;
    line-height: 16px;
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
    
    .text-header-03 {
        font-size: 14px;
        line-height: 16px;
    }
    
}

.text-user-info {
    font-family: Quicksand;
    font-style: normal;
    font-weight: normal;
    color: #333333;
}

.text-user-hello {
    font-size: 14px;
    line-height: 17px;   
}

.text-user-email {
    font-size: 12px;
    line-height: 15px;
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
    height: 34px;    
}

.txt-lng-box {
    font-family: Quicksand;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 17px;
    color: #333333;
    width: 42px;
}

.text-title-research {
    font-family: Roboto;
    font-style: normal;
    font-weight: 900;
    color: #ED7839;
}

.text-cit {    
    font-family: Roboto;
    font-style: normal;
    font-weight: 500;
    color: #ED7839;
}

.btn-orange {
    background: #ED7839;
    border-radius: 4px;
}

.btn-orange span {

    font-family: Roboto;
    font-style: normal;
    font-weight: 500;
    font-size: 16px;

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
    height: 90%;
}

@media ( min-width: 600px ) {
    .h-video-box {
        height: 439px;
    }
}

.box-details {
    border: 1px solid #ECECEC;
    height: 439px;
}

@media ( min-width: 600px ) {
    .box-details {
        border: 1px solid #ECECEC;
    }    
}

.box-details-top {
    height: 45px;    
    background: #FDF1EB;
    border: 1px solid #ECECEC;
    box-sizing: border-box;
    border-radius: 3px 3px 0px 0px;
}

.box-details-title {
    font-family: Roboto;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 25px;
    color: #4E4E4E;
}

.text-content-details {
    font-family: Quicksand;
    color: #5C5C5C;
    height: 349px;    
}

@media ( min-width: 600px ) {
    .text-content-details {
        font-family: Quicksand;
        color: #5C5C5C;
    }    
}

.box-generic-full {
    border: 1px solid #ECECEC;
}

.box-generic-full-top {
    height: 45px;    
    background: #FDF1EB;
    border: 1px solid #ECECEC;
    box-sizing: border-box;
    border-radius: 3px 3px 0px 0px;
}

.box-generic-full-title {
    font-family: Roboto;
    font-style: normal;
    font-weight: 500;
    font-size: 20px;
    line-height: 25px;
    color: #4E4E4E;
}

.box-generic-full-content {
    font-family: Quicksand;
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 23px;
    color: #5C5C5C;
}

.btn-more {
    font-style: bold;
    color: #ED7839;
}
</style>
