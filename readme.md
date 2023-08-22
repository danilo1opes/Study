Registro efetuado durante o processo de desenvolvimento do código.
        

         -webkit = prefixo para Safari Apple
           -moz- = firefox
           -ms- = Internet Explorer

         transition-timing-function: cubic-bezier(0.755, 0.05, 0.855, 0.06);
        (0.755) é a coordenada x do ponto de controle inicial.
        (0.05) é a coordenada y do ponto de controle inicial.
        (0.855) é a coordenada x do ponto de controle final.
        (0.06) é a coordenada y do ponto de controle final. 
        

         transform: translateX...; (Used quando se tem img) 

   
        transform: rotateX(150deg) rotateY(170deg) rotateZ(150deg);    /* X = largura horizontal, Y= altura vertical, Z= apenas quando se trata de transformation 3D*/
        transform-origin: 40% 50px 0;                                 /* valorX,valorY,valorZ (px,%,center...)*/
        transition-timing-function: ease-in-out;

        
        transform-box: border-box;                                /* Aplicará transformações à caixa de borda */
        transform: scale(1.5);                                   /* Aumentará o tamanho do elemento, incluindo margens e bordas */  
         animation: ida 3s ease-in-out infinite alternate;      /* Name---duration---timingFunction---InterationCount----Direction */
 
