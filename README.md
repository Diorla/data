# data

Some collections of data

## countries.json

- basic info about a country like language, official name, language, region etc.
- data type: array of objects
- data sample

```json
[
  {
    "name": {
      "common": "Nigeria",
      "official": "Federal Republic of Nigeria",
      "native": {
        "eng": {
          "official": "Federal Republic of Nigeria",
          "common": "Nigeria"
        }
      }
    },
    "tld": [".ng"],
    "cca2": "NG",
    "ccn3": "566",
    "cca3": "NGA",
    "cioc": "NGR",
    "currency": ["NGN"],
    "callingCode": ["234"],
    "capital": "Abuja",
    "altSpellings": [
      "NG",
      "Nijeriya",
      "Na\u00edj\u00edr\u00ed\u00e0",
      "Federal Republic of Nigeria"
    ],
    "region": "Africa",
    "subregion": "Western Africa",
    "languages": {
      "eng": "English"
    },
    "translations": {
      "deu": { "official": "Bundesrepublik Nigeria", "common": "Nigeria" },
      "fra": {
        "official": "R\u00e9publique f\u00e9d\u00e9rale du Nigeria",
        "common": "Nig\u00e9ria"
      },
      "hrv": { "official": "Savezna Republika Nigerija", "common": "Nigerija" },
      "ita": {
        "official": "Repubblica federale di Nigeria",
        "common": "Nigeria"
      },
      "jpn": {
        "official": "\u30ca\u30a4\u30b8\u30a7\u30ea\u30a2\u9023\u90a6\u5171\u548c\u56fd",
        "common": "\u30ca\u30a4\u30b8\u30a7\u30ea\u30a2"
      },
      "nld": { "official": "Federale Republiek Nigeria", "common": "Nigeria" },
      "por": {
        "official": "Rep\u00fablica Federal da Nig\u00e9ria",
        "common": "Nig\u00e9ria"
      },
      "rus": {
        "official": "\u0424\u0435\u0434\u0435\u0440\u0430\u0442\u0438\u0432\u043d\u0430\u044f \u0420\u0435\u0441\u043f\u0443\u0431\u043b\u0438\u043a\u0430 \u041d\u0438\u0433\u0435\u0440\u0438\u044f",
        "common": "\u041d\u0438\u0433\u0435\u0440\u0438\u044f"
      },
      "slk": {
        "official": "Nig\u00e9rijsk\u00e1 federat\u00edvna republika",
        "common": "Nig\u00e9ria"
      },
      "spa": {
        "official": "Rep\u00fablica Federal de Nigeria",
        "common": "Nigeria"
      },
      "fin": { "official": "Nigerian liittotasavalta", "common": "Nigeria" },
      "zho": {
        "official": "\u5C3C\u65E5\u5229\u4E9A\u8054\u90A6\u5171\u548C\u56FD",
        "common": "\u5C3C\u65E5\u5229\u4E9A"
      }
    },
    "latlng": [10, 8],
    "demonym": "Nigerian",
    "landlocked": false,
    "borders": ["BEN", "CMR", "TCD", "NER"],
    "area": 923768
  }
]
```

## css-color-names.json

```json
{
  "aliceblue": "#f0f8ff",
  "antiquewhite": "#faebd7",
  "aqua": "#00ffff",
  "aquamarine": "#7fffd4",
  "azure": "#f0ffff",
  ...
}
```

## city-list.json

- City informations
- Array of objects

```jsonc
[
  {
    "id": 707860,
    "name": "Hurzuf",
    "country": "UA", // Matches "cca2" from "countries.json"
    "coord": {
      "lon":34.283333,
      "lat":44.549999
    }
  }
...
]
```

## location.json

- Array of objects
- Each object contains the following information
  - Country, Subcountry, City and geonnameid
- Note, it is not as extensive as `city_list.json`

```json
[
  {
    "city": "les Escaldes",
    "country": "Andorra",
    "subcountry": "Escaldes-Engordany",
    "geonameid": 3040051
  },
  ...
]
```

## jobs

This is the list of occupations

## Bad habits

Behaviours that harmful consequences to the person or other people.

## Activities

- name: Name of the activity
- location: refers to whether the activity takes place inside a building(under a roof) or not
- mode(home or outing): `Home` refers to activity that you can do in the comfort of your house e.g. `chess` or `cooking`. On the other hand, `outing` requires you to leave your house. By default, all outdoor activities having `outing` mode. Some indoors activities also requires `outing` e.g. `cinema` or `watching a tennis match`.

```jsonc
[
  {
    "name": "Reading",
    "location": "indoor",
    "mode": "home"
  }
  //...
]
```
