# React Part Time Class Final Project

## Project Links

- [CodeSandbox Link](https://codesandbox.io/s/gifted-thunder-ctqmod)
- [Production Link](https://sicloot.com/natlist/garden)

## Project Description

The Garden Life site will summarize nature observations at a local community garden over the past few years.  The home page will list broad categories of life such as birds or insects.  Clicking on one of the categories will bring up a list of subcategories.  Each category/subcategory will detail the number of species and observations in that category.

A subcategory click will lead to a list of species observed.  Each species will contain a common name, scientific name, photo (if available), and information on total observations.

## Wireframes

Upload images of wireframe to cloudinary and add the link here with a description of the specific wireframe. Also, define the the React components and the architectural design of your app.

- <a href="https://wireframe.cc/b62NR4">Visual wireframes</a>


### MVP/PostMVP - 5min

#### MVP EXAMPLE
- Home page with main categories leading to subcategories
- Each category/subcategory contains summary data
- A list of species seen in each subcategory, including observations summaries and a photo if available

#### PostMVP EXAMPLE

- Add a "Needs ID" link to each category/subcategory which will lead to a list of observations that could use further identification
- The species list view can be switched to a summary view showing sortable columns of observation data
- Add months seen and years seen to the species detail view
- Clicking on a species leads to a list of all the observations of that species including photos taken
- If the observation has an iNaturalist link, use the iNaturalist API to pull data from the page for display

## API

If time permits, I will make use of the iNaturalist API to get details about an observation.


```
{
  "total_results": 1,
  "page": 1,
  "per_page": 30,
  "results": [
    {
      "id": 109731977,
      "uuid": "3406b810-b6a5-4d90-a01a-14697edcaa66",
      "user": {
        "id": 1396209,
        "login": "mpgranch",
        "spam": false,
        "suspended": false,
        "created_at": "2018-12-20T01:37:06+00:00",
        "login_autocomplete": "mpgranch",
        "login_exact": "mpgranch",
        "name": "",
        "name_autocomplete": "",
        "orcid": null,
        "icon": "https://static.inaturalist.org/attachments/users/icons/1396209/thumb.jpg?1579554691",
        "observations_count": 1951,
        "identifications_count": 0,
        "journal_posts_count": 0,
        "activity_count": 1951,
        "species_count": 586,
        "universal_search_rank": 1951,
        "roles": [],
        "site_id": 1,
        "icon_url": "https://static.inaturalist.org/attachments/users/icons/1396209/medium.jpg?1579554691"
      },
      "created_at": "2020-06-12T17:22:05+00:00",
      "created_at_details": {
        "date": "2020-06-12",
        "day": 12,
        "month": 6,
        "year": 2020,
        "hour": 17,
        "week": 24
      },
      "body": null,
      "category": "leading",
      "current": true,
      "flags": [],
      "own_observation": true,
      "taxon_change": null,
      "vision": false,
      "disagreement": false,
      "previous_observation_taxon_id": 495775,
      "spam": false,
      "taxon_id": 495775,
      "hidden": false,
      "current_taxon": true,
      "taxon": {
        "id": 495775,
        "rank": "species",
        "rank_level": 10,
        "iconic_taxon_id": 47158,
        "ancestor_ids": [
          1,
          47120,
          372739,
          47158,
          184884,
          47157,
          55518,
          423543,
          423545,
          173500,
          1341724,
          495775
        ],
        "is_active": true,
        "min_species_taxon_id": 495775,
        "min_species_ancestry": "1,47120,372739,47158,184884,47157,55518,423543,423545,173500,1341724,495775"
      },
      "observation": {
        "id": 49347218,
        "site_id": 1,
        "created_at": "2020-06-12T11:22:05-06:00",
        "created_at_details": {
          "date": "2020-06-12",
          "day": 12,
          "month": 6,
          "year": 2020,
          "hour": 11,
          "week": 24
        },
        "observed_on": "2020-06-11",
        "observed_on_details": {
          "date": "2020-06-11",
          "day": 11,
          "month": 6,
          "year": 2020,
          "hour": 0,
          "week": 24
        },
        "time_observed_at": null,
        "place_ids": [
          1,
          16,
          366,
          9853,
          59613,
          65360,
          66741,
          67760,
          82256,
          96683,
          97394,
          115716,
          153940,
          155051,
          167205
        ],
        "quality_grade": "needs_id",
        "taxon": {
          "id": 495775,
          "rank": "species",
          "rank_level": 10,
          "iconic_taxon_id": 47158,
          "ancestor_ids": [
            48460,
            1,
            47120,
            372739,
            47158,
            184884,
            47157,
            55518,
            423543,
            423545,
            173500,
            1341724,
            495775
          ],
          "is_active": true,
          "min_species_taxon_id": 495775,
          "name": "Ethmia mirusella",
          "parent_id": 1341724,
          "ancestry": "48460/1/47120/372739/47158/184884/47157/55518/423543/423545/173500/1341724",
          "min_species_ancestry": "48460,1,47120,372739,47158,184884,47157,55518,423543,423545,173500,1341724,495775",
          "extinct": false,
          "threatened": false,
          "introduced": false,
          "native": false,
          "endemic": false,
          "photos_locked": false,
          "taxon_schemes_count": 1,
          "wikipedia_url": "http://en.wikipedia.org/wiki/Ethmia_mirusella",
          "current_synonymous_taxon_ids": null,
          "created_at": "2016-05-19T18:43:01+00:00",
          "taxon_changes_count": 0,
          "complete_species_count": null,
          "universal_search_rank": 92,
          "observations_count": 92,
          "flag_counts": {
            "resolved": 0,
            "unresolved": 0
          },
          "atlas_id": null,
          "default_photo": {
            "id": 45545363,
            "license_code": "cc-by-nc",
            "attribution": "(c) Lena Zappia, certains droits réservés (CC BY-NC), uploaded by Lena Zappia",
            "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/45545363/square.jpg",
            "original_dimensions": {
              "height": 615,
              "width": 785
            },
            "flags": [],
            "square_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/45545363/square.jpg",
            "medium_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/45545363/medium.jpg"
          },
          "iconic_taxon_name": "Insecta"
        },
        "user_id": 1396209,
        "uuid": "e9805ed5-1ccf-4c6f-a151-17d880994ae5",
        "user": {
          "id": 1396209,
          "login": "mpgranch",
          "spam": false,
          "suspended": false,
          "created_at": "2018-12-20T01:37:06+00:00",
          "site_id": 1,
          "preferences": {},
          "login_autocomplete": "mpgranch",
          "login_exact": "mpgranch",
          "name": "",
          "name_autocomplete": "",
          "orcid": null,
          "icon": "https://static.inaturalist.org/attachments/users/icons/1396209/thumb.jpg?1579554691",
          "observations_count": 1951,
          "identifications_count": 0,
          "journal_posts_count": 0,
          "activity_count": 1951,
          "species_count": 586,
          "universal_search_rank": 1951,
          "roles": [],
          "icon_url": "https://static.inaturalist.org/attachments/users/icons/1396209/medium.jpg?1579554691"
        },
        "captive": false,
        "created_time_zone": "America/Denver",
        "updated_at": "2021-02-17T12:55:58-07:00",
        "observed_time_zone": "America/Denver",
        "time_zone_offset": "-07:00",
        "uri": "https://www.inaturalist.org/observations/49347218",
        "description": "",
        "mappable": true,
        "species_guess": "Ethmia mirusella",
        "place_guess": "Missoula County, US-MT, US",
        "observed_on_string": "2020-06-11",
        "license_code": "cc-by-nc",
        "geoprivacy": null,
        "taxon_geoprivacy": null,
        "map_scale": null,
        "oauth_application_id": 195,
        "community_taxon_id": null,
        "faves_count": 0,
        "cached_votes_total": 0,
        "num_identification_agreements": 0,
        "num_identification_disagreements": 0,
        "identifications_most_agree": false,
        "identifications_some_agree": false,
        "identifications_most_disagree": false,
        "project_ids": [],
        "project_ids_with_curator_id": [],
        "project_ids_without_curator_id": [],
        "reviewed_by": [
          442615,
          1287370,
          1396209
        ],
        "tags": [],
        "ofvs": [],
        "annotations": [],
        "sounds": [],
        "ident_taxon_ids": [
          48460,
          1,
          47120,
          372739,
          47158,
          184884,
          47157,
          55518,
          423543,
          423545,
          173500,
          1341724,
          495775
        ],
        "identifications_count": 0,
        "comments": [
          {
            "id": 6347399,
            "uuid": "e0c7cc7a-91c0-497b-b5a6-b3ed3dbc4059",
            "user": {
              "id": 266742,
              "login": "cgrinter",
              "spam": false,
              "suspended": false,
              "created_at": "2016-06-30T18:13:53+00:00",
              "login_autocomplete": "cgrinter",
              "login_exact": "cgrinter",
              "name": "Chris Grinter",
              "name_autocomplete": "Chris Grinter",
              "orcid": "https://orcid.org/0000-0002-3769-1664",
              "icon": "https://static.inaturalist.org/attachments/users/icons/266742/thumb.jpg?1600888016",
              "observations_count": 436,
              "identifications_count": 1919,
              "journal_posts_count": 0,
              "activity_count": 2355,
              "species_count": 374,
              "universal_search_rank": 436,
              "roles": [],
              "site_id": 1,
              "icon_url": "https://static.inaturalist.org/attachments/users/icons/266742/medium.jpg?1600888016"
            },
            "created_at": "2021-02-17T19:55:58+00:00",
            "created_at_details": {
              "date": "2021-02-17",
              "day": 17,
              "month": 2,
              "year": 2021,
              "hour": 19,
              "week": 7
            },
            "body": "Size would be good to help with ID. E. albicostella is larger, image on MPG website is 27mm. From Powell 1973, \"a rather small Ethmia,... which resembles a faded E. albicostella\". Specimen on MPG is 19mm. I'm leaning towards E. albicostella on this one since it doesn't look as faded as mirusella should look. ",
            "flags": [],
            "moderator_actions": [],
            "hidden": false
          }
        ],
        "comments_count": 1,
        "obscured": false,
        "positional_accuracy": null,
        "public_positional_accuracy": null,
        "location": "46.67723,-113.993",
        "geojson": {
          "type": "Point",
          "coordinates": [
            -113.993,
            46.67723
          ]
        },
        "votes": [],
        "outlinks": [],
        "owners_identification_from_vision": false,
        "preferences": {
          "prefers_community_taxon": null
        },
        "flags": [],
        "quality_metrics": [],
        "spam": false,
        "faves": [],
        "non_owner_ids": [],
        "identifications": [
          {
            "hidden": false,
            "disagreement": false,
            "flags": [],
            "created_at": "2020-06-12T17:22:05+00:00",
            "taxon_id": 495775,
            "body": null,
            "own_observation": true,
            "uuid": "3406b810-b6a5-4d90-a01a-14697edcaa66",
            "taxon_change": null,
            "moderator_actions": [],
            "vision": false,
            "current": true,
            "id": 109731977,
            "created_at_details": {
              "date": "2020-06-12",
              "day": 12,
              "month": 6,
              "year": 2020,
              "hour": 17,
              "week": 24
            },
            "category": "leading",
            "spam": false,
            "user": {
              "id": 1396209,
              "login": "mpgranch",
              "spam": false,
              "suspended": false,
              "created_at": "2018-12-20T01:37:06+00:00",
              "login_autocomplete": "mpgranch",
              "login_exact": "mpgranch",
              "name": "",
              "name_autocomplete": "",
              "orcid": null,
              "icon": "https://static.inaturalist.org/attachments/users/icons/1396209/thumb.jpg?1579554691",
              "observations_count": 1951,
              "identifications_count": 0,
              "journal_posts_count": 0,
              "activity_count": 1951,
              "species_count": 586,
              "universal_search_rank": 1951,
              "roles": [],
              "site_id": 1,
              "icon_url": "https://static.inaturalist.org/attachments/users/icons/1396209/medium.jpg?1579554691"
            },
            "previous_observation_taxon_id": 495775,
            "taxon": {
              "photos_locked": false,
              "taxon_schemes_count": 1,
              "ancestry": "48460/1/47120/372739/47158/184884/47157/55518/423543/423545/173500/1341724",
              "min_species_ancestry": "48460,1,47120,372739,47158,184884,47157,55518,423543,423545,173500,1341724,495775",
              "wikipedia_url": "http://en.wikipedia.org/wiki/Ethmia_mirusella",
              "current_synonymous_taxon_ids": null,
              "iconic_taxon_id": 47158,
              "created_at": "2016-05-19T18:43:01+00:00",
              "taxon_changes_count": 0,
              "complete_species_count": null,
              "rank": "species",
              "extinct": false,
              "id": 495775,
              "universal_search_rank": 92,
              "ancestor_ids": [
                48460,
                1,
                47120,
                372739,
                47158,
                184884,
                47157,
                55518,
                423543,
                423545,
                173500,
                1341724
              ],
              "observations_count": 92,
              "is_active": true,
              "flag_counts": {
                "resolved": 0,
                "unresolved": 0
              },
              "min_species_taxon_id": 495775,
              "rank_level": 10,
              "atlas_id": null,
              "parent_id": 1341724,
              "name": "Ethmia mirusella",
              "default_photo": {
                "id": 45545363,
                "license_code": "cc-by-nc",
                "attribution": "(c) Lena Zappia, certains droits réservés (CC BY-NC), uploaded by Lena Zappia",
                "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/45545363/square.jpg",
                "original_dimensions": {
                  "height": 615,
                  "width": 785
                },
                "flags": [],
                "square_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/45545363/square.jpg",
                "medium_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/45545363/medium.jpg"
              },
              "iconic_taxon_name": "Insecta",
              "ancestors": [
                {
                  "observations_count": 52125442,
                  "taxon_schemes_count": 2,
                  "is_active": true,
                  "ancestry": "48460",
                  "flag_counts": {
                    "resolved": 11,
                    "unresolved": 0
                  },
                  "wikipedia_url": "http://en.wikipedia.org/wiki/Animal",
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 1,
                  "rank_level": 70,
                  "taxon_changes_count": 4,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 48460,
                  "complete_rank": "order",
                  "name": "Animalia",
                  "rank": "kingdom",
                  "extinct": false,
                  "id": 1,
                  "default_photo": {
                    "id": 80678745,
                    "license_code": "cc0",
                    "attribution": "no rights reserved, uploaded by Abhas Misraraj",
                    "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/80678745/square.jpg",
                    "original_dimensions": {
                      "height": 2000,
                      "width": 2000
                    },
                    "flags": [],
                    "square_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/80678745/square.jpg",
                    "medium_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/80678745/medium.jpg"
                  },
                  "ancestor_ids": [
                    48460,
                    1
                  ],
                  "iconic_taxon_name": "Animalia",
                  "preferred_common_name": "Animals"
                },
                {
                  "observations_count": 27888597,
                  "taxon_schemes_count": 2,
                  "is_active": true,
                  "ancestry": "48460/1",
                  "flag_counts": {
                    "resolved": 1,
                    "unresolved": 0
                  },
                  "wikipedia_url": "http://en.wikipedia.org/wiki/Arthropod",
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 1,
                  "rank_level": 60,
                  "taxon_changes_count": 2,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 1,
                  "complete_rank": "order",
                  "name": "Arthropoda",
                  "rank": "phylum",
                  "extinct": false,
                  "id": 47120,
                  "default_photo": {
                    "id": 19061166,
                    "license_code": "cc-by-nc-sa",
                    "attribution": "(c) fiatlux, some rights reserved (CC BY-NC-SA)",
                    "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/19061166/square.jpg",
                    "original_dimensions": {
                      "height": 1361,
                      "width": 2048
                    },
                    "flags": [],
                    "square_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/19061166/square.jpg",
                    "medium_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/19061166/medium.jpg"
                  },
                  "ancestor_ids": [
                    48460,
                    1,
                    47120
                  ],
                  "iconic_taxon_name": "Animalia",
                  "preferred_common_name": "Arthropods"
                },
                {
                  "observations_count": 24287343,
                  "taxon_schemes_count": 2,
                  "is_active": true,
                  "ancestry": "48460/1/47120",
                  "flag_counts": {
                    "resolved": 0,
                    "unresolved": 0
                  },
                  "wikipedia_url": "http://en.wikipedia.org/wiki/Hexapoda",
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 1,
                  "rank_level": 57,
                  "taxon_changes_count": 0,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 47120,
                  "complete_rank": "order",
                  "name": "Hexapoda",
                  "rank": "subphylum",
                  "extinct": false,
                  "id": 372739,
                  "default_photo": {
                    "id": 9286598,
                    "license_code": null,
                    "attribution": "(c) Tony Gerard, todos los derechos reservados, uploaded by Tony Gerard",
                    "url": "https://static.inaturalist.org/photos/9286598/square.jpg",
                    "original_dimensions": {
                      "height": 726,
                      "width": 970
                    },
                    "flags": [],
                    "square_url": "https://static.inaturalist.org/photos/9286598/square.jpg",
                    "medium_url": "https://static.inaturalist.org/photos/9286598/medium.jpg"
                  },
                  "ancestor_ids": [
                    48460,
                    1,
                    47120,
                    372739
                  ],
                  "iconic_taxon_name": "Animalia",
                  "preferred_common_name": "Hexapods"
                },
                {
                  "observations_count": 24237464,
                  "taxon_schemes_count": 2,
                  "is_active": true,
                  "ancestry": "48460/1/47120/372739",
                  "flag_counts": {
                    "resolved": 42,
                    "unresolved": 0
                  },
                  "wikipedia_url": "http://en.wikipedia.org/wiki/Insect",
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 47158,
                  "rank_level": 50,
                  "taxon_changes_count": 3,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 372739,
                  "complete_rank": "order",
                  "name": "Insecta",
                  "rank": "class",
                  "extinct": false,
                  "id": 47158,
                  "default_photo": {
                    "id": 3510880,
                    "license_code": null,
                    "attribution": "(c) José Manuel Carreón Silva, all rights reserved",
                    "url": "https://static.inaturalist.org/photos/3510880/square.jpg",
                    "original_dimensions": {
                      "height": 1536,
                      "width": 2048
                    },
                    "flags": [],
                    "square_url": "https://static.inaturalist.org/photos/3510880/square.jpg",
                    "medium_url": "https://static.inaturalist.org/photos/3510880/medium.jpg"
                  },
                  "ancestor_ids": [
                    48460,
                    1,
                    47120,
                    372739,
                    47158
                  ],
                  "iconic_taxon_name": "Insecta",
                  "preferred_common_name": "Insects"
                },
                {
                  "observations_count": 24126589,
                  "taxon_schemes_count": 2,
                  "is_active": true,
                  "ancestry": "48460/1/47120/372739/47158",
                  "flag_counts": {
                    "resolved": 3,
                    "unresolved": 0
                  },
                  "wikipedia_url": "http://en.wikipedia.org/wiki/Pterygota",
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 47158,
                  "rank_level": 47,
                  "taxon_changes_count": 4,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 47158,
                  "complete_rank": "order",
                  "name": "Pterygota",
                  "rank": "subclass",
                  "extinct": false,
                  "id": 184884,
                  "default_photo": {
                    "id": 53637930,
                    "license_code": "cc-by-nc",
                    "attribution": "(c) dhfischer, some rights reserved (CC BY-NC), uploaded by dhfischer",
                    "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/53637930/square.jpg",
                    "original_dimensions": {
                      "height": 533,
                      "width": 800
                    },
                    "flags": [],
                    "square_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/53637930/square.jpg",
                    "medium_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/53637930/medium.jpg"
                  },
                  "ancestor_ids": [
                    48460,
                    1,
                    47120,
                    372739,
                    47158,
                    184884
                  ],
                  "iconic_taxon_name": "Insecta",
                  "preferred_common_name": "Winged and Once-winged Insects"
                },
                {
                  "observations_count": 10210603,
                  "taxon_schemes_count": 2,
                  "is_active": true,
                  "ancestry": "48460/1/47120/372739/47158/184884",
                  "flag_counts": {
                    "resolved": 11,
                    "unresolved": 0
                  },
                  "wikipedia_url": "http://en.wikipedia.org/wiki/Lepidoptera",
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 47158,
                  "rank_level": 40,
                  "taxon_changes_count": 5,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 184884,
                  "name": "Lepidoptera",
                  "rank": "order",
                  "extinct": false,
                  "id": 47157,
                  "default_photo": {
                    "id": 36127,
                    "license_code": "cc-by-nc",
                    "attribution": "(c) Anita, some rights reserved (CC BY-NC)",
                    "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/36127/square.jpg",
                    "original_dimensions": {
                      "height": 1601,
                      "width": 1683
                    },
                    "flags": [],
                    "square_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/36127/square.jpg",
                    "medium_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/36127/medium.jpg"
                  },
                  "ancestor_ids": [
                    48460,
                    1,
                    47120,
                    372739,
                    47158,
                    184884,
                    47157
                  ],
                  "iconic_taxon_name": "Insecta",
                  "preferred_common_name": "Butterflies and Moths"
                },
                {
                  "observations_count": 224294,
                  "taxon_schemes_count": 2,
                  "is_active": true,
                  "ancestry": "48460/1/47120/372739/47158/184884/47157",
                  "flag_counts": {
                    "resolved": 1,
                    "unresolved": 0
                  },
                  "wikipedia_url": "http://en.wikipedia.org/wiki/Gelechioidea",
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 47158,
                  "rank_level": 33,
                  "taxon_changes_count": 0,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 47157,
                  "name": "Gelechioidea",
                  "rank": "superfamily",
                  "extinct": false,
                  "id": 55518,
                  "default_photo": {
                    "id": 82226494,
                    "license_code": "cc-by-nc",
                    "attribution": "(c) John Morgan, some rights reserved (CC BY-NC), uploaded by John Morgan",
                    "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/82226494/square.jpeg",
                    "original_dimensions": {
                      "height": 798,
                      "width": 751
                    },
                    "flags": [],
                    "square_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/82226494/square.jpeg",
                    "medium_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/82226494/medium.jpeg"
                  },
                  "ancestor_ids": [
                    48460,
                    1,
                    47120,
                    372739,
                    47158,
                    184884,
                    47157,
                    55518
                  ],
                  "iconic_taxon_name": "Insecta",
                  "preferred_common_name": "Curved-horn Moths"
                },
                {
                  "observations_count": 31130,
                  "taxon_schemes_count": 1,
                  "is_active": true,
                  "ancestry": "48460/1/47120/372739/47158/184884/47157/55518",
                  "flag_counts": {
                    "resolved": 0,
                    "unresolved": 0
                  },
                  "wikipedia_url": "http://en.wikipedia.org/wiki/Depressariidae",
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 47158,
                  "rank_level": 30,
                  "taxon_changes_count": 0,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 55518,
                  "name": "Depressariidae",
                  "rank": "family",
                  "extinct": false,
                  "id": 423543,
                  "default_photo": {
                    "id": 28796346,
                    "license_code": "cc-by-nc",
                    "attribution": "(c) Andrey Ponomarev, some rights reserved (CC BY-NC), uploaded by Andrey Ponomarev",
                    "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/28796346/square.jpg",
                    "original_dimensions": {
                      "height": 1217,
                      "width": 1826
                    },
                    "flags": [],
                    "square_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/28796346/square.jpg",
                    "medium_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/28796346/medium.jpg"
                  },
                  "ancestor_ids": [
                    48460,
                    1,
                    47120,
                    372739,
                    47158,
                    184884,
                    47157,
                    55518,
                    423543
                  ],
                  "iconic_taxon_name": "Insecta",
                  "preferred_common_name": "Flat-bodied moths"
                },
                {
                  "observations_count": 5558,
                  "taxon_schemes_count": 1,
                  "is_active": true,
                  "ancestry": "48460/1/47120/372739/47158/184884/47157/55518/423543",
                  "flag_counts": {
                    "resolved": 0,
                    "unresolved": 0
                  },
                  "wikipedia_url": "http://en.wikipedia.org/wiki/Ethmiinae",
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 47158,
                  "rank_level": 27,
                  "taxon_changes_count": 1,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 423543,
                  "name": "Ethmiinae",
                  "rank": "subfamily",
                  "extinct": false,
                  "id": 423545,
                  "default_photo": {
                    "id": 1473495,
                    "license_code": "cc-by-nc",
                    "attribution": "(c) Scott King, some rights reserved (CC BY-NC)",
                    "url": "https://static.inaturalist.org/photos/1473495/square.jpg",
                    "original_dimensions": {
                      "height": 974,
                      "width": 1624
                    },
                    "flags": [],
                    "square_url": "https://static.inaturalist.org/photos/1473495/square.jpg",
                    "medium_url": "https://static.inaturalist.org/photos/1473495/medium.jpg"
                  },
                  "ancestor_ids": [
                    48460,
                    1,
                    47120,
                    372739,
                    47158,
                    184884,
                    47157,
                    55518,
                    423543,
                    423545
                  ],
                  "iconic_taxon_name": "Insecta"
                },
                {
                  "observations_count": 5182,
                  "taxon_schemes_count": 1,
                  "is_active": true,
                  "ancestry": "48460/1/47120/372739/47158/184884/47157/55518/423543/423545",
                  "flag_counts": {
                    "resolved": 1,
                    "unresolved": 0
                  },
                  "wikipedia_url": "http://en.wikipedia.org/wiki/Ethmia",
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 47158,
                  "rank_level": 20,
                  "taxon_changes_count": 0,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 423545,
                  "name": "Ethmia",
                  "rank": "genus",
                  "extinct": false,
                  "id": 173500,
                  "default_photo": {
                    "id": 249687,
                    "license_code": "cc-by-nc",
                    "attribution": "(c) Greg Lasley, some rights reserved (CC BY-NC), uploaded by Greg Lasley",
                    "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/249687/square.jpg",
                    "original_dimensions": {
                      "height": 1500,
                      "width": 1000
                    },
                    "flags": [],
                    "square_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/249687/square.jpg",
                    "medium_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/249687/medium.jpg"
                  },
                  "ancestor_ids": [
                    48460,
                    1,
                    47120,
                    372739,
                    47158,
                    184884,
                    47157,
                    55518,
                    423543,
                    423545,
                    173500
                  ],
                  "iconic_taxon_name": "Insecta"
                },
                {
                  "observations_count": 346,
                  "taxon_schemes_count": 0,
                  "is_active": true,
                  "ancestry": "48460/1/47120/372739/47158/184884/47157/55518/423543/423545/173500",
                  "flag_counts": {
                    "resolved": 0,
                    "unresolved": 0
                  },
                  "wikipedia_url": null,
                  "current_synonymous_taxon_ids": null,
                  "iconic_taxon_id": 47158,
                  "rank_level": 13,
                  "taxon_changes_count": 0,
                  "atlas_id": null,
                  "complete_species_count": null,
                  "parent_id": 173500,
                  "name": "Ethmia trifurcella",
                  "rank": "section",
                  "extinct": false,
                  "id": 1341724,
                  "default_photo": null,
                  "ancestor_ids": [
                    48460,
                    1,
                    47120,
                    372739,
                    47158,
                    184884,
                    47157,
                    55518,
                    423543,
                    423545,
                    173500,
                    1341724
                  ],
                  "iconic_taxon_name": "Insecta"
                }
              ]
            },
            "previous_observation_taxon": {
              "photos_locked": false,
              "taxon_schemes_count": 1,
              "ancestry": "48460/1/47120/372739/47158/184884/47157/55518/423543/423545/173500/1341724",
              "min_species_ancestry": "48460,1,47120,372739,47158,184884,47157,55518,423543,423545,173500,1341724,495775",
              "wikipedia_url": "http://en.wikipedia.org/wiki/Ethmia_mirusella",
              "current_synonymous_taxon_ids": null,
              "iconic_taxon_id": 47158,
              "created_at": "2016-05-19T18:43:01+00:00",
              "taxon_changes_count": 0,
              "complete_species_count": null,
              "rank": "species",
              "extinct": false,
              "id": 495775,
              "universal_search_rank": 92,
              "ancestor_ids": [
                48460,
                1,
                47120,
                372739,
                47158,
                184884,
                47157,
                55518,
                423543,
                423545,
                173500,
                1341724,
                495775
              ],
              "observations_count": 92,
              "is_active": true,
              "flag_counts": {
                "resolved": 0,
                "unresolved": 0
              },
              "min_species_taxon_id": 495775,
              "rank_level": 10,
              "atlas_id": null,
              "parent_id": 1341724,
              "name": "Ethmia mirusella",
              "default_photo": {
                "id": 45545363,
                "license_code": "cc-by-nc",
                "attribution": "(c) Lena Zappia, certains droits réservés (CC BY-NC), uploaded by Lena Zappia",
                "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/45545363/square.jpg",
                "original_dimensions": {
                  "height": 615,
                  "width": 785
                },
                "flags": [],
                "square_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/45545363/square.jpg",
                "medium_url": "https://inaturalist-open-data.s3.amazonaws.com/photos/45545363/medium.jpg"
              },
              "iconic_taxon_name": "Insecta"
            }
          }
        ],
        "project_observations": [],
        "photos": [
          {
            "id": 78334888,
            "license_code": "cc-by-nc",
            "original_dimensions": {
              "width": 2048,
              "height": 1536
            },
            "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/78334888/square.jpeg",
            "attribution": "(c) mpgranch, some rights reserved (CC BY-NC)",
            "flags": []
          }
        ],
        "observation_photos": [
          {
            "id": 72845865,
            "position": 0,
            "uuid": "767b3e7a-b8ff-4bc4-85e0-dc86c88076e3",
            "photo": {
              "id": 78334888,
              "license_code": "cc-by-nc",
              "original_dimensions": {
                "width": 2048,
                "height": 1536
              },
              "url": "https://inaturalist-open-data.s3.amazonaws.com/photos/78334888/square.jpeg",
              "attribution": "(c) mpgranch, some rights reserved (CC BY-NC)",
              "flags": []
            }
          }
        ]
      },
      "moderator_actions": []
    }
  ]
}
```

## Components
##### Writing out your components and its descriptions isn't a required part of the proposal but can be helpful.

Based on the initial logic defined in the previous sections try and breakdown the logic further into stateless/stateful components. 

| Component | Description | 
| --- | :---: |  
| App | This will make the initial data pull and include React Router| 
| Header | This will render the header include the nav | 
| Footer | This will render the header include the nav | 


## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project such as Axios, ReactStrap, D3, etc. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description.  Code snippet should not be greater than 10 lines of code. 

```
function reverse(string) {
	// here is the code to reverse a string of text
}
```
