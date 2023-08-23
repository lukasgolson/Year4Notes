The Earth is Not Round

-   First the Earth was flat
-   500 BC Pythagoras declared it was a sphere
-   1600's Sir Issac Newton hypothesized that the true shape of the
    earth was really closer to an ellipse
    -   More precisely, an oblate ellipsoid 

 

Eratosthenes

-   Greek Mathematician
-   Lived 276-194 BC
-   Responsible for
    -   Establishing geography
    -   First accurate measure of Earth's circumference
        -   Noticed how the Sun shone directly down a well in Syene at
            noon on the Solstice. Made a second observation at
            Alexandria with a pole and noticed a shadow. He measured the
            angle of the Shadow and inferred the circumference of Earth,
            which was already known to be spherical
    -   Calculating the tilt of Earth's axis
    -   Calculating the distance of Earth to the Sun
    -   Invention of the leap day
    -   First world map of the (spherical) Earth

 

 

Geodesy

-   The science that studies and determines the shape and dimensions of
    the Earth
-   Different models have been defined to represent Earth's shape,
    varying in complexity and accuracy.

 

Geoid

-   Physical approximation of the figure of the Earth
-   Shape of the surface of calmed oceans, in the absence of other
    influences such as winds and tides
-   Computed using complex physical models and gravity readings of
    Earth's surface
-   Used to measure surface elevations with a high degree of accuracy

 

Ellipsoid

-   Mathematical approximation of the shape of the earth
-   The earth is flattened at the poles and bulges at the equator due to
    its revolution
-   Ellipsoid geodesy is uniquely defined by two numbers: semi-major
    (wide axis) and semi-minor axis (shorter axis)
    -   A\>B

 

Sphere

-   Simplest (and least accurate) approximation of the shape of the
    Earth
-   Radius is constant
-   a=b

 

Spheroid is an ellipsoid that approximates the shape of a sphere

-   Earth can be approximated by an oblate ellipsoid, but it's major and
    minor axes do not vary greatly
-   Shape is so close to a sphere that is it often called a spheroid
    rather than an ellipsoid

 

 

 

Why do we need more than one ellipsoid?

-   The Earth's surface is not perfectly symmetrical
-   The semi-major and semi-minor axes that fit one geographical region
    do not necessarily fit another

 

Datum

-   A reference ellipsoid for locating points on Earth's surface
    -   Defines origin and orientation of latitude/longitude line
    -   Defined by ellipsoid and ellipsoid's position relative to
        Earth's center
    -   Two Types
        -   Earth-centered
        -   Local

 

 

Latitude

-   Angle from center Earth that describes the North-South position

Longitude

-   Angle from center Earth that describes the east-west position

 

Latitude/longitude

-   Not uniform units of measure
-   Meridians converge near poles

 

 

Prime meridian

-   Arbitrary origin of Longitude lines
-   Usually greenwich, England
-   Others include Paris, Bogota, etc.

 

Degrees Minutes Seconds (DMS)

-   Degrees of latitude and longitude are further broken down into
    Minutes and Seconds

 

Decimal Degrees (DD)

-   Decimal degrees are similar to degree/minutes/seconds (DMS) except
    that minute and seconds are expressed as decimal values
-   Decimal degrees make digital storage of coordinates easier and
    computations faster

 

 

Conversion from DMS to DD:

-   Example coordinate is 37 (deg) 36' 30\" (dms)
-   Divide each value by the number of minutes or seconds in a degree:
    -   36 minutes = 0.6 degrees (36 /60)
    -   30 seconds = 0.0833 degrees (30/3600)
    -   Add up the degrees to get the answer
    -   37 (deg) + .60 (deg) + 0.0833 (deg) = 37.60833 DD

 

 

 

Basic Geodesy Facts

-   Great circle - arc formed by the intersection of the earth with a
    plane passing through any two surface points and the center of the
    Earth
-   Magnetic directions must take into account the compass variation
    (magnetic declination)
-   Rhumb line - loxodrome or constant azimuth - line which makes a
    fixed angle with all meridians; spirals to pole

 

Geographic Coordinate System

-   The Equator and Prime Meridian are the reference points
-   Latitude / Longitude measure angles
    -   Latitude (parallels) 0 deg - 90 deg
    -   Longitude (meridians) 0 deg - 180 deg
-   Defines locations on 3-D surface
-   Units are degrees (or grads)
-   Not a map projection

 

 

Map projection

-   Curved surface (3D) -\> 2D flat surface
-   Approaches to transfer the spherical Earth on a two dimensional
    plane
-   Some distortions will always occur
-   Visualize a light shine through the Earth onto a surface
-   Distortions
    -   Fitting sphere to plane causes stretching or shrinking of
        features
    -   Types
        -   Shape
        -   Area
        -   Distance
        -   Direction

 

Projection Properties

-   Conformal
    -   Maintains shape
-   Equal-area
    -   Maintains area
-   Equidistant
    -   Maintains distance
-   Azimuthal (Planar)
    -   Maintains some directions

 

 

 

How to measure distortion from map projections?

-   Tissot's Indicatrix
    -   Measures and visualize distortions of shape and area at a single
        location on a projected map relative to a reference globe

 

 

Developable Surfaces

1.  Cylindrical projections
    1.  The earth is projected on a cylinder
    2.  Whole-world maps are rectangular
    3.  Distortion on the poles
2.  Conic projections
    1.  The Earth is projected on a cone
    2.  Good for representing parts of the Earth
3.  Planar projections
    1.  The Earth is projected on a plane
    2.  Lots of distortion towards the edges

 

Developable surfaces contacting spheres

-   Tangent
    -   Projection surface touches sphere
-   Secant
    -   Surface cuts through sphere
-   No distortion at contact points
-   Increases away from contact points

 

 

Cylindrical projection

-   Longitudes equally spaced
-   Latitudes unequally spaced
-   Scale is true along equator
-   Shape and scale distortions increase near poles
-   Best for equatorial or low latitudes

 

 

 

Common projections

-   Mercator
    -   Projected on a cylinder
    -   Any straight line is a line of constant direction
    -   Used for navigation
    -   True directions
    -   Conformal (angles and shapes true in small areas) but not equal
        area or equidistant
    -   Cylindrical
-   Universal transverse Mercator
    -   Divides the earth from latitudes 84N to 80S in 60 vertical zones
        that are 6 deg wide
    -   Zones are numbered starting at 180th meridian in eastward
        direction
    -   Each zone is divided into sections of 8 deg latitude each
    -   Eastings (from Central meridian) and Northings (from equator)
        can be designated for each zone
    -   UTM preserves area, Distance, and Shape well
-   Albers equal area
    -   Conic (secant case)
    -   Well suited for areas that are mainly east-west in extent
    -   Areas - True
    -   Drections - Reasonably accurate in limited regions
    -   Distances and Scale true only along standard parallels
    -   Map - not conformal
    -   Used for Thematic maps
-   Lambert's conformal conic
    -   Conic (Secant case)
    -   Distances - True only along standard parallels
    -   Map - conformal but not equal area or equidistant
    -   Area and Shape - Distortion minimal at std. parallels
    -   Directions - Reasonably accurate
    -   Shape - True for small areas
    -   To map large ocean Areas and regions in E-W extent
-   Azimuthal equidistant
    -   Extent - World; Eq/mid-lat/Polar
    -   Distances measured from centre are true; Distortion of other
        properties increases from centre point
    -   Useful for showing airline distances from centre point
    -   Useful for seismic and radio work
