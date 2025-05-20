# Function: <code>parse_dmar_table</code>

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
In drivers/iommu/dmar.c (ffffffff81faab91)
Location: drivers/iommu/dmar.c:594
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff81fd7697)
Location: drivers/iommu/dmar.c:606
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff820152bf)
Location: drivers/iommu/dmar.c:605
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff820f6f2c)
Location: drivers/iommu/dmar.c:609
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff82700697)
Location: drivers/iommu/dmar.c:609
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff8272a3be)
Location: drivers/iommu/dmar.c:609
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff828e2c7c)
Location: drivers/iommu/dmar.c:609
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff828fd73b)
Location: drivers/iommu/dmar.c:598
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff82906770)
Location: drivers/iommu/dmar.c:608
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_dmar_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff82d1cc5b)
Location: drivers/iommu/intel/dmar.c:608
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff82d1cc5b-ffffffff82d1cd5d: parse_dmar_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_dmar_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8300a9da)
Location: drivers/iommu/intel/dmar.c:630
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff8300a9da-ffffffff8300aadc: parse_dmar_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_dmar_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff83215732)
Location: drivers/iommu/intel/dmar.c:636
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff83215732-ffffffff83215845: parse_dmar_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_dmar_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff832fef8b)
Location: drivers/iommu/intel/dmar.c:635
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff832fef8b-ffffffff832ff09e: parse_dmar_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_dmar_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff834b7b37)
Location: drivers/iommu/intel/dmar.c:632
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff834b7b37-ffffffff834b7c51: parse_dmar_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_dmar_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff83ef4610)
Location: drivers/iommu/intel/dmar.c:632
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff83ef4610-ffffffff83ef4762: parse_dmar_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_dmar_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8371a1e0)
Location: drivers/iommu/intel/dmar.c:634
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff8371a1e0-ffffffff8371a330: parse_dmar_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_dmar_table();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8394dcc0)
Location: drivers/iommu/intel/dmar.c:634
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_table_init
```
**Symbols:**

```
ffffffff8394dcc0-ffffffff8394de10: parse_dmar_table (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff828edf57)
Location: drivers/iommu/dmar.c:608
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff828e53e4)
Location: drivers/iommu/dmar.c:608
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff82901a93)
Location: drivers/iommu/dmar.c:608
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
In drivers/iommu/dmar.c (ffffffff829077d2)
Location: drivers/iommu/dmar.c:608
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_table_init
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
