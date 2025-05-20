# Function: <code>pci_bridge_d3_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev, bool remove);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481210)
Location: drivers/pci/pci.c:2244
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_d3_device_removed
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff81481210-ffffffff8148130b: pci_bridge_d3_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a4540)
Location: drivers/pci/pci.c:2297
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff814a4540-ffffffff814a4652: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae600)
Location: drivers/pci/pci.c:2314
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff814ae600-ffffffff814ae712: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ed9d0)
Location: drivers/pci/pci.c:2323
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff814ed9d0-ffffffff814edae2: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d600)
Location: drivers/pci/pci.c:2398
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff8151d600-ffffffff8151d718: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532d40)
Location: drivers/pci/pci.c:2588
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff81532d40-ffffffff81532e58: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815624b0)
Location: drivers/pci/pci.c:2703
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff815624b0-ffffffff815625cc: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81583650)
Location: drivers/pci/pci.c:2699
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff81583650-ffffffff8158376c: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162a190)
Location: drivers/pci/pci.c:2769
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff8162a190-ffffffff8162a2c6: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816505f0)
Location: drivers/pci/pci.c:2936
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff816505f0-ffffffff81650726: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81633220)
Location: drivers/pci/pci.c:2966
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff81633220-ffffffff8163333c: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3008
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff81ce48cf-ffffffff81ce4933: pci_bridge_d3_update.cold (STB_LOCAL)
ffffffff816a33b0-ffffffff816a34df: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3095
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff81eab334-ffffffff81eab398: pci_bridge_d3_update.cold (STB_LOCAL)
ffffffff817c55d0-ffffffff817c5717: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3045
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff8208f214-ffffffff8208f278: pci_bridge_d3_update.cold (STB_LOCAL)
ffffffff818e26c0-ffffffff818e2807: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3083
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff8210f57a-ffffffff8210f5de: pci_bridge_d3_update.cold (STB_LOCAL)
ffffffff81925b00-ffffffff81925c47: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3196
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_bridge_d3_update
  - drivers/pci/pci-sysfs.c:d3cold_allowed_store
```
**Symbols:**

```
ffffffff821ed201-ffffffff821ed265: pci_bridge_d3_update.cold (STB_LOCAL)
ffffffff8196e280-ffffffff8196e3c7: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e7618)
Location: drivers/pci/pci.c:2699
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffff8000106e7618-ffff8000106e7734: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0882710)
Location: drivers/pci/pci.c:2699
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
c0882710-c0882844: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000861db0)
Location: drivers/pci/pci.c:2699
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
c000000000861db0-c000000000861f50: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bdd1a)
Location: drivers/pci/pci.c:2699
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffe0004bdd1a-ffffffe0004bde14: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577b70)
Location: drivers/pci/pci.c:2699
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff81577b70-ffffffff81577c8c: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815662b0)
Location: drivers/pci/pci.c:2699
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff815662b0-ffffffff815663cc: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815773a0)
Location: drivers/pci/pci.c:2699
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff815773a0-ffffffff815774bc: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_bridge_d3_update(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81591860)
Location: drivers/pci/pci.c:2699
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_add_device
  - drivers/pci/remove.c:pci_remove_bus_device
  - drivers/pci/pci.c:pci_d3cold_disable
  - drivers/pci/pci.c:pci_d3cold_enable
  - drivers/pci/pci.c:pci_bridge_d3_update
```
**Symbols:**

```
ffffffff81591860-ffffffff8159197c: pci_bridge_d3_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool remove</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
