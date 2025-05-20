# Function: <code>pci_alloc_child_bus</code>

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
In drivers/pci/probe.c (ffffffff8143195e)
Location: drivers/pci/probe.c:717
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff8147d14e)
Location: drivers/pci/probe.c:720
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff8149e6be)
Location: drivers/pci/probe.c:839
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff814a854e)
Location: drivers/pci/probe.c:865
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff814e757e)
Location: drivers/pci/probe.c:865
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81516bbe)
Location: drivers/pci/probe.c:928
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c61e)
Location: drivers/pci/probe.c:928
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155afbe)
Location: drivers/pci/probe.c:985
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157c06e)
Location: drivers/pci/probe.c:981
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_alloc_child_bus(struct pci_bus *parent, struct pci_dev *bridge, int busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1029
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81621730-ffffffff8162195f: pci_alloc_child_bus (STB_LOCAL)
ffffffff816239a2-ffffffff816239d8: pci_alloc_child_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_alloc_child_bus(struct pci_bus *parent, struct pci_dev *bridge, int busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1042
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff816482c0-ffffffff81648517: pci_alloc_child_bus (STB_LOCAL)
ffffffff81bf76ac-ffffffff81bf76e2: pci_alloc_child_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_alloc_child_bus(struct pci_bus *parent, struct pci_dev *bridge, int busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1086
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8162aee0-ffffffff8162b128: pci_alloc_child_bus (STB_LOCAL)
ffffffff81be94d2-ffffffff81be9508: pci_alloc_child_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_alloc_child_bus(struct pci_bus *parent, struct pci_dev *bridge, int busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1095
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8169a3b0-ffffffff8169a5fa: pci_alloc_child_bus (STB_LOCAL)
ffffffff81ce3e78-ffffffff81ce3eae: pci_alloc_child_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pci_bus *pci_alloc_child_bus(struct pci_bus *parent, struct pci_dev *bridge, int busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1076
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff817bbb10-ffffffff817bbd66: pci_alloc_child_bus (STB_LOCAL)
ffffffff81eaa8d0-ffffffff81eaa904: pci_alloc_child_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_bus *pci_alloc_child_bus(struct pci_bus *parent, struct pci_dev *bridge, int busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d7670)
Location: drivers/pci/probe.c:1081
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff818d7670-ffffffff818d78f6: pci_alloc_child_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_bus *pci_alloc_child_bus(struct pci_bus *parent, struct pci_dev *bridge, int busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191a900)
Location: drivers/pci/probe.c:1084
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff8191a900-ffffffff8191ab82: pci_alloc_child_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_bus *pci_alloc_child_bus(struct pci_bus *parent, struct pci_dev *bridge, int busnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81962d00)
Location: drivers/pci/probe.c:1095
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_bridge_extend
  - drivers/pci/probe.c:pci_scan_bridge_extend
```
**Symbols:**

```
ffffffff81962d00-ffffffff81962f82: pci_alloc_child_bus (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106df6c0)
Location: drivers/pci/probe.c:981
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087b32c)
Location: drivers/pci/probe.c:981
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000858118)
Location: drivers/pci/probe.c:981
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b769a)
Location: drivers/pci/probe.c:981
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
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
In drivers/pci/probe.c (ffffffff8157058e)
Location: drivers/pci/probe.c:981
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff8155ecee)
Location: drivers/pci/probe.c:981
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156fdbe)
Location: drivers/pci/probe.c:981
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158a29e)
Location: drivers/pci/probe.c:981
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
