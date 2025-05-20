# Function: <code>get_irq_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid, bool ioapic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815315f0)
Location: drivers/iommu/amd_iommu.c:3551
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff815315f0-ffffffff81531915: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid, bool ioapic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81582270)
Location: drivers/iommu/amd_iommu.c:3565
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
```
**Symbols:**

```
ffffffff81582270-ffffffff815825d5: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid, bool ioapic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815af760)
Location: drivers/iommu/amd_iommu.c:3659
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff815af760-ffffffff815afa5c: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid, bool ioapic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c58f0)
Location: drivers/iommu/amd_iommu.c:3799
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff815c58f0-ffffffff815c5bef: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid, bool ioapic);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162c4d0)
Location: drivers/iommu/amd_iommu.c:3585
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff8162c4d0-ffffffff8162c6b9: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81665fe0)
Location: drivers/iommu/amd_iommu.c:3612
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff81665fe0-ffffffff81666076: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684890)
Location: drivers/iommu/amd_iommu.c:3677
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff81684890-ffffffff81684926: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bbde0)
Location: drivers/iommu/amd_iommu.c:3658
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff816bbde0-ffffffff816bbe76: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816dec70)
Location: drivers/iommu/amd_iommu.c:3694
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff816dec70-ffffffff816ded06: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81795640)
Location: drivers/iommu/amd/iommu.c:3110
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff81795640-ffffffff817956d6: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a3af0)
Location: drivers/iommu/amd/iommu.c:3201
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff817a3af0-ffffffff817a3b86: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817864b0)
Location: drivers/iommu/amd/iommu.c:2567
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff817864b0-ffffffff81786546: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2635
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff8180d4d0-ffffffff8180d59e: get_irq_table (STB_LOCAL)
ffffffff81cfdc60-ffffffff81cfdc9a: get_irq_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2661
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff8194dc90-ffffffff8194dd63: get_irq_table (STB_LOCAL)
ffffffff81ec6566-ffffffff81ec65aa: get_irq_table.cold (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2826
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff81ab2790-ffffffff81ab2876: get_irq_table.isra.0 (STB_LOCAL)
ffffffff82096d12-ffffffff82096d58: get_irq_table.isra.0.cold (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2872
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff81afe9f0-ffffffff81afeab9: get_irq_table.isra.0 (STB_LOCAL)
ffffffff82117bf2-ffffffff82117c1c: get_irq_table.isra.0.cold (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2911
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:free_irte
```
**Symbols:**

```
ffffffff81b51fe0-ffffffff81b520a9: get_irq_table.isra.0 (STB_LOCAL)
ffffffff821f593f-ffffffff821f5969: get_irq_table.isra.0.cold (STB_LOCAL)
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
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a46c0)
Location: drivers/iommu/amd_iommu.c:3694
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff816a46c0-ffffffff816a4756: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816820b0)
Location: drivers/iommu/amd_iommu.c:3694
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff816820b0-ffffffff81682146: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2930)
Location: drivers/iommu/amd_iommu.c:3694
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff816d2930-ffffffff816d29c6: get_irq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_remap_table *get_irq_table(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ecfd0)
Location: drivers/iommu/amd_iommu.c:3694
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
```
**Symbols:**

```
ffffffff816ecfd0-ffffffff816ed066: get_irq_table (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool ioapic</code>
</li>
</ul>
</details>
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
