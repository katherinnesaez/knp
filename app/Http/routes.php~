<?php

/*
|--------------------------------------------------------------------------
| Application Routes
|--------------------------------------------------------------------------
|
| Here is where you can register all of the routes for an application.
| It's a breeze. Simply tell Laravel the URIs it should respond to
| and give it the controller to call when that URI is requested.
|
*/

Route::get('acerca', function(){
    return "Es una empresa chilena, dedicada a la formulación y fabricación de abonos y correctores nutricionales específicos para la Agricultura moderna. Nuestra misión es la búsqueda permanente de soluciones, desde un punto de vista fisiológico, a problemas que afectan la calidad y rendimiento de las plantas sin abusar del uso de agroquímicos y fertilizantes. Esto nos obliga día a día a observar y aprender de las plantas, forzándonos a estudiar y desarrollar ideas concretas e innovadores, sin obviar uno de nuestros principales principios, que es el respeto por el medio ambiente.";
});

Route::get('nombre/{nombre}', function($nombre){
    return "Mi nombre es ".$nombre;
});

Route::get('/', function () {
    return view('welcome');
});
