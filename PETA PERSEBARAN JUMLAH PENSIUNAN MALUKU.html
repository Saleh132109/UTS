<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="initial-scale=1,user-scalable=no,maximum-scale=1,width=device-width">
        <meta name="mobile-web-app-capable" content="yes">
        <meta name="apple-mobile-web-app-capable" content="yes">
        <link rel="stylesheet" href="css/leaflet.css"><link rel="stylesheet" href="css/L.Control.Locate.min.css">
        <link rel="stylesheet" href="css/qgis2web.css"><link rel="stylesheet" href="css/fontawesome-all.min.css">
        <link rel="stylesheet" href="css/leaflet-search.css">
        <link rel="stylesheet" href="css/leaflet-control-geocoder.Geocoder.css">
        <style>
        #map {
            width: auto;
            height: 778px;
        }
        html, body, #map {
                width: auto;
                height: 680px;
                padding: 0;
                margin: 0;
            }
            </style>
            <style>
                .row.content {
                    height: 680px;
                }
                
                .sidenav {
                background-color: #70a8c0;
                height: 100%;
                }
                
                footer {
                background-color: #a97f7f;
                color: white;
                padding: 10px;
                text-align: center;
                }
                
                @media screen and (max-width: 767px) {
                .sidenav {
                    height: auto;
                    padding: 500px;
                }
                .row.content {
                    height: auto;
                    background-color: #d3d3d3;
                } 
                }
            </style>
        
        </style>
        <title>PETA PERSEBARAN JUMLAH PENSIUNAN PROVINSI MALUKU</title>
    </head>
    <body>
        <div id="map">
        </div>
        <script src="js/qgis2web_expressions.js"></script>
        <script src="js/leaflet.js"></script><script src="js/L.Control.Locate.min.js"></script>
        <script src="js/leaflet.rotatedMarker.js"></script>
        <script src="js/leaflet.pattern.js"></script>
        <script src="js/leaflet-hash.js"></script>
        <script src="js/Autolinker.min.js"></script>
        <script src="js/rbush.min.js"></script>
        <script src="js/labelgun.min.js"></script>
        <script src="js/labels.js"></script>
        <script src="js/leaflet-control-geocoder.Geocoder.js"></script>
        <script src="js/leaflet-search.js"></script>
        <script src="data/MALUKU_2.js"></script>
        <script>
        var highlightLayer;
        function highlightFeature(e) {
            highlightLayer = e.target;

            if (e.target.feature.geometry.type === 'LineString') {
              highlightLayer.setStyle({
                color: '#ffff00',
              });
            } else {
              highlightLayer.setStyle({
                fillColor: '#ffff00',
                fillOpacity: 1
              });
            }
        }
        var map = L.map('map', {
            zoomControl:true, maxZoom:28, minZoom:1
        }).fitBounds([[-11.847081097420023,108.75778053190196],[2.0068354123215926,132.91286949798496]]);
        var hash = new L.Hash(map);
        map.attributionControl.setPrefix('<a href="https://github.com/tomchadwin/qgis2web" target="_blank">qgis2web</a> &middot; <a href="https://leafletjs.com" title="A JS library for interactive maps">Leaflet</a> &middot; <a href="https://qgis.org">QGIS</a>');
        var autolinker = new Autolinker({truncate: {length: 30, location: 'smart'}});
        L.control.locate({locateOptions: {maxZoom: 19}}).addTo(map);
        var bounds_group = new L.featureGroup([]);
        function setBounds() {
            map.setMaxBounds(map.getBounds());
        }
        map.createPane('pane_OpenStreetMap_0');
        map.getPane('pane_OpenStreetMap_0').style.zIndex = 400;
        var layer_OpenStreetMap_0 = L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
            pane: 'pane_OpenStreetMap_0',
            opacity: 1.0,
            attribution: '',
            minZoom: 1,
            maxZoom: 28,
            minNativeZoom: 0,
            maxNativeZoom: 19
        });
        layer_OpenStreetMap_0;
        map.addLayer(layer_OpenStreetMap_0);
        map.createPane('pane_arcgis_1');
        map.getPane('pane_arcgis_1').style.zIndex = 401;
        var layer_arcgis_1 = L.tileLayer('http://server.arcgisonline.com/ArcGIS/rest/services/World_Street_Map/MapServer/tile/{z}/{y}/{x}.png', {
            pane: 'pane_arcgis_1',
            opacity: 1.0,
            attribution: '',
            minZoom: 1,
            maxZoom: 28,
            minNativeZoom: 0,
            maxNativeZoom: 18
        });
        layer_arcgis_1;
        map.addLayer(layer_arcgis_1);
        function pop_MALUKU_2(feature, layer) {
            layer.on({
                mouseout: function(e) {
                    for (i in e.target._eventParents) {
                        e.target._eventParents[i].resetStyle(e.target);
                    }
                },
                mouseover: highlightFeature,
            });
            var popupContent = '<table>\
                    <tr>\
                        <th scope="row">DESA</th>\
                        <td>' + (feature.properties['DESA'] !== null ? autolinker.link(feature.properties['DESA'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">PROVINSI</th>\
                        <td>' + (feature.properties['PROVINSI'] !== null ? autolinker.link(feature.properties['PROVINSI'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">KAB_KOTA</th>\
                        <td>' + (feature.properties['KAB_KOTA'] !== null ? autolinker.link(feature.properties['KAB_KOTA'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">KECAMATAN</th>\
                        <td>' + (feature.properties['KECAMATAN'] !== null ? autolinker.link(feature.properties['KECAMATAN'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">DESA_KELUR</th>\
                        <td>' + (feature.properties['DESA_KELUR'] !== null ? autolinker.link(feature.properties['DESA_KELUR'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">JUMLAH_PEN</th>\
                        <td>' + (feature.properties['JUMLAH_PEN'] !== null ? autolinker.link(feature.properties['JUMLAH_PEN'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">TENAGA_KES</th>\
                        <td>' + (feature.properties['TENAGA_KES'] !== null ? autolinker.link(feature.properties['TENAGA_KES'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">PENSIUNAN</th>\
                        <td>' + (feature.properties['PENSIUNAN'] !== null ? autolinker.link(feature.properties['PENSIUNAN'].toLocaleString()) : '') + '</td>\
                    </tr>\
                    <tr>\
                        <th scope="row">APOTEK_</th>\
                        <td>' + (feature.properties['APOTEK_'] !== null ? autolinker.link(feature.properties['APOTEK_'].toLocaleString()) : '') + '</td>\
                    </tr>\
                </table>';
            layer.bindPopup(popupContent, {maxHeight: 400});
        }

        function style_MALUKU_2_0() {
            return {
                pane: 'pane_MALUKU_2',
                opacity: 1,
                color: 'rgba(35,35,35,1.0)',
                dashArray: '',
                lineCap: 'butt',
                lineJoin: 'miter',
                weight: 1.0, 
                fill: true,
                fillOpacity: 1,
                fillColor: 'rgba(145,82,45,1.0)',
                interactive: true,
            }
        }
        map.createPane('pane_MALUKU_2');
        map.getPane('pane_MALUKU_2').style.zIndex = 402;
        map.getPane('pane_MALUKU_2').style['mix-blend-mode'] = 'normal';
        var layer_MALUKU_2 = new L.geoJson(json_MALUKU_2, {
            attribution: '',
            interactive: true,
            dataVar: 'json_MALUKU_2',
            layerName: 'layer_MALUKU_2',
            pane: 'pane_MALUKU_2',
            onEachFeature: pop_MALUKU_2,
            style: style_MALUKU_2_0,
        });
        bounds_group.addLayer(layer_MALUKU_2);
        map.addLayer(layer_MALUKU_2);
            var title = new L.Control();
            title.onAdd = function (map) {
                this._div = L.DomUtil.create('div', 'info');
                this.update();
                return this._div;
            };
            title.update = function () {
                this._div.innerHTML = '<div class="container-fluid"><h2 style="text-align: center;">PETA PERSEBARAN JUMLAH PENSIUNAN PROVINSI MALUKU</h2></div>';
            };
            title.addTo(map);
            var abstract = new L.Control({'position':'topright'});
            abstract.onAdd = function (map) {
                this._div = L.DomUtil.create('div',
                'leaflet-control abstract');
                this._div.id = 'abstract'

                    abstract.show();
                    return this._div;
                };
                abstract.show = function () {
                    this._div.classList.remove("abstract");
                    this._div.classList.add("abstractUncollapsed");
                    this._div.innerHTML = 'M. SALEH ARASYID (20/457286/SV/17733) <br><hr> Dosen: Hidayat Panuntun, ST, M.Eng., D.Sc';
            };
            abstract.addTo(map);
        var osmGeocoder = new L.Control.Geocoder({
            collapsed: true,
            position: 'topleft',
            text: 'Search',
            title: 'Testing'
        }).addTo(map);
        document.getElementsByClassName('leaflet-control-geocoder-icon')[0]
        .className += ' fa fa-search';
        document.getElementsByClassName('leaflet-control-geocoder-icon')[0]
        .title += 'Search for a place';
        var baseMaps = {};
        L.control.layers(baseMaps,{'<img src="utara.png" style="display: block; margin-left: auto; margin-right: auto;" width="100" height="100"> <hr><h1 style="text-align: center;">LEGENDA</h1>': layer_MALUKU_2,'<img src="legend/MALUKU_2.png" /> MALUKU': layer_MALUKU_2,"arcgis": layer_arcgis_1,"OpenStreetMap <hr>": layer_OpenStreetMap_0,},{collapsed:false}).addTo(map); 
        L.control.layers(baseMaps,{'<img src="logoUGM.png" style="display: block; margin-left: auto; margin-right: auto;" width="100" height="100"> <p style="text-align: center;"><b>Praktikum SIG Berbasis Web<br>Teknologi Survei dan Pemetaan Dasar<br>Universitas Gadjah Mada<br>Yogyakarta<br>2022</b></p>': layer_MALUKU_2,},{collapsed:false}).addTo(map); 
        setBounds();
        map.addControl(new L.Control.Search({
            layer: layer_MALUKU_2,
            initial: false,
            hideMarkerOnCollapse: true,
            propertyName: 'DESA'}));
        document.getElementsByClassName('search-button')[0].className +=
         ' fa fa-binoculars';
        </script>
                        <div class="footer">
                            <p style="background-color:#333333;color:white; text-align:center;"><br>UTS PRAKTIKUM SIG BERBASIS WEB<br><br></P>
                            </div>
    </body>
</html>
