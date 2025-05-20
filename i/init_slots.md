# Function: <code>init_slots</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144d9e6)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:364
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8149a128)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:364
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bbd08)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:364
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c6509)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:365
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81506ad9)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:365
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81537437)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:351
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153bee8)
Location: drivers/pci/hotplug/shpchp_core.c:80
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154eb43)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815533b3)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: True
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157ea90)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81583254)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: True
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815a04d0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815a4c34)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
int init_slots(int clear_ins);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81648830-ffffffff8164890c: init_slots (STB_LOCAL)
ffffffff816492a8-ffffffff81649336: init_slots.cold (STB_LOCAL)
ffffffff8164d740-ffffffff8164d964: init_slots (STB_LOCAL)
ffffffff8164dc68-ffffffff8164dcf0: init_slots.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int init_slots(int clear_ins);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff8166d8e0-ffffffff8166d9bc: init_slots (STB_LOCAL)
ffffffff81bfb5e2-ffffffff81bfb670: init_slots.cold (STB_LOCAL)
ffffffff81671900-ffffffff81671b24: init_slots (STB_LOCAL)
ffffffff81bfc4c1-ffffffff81bfc549: init_slots.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int init_slots(int clear_ins);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8164fed0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81653e10-ffffffff81654034: init_slots (STB_LOCAL)
ffffffff81bee3ac-ffffffff81bee434: init_slots.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int init_slots(int clear_ins);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816c1c20)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff816c5c40-ffffffff816c5e6e: init_slots (STB_LOCAL)
ffffffff81ce92a4-ffffffff81ce9347: init_slots.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int init_slots(int clear_ins);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff817e74f0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff817ebb00-ffffffff817ebd4a: init_slots (STB_LOCAL)
ffffffff81eb0340-ffffffff81eb03e0: init_slots.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int init_slots(int clear_ins);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190c700)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff81912150-ffffffff8191241c: init_slots (STB_LOCAL)
ffffffff8208fa1a-ffffffff8208fa35: init_slots.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int init_slots(int clear_ins);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8194fd80)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:63
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff819557e0-ffffffff81955aac: init_slots (STB_LOCAL)
ffffffff8210fd7a-ffffffff8210fd95: init_slots.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int init_slots(int clear_ins);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff819991b0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_start
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp_core.c:63
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
**Symbols:**

```
ffffffff8199eca0-ffffffff8199ef97: init_slots (STB_LOCAL)
ffffffff821edaa2-ffffffff821edabd: init_slots.cold (STB_LOCAL)
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff8000107087f0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d9a8)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: True
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
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000881bb0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d66c4)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004da06c)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81593ce0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598444)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81582e70)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815875d4)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: True
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81594220)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598984)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: True
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815ae6a0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:295
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815b2dc4)
Location: drivers/pci/hotplug/shpchp_core.c:64
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
