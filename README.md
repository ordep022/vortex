:root {
    --branco-principal: #FFFFFF ; 
    --cinza-segundario : #C0C0C0 ;
    --botao-azul : #167bf7;
    --cor-fundo : #00030C;
}

body{
    background-color: var(--cor-fundo);
    color: var(--branco-principal);
}
* {
    margin: 0;
    padding: 0;
}
.principal{
    background-image:url("img/home.png") ;
    background-repeat: no-repeat;
    background-size: contain;

}
.container{
    height: 100vh;
}
.container__botao{
    background-color: #167bf7;
    border-radius: 5px;
    padding:1em;
    color : var(--branco-principal)
}
.botao_secundario{
    background-color: #000000;
    padding:1em;
    border:2px solid var(--branco-principal)
}
