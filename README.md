# sfomuseum-data-faa-2018

2018 data from the FAA's Airport Status Web Service for SFO.

## Important

Data is only available from 2018-08-18 through 2018-12-31.

This is highly experiental work right now. If you are planning to try using it, for anything at all, understand that everything is in flux and subject to change and may still break along the way.

## Example

```
$> cat data/152/799/564/7/1527995647.geojson

{
  "id": 1527995647,
  "type": "Feature",
  "properties": {
    "date:cessation_lower":"2018-08-29",
    "date:cessation_upper":"2018-08-29",
    "date:inception_lower":"2018-08-29",
    "date:inception_upper":"2018-08-29",
    "edtf:cessation":"2018-08-29T17:07:54",
    "edtf:inception":"2018-08-29T17:07:54",
    "faa:credit":"http://weather.gov/",
    "faa:delay":false,
    "faa:delay_count":0,
    "faa:last_update":"Last Updated on Aug 29 2018, 4:56 pm PDT",
    "faa:temperature_c":21.1,
    "faa:temperature_f":70,
    "faa:temperature_raw":"70.0 F (21.1 C)",
    "faa:visibility":10,
    "faa:wind_direction":"Southwest",
    "faa:wind_raw":"Southwest at 15.0",
    "faa:wind_speed":15,
    "geom:area":0.0,
    "geom:bbox":"-122.37,37.62,-122.37,37.62",
    "geom:latitude":37.62,
    "geom:longitude":-122.37,
    "iso:country":"US",
    "mz:hierarchy_label":1,
    "mz:is_current":0,
    "sfomuseum:placetype":"weather",
    "sfomuseum:uri":"2018/08/29/20180829T170754.json",
    "src:geom":"flysfo",
    "wof:belongsto":[
        102527513,
        85688637,
        102191575,
        85633793,
        85922583,
        102087579,
        554784711,
        102085387
    ],
    "wof:breaches":[],
    "wof:concordances":{
        "iata:code":"SFO",
        "icao:code":"KSFO"
    },
    "wof:country":"US",
    "wof:created":1535562474,
    "wof:geomhash":"6e11b039d229c1f441fd06b875619d83",
    "wof:hierarchy":[
        {
            "campus_id":102527513,
            "continent_id":102191575,
            "country_id":85633793,
            "county_id":102087579,
            "custom_id":1527995647,
            "locality_id":85922583,
            "postalcode_id":554784711,
            "region_id":85688637
        },
        {
            "campus_id":102527513,
            "continent_id":102191575,
            "country_id":85633793,
            "county_id":102085387,
            "custom_id":1527995647,
            "region_id":85688637
        }
    ],
    "wof:id":1527995647,
    "wof:lastmodified":1580493883,
    "wof:name":"FAA status for SFO, 2018-08-29T17:07:54",
    "wof:parent_id":102527513,
    "wof:placetype":"custom",
    "wof:repo":"sfomuseum-data-faa-2018",
    "wof:superseded_by":[],
    "wof:supersedes":[],
    "wof:tags":[]
},
  "bbox": [
    -122.37,
    37.62,
    -122.37,
    37.62
],
  "geometry": {"coordinates":[-122.37,37.62],"type":"Point"}
}

```

## License

This data is published under the [Community Data License Agreement – Permissive – Version 1.0](LICENSE) license, but we'd love a [shout-out](https://twitter.com/flysfo) and generally to hear what you're doing if you use the data.

## See also

* https://services.faa.gov/
* https://github.com/Federal-Aviation-Administration/ASWS