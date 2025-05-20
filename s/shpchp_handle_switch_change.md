# Function: <code>shpchp_handle_switch_change</code>

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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153d290)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8153d290-ffffffff8153d441: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81554690)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81554690-ffffffff81554838: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81584aab-ffffffff81584baf: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff81584120-ffffffff815841c4: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff815a648b-ffffffff815a658f: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff815a5b00-ffffffff815a5ba4: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8164f195-ffffffff8164f299: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff8164e7e0-ffffffff8164e884: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81bfcbe6-ffffffff81bfccea: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff81672750-ffffffff816727f4: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81beeac1-ffffffff81beebc5: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff81654c40-ffffffff81654ce4: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81ce9aba-ffffffff81ce9beb: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff816c6b30-ffffffff816c6bea: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81eb0b81-ffffffff81eb0cbd: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff817ecac0-ffffffff817ecb7a: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8208fb76-ffffffff8208fba0: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff81913880-ffffffff81913a5e: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8210fed2-ffffffff8210fefc: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff81956ef0-ffffffff819570ce: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff821edbfa-ffffffff821edc24: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff819a0440-ffffffff819a061e: shpchp_handle_switch_change (STB_GLOBAL)
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070ec78)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffff80001070ec78-ffff80001070ee24: shpchp_handle_switch_change (STB_GLOBAL)
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004db05e)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffe0004db05e-ffffffe0004db1b6: shpchp_handle_switch_change (STB_GLOBAL)
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
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81599c9b-ffffffff81599d9f: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff81599310-ffffffff815993b4: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff81588e2b-ffffffff81588f2f: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff815884a0-ffffffff81588544: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff8159a1db-ffffffff8159a2df: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff81599850-ffffffff815998f4: shpchp_handle_switch_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u8 shpchp_handle_switch_change(u8 hp_slot, struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp_ctrl.c:68
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:shpc_isr
```
**Symbols:**

```
ffffffff815b461b-ffffffff815b471f: shpchp_handle_switch_change.cold (STB_LOCAL)
ffffffff815b3c90-ffffffff815b3d34: shpchp_handle_switch_change (STB_GLOBAL)
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
