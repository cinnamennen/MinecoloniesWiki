---
title: MineColonies Wiki
layout: default
---
# Stone Smeltery

<div class="infobox box text-center">
    <img src="../../assets/images/buildings/stonesmeltery.png" alt="Stone Smeltery's Hut" />
    <hr />
    <div class="row section-text text-left">
        <div class="col">
        <p><strong>Worker:</strong></p>
        </div>
        <div class="col">
        <p><a href="../workers/stonesmelter">Stone Smelter</a></p>
        </div>
    </div>
    <hr />
    <recipe>stonesmeltery</recipe>
</div>

## About the Stone Smeltery

### Note: The Stone Smeltery cannot be built until you have a level 3 [Smeltery](../../source/buildings/smeltery) (or three level 1 Smelteries, or another equivalent) and have finished the research in the [University](../../source/buildings/university).
<br>

The Stone Smeltery is where the Stone Smelter will smelt cobblestone into stone, stone bricks into cracked stone bricks, clay balls into bricks, and clay blocks into terracotta. The Stone Smelter will only do this if they receive a request from another worker and they have the needed materials/fuel.

**Hint:** The higher the level of the Stone Smeltery, the more furnaces the Stone Smelter will be able to use. So:


| Building Level |  Furnaces |
| :-----: | :-----: | 
| 1 |  1 |
| 2 |  2 |
| 3 |  3 |
| 4 |  4 |
| 5 |  5 |


## Stone Smeltery GUI

When accessing the Stone Smeltery's hut block by right-clicking on it, you will see a GUI with different options:

<br>
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/stonesmelterygui1.png" class="img-fluid mx-auto" alt="Stone Smeltery GUI">
  </div>
  <div class="col-sm-12 col-md">
    <br>
    <ul>
      {% for item in site.data.gui.global %}
        <li><strong>{{ item.button }}:</strong> {{ item.content }}</li>
      {% endfor %}
    </ul>
  </div>
</div>
<br>
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/stonesmelterygui2.png" class="img-fluid mx-auto" alt="Smeltery GUI">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
      <li><strong>Fuel: </strong>Listed here are items that can be used by the Stone Smelter as fuel in their furnaces. Turn on any that you want your Stone Smelter to use, and a Deliveryman will deliver those items to the Stone Smelter when they need fuel. (The black box at the top is to search for items.)
      </ul>
    </ul>
  </div>
</div>  
  
  <br>
