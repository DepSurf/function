# Function: <code>set_remap_table_entry</code>

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
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81667900)
Location: drivers/iommu/amd_iommu.c:3651
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff81667900-ffffffff816679c6: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685e20)
Location: drivers/iommu/amd_iommu.c:3716
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff81685e20-ffffffff81685ee6: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bd580)
Location: drivers/iommu/amd_iommu.c:3697
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff816bd580-ffffffff816bd644: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e0690)
Location: drivers/iommu/amd_iommu.c:3733
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff816e0690-ffffffff816e06d1: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81796710)
Location: drivers/iommu/amd/iommu.c:3149
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff81796710-ffffffff817967b4: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4e30)
Location: drivers/iommu/amd/iommu.c:3240
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff817a4e30-ffffffff817a4ed4: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81786ff0)
Location: drivers/iommu/amd/iommu.c:2606
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff81786ff0-ffffffff8178709b: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180e110)
Location: drivers/iommu/amd/iommu.c:2674
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff8180e110-ffffffff8180e1bb: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194eeb0)
Location: drivers/iommu/amd/iommu.c:2700
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff8194eeb0-ffffffff8194ef65: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab4010)
Location: drivers/iommu/amd/iommu.c:2868
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff81ab4010-ffffffff81ab40c1: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b01c3d)
Location: drivers/iommu/amd/iommu.c:2914
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
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
In drivers/iommu/amd/iommu.c (ffffffff81b555ad)
Location: drivers/iommu/amd/iommu.c:2953
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
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
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a60e0)
Location: drivers/iommu/amd_iommu.c:3733
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff816a60e0-ffffffff816a6121: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81683ad0)
Location: drivers/iommu/amd_iommu.c:3733
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff81683ad0-ffffffff81683b11: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d4350)
Location: drivers/iommu/amd_iommu.c:3733
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff816d4350-ffffffff816d4391: set_remap_table_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_remap_table_entry(struct amd_iommu *iommu, u16 devid, struct irq_remap_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816eea50)
Location: drivers/iommu/amd_iommu.c:3733
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
```
**Symbols:**

```
ffffffff816eea50-ffffffff816eea91: set_remap_table_entry (STB_LOCAL)
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
