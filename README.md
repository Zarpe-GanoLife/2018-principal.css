
.tachado { text-decoration: line-through; }
hr { margin: 12px 0; border: 0; border-top: 1px solid #e2e2e2; border-bottom: 0px solid #fff;}

.main-sidebar {background-color:#e6e6e6;}
.sidebar-menu>li.header{color:#4b646f;background:#e6e6e6}
.sidebar-menu>li>a{border-left:13px solid transparent}

.icono_menu { width: 13px;}
.alinear_icono_menu { float:left; padding:8px; padding-left:22px; }
h2 { font-size: 26px!important;}
.content-wrapper, .main-footer{-webkit-transition:-webkit-transform .3s ease-in-out,margin .3s ease-in-out;
          -moz-transition:-moz-transform .3s ease-in-out,margin .3s ease-in-out; -o-transition:-o-transform .3s ease-in-out,margin .3s ease-in-out;
          transition:transform .3s ease-in-out,margin .3s ease-in-out; margin-left:230px;z-index:820; }

.ancho_div_cambio { width: 120px;}
.subir_buscar { margin-top: 0px;}





/*  Movil   and (orientation : portrait) */
@media (max-device-width: 1200px)  {
.ocultar_movil { display:none!important;}
.ver_movil { display:inline-block!important;}


.select-style7, .select-style8 { width: 70px!important; background-position: 35px -1px!important;}
.select-style7 select, .select-style8 select { padding: 4px 0px 2px 14px!important;}

.select-style { width: 170px!important; background: #ffffff url(../img/icono_flecha_3.jpg) no-repeat 100% 40%; background-size:30%;}
.select-style5 { width: 120px!important; background: #ffffff url(../img/icono_flecha_3.jpg) no-repeat 100% 40%; background-size:30%;}
.select-style6 { width: 190px!important; background: #ffffff url(../img/icono_flecha_3.jpg) no-repeat 100% 40%; background-size:30%;}

}   



@media (max-device-width:768px){
.ocultar_movil { display:none!important;}
.ver_movil { display:inline-block!important;}

h2 { font-size: 26px!important;}
.subir_salir { margin-top: 15px!important;}
.ocultar_en_tablet2 { visibility: hidden; display: none;}

}


@media (max-device-width:425px){
.ocultar_movil { display:none!important;}
.ver_movil { display:inline-block!important;}

h2 { font-size: 34px!important;}
.icono_menu { width: 35px;}
.sidebar-mini.sidebar-collapse .content-wrapper, .sidebar-mini.sidebar-collapse .right-side, .sidebar-mini.sidebar-collapse .main-footer {
    margin-left: 400px !important;}

.menu_dashboard, .menu_crm, .menu_pedido, .menu_sucursales, .menu_reportes, .menu_finanzas, .menu_rrhh, .menu_sms { background-position: 7px 18px!important;}

.subir_buscar { margin-top: 20px!important;}
.ancho_div_cambio { width: 220px;}
.subir_salir { margin-top: -50px!important;}

.sidebar-menu>li>a { margin-right: 0px; margin-left: -40px; height: 60px!important; line-height: 60px;}
.main-sidebar { -webkit-transform: translate(-400px, 0); -ms-transform: translate(-400px, 0); -o-transform: translate(-400px, 0); 
    /* transform: translate(-230px, 0); */ top: 235px!important; box-shadow: 0px 0px 0px 0px rgba(0,0,0,0.0)!important;}

.sidebar-mini.sidebar-collapse .main-sidebar { -webkit-transition: -webkit-transform .3s ease-in-out,margin .3s ease-in-out;
    -moz-transition: -moz-transform .3s ease-in-out,margin .3s ease-in-out; -o-transition: -o-transform .3s ease-in-out,margin .3s ease-in-out;
    transition: transform .3s ease-in-out,margin .3s ease-in-out; width: 400px !important; z-index: 850;
    box-shadow: 2400px 2000px 0px 2000px rgba(0,0,0,0.5)!important;}

.content-wrapper, .main-footer { -webkit-transition: -webkit-transform .3s ease-in-out,margin .3s ease-in-out;
    -moz-transition: -moz-transform .3s ease-in-out,margin .3s ease-in-out; -o-transition: -o-transform .3s ease-in-out,margin .3s ease-in-out;
    transition: transform .3s ease-in-out,margin .3s ease-in-out; margin-left: 0px!important; z-index: 820;}
.sidebar-mini.sidebar-collapse .content-wrapper, .sidebar-mini.sidebar-collapse .right-side, .sidebar-mini.sidebar-collapse .main-footer {
    margin-left: 400px !important; z-index: 840;}

.sidebar-mini.sidebar-collapse .sidebar-menu>li {padding-left: 40px!important;}
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a, 
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a:hover { padding: 14px 5px 0px 20px!important; margin-right: 0px; margin-left: -40px; 
                                                          height: 70px!important; line-height: 60px;}
.sidebar-mini.sidebar-collapse .main-sidebar { -webkit-transform: translate(0, 0); -ms-transform: translate(0, 0); -o-transform: translate(0, 0);
    transform: translate(0, 0); width: 400px !important; z-index: 850;}
.sidebar-mini.sidebar-collapse .main-sidebar .user-panel>.info,
.sidebar-mini.sidebar-collapse .sidebar-form,
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>span,
.sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu,
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>.pull-right,
.sidebar-mini.sidebar-collapse .sidebar-menu li.header {display: inline-block!important;-webkit-transform:translateZ(0)}


}


@media (max-device-width:375px){
       
}



@media (max-device-width:320px){
}


.ver_movil { display:none;}



@media (max-width:1200px){
.select-style { width: 165px; }
   
}



/* OTRAS resoluciones */
@media (min-device-width: 426px) and (max-device-width: 585px) {  

.icono_menu { width: 35px;}
.sidebar-mini.sidebar-collapse .content-wrapper, .sidebar-mini.sidebar-collapse .right-side, .sidebar-mini.sidebar-collapse .main-footer {
    margin-left: 400px !important;}

.menu_dashboard, .menu_crm, .menu_pedido, .menu_sucursales, .menu_reportes, .menu_finanzas, .menu_rrhh, .menu_sms { background-position: 7px 18px!important;}

.ancho_div_cambio { width: 220px;}
.subir_salir { margin-top: -50px!important;}
.sidebar-menu>li>a { margin-right: 0px; margin-left: -40px; height: 60px!important; line-height: 60px;}
.main-sidebar { -webkit-transform: translate(-400px, 0); -ms-transform: translate(-400px, 0); -o-transform: translate(-400px, 0); 
    /* transform: translate(-230px, 0); */ top: 235px!important; box-shadow: 0px 0px 0px 0px rgba(0,0,0,0.0)!important;}

.sidebar-mini.sidebar-collapse .main-sidebar { -webkit-transition: -webkit-transform .3s ease-in-out,margin .3s ease-in-out;
    -moz-transition: -moz-transform .3s ease-in-out,margin .3s ease-in-out; -o-transition: -o-transform .3s ease-in-out,margin .3s ease-in-out;
    transition: transform .3s ease-in-out,margin .3s ease-in-out; width: 400px !important; z-index: 850;
    box-shadow: 1200px 800px 0px 800px rgba(0,0,0,0.5)!important;}

.content-wrapper, .main-footer { -webkit-transition: -webkit-transform .3s ease-in-out,margin .3s ease-in-out;
    -moz-transition: -moz-transform .3s ease-in-out,margin .3s ease-in-out; -o-transition: -o-transform .3s ease-in-out,margin .3s ease-in-out;
    transition: transform .3s ease-in-out,margin .3s ease-in-out; margin-left: 0px!important; z-index: 820;}
.sidebar-mini.sidebar-collapse .content-wrapper, .sidebar-mini.sidebar-collapse .right-side, .sidebar-mini.sidebar-collapse .main-footer {
    margin-left: 400px !important; z-index: 840;}

.sidebar-mini.sidebar-collapse .sidebar-menu>li {padding-left: 40px!important;}
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a, 
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a:hover { padding: 14px 5px 0px 20px!important; margin-right: 0px; margin-left: -40px; 
                                                          height: 70px!important; line-height: 60px;}
.sidebar-mini.sidebar-collapse .main-sidebar { -webkit-transform: translate(0, 0); -ms-transform: translate(0, 0); -o-transform: translate(0, 0);
    transform: translate(0, 0); width: 400px !important; z-index: 850;}
.sidebar-mini.sidebar-collapse .main-sidebar .user-panel>.info,
.sidebar-mini.sidebar-collapse .sidebar-form,
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>span,
.sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu,
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>.pull-right,
.sidebar-mini.sidebar-collapse .sidebar-menu li.header {display: inline-block!important;-webkit-transform:translateZ(0)}
}

@media (min-device-width: 586px) and (max-device-width: 767px) {  
.main-sidebar { top: 55px!important;}

}



.main-sidebar { box-shadow: 0px 0px 0px 0px rgba(0,0,0,0);}
    
.sidebar-mini.sidebar-collapse .content-wrapper,
.sidebar-mini.sidebar-collapse .right-side,
.sidebar-mini.sidebar-collapse .main-footer{margin-left:50px;z-index:840}
.sidebar-mini.sidebar-collapse .main-sidebar{-webkit-transform:translate(0, 0);-ms-transform:translate(0, 0);
                                             -o-transform:translate(0, 0);transform:translate(0, 0);
                                             width:50px ;z-index:850}
	
@media (min-width:768px){

.mover_izquierda_1 { margin-left:22px; }
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a { background-color: #e6e6e6;   }


.sidebar-mini.sidebar-collapse .icono_inicio, .sidebar-mini.sidebar-collapse .icono_suscripcion,
.sidebar-mini.sidebar-collapse .icono_x5,  .sidebar-mini.sidebar-collapse .icono_x3,
.sidebar-mini.sidebar-collapse .icono_extralife, .sidebar-mini.sidebar-collapse .icono_herramientas,
.sidebar-mini.sidebar-collapse .icono_ayuda { background-position-x: 5px;}
.sidebar-mini.sidebar-collapse .icono_zarpe, .sidebar-mini.sidebar-collapse .icono_genealogia,
.sidebar-mini.sidebar-collapse .icono_comisiones, .sidebar-mini.sidebar-collapse .icono_compras { background-position-x: 3px;}
.sidebar-mini.sidebar-collapse .icono_inscribir, .sidebar-mini.sidebar-collapse .icono_creditos { background-position-x: 7px;}

/* Anterior */

                                                                                        
.sidebar-mini.sidebar-collapse .sidebar-menu>li{position:relative; padding-bottom: 0px;}
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a{margin-right:0px; margin-left:-40px; height: 19px;}
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>span{border-top-right-radius:4px; margin-top: 0px;}
.sidebar-mini.sidebar-collapse .sidebar-menu>li:not(.treeview)>a>span{ border-bottom-right-radius:4px; }
.sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu{padding-top:5px;padding-bottom:5px; margin-left:-50px;
                                                               border-bottom-right-radius:4px}
.sidebar-mini.sidebar-collapse .main-sidebar .user-panel>.info,
.sidebar-mini.sidebar-collapse .sidebar-form,
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>span,
.sidebar-mini.sidebar-collapse .sidebar-menu>li>.treeview-menu,
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>.pull-right,
.sidebar-mini.sidebar-collapse .sidebar-menu li.header {display:none;-webkit-transform:translateZ(0)}

.sidebar-mini.sidebar-collapse .main-header .logo{width:140px}
.sidebar-mini.sidebar-collapse .main-header .logo>.logo-mini{display:block;margin-left:-15px;margin-right:-15px;font-size:18px}
.sidebar-mini.sidebar-collapse .main-header .logo>.logo-lg{display:none}
.sidebar-mini.sidebar-collapse .main-header .navbar{margin-left:230px}



}








    
@media (max-width:767px){.content-wrapper,.main-footer{margin-left:0}}
@media (min-width:768px){
    .sidebar-collapse .content-wrapper,
    .sidebar-collapse .main-footer{margin-left:0}   
}



@media (max-width:767px){
.sidebar-open .content-wrapper,
.sidebar-open .main-footer{-webkit-transform:translate(230px, 0);-ms-transform:translate(230px, 0);
        -o-transform:translate(230px, 0);transform:translate(230px, 0)}
.content-wrapper, .main-footer{padding-right:0px;}
}

.content-wrapper{min-height:100%;background-color:#ffffff;z-index:800;}
.main-footer{background:#fff; padding-right:60px; color:#444;border-top:0px solid #d2d6de}
.fixed .main-header,
.fixed .main-sidebar,
.fixed .left-side{position:fixed}
.fixed .main-header{top:0;right:0;left:0}
.fixed .content-wrapper,
.fixed .right-side{padding-top:50px}

@media (max-width:767px){.fixed .content-wrapper,
                         .fixed .right-side{padding-top:100px}}

.fixed.layout-boxed .wrapper{max-width:100%}.fixed .wrapper{overflow:hidden}
.hold-transition .content-wrapper,
.hold-transition .right-side,
.hold-transition .main-footer,
.hold-transition .main-sidebar,
.hold-transition .left-side,
.hold-transition .main-header .navbar,
.hold-transition .main-header .logo,
.hold-transition .menu-open .fa-angle-left{-webkit-transition:none;-o-transition:none;transition:none}
.content{min-height:250px;padding:15px;margin-right:auto;margin-left:auto;padding-left:15px;
         padding-right:15px}


.page-header{margin:10px 0 20px 0;font-size:22px}
.page-header>small{color:#666;display:block;margin-top:5px}
.main-header{position:relative;max-height:100px;z-index:1030; background:rgba(0,0,0,0.0); width:200px;}
.main-header .navbar{-webkit-transition:margin-left .3s ease-in-out;
                     -o-transition:margin-left .3s ease-in-out;
                     transition:margin-left .3s ease-in-out;
                     margin-bottom:0;margin-left:230px;border:none;min-height:50px;border-radius:0}
.layout-top-nav .main-header .navbar{margin-left:0}
.main-header #navbar-search-input.form-control{background:rgba(255,255,255,0.2);
                                               border-color:transparent}
.main-header #navbar-search-input.form-control:focus,
.main-header #navbar-search-input.form-control:active{border-color:rgba(0,0,0,0.1);
                                                      background:rgba(255,255,255,0.9)}
.main-header #navbar-search-input.form-control::-moz-placeholder{color:#ccc;opacity:1}
.main-header #navbar-search-input.form-control:-ms-input-placeholder{color:#ccc}
.main-header #navbar-search-input.form-control::-webkit-input-placeholder{color:#ccc}
.main-header .navbar-custom-menu,
.main-header .navbar-right{float:right}

@media (max-width:991px){.main-header .navbar-custom-menu a,
                         .main-header .navbar-right a{color:inherit;background:transparent}}
@media (max-width:767px){.main-header .navbar-right{float:none}
                         .navbar-collapse .main-header .navbar-right{margin:7.5px -15px}
                         .main-header .navbar-right>li{color:inherit;border:0}}

.main-header .sidebar-toggle{float:left;background-color:transparent;background-image:none;
                             padding:15px 15px;font-family:fontAwesome}
.main-header .sidebar-toggle:before{content:"\f0c9"}
.main-header .sidebar-toggle:hover{color:#fff}
.main-header .sidebar-toggle:focus,
.main-header .sidebar-toggle:active{background:transparent}
.main-header .sidebar-toggle .icon-bar{display:none}
.main-header .navbar .nav>li.user>a>.fa,
.main-header .navbar .nav>li.user>a>.glyphicon,
.main-header .navbar .nav>li.user>a>.ion{margin-right:5px}
.main-header .navbar .nav>li>a>.label{position:absolute;top:9px;right:7px;text-align:center;font-size:9px;
                                      padding:2px 3px;line-height:.9}
.main-header .logo{-webkit-transition:width .3s ease-in-out;-o-transition:width .3s ease-in-out;
                   transition:width .3s ease-in-out;
                   display:block;float:left;height:62px;font-size:20px;line-height:50px;text-align:center;
                   width:140px;
                   font-family:"Helvetica Neue",Helvetica,Arial,sans-serif;padding:0 15px;font-weight:300;
                   overflow:hidden}
.main-header .logo .logo-lg{display:block}
.main-header .logo .logo-mini{display:none}
.main-header .navbar-brand{color:#fff}
.content-header{position:relative;padding:15px 15px 0 15px}
.content-header>h1{margin:0;font-size:24px}
.content-header>h1>small{font-size:15px;display:inline-block;padding-left:4px;font-weight:300}
.content-header>.breadcrumb{float:right;background:transparent;margin-top:0;margin-bottom:0;font-size:12px;
                            padding:7px 5px;position:absolute;top:15px; right:10px;border-radius:2px}
.content-header>.breadcrumb>li>a{color:#444;text-decoration:none;display:inline-block}
.content-header>.breadcrumb>li>a>.fa,
.content-header>.breadcrumb>li>a>.glyphicon,
.content-header>.breadcrumb>li>a>.ion{margin-right:5px}
.content-header>.breadcrumb>li+li:before{content:'>\00a0'}

@media (max-width:991px){.content-header>.breadcrumb{position:relative;margin-top:5px;top:0;right:0;
                                                     float:none;background:#d2d6de;padding-left:10px}
                         .content-header>.breadcrumb li:before{color:#97a0b3}}

.navbar-toggle{color:#fff;border:0;margin:0;padding:15px 15px}

@media (max-width:991px){
.navbar-custom-menu .navbar-nav>li{float:left}
.navbar-custom-menu .navbar-nav{margin:0;float:left}
.navbar-custom-menu .navbar-nav>li>a{padding-top:15px;padding-bottom:15px;line-height:20px}}

@media (max-width:767px){
.main-header{position:relative}
.main-header .logo,.main-header .navbar{width:100%;float:none}
.main-header .navbar{margin:0}
.main-header .navbar-custom-menu{float:right}}

@media (max-width:991px){
.navbar-collapse.pull-left{float:none !important}
.navbar-collapse.pull-left+.navbar-custom-menu{display:block;position:absolute;top:0;right:40px}
}


.main-sidebar{position:absolute;top:55px;left:0;padding-top:15px;min-height:100%;width:230px;z-index:810;
    -webkit-transition:-webkit-transform .3s ease-in-out,width .3s ease-in-out; -moz-transition:-moz-transform .3s ease-in-out,width .3s ease-in-out;
    -o-transition:-o-transform .3s ease-in-out,width .3s ease-in-out; transition:transform .3s ease-in-out,width .3s ease-in-out}


.sidebar{padding-bottom:10px}
.sidebar-form input:focus{border-color:transparent}


.sidebar-menu>li>a>.extralife_texto { display:inline-block; }
.sidebar-menu>li>a>.extralife_texto_on { display:none;}
.sidebar-menu>li:hover>a>.extralife_texto { display:none}
.sidebar-menu>li:hover>a>.extralife_texto_on { display:inline-block;}


.sidebar-menu>li>a>span{margin-top: -10px; display: inline-block;}
.sidebar-menu{list-style:none;margin:0;padding:0; padding-left:0px;}


.sidebar-mini.sidebar-collapse .sidebar-menu>li { padding-left: 15px;}
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>span { height: 20px;}



.sidebar-menu>li{position:relative;margin:0;padding:0}
.sidebar-menu>li>a{ padding:14px 5px 0px 20px; display:block; background-color: #e6e6e6; height: 19px; }
.sidebar-menu>li>a>.fa,
.sidebar-menu>li>a>.glyphicon,
.sidebar-menu>li>a>.ion{width:40px}
.sidebar-menu>li .label,
.sidebar-menu>li .badge{margin-right:5px}
.sidebar-menu>li .badge{margin-top:3px}
.sidebar-menu li.header{padding:10px 25px 10px 15px;font-size:12px}
.sidebar-menu li>a>.fa-angle-left,
.sidebar-menu li>a>.pull-right-container>.fa-angle-left{width:auto;height:auto;padding:0;margin-right:10px;
                                                        -webkit-transition:transform .5s ease;
                                                        -o-transition:transform .5s ease;
                                                        transition:transform .5s ease}
.sidebar-menu li>a>.fa-angle-left{position:absolute;top:50%;right:10px;margin-top:-8px}
.sidebar-menu .menu-open>a>.fa-angle-left,
.sidebar-menu .menu-open>a>.pull-right-container>.fa-angle-left{-webkit-transform:rotate(-90deg);
                                  -ms-transform:rotate(-90deg);-o-transform:rotate(-90deg);
                                  transform:rotate(-90deg)}
                                  
.sidebar-menu .active>.treeview-menu{display:block}


/*  Menu */
.menu_dashboard { margin: 0px 0px 0px 0px; padding: 15px 10px 10px 15px !important; background-image: url(../img/icono_inicio1.png); 
    background-repeat: no-repeat; transition: all 0.2s ease-in-out; background-position: 7px -2px;}
.menu_dashboard:hover  {background-image: url(../img/icono_inicio2.png); background-color: #bababa!important; color: #ffffff !important;}
.menu_dashboard.on { background-image: url(../img/icono_inicio2.png); background-repeat: no-repeat; background-color: #bababa!important;
	color: #ffffff !important; }

.menu_crm { margin: 0px 0px 0px 0px; padding: 15px 10px 10px 15px !important; background-image: url(../img/icono_crm1.png); 
    background-repeat: no-repeat; transition: all 0.2s ease-in-out; background-position: 7px 0px;}
.menu_crm:hover  {background-image: url(../img/icono_crm2.png); background-color: #13c4a5!important; color: #ffffff !important;}
.menu_crm.on { background-image: url(../img/icono_crm2.png); background-repeat: no-repeat; background-color: #13c4a5!important;
	color: #ffffff !important; }
	
.menu_pedido { margin: 0px 0px 0px 0px; padding: 15px 10px 10px 15px !important; background-image: url(../img/icono_distribuidores1.png); 
    background-repeat: no-repeat; transition: all 0.2s ease-in-out; background-position: 7px -2px;}
.menu_pedido:hover  {background-image: url(../img/icono_distribuidores2.png); background-color: #5191d1!important; color: #ffffff !important;}
.menu_pedido.on { background-image: url(../img/icono_distribuidores2.png); background-repeat: no-repeat; background-color: #5191d1!important;
	color: #ffffff !important; }	
	
.menu_sucursales { margin: 0px 0px 0px 0px; padding: 15px 10px 10px 15px !important; background-image: url(../img/icono_pedidos1.png); 
    background-repeat: no-repeat; transition: all 0.2s ease-in-out; background-position: 7px -2px;}
.menu_sucursales:hover  {background-image: url(../img/icono_pedidos2.png); background-color: #ffa60a!important; color: #ffffff !important;}
.menu_sucursales.on { background-image: url(../img/icono_pedidos2.png); background-repeat: no-repeat; background-color: #ffa60a!important;
	color: #ffffff !important; }	
	
.menu_reportes { margin: 0px 0px 0px 0px; padding: 15px 10px 10px 15px !important; background-image: url(../img/icono_reportes1.png); 
    background-repeat: no-repeat; transition: all 0.2s ease-in-out; background-position: 7px -2px;}
.menu_reportes:hover  {background-image: url(../img/icono_reportes2.png); background-color: #ff5f7d!important; color: #ffffff !important;}
.menu_reportes.on { background-image: url(../img/icono_reportes2.png); background-repeat: no-repeat; background-color: #ff5f7d!important;
	color: #ffffff !important; }
	
.menu_finanzas { margin: 0px 0px 0px 0px; padding: 15px 10px 10px 15px !important; background-image: url(../img/icono_finanzas1.png); 
    background-repeat: no-repeat; transition: all 0.2s ease-in-out; background-position: 7px -2px;}
.menu_finanzas:hover  {background-image: url(../img/icono_finanzas2.png); background-color: #3fcf7f!important; color: #ffffff !important;}
.menu_finanzas.on { background-image: url(../img/icono_finanzas2.png); background-repeat: no-repeat; background-color: #3fcf7f!important;
	color: #ffffff !important; }	
	
.menu_rrhh { margin: 0px 0px 0px 0px; padding: 15px 10px 10px 15px !important; background-image: url(../img/icono_recursos1.png); 
    background-repeat: no-repeat; transition: all 0.2s ease-in-out; background-position: 7px -2px;}
.menu_rrhh:hover  {background-image: url(../img/icono_recursos2.png); background-color: #8666d0!important; color: #ffffff !important;}
.menu_rrhh.on { background-image: url(../img/icono_recursos2.png); background-repeat: no-repeat; background-color: #8666d0!important;
	color: #ffffff !important; }	
		
.menu_sms { margin: 0px 0px 0px 0px; padding: 15px 10px 10px 15px !important; background-image: url(../img/icono_sms1.png); 
    background-repeat: no-repeat; transition: all 0.2s ease-in-out; background-position: 7px -2px;}
.menu_sms:hover  {background-image: url(../img/icono_sms2.png); background-color: #ff7215!important; color: #ffffff !important;}
.menu_sms.on { background-image: url(../img/icono_sms2.png); background-repeat: no-repeat; background-color: #ff7215!important;
	color: #ffffff !important; }	

		

	



.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>.mover_izquierda_1 {display:none;-webkit-transform:translateZ(0);
                                                                      background-color: #e6e6e6; margin-top:-35px!important;}
.sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>.mover_izquierda_1 {
    display:block !important;position:absolute; width:180px;left:25px; padding:10px; padding-left:20px;  }


.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>.extralife_texto { display:none;}
.sidebar-mini.sidebar-collapse .sidebar-menu>li>a>.extralife_texto_on { display:none;}
.sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>.extralife_texto { display:none}
.sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>.extralife_texto_on { display:inline-block; 
                  padding:10px; padding-left:25px;background-color: #e6e6e6;margin-top:-28px!important; padding-right:56px;}


.sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>span:not(.pull-right),
.sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>.treeview-menu {
    display:block !important;position:absolute; width:180px;left:50px}
.sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>span{
    top:0;margin-left:-3px;padding:12px 5px 12px 20px; background-color:inherit}
.sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>.pull-right-container{
    position:relative !important; float:right;width:auto !important;left:180px !important;top:-22px !important;z-index:900}
.sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>a>.pull-right-container>.label:not(:first-of-type){
   display:none}
.sidebar-mini:not(.sidebar-mini-expand-feature).sidebar-collapse .sidebar-menu>li:hover>.treeview-menu{top:44px;margin-left:0}
.sidebar-expanded-on-hover .main-footer,
.sidebar-expanded-on-hover .content-wrapper{margin-left:50px}
.sidebar-expanded-on-hover .main-sidebar{box-shadow:3px 0 8px rgba(0,0,0,0.125)}
.sidebar-menu,.main-sidebar .user-panel,
.sidebar-menu>li.header{white-space:nowrap;overflow:hidden}
.sidebar-menu:hover{overflow:visible}
.sidebar-form,.sidebar-menu>li.header{overflow:hidden;text-overflow:clip}
.sidebar-menu li>a{position:relative}
.sidebar-menu li>a>.pull-right-container{position:absolute;right:10px;top:50%;margin-top:-7px}
.control-sidebar-bg{position:fixed;z-index:1000;bottom:0}
.control-sidebar-bg,
.control-sidebar{top:0;right:-230px;width:230px;-webkit-transition:right .3s ease-in-out;
                                     -o-transition:right .3s ease-in-out;transition:right .3s ease-in-out}
.control-sidebar{position:absolute;padding-top:50px;z-index:1010}



@media (max-width:768px){.control-sidebar{padding-top:100px}}

.control-sidebar>.tab-content{padding:10px 15px}
.control-sidebar.control-sidebar-open,
.control-sidebar.control-sidebar-open+.control-sidebar-bg{right:0}
.control-sidebar-open .control-sidebar-bg,
.control-sidebar-open .control-sidebar{right:0}






@keyframes flipInX{0%{transform:perspective(400px) rotate3d(1, 0, 0, 90deg);
                   transition-timing-function:ease-in;opacity:0}
40%{transform:perspective(400px) rotate3d(1, 0, 0, -20deg);transition-timing-function:ease-in}
60%{transform:perspective(400px) rotate3d(1, 0, 0, 10deg);opacity:1}
80%{transform:perspective(400px) rotate3d(1, 0, 0, -5deg)}
100%{transform:perspective(400px)}
}

@-webkit-keyframes flipInX{0%{-webkit-transform:perspective(400px) rotate3d(1, 0, 0, 90deg);
    -webkit-transition-timing-function:ease-in;opacity:0}40%{-webkit-transform:perspective(400px) rotate3d(1, 0, 0, -20deg);
    -webkit-transition-timing-function:ease-in}60%{-webkit-transform:perspective(400px) rotate3d(1, 0, 0, 10deg);
    opacity:1}80%{-webkit-transform:perspective(400px) rotate3d(1, 0, 0, -5deg)}100%{-webkit-transform:perspective(400px)}}






@media print{
.no-print,.main-sidebar,.left-side,.main-header,.content-header{display:none !important}
.content-wrapper,.right-side,.main-footer{margin-left:0 !important;min-height:0 !important;
                                          -webkit-transform:translate(0, 0) !important;
-ms-transform:translate(0, 0) !important;-o-transform:translate(0, 0) !important;transform:translate(0, 0) !important}
.fixed .content-wrapper,.fixed .right-side{padding-top:0 !important}
.invoice{width:100%;border:0;margin:0;padding:0}
.invoice-col{float:left;width:33.3333333%}.table-responsive{overflow:auto}
.table-responsive>.table tr th,.table-responsive>.table tr td{white-space:normal !important}
}
