# Spatial relationships

Determine spatial relationships between two geometries.

![](screenshot.png)

## Use case

In case of a natural disaster, emergency services can represent the affected areas using polygons. By determining the spatial relationships between these and any other existing features such as populated areas, infrastructure, or natural resources, it is possible to quickly determine which of the existing features might be affected or is in further danger, helping to assess risk and define further action.

## How to use the sample

Select one of the three graphics. The tree view will list the relationships the selected graphic has to the other graphic geometries.

## How it works

1.  Get the geometry from two different graphics. In this example the geometry of the selected graphic is compared to the geometry of each unselected graphic.
2.  Use the methods in `GeometryEngine` to check the relationship between the geometries, e.g. `contains`, `disjoint`, `intersects`, etc. If the method returns `true`, the relationship exists.

## Relevant API

*   Geometry
*   GeometryEngine
*   GeometryEngine::contains
*   GeometryEngine::crosses
*   GeometryEngine::disjoint
*   GeometryEngine::intersects
*   GeometryEngine::overlaps
*   GeometryEngine::touches
*   GeometryEngine::within
*   GeometryType
*   Graphic
*   Point
*   Polygon
*   Polyline

## Tags

geometries, relationship, spatial analysis
