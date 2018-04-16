# slrrrp
Custom Fonts for SLRRRP

CODE:
<strong><em>- STYLESHEET -</em></strong>
@font-face {
    font-family: 'kenyan_coffeebold_italic' !important;
    src: url('fonts/kenyan_coffee_bd_it-webfont.eot');
    src: url('fonts/kenyan_coffee_bd_it-webfont.eot?#iefix') format('embedded-opentype'),
         url('fonts/kenyan_coffee_bd_it-webfont.woff2') format('woff2'),
         url('fonts/kenyan_coffee_bd_it-webfont.woff') format('woff'),
         url('fonts/kenyan_coffee_bd_it-webfont.ttf') format('truetype'),
         url('fonts/kenyan_coffee_bd_it-webfont.svg#kenyan_coffeebold_italic') format('svg');
    font-weight: normal;
    font-style: normal;}

@font-face {
    font-family: 'kenyan_coffeebold' !important;
    src: url('fonts/kenyan_coffee_bd-webfont.eot');
    src: url('fonts/kenyan_coffee_bd-webfont.eot?#iefix') format('embedded-opentype'),
         url('fonts/kenyan_coffee_bd-webfont.woff2') format('woff2'),
         url('fonts/kenyan_coffee_bd-webfont.woff') format('woff'),
         url('fonts/kenyan_coffee_bd-webfont.ttf') format('truetype'),
         url('fonts/kenyan_coffee_bd-webfont.svg#kenyan_coffeebold') format('svg');
    font-weight: normal;
    font-style: normal;}

@font-face {
    font-family: 'kenyan_coffeeitalic' !important;
    src: url('fonts/kenyan_coffee_rg_it-webfont.eot');
    src: url('fonts/kenyan_coffee_rg_it-webfont.eot?#iefix') format('embedded-opentype'),
         url('fonts/kenyan_coffee_rg_it-webfont.woff2') format('woff2'),
         url('fonts/kenyan_coffee_rg_it-webfont.woff') format('woff'),
         url('fonts/kenyan_coffee_rg_it-webfont.ttf') format('truetype'),
         url('fonts/kenyan_coffee_rg_it-webfont.svg#kenyan_coffeeitalic') format('svg');
    font-weight: normal;
    font-style: normal;}

@font-face {
    font-family: 'kenyan_coffeeregular' !important;
    src: url('fonts/kenyan_coffee_rg-webfont.eot');
    src: url('fonts/kenyan_coffee_rg-webfont.eot?#iefix') format('embedded-opentype'),
         url('fonts/kenyan_coffee_rg-webfont.woff2') format('woff2'),
         url('fonts/kenyan_coffee_rg-webfont.woff') format('woff'),
         url('fonts/kenyan_coffee_rg-webfont.ttf') format('truetype'),
         url('fonts/kenyan_coffee_rg-webfont.svg#kenyan_coffeeregular') format('svg');
    font-weight: normal;
    font-style: normal;}

<strong><em>- Theme Functions -</em></strong>

    $system_fonts[ 'kenyan_coffeebold_italic' ] = array(
        'fallback' => 'Helvetica, Arial, sans-serif',
        'weights' => array(
            '400',
        ),
    );
	
	    $system_fonts[ 'kenyan_coffeebold' ] = array(
        'fallback' => 'Helvetica, Arial, sans-serif',
        'weights' => array(
            '400',
        ),
    );
	
		    $system_fonts[ 'kenyan_coffeeitalic' ] = array(
        'fallback' => 'Helvetica, Arial, sans-serif',
        'weights' => array(
            '400',
        ),
    );
	
		    $system_fonts[ 'kenyan_coffeeregular' ] = array(
        'fallback' => 'Helvetica, Arial, sans-serif',
        'weights' => array(
            '400',
        ),
    );

    return $system_fonts;
}

<strong><em>- Additional CSS -</em></strong>
h1,h2,h3,h4,h5,h6 {
	font-family: 'KenyanCoffeeRg-Regular', Open Sans, Arial, sans-serif !important;
letter-spacing: .03em;}
