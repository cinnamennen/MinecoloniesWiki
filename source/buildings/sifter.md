---
title: MineColonies Wiki
layout: default
---
# Sifter's Hut

<div class="infobox box text-center">
    <img src="../../assets/images/buildings/sifter.png" alt="Sifter's Hut" />
    <hr />
    <div class="row section-text text-left">
        <div class="col">
        <p><strong>Worker:</strong></p>
        </div>
        <div class="col">
        <p><a href="../workers/sifter">Sifter</a></p>
        </div>
    </div>
    <hr />
    <recipe>sifter</recipe>
</div>

## About the Sifter's Hut

### Note: The Sifter's Hut cannot be built until you have a level 3 [Fisherman's Hut](../../source/buildings/fisherman) (or three level 1 Fisherman's Huts, or another equivalent) and have finished the research in the [University](../../source/buildings/university).
<br>

The Sifter's Hut is where the Sifter will sift through dirt, gravel, sand, or soul sand to find loot. Doing this will make the block the Sifter is sifting disappear. 


| Sifted Block| Chance for |
| ----- | ----- |
| Dirt |	Beetroot seeds
| Dirt |	Carrots
| Dirt |	Melon seeds
| Dirt |	Potatoes
| Dirt |	Pumpkin seeds
| Dirt |	Oak saplings
| Dirt |	Spruce saplings
| Dirt |	Birch saplings
| Dirt |	Jungle saplings
| Dirt |	Acacia saplings
| Dirt |	Dark oak saplings
| Dirt |	Wheat seeds
| Gravel |	Coal
| Gravel |	Diamonds
| Gravel |	Lapis lazuli
| Gravel |	Emeralds
| Gravel |	Flint
| Gravel |	Gold ingots
| Gravel |	Iron ingots
| Gravel |	Iron nuggets
| Gravel |	Redstone
| Sand |	Cacti
| Sand |	Cocoa beans
| Sand |	Gold nuggets
| Sand |	Sugarcane
| Soul Sand |	Blaze powder
| Soul Sand |	Glowstone dust
| Soul Sand |	Magma cream
| Soul Sand |	Nether wart
| Soul Sand |	Quartz
| Soul Sand |	Human skulls


You can choose between four meshes. The higher the level of the mesh, the higher the likelihood that the Sifter will find loot.


| Hut Level | Mesh Available | 
| ----- | ----- | 
| 1         | String         | 
| 2         | Flint          | 
| 3         | Iron           | 
| 4         | Diamond        | 


## Sifter Hut GUI

When accessing the Sifter's Hut block by right-clicking on it, you will see a GUI with different options:

<br>
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/siftergui1.png" class="img-fluid mx-auto" alt="Sifter GUI">
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
<br> <br>
This is page two of the Sifter's Hut GUI.
<br>
<div class="row">
  <div class="col-sm-12 col-md">
    <img src="../../assets/images/gui/sifter_gui2.png" class="img-fluid mx-auto" alt="Sifter GUI">
  </div>
  <div class="col-sm-12 col-md">
    <ul>
     <li><strong>Block: </strong>You can choose what block you want the Sifter to sift by clicking on the button. The blocks to choose from are dirt, gravel, sand, and soul sand, however you can change this in the config file. If you change this, you must click save.</li>
     <li><strong>Amount: </strong>You can choose how many blocks are sifted daily. The max number is based on the level of the Sifter's Hut. If you change this, you must click save.</li>
     <li><strong>Meshes: </strong>You can purchase different levels of meshes, and each level has a higher likelihood of getting loot. If you have string, flint, iron ingots, or diamonds in your inventory, you will see the buy option beside the mesh type. If a mesh is in green, like string is in this picture, it means that mesh is the one the Sifter will use. You can only use one mesh at a time.</li>
    </ul>
  </div>
</div>  
