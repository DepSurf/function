# Function: <code>amd_pogo_errata_restore_misc_reg</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff8153cf56)
Location: drivers/pci/hotplug/shpchp.h:244
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81554366)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81583ee0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815a58c0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void amd_pogo_errata_restore_misc_reg(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff8164dee0-ffffffff8164e011: amd_pogo_errata_restore_misc_reg (STB_LOCAL)
ffffffff8164ecc6-ffffffff8164ecf2: amd_pogo_errata_restore_misc_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void amd_pogo_errata_restore_misc_reg(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff81671e50-ffffffff81671f81: amd_pogo_errata_restore_misc_reg (STB_LOCAL)
ffffffff81bfc717-ffffffff81bfc743: amd_pogo_errata_restore_misc_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void amd_pogo_errata_restore_misc_reg(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff81654360-ffffffff81654491: amd_pogo_errata_restore_misc_reg (STB_LOCAL)
ffffffff81bee602-ffffffff81bee62e: amd_pogo_errata_restore_misc_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void amd_pogo_errata_restore_misc_reg(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff816c6210-ffffffff816c6355: amd_pogo_errata_restore_misc_reg (STB_LOCAL)
ffffffff81ce95a0-ffffffff81ce95e1: amd_pogo_errata_restore_misc_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void amd_pogo_errata_restore_misc_reg(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff817ec120-ffffffff817ec28a: amd_pogo_errata_restore_misc_reg (STB_LOCAL)
ffffffff81eb0640-ffffffff81eb0681: amd_pogo_errata_restore_misc_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void amd_pogo_errata_restore_misc_reg(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff81912a70-ffffffff81912c06: amd_pogo_errata_restore_misc_reg (STB_LOCAL)
ffffffff8208fa73-ffffffff8208fa88: amd_pogo_errata_restore_misc_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void amd_pogo_errata_restore_misc_reg(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff819560f0-ffffffff81956286: amd_pogo_errata_restore_misc_reg (STB_LOCAL)
ffffffff8210fdd3-ffffffff8210fde8: amd_pogo_errata_restore_misc_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void amd_pogo_errata_restore_misc_reg(struct slot *p_slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
```
**Symbols:**

```
ffffffff8199f610-ffffffff8199f7a6: amd_pogo_errata_restore_misc_reg (STB_LOCAL)
ffffffff821edafb-ffffffff821edb10: amd_pogo_errata_restore_misc_reg.cold (STB_LOCAL)
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffff80001070e918)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
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
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffe0004dad22)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815990d0)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81588260)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff81599610)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
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
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff815b3a50)
Location: drivers/pci/hotplug/shpchp.h:246
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_enable_slot
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
