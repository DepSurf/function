# Function: <code>release_memory_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81819bc2)
Location: mm/memory_hotplug.c:148
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
```
In drivers/xen/balloon.c (ffffffff814c69f7)
Location: drivers/xen/balloon.c:274
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81894771)
Location: mm/memory_hotplug.c:169
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
```
In drivers/xen/balloon.c (ffffffff81517202)
Location: drivers/xen/balloon.c:249
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818c8e61)
Location: mm/memory_hotplug.c:169
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
```
In drivers/xen/balloon.c (ffffffff815435e2)
Location: drivers/xen/balloon.c:246
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819003f1)
Location: mm/memory_hotplug.c:119
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
```
In drivers/xen/balloon.c (ffffffff8155746a)
Location: drivers/xen/balloon.c:247
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8198a3ba)
Location: mm/memory_hotplug.c:127
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
```
In drivers/xen/balloon.c (ffffffff815bb543)
Location: drivers/xen/balloon.c:247
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
Direct callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff815bb2d0-ffffffff815bb2ed: release_memory_resource.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819e6cea)
Location: mm/memory_hotplug.c:127
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory
```
```
In drivers/xen/balloon.c (ffffffff815f428b)
Location: drivers/xen/balloon.c:247
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
Direct callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff815f3970-ffffffff815f398d: release_memory_resource.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a22133)
Location: mm/memory_hotplug.c:127
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff8160f103)
Location: drivers/xen/balloon.c:241
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a91f54)
Location: mm/memory_hotplug.c:131
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff81642eb0)
Location: drivers/xen/balloon.c:238
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac96e4)
Location: mm/memory_hotplug.c:131
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff8166545d)
Location: drivers/xen/balloon.c:236
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e19dc)
Location: mm/memory_hotplug.c:137
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff81714c1d)
Location: drivers/xen/balloon.c:235
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:additional_memory_resource
  - drivers/xen/balloon.c:additional_memory_resource
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ec933)
Location: mm/memory_hotplug.c:137
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff81c04c90)
Location: drivers/xen/balloon.c:234
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c7503)
Location: mm/memory_hotplug.c:150
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff81bf691a)
Location: drivers/xen/balloon.c:234
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130c283)
Location: mm/memory_hotplug.c:215
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff81cf5536)
Location: drivers/xen/balloon.c:239
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81375284)
Location: mm/memory_hotplug.c:232
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff81ebd640)
Location: drivers/xen/balloon.c:241
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f2ca4)
Location: mm/memory_hotplug.c:224
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff81a1b0a2)
Location: drivers/xen/balloon.c:241
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814266e4)
Location: mm/memory_hotplug.c:223
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff81a64252)
Location: drivers/xen/balloon.c:223
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814538a4)
Location: mm/memory_hotplug.c:291
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff81ab6ac1)
Location: drivers/xen/balloon.c:222
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff800010d9d4fc)
Location: mm/memory_hotplug.c:131
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffff80001082ecfc)
Location: drivers/xen/balloon.c:236
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c000000000430540)
Location: mm/memory_hotplug.c:131
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a68554)
Location: mm/memory_hotplug.c:131
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a25014)
Location: mm/memory_hotplug.c:131
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad4964)
Location: mm/memory_hotplug.c:131
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff8165929d)
Location: drivers/xen/balloon.c:236
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ae0e44)
Location: mm/memory_hotplug.c:131
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_memory
```
```
In drivers/xen/balloon.c (ffffffff81673898)
Location: drivers/xen/balloon.c:236
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
</details>
</li>
</ul>

## Differences
