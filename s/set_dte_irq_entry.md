# Function: <code>set_dte_irq_entry</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8153168d)
Location: drivers/iommu/amd_iommu.c:3535
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
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
In drivers/iommu/amd_iommu.c (ffffffff8158230d)
Location: drivers/iommu/amd_iommu.c:3549
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
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
In drivers/iommu/amd_iommu.c (ffffffff815af7fd)
Location: drivers/iommu/amd_iommu.c:3645
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
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
In drivers/iommu/amd_iommu.c (ffffffff815c598d)
Location: drivers/iommu/amd_iommu.c:3785
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162a9d0)
Location: drivers/iommu/amd_iommu.c:3571
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
```
**Symbols:**

```
ffffffff8162a9d0-ffffffff8162aa3e: set_dte_irq_entry (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff81667936)
Location: drivers/iommu/amd_iommu.c:3598
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
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
In drivers/iommu/amd_iommu.c (ffffffff81685e56)
Location: drivers/iommu/amd_iommu.c:3663
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
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
In drivers/iommu/amd_iommu.c (ffffffff816bd5b7)
Location: drivers/iommu/amd_iommu.c:3644
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816de2b0)
Location: drivers/iommu/amd_iommu.c:3680
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff816de2b0-ffffffff816de31d: set_dte_irq_entry (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff817958e0)
Location: drivers/iommu/amd/iommu.c:3096
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff817958e0-ffffffff81795946: set_dte_irq_entry.isra.0 (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff817a3e60)
Location: drivers/iommu/amd/iommu.c:3187
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff817a3e60-ffffffff817a3ec6: set_dte_irq_entry.isra.0 (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff817866f0)
Location: drivers/iommu/amd/iommu.c:2553
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff817866f0-ffffffff81786756: set_dte_irq_entry.isra.0 (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff8180d7c0)
Location: drivers/iommu/amd/iommu.c:2621
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff8180d7c0-ffffffff8180d826: set_dte_irq_entry.isra.0 (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff8194e0f0)
Location: drivers/iommu/amd/iommu.c:2647
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff8194e0f0-ffffffff8194e162: set_dte_irq_entry.isra.0 (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff81ab2890)
Location: drivers/iommu/amd/iommu.c:2810
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff81ab2890-ffffffff81ab2914: set_dte_irq_entry.isra.0 (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff81afead0)
Location: drivers/iommu/amd/iommu.c:2856
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
```
**Symbols:**

```
ffffffff81afead0-ffffffff81afeb54: set_dte_irq_entry.isra.0 (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff81b52220)
Location: drivers/iommu/amd/iommu.c:2895
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
```
**Symbols:**

```
ffffffff81b52220-ffffffff81b522a4: set_dte_irq_entry.isra.0 (STB_LOCAL)
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
void set_dte_irq_entry(u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a3d00)
Location: drivers/iommu/amd_iommu.c:3680
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff816a3d00-ffffffff816a3d6d: set_dte_irq_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816816f0)
Location: drivers/iommu/amd_iommu.c:3680
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff816816f0-ffffffff8168175d: set_dte_irq_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d1f70)
Location: drivers/iommu/amd_iommu.c:3680
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff816d1f70-ffffffff816d1fdd: set_dte_irq_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_dte_irq_entry(u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ec570)
Location: drivers/iommu/amd_iommu.c:3680
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
```
**Symbols:**

```
ffffffff816ec570-ffffffff816ec5dd: set_dte_irq_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
