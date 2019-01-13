< html >

  < tête >

    < meta  charset = " utf-8 " >
    < meta  http-equiv = " Compatible X-UA "  content = " IE = edge " >
    < meta  name = " viewport "  content = " width = device-width, initial-scale = 1 " >
    < title > La maison de l'architecte </ title >
    < meta  name = " description "  content = " Le site de la maison de l'architecture " >

    < link  href = " https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css "  rel = " stylesheet " >
    < link  href = " https://maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css "  rel = " stylesheet " >
    < link  href = ' http://fonts.googleapis.com/css?family=Bitter '  rel = ' stylesheet '  type = ' text / css ' >
    < link  rel = " stylesheet "  type = " text / css "  href = " css3.css " >
    <! - Prise en charge des éléments HTML5 et des requêtes multimédias dans HTML5 Shim et Respond.js IE8 ->
    <! - AVERTISSEMENT: Respond.js ne fonctionne pas si vous affichez la page via le fichier: // ->
    <! - [si lt IE 9]>
      <script src = "https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"> </ script>
      <script src = "https://oss.maxcdn.com/respond/1.4.2/respond.min.js"> </ script>
    <! [endif] ->


     
  </ head >

  < body  id = " page-top "  data-spy = " scroll "  data-target = " .navbar " >

    <en- tête >

      <! - Navigation
      =============================================== ->
      
      < nav  class = " navbar navbar-default "  role = " navigation " >   
        < div  class = " conteneur " >
          < div  class = " navbar-header " >
            < type de bouton  = " bouton " class = " navbar-toggle " / data-toggle = " collapse " data-target = " .navbar-collapse " >   
                < span  class = " icon-bar " > </ span >
                < span  class = " icon-bar " > </ span >
                < span  class = " icon-bar " > </ span >
            </ button >
            < A  class = " navbar-marque "  href = " # page-top " > Alimentation, Llc </ a >
          </ div >
          < div  id = " header "  class = " collapse navbar-collapse " >
            < ul  class = " nav navbar-nav navbar-right " >
              < Li  class = " caché " > < a  href = " # page-top " > </ a > </ li >
              < Li > < a  href = " #chicken " > Chicken </ a > </ li >
              < Li > < a  href = " #beef " > Boeuf </ a > </ li >
              < Li > < a  href = " #sushi " > Sushi </ a > </ li >
            </ ul >
          </ div >
        </ div >
      </ nav >

    </ header >
    < h1 > Notre menu </ h1 >
    < div  class = " row " >
  < div  class = " col-lg-4 col-md-6 col-sm-12 col-xs-12 " >
  < section  id = " section1 " >
    < h3  id = " chicken " > Poulet </ h3 >
    < P > motui etuir butik li EPSUM loren pitori molinetire vilityre fujiyht fesuji hijutyr buji kiloj ujytu rytui gyjui kilji jutygi jimo boliyut niferyjui hijokli moliujy fesiytu opiloyt nioy NTY ruijo Huti filouy tyjui nerwsio Jiko lihuy jyrute bokiyut niyjik lokiu joigy Koli JTI moli kulom go li jikolu tjuhyr suivu dimj lkimo kiytju. < a  class = " retour "  href = " # page-top " > Retour en haut </ a > </ p >
    
  </ section >
</ div >
  < div  class = " col-lg-4 col-md-6 col-sm-12 col-xs-12 " >
  < section  id = " section2 " >
    < h3  id = " beef " > Boeuf </ h3 >
    < P > totiy ferytu cesilu mùigt Cuio desuyt botyu dezex Gatex fili kolu htyuji nresuij moiklu jretyun colikoj voiloytu verokluty juityiu huteru niobyut gterswe gyjukiylok kolijuy vilutyre niloku viluty Boliko jutyki molijuyht cilokmyujt colikujy colikujyh foliko bolki bodyt soli xaytu vetyjuko liko mokiju hgy uf deru IUL. < a  class = " back "  href = " # page-top " > Haut de page </ a > </ p >
    
  </ section >
</ div >
  < div  class = " col-lg-4 col-md-12 col-sm-12 col-xs-12 " >
  < section  id = " section3 " >
    < h3  id = " sushi " > Suchi </ h3 >
    < P > polityu slojit cesryuji viokuyter vuintyre dujiokuy louytiku hijuk mityrx vuxity verioytu gujity cerytujin bonijutry bolikuj dujytim momuty fokily dsewcxi noikl fytujiko voliju comikuhy devuity rjuhyt jilotu gutyhi nuryji fyturi jolikuty biloki joliko nimoli biloyt Tujiko vijuty verikou yjiku. < A  class = " retour "  href = " # page-top " > Haut de page </ a > </ p >
  </ section >
      </ div >
   
    <! - jQuery ->
    < script  src = " https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js " > </ script >
    <! - Javascript de Bootstrap ->
    < script  src = " https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js " > </ script >

    < script >
      // Scrollspy fluide
      $ ( fonction () {
        $ ( 'en- tête a ' ). sur ( ' clic ' , fonction ( e ) {
          e . preventDefault ();
          var hash =  ceci . le hash ;
          $ ( ' html, body ' ). animer ({
            scrollTop :  $ ( this . hash ). offset (). Haut
          }, 1000 , fonction () {
            fenêtre . emplacement . hash  = hash;
          });
        });
      });
    </ script >

  </ body >

</ html >
