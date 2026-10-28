# Iwate extract of 現存植生図2024: verification and profile

- polygons: 248,187 (248,187 MultiPolygon), CRS EPSG:6668, bbox lon 140.6531 to 142.0725, lat 38.7477 to 40.4503
- source files: {'veg2024bk2b.gpkg': 248021, 'veg2024bk2a.gpkg': 166}
- cut: 244,799 polygons wholly inside Iwate kept as they are; 3,388 polygons that cross the boundary were clipped to it (none dropped); the clipped polygons had 2832.5 km2 before the cut and keep 728.1 km2
- area: 15271.797 km2 in EPSG:6678, against 15271.748 km2 for the N03 polygon of Iwate (100.00032%, difference +0.049 km2)
- area by 地域ブロック: 2 東北 15271.797 km2 (100.00% of N03)
- geometry validity: 0 invalid, 0 empty; fid unique: True
- overlaps: 830 pairs of polygons overlap by a sliver (largest 1.33e-07 square degrees, about 1258 m2); not repaired
- NULLs: 0 in all columns

## 作成年度 (polygons)

| year | polygons |
| --- | ---: |
| 2003 | 17,531 |
| 2005 | 13,128 |
| 2008 | 41,928 |
| 2010 | 5,783 |
| 2013 | 20,265 |
| 2014 | 65,715 |
| 2015 | 83,785 |
| 2016 | 52 |

## Legends whose name contains ブナ, ミズナラ, ナラ or コナラ

18 of the 131 legends present in Iwate; 39,872 polygons, 5807.2 km2 together (the legends overlap in meaning, do not read this as one class).

| code | name (original) | polygons | area km2 | ブナ | ミズナラ | ナラ | コナラ |
| --- | --- | ---: | ---: | :-: | :-: | :-: | :-: |
| 110100 | チシマザサ－ブナ群団 | 958 | 712.36 | x |  |  |  |
| 110103 | スギ－ブナ群落 | 92 | 5.27 | x |  |  |  |
| 130105 | スズタケ－ブナ群集 | 3 | 3.35 | x |  |  |  |
| 130200 | イヌブナ群落 | 37 | 6.47 | x |  |  |  |
| 190100 | ウラジロヨウラク－ミヤマナラ群団 | 233 | 31.56 |  |  | x |  |
| 220100 | ブナ－ミズナラ群落 | 1,175 | 308.77 | x | x | x |  |
| 220101 | スギ－ミズナラ群落 | 1 | 0.23 |  | x | x |  |
| 220102 | クリ－ミズナラ群集 | 262 | 90.18 |  | x | x |  |
| 220103 | オオバクロモジ－ミズナラ群集 | 2,211 | 466.99 |  | x | x |  |
| 220104 | ブナ二次林 | 6 | 0.81 | x |  |  |  |
| 220106 | キタコブシ－ミズナラ群集 | 1,064 | 274.51 |  | x | x |  |
| 220500 | コナラ群落（V） | 19,263 | 1798.81 |  |  | x | x |
| 220501 | オクチョウジザクラ－コナラ群集 | 237 | 18.59 |  |  | x | x |
| 220502 | カスミザクラ－コナラ群落 | 1,205 | 125.91 |  |  | x | x |
| 220505 | ホソバヒカゲスゲ－コナラ群集 | 5,797 | 669.16 |  |  | x | x |
| 221100 | ミズナラ群落（V） | 3,949 | 859.93 |  | x | x |  |
| 221500 | イヌブナ二次林 | 2 | 0.08 | x |  |  |  |
| 410101 | クリ－コナラ群集 | 3,377 | 434.26 |  |  | x | x |

The match is by substring on the original name. ナラ also matches names that are neither ミズナラ nor コナラ: ウラジロヨウラク－ミヤマナラ群団 (190100). ブナ also matches イヌブナ, another species: イヌブナ群落 (130200), イヌブナ二次林 (221500).
The full list of Iwate legends is `legend_iwate.tsv`.

## 作成年度 of the polygons of those legends

| year | polygons |
| --- | ---: |
| 2003 | 2,364 |
| 2005 | 2,081 |
| 2008 | 7,622 |
| 2010 | 748 |
| 2013 | 3,932 |
| 2014 | 10,189 |
| 2015 | 12,919 |
| 2016 | 17 |
