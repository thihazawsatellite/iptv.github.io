# iptv.github.io
Live Stream
<html xmlns="http://www.w3.org/1999/xhtml" lang="en">

<head>
 <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
 <title>Live TV</title>


</head>



<link rel="icon" href="img/Paraguay_TV_logo.png" />      
 <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">

       
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

       
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>

        <!-- Latest compiled JavaScript -->
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script> 
        <link href="https://unpkg.com/video.js/dist/video-js.css" rel="stylesheet">
        <link href="css/style.css" rel="stylesheet">

        <!--[if lt IE 9]>
                <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
                <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
        <![endif]-->

        
        
          
          <style>
            @import url('https://fonts.googleapis.com/css?family=Rambla:400i');
body {
    font-family: "myriad pro", tahoma, verdana, arial, sans-serif;
    font-size: 12px;
    margin: 0;
    padding: 0;
   
   
   
}


.tv-area { margin-top: 50px; }
.channel-list { 
    margin-top: 20px;
    width: 100%;
    height: 100%;
}
.thumbnail-slider { margin:0; padding:0;  }
.thumbnail-slider ul,.thumbnail-slider ul li {
    display: block;
    list-style: none;
    margin: 0;
    padding: 0;
}
.thumbnail-slider li{
    width: 23%; 
    height: 75px;
    margin: 5px 1%;
    list-style: none;
}
.thumbnail-slider li img {
    width: 100%;
    height: 100%;
    max-width: 100%;
    max-height: 100%;
    border-radius: 5px;
}


.channel-list::-webkit-scrollbar {
    width: 12px;
    border-radius: 10px;
    background-color: hsl(0, 3%, 7%);
}
.channel-list::-webkit-scrollbar-thumb {
    border-radius: 10px;
    -webkit-box-shadow: inset 0 0 6px rgba(0,0,0,.3);
    background-color: #29d671;
}

