# Function: <code>modify_irte_ga</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815afb90)
Location: drivers/iommu/amd_iommu.c:3778
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_set_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff815afb90-ffffffff815afc5e: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c5d70)
Location: drivers/iommu/amd_iommu.c:3918
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_set_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff815c5d70-ffffffff815c5e80: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162c840)
Location: drivers/iommu/amd_iommu.c:3711
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_set_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff8162c840-ffffffff8162c950: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81666d50)
Location: drivers/iommu/amd_iommu.c:3771
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_set_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff81666d50-ffffffff81666e53: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816853e0)
Location: drivers/iommu/amd_iommu.c:3836
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff816853e0-ffffffff816854e3: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bc910)
Location: drivers/iommu/amd_iommu.c:3817
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff816bc910-ffffffff816bca1a: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816df870)
Location: drivers/iommu/amd_iommu.c:3872
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd_iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff816df870-ffffffff816df97a: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81797550)
Location: drivers/iommu/amd/iommu.c:3288
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd/iommu.c:irte_ga_deactivate
  - drivers/iommu/amd/iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff81797550-ffffffff81797681: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a5cc0)
Location: drivers/iommu/amd/iommu.c:3379
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd/iommu.c:irte_ga_deactivate
  - drivers/iommu/amd/iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff817a5cc0-ffffffff817a5df1: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817878c0)
Location: drivers/iommu/amd/iommu.c:2745
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd/iommu.c:irte_ga_deactivate
  - drivers/iommu/amd/iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff817878c0-ffffffff817879fd: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2813
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd/iommu.c:irte_ga_deactivate
  - drivers/iommu/amd/iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff8180f190-ffffffff8180f2d9: modify_irte_ga (STB_LOCAL)
ffffffff81cfe13c-ffffffff81cfe150: modify_irte_ga.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194fd30)
Location: drivers/iommu/amd/iommu.c:2839
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd/iommu.c:irte_ga_deactivate
  - drivers/iommu/amd/iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff8194fd30-ffffffff8194fe6c: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int modify_irte_ga(struct amd_iommu *iommu, u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab4d00)
Location: drivers/iommu/amd/iommu.c:3008
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd/iommu.c:irte_ga_deactivate
  - drivers/iommu/amd/iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff81ab4d00-ffffffff81ab4e26: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int modify_irte_ga(struct amd_iommu *iommu, u16 devid, int index, struct irte_ga *irte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81afed60)
Location: drivers/iommu/amd/iommu.c:3054
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd/iommu.c:irte_ga_deactivate
  - drivers/iommu/amd/iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff81afed60-ffffffff81afedff: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b52533)
Location: drivers/iommu/amd/iommu.c:3124
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd/iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd/iommu.c:irte_ga_deactivate
  - drivers/iommu/amd/iommu.c:irte_ga_activate
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a52c0)
Location: drivers/iommu/amd_iommu.c:3872
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd_iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff816a52c0-ffffffff816a53ca: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81682cb0)
Location: drivers/iommu/amd_iommu.c:3872
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd_iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff81682cb0-ffffffff81682dba: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d3530)
Location: drivers/iommu/amd_iommu.c:3872
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd_iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff816d3530-ffffffff816d363a: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int modify_irte_ga(u16 devid, int index, struct irte_ga *irte, struct amd_ir_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816edc30)
Location: drivers/iommu/amd_iommu.c:3872
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_deactivate_guest_mode
  - drivers/iommu/amd_iommu.c:amd_iommu_activate_guest_mode
  - drivers/iommu/amd_iommu.c:irte_ga_deactivate
  - drivers/iommu/amd_iommu.c:irte_ga_activate
```
**Symbols:**

```
ffffffff816edc30-ffffffff816edd3a: modify_irte_ga (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct amd_iommu *iommu</code>
</li>
<li>
<b>Param reordered. </b>
<code>devid, index, irte, data</code> ➡️ <code>iommu, devid, index, irte, data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct amd_ir_data *data</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
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
