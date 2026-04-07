Define a collective heating demand cluster
==========================================

To define a collective heating demand cluster, the following steps must be followed:

1. Add a HeatingDemand asset to the map
---------------------------------------
The HeatingDemand asset represents the heat exchange (WOS) and the distribution network that connects the individual buildings.

From the AssetDrawToolbar at the bottom select the HeatingDemand asset

  .. image:: images/select_heating_demand.png
    :alt: AssetDrawToolbar - HeatingDemand asset

This asset can then be added as a point (representing a single location) or as a polygon (indicating the area)

To add the asset with a point shape geometry, just click anywhere on the map.
To add the asset with a polygon shape geometry, change the drawing behaviour to polygons

  .. image:: images/change_to_polygon.png
    :alt: Change to draw a polygon shaped asset

Then start drawing you polygon on the map. Finish the polygon by clicking on the first point again

  .. image:: images/finalized_heating_demand_cluster.png
    :alt: Finalized heating demand cluster

2. Specify the maximum capacity
-------------------------------
Click on the asset with the mouse and edit the power attribute in the sidebar. The power must be entered in Watts. The user can enter things like `2G` for 2 Giga Watts or `10.5M` for 10.5 Mega Watts.

  .. image:: images/changing_the_power.png
    :alt: Changing the power

3. Specify the CAPEX costs
--------------------------
The CAPEX costs of the HeatingDemand asset represent the CAPEX costs of the secondary system between the heating transfer substation and building connections

The CAPEX costs are given in EUR/MW and scaled with the value of the power attribute.

Click on the `Change or add costs` button

  .. image:: images/cost_information.png
    :alt: Cost information

Change the value of the investment costs or any other costs according to your needs

  .. image:: images/change_the_cost_values.png
    :alt: change_the_cost_values.png

4. Add the heating demand profile
---------------------------------

To be added