/*[data-player] { position: relative; width: 100%; height: auto; margin: 0; }
[data-player] .container[data-container] { width: 100%; height: auto; position: relative; }
[data-player] .media-control[data-media-control] { top: 0; right: 0; bottom: 0; left: 0; }
[data-player] video { position: relative; display: block; width: 100%; height: auto; }*/
/*
@media (max-width: 1199px) {
    .channel-list { height: 425px; }
}
@media (max-width: 990px) {
    .channel-list { padding: 10px 15px; height: auto !important; overflow-y: hidden; overflow-x: auto; }
    .thumbnail-slider li { display: inline-block; margin: 0 5px 0 0; }
    .thumbnail-slider li a { display: block; width: 80px; }
}
@media (max-width: 410px) {
    .thumbnail-slider li a { width: 50px; }
}*/
            
        </style>

          
          
        <script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/clappr-chromecast-plugin/0.1.1/clappr-chromecast-plugin.min.js"></script>
        <style class="clappr-style">
            @font-face{font-family:Roboto;font-style:normal;font-weight:400;src:local("Roboto"),local("Roboto-Regular"),url(https://cdn.jsdelivr.net/npm/clappr@latest/dist/38861cba61c66739c1452c3a71e39852.ttf) format("truetype")}
            body {
              background-image: url(img/polygon-pony-1175.jpg)  ;
            }
        </style>
   

        <div class="container-fluid">
            <div class="row justify-content-center" style="margin-top: 50px;">

                <div class="col-12 col-lg-8">
                    <div class="embed-responsive embed-responsive-16by9">
<div id="player" class="embed-responsive-item">
                            <video id="vid1" class="video-js vjs-default-skin vjs-fluid" poster="http://i.imgur.com/xxqm7EE.png" width="640" height="360" controls autoplay preload="none" data-setup='{ "techOrder": ["html5", "flash", "youtube"], "sources": [{ "type": "application/x-mpegURL", "src": "https://nmxlive.akamaized.net/hls/live/529965/Live_1/index.m3u8"}]}'></video>
                        </div>
                    </div>
                </div>

                <div class="col-12 col-lg-4">
                    <div class="channel-list">
                        <ul class="nav nav-tabs nav-justified" style=" margin-bottom: 15px;">
                            <li class="nav-item">
                                <h3 style="background-color:#0090d3;">LIVE SPORTS</h3>
                            </li>
                        </ul>
                        <ul id="vidlink" class="thumbnail-slider d-flex flex-wrap">
       
                            
                            <li class="Bangla"><a id="myLink" title="Click" href="https://live.tsports.com/mobile_hls/tsports_live/auto.m3u8"><img src="img/tsports.png" alt=""></a></li>
                            <li class="Bangla"><a id="myLink" title="Click" href="https://tempe.jagobd.com:444/cZMLmVyX3RpbEU9Mi8xNy8yMDE0GIDU6RgzQ6NTAgdEoaeFzbF92YWxIZTO0U0ezN1IzMyfvcGVMZEJCTEFWeVN3PTOmdFsaWRtaW51aiPhnPTI/asian-test-sample-ok-d.stream/playlist.m3u8"><img src="img/images.jpg" alt=""></a></li>
                            <li class="Bangla"><a id="myLink" title="Click" href="https://video-weaver.bom01.hls.live-video.net/v1/playlist/CswFhWBpSyaIVzt0dfP_HUL5Sjx4OzQcDkfAo11_GbTZqqP-fengJAsl34jkLYTEIuswmwtc8yXh8BCdIBKnFqO2hhb8BxuxULJ0xGTRNAhbBJomZ4Pd3KtUxGkN9vREn5tk4h_BqcP-chxXANaV05wjMxnXPMyq2K-3meyl8_gsIH9DzfR0cXFzxhkclV1pQT4P1d_DmxazZMJEvE0l_lXP_L0tNBi_OUL4so7QNB4BxoFg-ayELX2eVZyV-wJLQQExQlTtOUwVn0iiquJqaXFgoX6mvkIpYzA7_8FU_5U0daPjt_z0Dei6DScJRWyMDUQdN87f7U2nHVXxsetZxHNDdGEdRHmRl7hsMAYXP910cEuldRA0TE_B4TkJgvguVFkSktpwQYfTmd39Em5G-hN0CaPlU-F6LZbgAp0pLHPRExmLDbxZd15P9FVe0Z5ZG8k1TSCmkPrD8rPfvPzyyThzNHqqVqkNpGNGVuH6_QFZuEzU8zMlbzK7XojNNvEDT2jcRBgL6rRU2X4du53qSwesKO6cxCIy26PlS1rRKI-elOxX1YCvPllp6mZ2Ecg2mUzX6DTiilh3yQQrzBH7fNqHXsv5_IQyT5InJQCun14-XE6OvgXDj_5z9cOkEDNt6hKydyDm60Zj0oyCZIxleCjKV0rxTGd6tFq7UTG-zi-64TQ7mRLg0fbkjK4sKde8bmjakvWq4oMjzI5T2Ffq0835_kzSaCyQxqdnbNtynA05u2OxKJ3-X56k88P7TFX1uYJj7rdyYaNwxw-niVYVmLOZ452zABneRUS5ZTb-fx0AGVdfBPyoh6zhq2OKi-1lgjhCO4xAKfurR-sX6MFKYTHYij6g6CpNJ-UAHSeYqTKqj8lFnJul9rite1UjZUAOiidRB4QLS26KuFlrTuwhpTKlZx466mN8k03A6YWXC9qhmKXYUFCyCfwK7qOBnpYaDLjQYoF6-DBrPF_YuCABKgl1cy1lYXN0LTIw6Ac.m3u8"><img src="img/images.jpg" alt=""></a></li>
       


                        </ul>
                    </div>
                </div>

            </div>
        </div>
        <br>
       
        <a class="btn btn-primary"  href="https://t.me/Asif065" role="button "
        ><i class="fab fa-telegram"></i>
      </a>

        <script src="https://unpkg.com/video.js@7.10.2/dist/video.js"></script>
        <script src="https://unpkg.com/@videojs/http-streaming@2.4.2/dist/videojs-http-streaming.min.js"></script>
        
          
      <script type='text/javascript'>
//<![CDATA[    
          
          
    var vgsPlayer, poster;
vgsPlayer = videojs('vid1');
vgsPlayer.poster('https://wallpaperaccess.com/full/3214373.jpg');

/*** LOAD URL ***/
$('#vidlink li a').on('click', function (e) {
    e.preventDefault();
    var vidlink = $(this).attr('href');
    vsgLoadVideo(vidlink);
    //$('#vsg-vurl').val(vidlink);  
    //$('input[type=submit]').click();
});

jQuery(function ($) {


    $("#vidlink li").css('display', 'none');
    $("#vidlink .Bangla").css('display', '');

    $(".channel-list .nav-link").click(function () {
        $(".channel-list .nav-link").removeClass('active');

        $(this).addClass('active');

        var ShowClass = $(this).data('type');

        $("#vidlink li").css('display', 'none');
        $("#vidlink ." + ShowClass).css('display', '');
    });
$("#vsg-loadvideo").submit(function (e) {
        e.preventDefault();

        var vidURL = $("#vsg-vurl").val();

        vsgLoadVideo(vidURL);

    });

});


function vsgLoadVideo(vidURL, poster) {
    var type = getType(vidURL);

    if (getId(vidURL))
        poster = "http://img.youtube.com/vi/" + getId(vidURL) + "/hqdefault.jpg";

    vgsPlayer.src({
        "src": vidURL,
        "type": type
    });
    if (poster)
        vgsPlayer.poster(poster);
    else
        vgsPlayer.poster("//i.imgur.com/aE0LoTe.png");

    // play seem to trigger to fast before Youtube is ready

    //vgsPlayer.pause();
// vgsPlayer.load();
    vgsPlayer.play();
    /*   setTimeout(function() {
     vgsPlayer.play();
     }, 500); */

    return false;

}


function ytVidId(url) {
    //var p = /^(?:https?:\/\/)?(?:www\.)?youtube\.com\/watch\?(?=.*v=((\w|-){11}))(?:\S+)?$/;
    //var p = /^.*(youtu.be\/|v\/|u\/\w\/|embed\/|watch\?v=|\&v=)([^#\&\?]*).*/;
    var p = /^.*(youtu.be\/|v\/|u\/\w\/|embed\/|watch\?v=|\&v=|\?v=)([^#\&\?]*).*/;

    if (url.match(p) || getId(url).length == 11)
        return false;
}

/**/
function getId(url) {
    //var regExp = /^.*(youtu.be\/|v\/|u\/\w\/|embed\/|watch\?v=|\&v=)([^#\&\?]*).*/;
    var regExp = /^.*(youtu.be\/|v\/|u\/\w\/|embed\/|watch\?v=|\&v=|\?v=)([^#\&\?]*).*/;
    var match = url.match(regExp);

    if (match && match[2].length == 11) {
        return match[2];
    } else {
        return false;
    }
}

var rtmp_suffix = /^rtmp:\/\//;
var hls_suffix = /\.m3u8/;
var mp4_suffix = /\.(mp4|m4p|m4v|mov)/i;
var hds_suffix = /\.f4m/;
var dash_suffix = /\.mpd/;
var flv_suffix = /\.flv/;
var webm_suffix = /\.webm/;
/* AUDIO */
//var mp3_suffix = /\.mp3/;
var mpeg_suffix = /\.(mp3|m4a)/i;
var ogg_suffix = /\.ogg/;

//var youtube_suffix = /\.youtube.com/;
//var yt_suffix = /^(?:https?:\/\/)?(?:www\.)?youtube\.com\/watch\?(?=.*v=((\w|-){11}))(?:\S+)?$/;
var yt_suffix = /^.*(youtu.be\/|v\/|u\/\w\/|embed\/|watch\?v=|\&v=)([^#\&\?]*).*/;
var dm_suffix = /\.?dailymotion.com/;
var vm_suffix = /\.?vimeo.com/;
/* ADVANCED REGEX */
//      var regVimeo = /^.*(vimeo.com\/)((channels\/[A-z]+\/)|(groups\/[A-z]+\/videos\/))?([0-9]+)/;
//      var regDailymotion = /^.+dailymotion.com\/(video|hub)\/([^_]+)[^#]*(#video=([^_&]+))?/;
//      var regMetacafe = /^.*(metacafe.com)(\/watch\/)(d+)(.*)/i;
//      var youtube_suffix = /(youtu.be\/|v\/|u\/\w\/|embed\/|watch\?v=|\&v=)([^#\&\?]*).*/;

function getType(url) {

    /* AUDIO */
    if (mpeg_suffix.test(url))
        return 'audio/mpeg';
    if (ogg_suffix.test(url))
        return 'audio/ogg';
    if (dash_suffix.test(url))
        return 'application/dash+xml';
    if (rtmp_suffix.test(url))
        return 'rtmp/mp4';
    if (hls_suffix.test(url))
        return 'application/x-mpegurl';
    if (mp4_suffix.test(url))
        return 'video/mp4';
    if (hds_suffix.test(url))
        return 'application/adobe-f4m';
    if (flv_suffix.test(url))
        return 'video/flv';
    if (webm_suffix.test(url))
        return 'video/webm';
    if (yt_suffix.test(url)) {
        //alert(url.match(yt_suffix)[2]);
        //player.poster(ytmaxres(url.match(yt_suffix)[2]));
        //alert(ytmaxres(url.match(yt_suffix)[2]));
        return 'video/youtube';
    }
    if (dm_suffix.test(url))
        return 'video/dailymotion';
    if (vm_suffix.test(url))
        return 'video/vimeo';

    console.log('could not guess link type: "' + url + '" assuming mp4');
    return 'video/mp4';
}
;

function getExt(ext) {

    //if (ext == "youtube") ext = "mp4";
    if (ext == "mp4" || ext == "m4v")
        ext = "m4v";
    if (ext == "ogg" || ext == "ogv")
        ext = "oga";
    if (ext == "webm")
        ext = "webmv";

    return ext;
}
      
          
    //]]>
</script>

 
          
          
          
          
          
          




</body>

</html>
