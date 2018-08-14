---
layout: page

category: "Reference"
title:  "Item Attributes"

---

Players or mobs carrying or wearing items with these attributes will have the effects specified applied to themselves.

<div class='table-responsive'>
  <table class='table table-striped table-condensed'>
    <thead>
      <tr>
        <th>Name</th>
        <th>Description</th>
        <th>Default Base</th>
        <th>Min</th>
        <th style='min-width: 60px;'>Max</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>
          <code>generic.maxHealth</code>
        </td>
        <td>The maximum health of this mob, determines the highest health they may be healed to.</td>
        <td>20.0</td>
        <td>0.0</td>
        <td>1.7x10<sup>308</sup></td>
      </tr>
      <tr>
        <td>
          <code>generic.knockbackResistance</code>
        </td>
        <td>
          Resistance to knockback from attacks, explosions, and projectiles.
          <br/>
          <i>1.0 is full knockback resistance.</i>
        </td>
        <td>0.0</td>
        <td>0.0</td>
        <td>1.0</td>
      </tr>
      <tr>
        <td>
          <code>generic.movementSpeed</code>
        </td>
        <td>Speed of movement in some unknown metric. The mob's maximum speed in blocks/second is a bit over 43 times this value, but can be affected by various conditions.</td>
        <td>0.7</td>
        <td>0.0</td>
        <td>1.7x10<sup>308</sup></td>
      </tr>
      <tr>
        <td>
          <code>generic.attackDamage</code>
        </td>
        <td>Damage dealt by attacks, in half-hearts.</td>
        <td>2.0</td>
        <td>0.0</td>
        <td>1.7x10<sup>308</sup></td>
      </tr>
      <tr>
        <td>
          <code>generic.armor</code>
        </td>
        <td>Armor defense points.</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>30.0</td>
      </tr>
      <tr>
        <td>
          <code>generic.armorToughness</code>
        </td>
        <td>Armor toughness.</td>
        <td>0.0</td>
        <td>0.0</td>
        <td>20.0</td>
      </tr>
      <tr>
        <td>
          <code>generic.followRange</code>
        </td>
        <td>The range in blocks within which a mob with this attribute will target players or other mobs to track. </td>
        <td>32.0</td>
        <td>0.0</td>
        <td>2048.0</td>
      </tr>
      <tr>
        <th colspan='5'>Player Attributes</th>
      </tr>
      <tr>
        <td>
          <code>generic.attackSpeed</code>
        </td>
        <td>Determines speed at which attack strength recharges. Value is the number of full-strength attacks per second.</td>
        <td>4.0</td>
        <td>0.0</td>
        <td>1024.0</td>
      </tr>
      <tr>
        <td>
          <code>generic.luck</code>
        </td>
        <td>Affects the results of loot tables using the quality or bonus_rolls tag (e.g. when opening chests or chest minecarts, fishing, and killing mobs).</td>
        <td>0.0</td>
        <td>-1024.0</td>
        <td>1024.0</td>
      </tr>
      <tr>
        <th colspan='5'>Horse Attributes</th>
      </tr>
      <tr>
        <td>
          <code>horse.jumpStrength</code>
        </td>
        <td>Horse jump strength in some unknown metric.</td>
        <td>0.7</td>
        <td>0.0</td>
        <td>2.0</td>
      </tr>
    </tbody>
  </table>
</div>

Incomplete list, copied from: [Minecraft Wiki Attributes](http://minecraft.gamepedia.com/Attribute)
