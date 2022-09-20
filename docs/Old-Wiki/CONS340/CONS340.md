Tin - Triangulated irregular Network

-   The world represented as a network as linked triangles drawn
    irregularly spaces points with x,y,z values
-   Although tin is a vector format, it is a specialized vector format
    because it does not represent individual features
-   Tin represents a surface
-   Efficient way to store and analyze surfaces
-   When you zoom in on the surface you will note that it is made of
    triangles

Tin creation

mass points

-   Lidar points, record different returns at different levels close to
    the surface to make a mass point
-   Replaces polygons
    -   adds polygon
-   Erase polygons
    -   erases polygons
-   Clip
    -   Can clip polygons as well

breakline Enforcement

-   Creates a breakline to help serpreate and visual information on a
    surface

interpolation and contouring

-   can interpolate to a raster or a TIN
    -   Can go back and forth between raster or tin

Generate surfaces from point measurement - Natural neighbors - Minimum
curvature spline - Spline and barriers - TopotoRaster - Kriging

-   Polynomial trend Surface
-   Inverse distance weighted (IDW)

Create contours from surfaces

-   Batch GP tools
-   Interactive contours

Choosing an interpolation method

You know nothing about your data...

-   Use NAtural Neighbors its the most conservative, Assumes all highs
    and lows are sampled, will not create artifacts
    -   Will not create a high higher than the max that you set Your
        input data is contours
-   Use TopoToRaster. It is optimized for contour input. If not creating
    a DEM, turn off the drainage enforcement option You know the highs
    and lows are not sampled...
-   Use Spline. Be careful of point that are near in space but very
    different in values creating unnatural artifacts Your surface is not
    continuous
-   Use Spline with Barriers if you know there are faults or other
    discontinuities in the surface

Natural Neighbors

-   Based on Voronoi tessellation

-   Strengths

-   Conservatievely smooth

-   Interpolated Z range from within a range of data

-   Smart Selection of samples

-   Supported input data types

    -   Points (2D - with attributes)
    -   Note: Also supported by TIN to raster Green on a Natural
        Neighbor will be the "weight" and will determine how much
        significant it is to the elevation value to the polygon

Topo To Raster

-   Strengths
    -   Creates raster from contours
    -   Can add additional information and input data

spline

-   Minimum curvature spline that honors barriers, faults, etc

Kriging

-   Strengths
    -   Probabilistic
    -   Well behaved with sparse data
    -   Great at "guessing data"

what is linear referencing

-   Method of storing geographic features by using relative positions
    along with a measured line feature
    -   Essentially creates a route for you by analyzing different lines
        in between (essentially using the google line to travel)

features using a linear system

-   Feature's location determined using a linear system of a measure
    values, instead of using x,y coordinates

Dynamic segmentation

-   Anything linear will use this type of information storage
    -   Width Information is also stored
-   Enables the association of multisets of attributes to portions of
    linear features about segmenting the underlying line each time
    attribute value changes

Features containing one to many relationships

-   Two or more pieces of information associated with the same location
    on a line
-   can see speed, width, gradients, habitats on a river, and data will
    be stored for each on the same line (kind of like additionally
    attributes)

features containing frequently segmented data

-   Some types of features have attributes that change frequently

routes

-   Linear features - (in a polyline feature class) Must have an
    identifier & measurement system
-   Store in Geodatabase, Shapefile, or Coverage. Routes can model
-   Looping, Branching, 180 degree turns

event table

-   Routes locations thematically stored in tables are called "route
    events: or simply"events\"

2 types

-   Point event table
    -   Accident, samples sites,
    -   Requires 2 fields = Route location and Attributes
    -   The measure is the event's location on the line
-   Line Event Table
    -   Store regions on a line

EN

/Lecture 18 surfaces

Markdown
