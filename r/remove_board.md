# Function: <code>remove_board</code>

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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144fb79)
Location: drivers/pci/hotplug/pciehp_ctrl.c:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149c31a)
Location: drivers/pci/hotplug/pciehp_ctrl.c:134
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bde9a)
Location: drivers/pci/hotplug/pciehp_ctrl.c:135
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c867f)
Location: drivers/pci/hotplug/pciehp_ctrl.c:135
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81508c2f)
Location: drivers/pci/hotplug/pciehp_ctrl.c:136
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81539b7c)
Location: drivers/pci/hotplug/pciehp_ctrl.c:122
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153c757)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815507ff)
Location: drivers/pci/hotplug/pciehp_ctrl.c:105
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81553b6b)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815806d3)
Location: drivers/pci/hotplug/pciehp_ctrl.c:107
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81583983)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815a2193)
Location: drivers/pci/hotplug/pciehp_ctrl.c:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815a5363)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void remove_board(struct controller *ctrl, bool safe_removal);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8164ac71)
Location: drivers/pci/hotplug/pciehp_ctrl.c:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff8164e4e0-ffffffff8164e59b: remove_board (STB_LOCAL)
ffffffff8164f029-ffffffff8164f0ce: remove_board.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void remove_board(struct controller *ctrl, bool safe_removal);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8166f3c1)
Location: drivers/pci/hotplug/pciehp_ctrl.c:109
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:337
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
```
**Symbols:**

```
ffffffff81672450-ffffffff8167250b: remove_board (STB_LOCAL)
ffffffff81bfca7a-ffffffff81bfcb1f: remove_board.cold (STB_LOCAL)
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff816518e1)
Location: drivers/pci/hotplug/pciehp_ctrl.c:109
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff816549a6)
Location: drivers/pci/hotplug/shpchp_ctrl.c:337
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff816c3661)
Location: drivers/pci/hotplug/pciehp_ctrl.c:109
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff816c6866)
Location: drivers/pci/hotplug/shpchp_ctrl.c:337
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff817e90c1)
Location: drivers/pci/hotplug/pciehp_ctrl.c:109
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff817ec7d6)
Location: drivers/pci/hotplug/shpchp_ctrl.c:337
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8190ec61)
Location: drivers/pci/hotplug/pciehp_ctrl.c:109
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff819134ae)
Location: drivers/pci/hotplug/shpchp_ctrl.c:337
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff819522dd)
Location: drivers/pci/hotplug/pciehp_ctrl.c:109
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81956b1e)
Location: drivers/pci/hotplug/shpchp_ctrl.c:337
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8199b76d)
Location: drivers/pci/hotplug/pciehp_ctrl.c:109
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff819a003e)
Location: drivers/pci/hotplug/shpchp_ctrl.c:337
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070aa04)
Location: drivers/pci/hotplug/pciehp_ctrl.c:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070e0b0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffe0004d7776)
Location: drivers/pci/hotplug/pciehp_ctrl.c:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004da664)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815959a3)
Location: drivers/pci/hotplug/pciehp_ctrl.c:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81598b73)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81584b33)
Location: drivers/pci/hotplug/pciehp_ctrl.c:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81587d03)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81595ee3)
Location: drivers/pci/hotplug/pciehp_ctrl.c:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815990b3)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815b0363)
Location: drivers/pci/hotplug/pciehp_ctrl.c:111
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815b34f3)
Location: drivers/pci/hotplug/shpchp_ctrl.c:338
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_disable_slot
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
</ul>
