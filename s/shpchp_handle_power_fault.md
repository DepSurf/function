# Function: <code>shpchp_handle_power_fault</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153d560)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8153d560-ffffffff8153d691: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81554940)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81554940-ffffffff81554a68: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81584c53-ffffffff81584d22: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff81584250-ffffffff815842c3: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff815a6633-ffffffff815a6702: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff815a5c30-ffffffff815a5ca3: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8164f33d-ffffffff8164f40d: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff8164e910-ffffffff8164e984: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81bfcd8e-ffffffff81bfce5e: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff81672880-ffffffff816728f4: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81beec69-ffffffff81beed39: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff81654d70-ffffffff81654de4: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81ce9ca6-ffffffff81ce9d8b: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff816c6c80-ffffffff816c6d03: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81eb0d83-ffffffff81eb0e71: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff817ecc10-ffffffff817ecc8f: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8208fbb5-ffffffff8208fbc9: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff81913ba0-ffffffff81913ce2: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8210ff11-ffffffff8210ff25: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff81957210-ffffffff81957352: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff821edc39-ffffffff821edc4d: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff819a0760-ffffffff819a08a2: shpchp_handle_power_fault (STB_GLOBAL)
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070ef48)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffff80001070ef48-ffff80001070f080: shpchp_handle_power_fault (STB_GLOBAL)
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004db2b0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffe0004db2b0-ffffffe0004db3c6: shpchp_handle_power_fault (STB_GLOBAL)
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
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81599e43-ffffffff81599f12: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff81599440-ffffffff815994b3: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81588fd3-ffffffff815890a2: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff815885d0-ffffffff81588643: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8159a383-ffffffff8159a452: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff81599980-ffffffff815999f3: shpchp_handle_power_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_power_fault(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:141
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff815b47c3-ffffffff815b4892: shpchp_handle_power_fault.cold (STB_LOCAL)
ffffffff815b3dc0-ffffffff815b3e33: shpchp_handle_power_fault (STB_GLOBAL)
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
