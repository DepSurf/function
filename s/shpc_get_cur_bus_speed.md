# Function: <code>shpc_get_cur_bus_speed</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int shpc_get_cur_bus_speed(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff8153e5c0-ffffffff8153e636: shpc_get_cur_bus_speed (STB_LOCAL)
ffffffff8153f694-ffffffff8153f6ac: shpc_get_cur_bus_speed.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int shpc_get_cur_bus_speed(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff81555990-ffffffff81555a06: shpc_get_cur_bus_speed (STB_LOCAL)
ffffffff81556abd-ffffffff81556ad5: shpc_get_cur_bus_speed.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shpc_get_cur_bus_speed(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff81585990-ffffffff81585a0b: shpc_get_cur_bus_speed (STB_LOCAL)
ffffffff81586191-ffffffff815861a9: shpc_get_cur_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int shpc_get_cur_bus_speed(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff815a7370-ffffffff815a73eb: shpc_get_cur_bus_speed (STB_LOCAL)
ffffffff815a7b71-ffffffff815a7b89: shpc_get_cur_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff81650080-ffffffff816500eb: shpc_get_cur_bus_speed.isra.0 (STB_LOCAL)
ffffffff81650926-ffffffff8165093e: shpc_get_cur_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff81673520-ffffffff8167358b: shpc_get_cur_bus_speed.isra.0 (STB_LOCAL)
ffffffff81bfd250-ffffffff81bfd268: shpc_get_cur_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:632
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff81655a40-ffffffff81655aa9: shpc_get_cur_bus_speed.isra.0 (STB_LOCAL)
ffffffff81bef03e-ffffffff81bef057: shpc_get_cur_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:632
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff816c7b00-ffffffff816c7b83: shpc_get_cur_bus_speed.isra.0 (STB_LOCAL)
ffffffff81cea1f7-ffffffff81cea226: shpc_get_cur_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:632
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff817eda00-ffffffff817eda91: shpc_get_cur_bus_speed.isra.0 (STB_LOCAL)
ffffffff81eb1265-ffffffff81eb1294: shpc_get_cur_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:615
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff81914df0-ffffffff81914ea4: shpc_get_cur_bus_speed.isra.0 (STB_LOCAL)
ffffffff8208fcc5-ffffffff8208fcdf: shpc_get_cur_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:615
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff81958410-ffffffff819584c4: shpc_get_cur_bus_speed.isra.0 (STB_LOCAL)
ffffffff82110019-ffffffff82110033: shpc_get_cur_bus_speed.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:615
Inline: True
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff819a1980-ffffffff819a1a34: shpc_get_cur_bus_speed.isra.0 (STB_LOCAL)
ffffffff821edd41-ffffffff821edd5b: shpc_get_cur_bus_speed.isra.0.cold (STB_LOCAL)
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
int shpc_get_cur_bus_speed(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffff80001070f9b0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffff80001070f9b0-ffff80001070faa4: shpc_get_cur_bus_speed (STB_LOCAL)
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
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shpc_get_cur_bus_speed(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dc3c2)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffe0004dc3c2-ffffffe0004dc46c: shpc_get_cur_bus_speed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int shpc_get_cur_bus_speed(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff8159ab80-ffffffff8159abfb: shpc_get_cur_bus_speed (STB_LOCAL)
ffffffff8159b381-ffffffff8159b399: shpc_get_cur_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int shpc_get_cur_bus_speed(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff81589d10-ffffffff81589d8b: shpc_get_cur_bus_speed (STB_LOCAL)
ffffffff8158a511-ffffffff8158a529: shpc_get_cur_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int shpc_get_cur_bus_speed(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff8159b0c0-ffffffff8159b13b: shpc_get_cur_bus_speed (STB_LOCAL)
ffffffff8159b8c1-ffffffff8159b8d9: shpc_get_cur_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int shpc_get_cur_bus_speed(struct controller *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:637
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_init
  - drivers/pci/hotplug/shpchp_hpc.c:hpc_set_bus_speed_mode
```
**Symbols:**

```
ffffffff815b5500-ffffffff815b557b: shpc_get_cur_bus_speed (STB_LOCAL)
ffffffff815b5cf1-ffffffff815b5d09: shpc_get_cur_bus_speed.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
