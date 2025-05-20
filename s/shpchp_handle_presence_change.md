# Function: <code>shpchp_handle_presence_change</code>

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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153d450)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8153d450-ffffffff8153d553: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81554840)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81554840-ffffffff8155493a: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81584baf-ffffffff81584c53: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff815841d0-ffffffff8158424b: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff815a658f-ffffffff815a6633: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff815a5bb0-ffffffff815a5c2b: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8164f299-ffffffff8164f33d: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff8164e890-ffffffff8164e90b: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81bfccea-ffffffff81bfcd8e: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff81672800-ffffffff8167287b: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81beebc5-ffffffff81beec69: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff81654cf0-ffffffff81654d6b: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81ce9beb-ffffffff81ce9ca6: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff816c6bf0-ffffffff816c6c7c: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81eb0cbd-ffffffff81eb0d83: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff817ecb80-ffffffff817ecc07: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8208fba0-ffffffff8208fbb5: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff81913a70-ffffffff81913b88: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8210fefc-ffffffff8210ff11: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff819570e0-ffffffff819571f8: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff821edc24-ffffffff821edc39: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff819a0630-ffffffff819a0748: shpchp_handle_presence_change (STB_GLOBAL)
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070ee28)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffff80001070ee28-ffff80001070ef44: shpchp_handle_presence_change (STB_GLOBAL)
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004db1b6)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffe0004db1b6-ffffffe0004db2b0: shpchp_handle_presence_change (STB_GLOBAL)
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
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81599d9f-ffffffff81599e43: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff815993c0-ffffffff8159943b: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81588f2f-ffffffff81588fd3: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff81588550-ffffffff815885cb: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8159a2df-ffffffff8159a383: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff81599900-ffffffff8159997b: shpchp_handle_presence_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_presence_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:106
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff815b471f-ffffffff815b47c3: shpchp_handle_presence_change.cold (STB_LOCAL)
ffffffff815b3d40-ffffffff815b3dbb: shpchp_handle_presence_change (STB_GLOBAL)
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
