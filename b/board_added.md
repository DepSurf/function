# Function: <code>board_added</code>

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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144f918)
Location: drivers/pci/hotplug/pciehp_ctrl.c:85
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149c0b4)
Location: drivers/pci/hotplug/pciehp_ctrl.c:85
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bdc2a)
Location: drivers/pci/hotplug/pciehp_ctrl.c:85
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c840a)
Location: drivers/pci/hotplug/pciehp_ctrl.c:85
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815089ba)
Location: drivers/pci/hotplug/pciehp_ctrl.c:85
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int board_added(struct slot *p_slot);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81539910)
Location: drivers/pci/hotplug/pciehp_ctrl.c:71
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153c940)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff8153c940-ffffffff8153cd59: board_added (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81550c60)
Location: drivers/pci/hotplug/pciehp_ctrl.c:54
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81553d50)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff81553d50-ffffffff81554169: board_added (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81580dcb)
Location: drivers/pci/hotplug/pciehp_ctrl.c:56
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff81583ae0-ffffffff81583d16: board_added (STB_LOCAL)
ffffffff8158474f-ffffffff81584988: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a24fb)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff815a54c0-ffffffff815a56f6: board_added (STB_LOCAL)
ffffffff815a612f-ffffffff815a6368: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff8164ad10-ffffffff8164adbb: board_added (STB_LOCAL)
ffffffff8164b400-ffffffff8164b4c5: board_added.cold (STB_LOCAL)
ffffffff8164e070-ffffffff8164e291: board_added (STB_LOCAL)
ffffffff8164ed3f-ffffffff8164ef78: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff8166f460-ffffffff8166f545: board_added (STB_LOCAL)
ffffffff81bfbdb0-ffffffff81bfbe1b: board_added.cold (STB_LOCAL)
ffffffff81671fe0-ffffffff81672201: board_added (STB_LOCAL)
ffffffff81bfc790-ffffffff81bfc9c9: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff816519e7)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff816544f0-ffffffff81654711: board_added (STB_LOCAL)
ffffffff81bee67b-ffffffff81bee8b4: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff816c3767)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff816c6360-ffffffff816c65c5: board_added (STB_LOCAL)
ffffffff81ce95e1-ffffffff81ce9864: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff817e91d7)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff817ec290-ffffffff817ec527: board_added (STB_LOCAL)
ffffffff81eb0681-ffffffff81eb0948: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190edb7)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff81912c20-ffffffff81913098: board_added (STB_LOCAL)
ffffffff8208fa88-ffffffff8208fb30: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81952427)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff819562a0-ffffffff8195670f: board_added (STB_LOCAL)
ffffffff8210fde8-ffffffff8210fe8c: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199b8b7)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff8199f7c0-ffffffff8199fc2f: board_added (STB_LOCAL)
ffffffff821edb10-ffffffff821edbb4: board_added.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070af24)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070e348)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffff80001070e348-ffff80001070e744: board_added (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d7bf2)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004da880)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffe0004da880-ffffffe0004dabc4: board_added (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595d0b)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff81598cd0-ffffffff81598f06: board_added (STB_LOCAL)
ffffffff8159993f-ffffffff81599b78: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81584e9b)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff81587e60-ffffffff81588096: board_added (STB_LOCAL)
ffffffff81588acf-ffffffff81588d08: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8159624b)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff81599210-ffffffff81599446: board_added (STB_LOCAL)
ffffffff81599e7f-ffffffff8159a0b8: board_added.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int board_added(struct controller *ctrl);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b06cb)
Location: drivers/pci/hotplug/pciehp_ctrl.c:59
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:229
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff815b3650-ffffffff815b3886: board_added (STB_LOCAL)
ffffffff815b42bf-ffffffff815b44f8: board_added.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct controller *ctrl</code>
</li>
<li>
<b>Param removed. </b>
<code>struct slot *p_slot</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
