# Function: <code>nvmem_add_cells</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5fb0)
Location: drivers/nvmem/core.c:356
Inline: True
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
In drivers/nvmem/core.c (ffffffff8181d149)
Location: drivers/nvmem/core.c:356
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nvmem_add_cells(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, int ncells);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818670a0)
Location: drivers/nvmem/core.c:365
Inline: False
```
**Symbols:**

```
ffffffff818670a0-ffffffff8186723d: nvmem_add_cells (STB_GLOBAL)
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
In drivers/nvmem/core.c (ffffffff81887254)
Location: drivers/nvmem/core.c:385
Inline: True
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
In drivers/nvmem/core.c (ffffffff818d143b)
Location: drivers/nvmem/core.c:173
Inline: True
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
In drivers/nvmem/core.c (ffffffff8190383b)
Location: drivers/nvmem/core.c:170
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nvmem_add_cells(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, int ncells);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819dabc0)
Location: drivers/nvmem/core.c:395
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff819dabc0-ffffffff819dad64: nvmem_add_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvmem_add_cells(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, int ncells);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d9a70)
Location: drivers/nvmem/core.c:500
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff819d9a70-ffffffff819d9c35: nvmem_add_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvmem_add_cells(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, int ncells);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819bf5d0)
Location: drivers/nvmem/core.c:500
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff819bf5d0-ffffffff819bf795: nvmem_add_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nvmem_add_cells(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, int ncells);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6ec20)
Location: drivers/nvmem/core.c:506
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81a6ec20-ffffffff81a6ede5: nvmem_add_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nvmem_add_cells(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, int ncells);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81bdfc70)
Location: drivers/nvmem/core.c:512
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81bdfc70-ffffffff81bdfe58: nvmem_add_cells (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvmem_add_cells(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, int ncells);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8b410)
Location: drivers/nvmem/core.c:512
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81d8b410-ffffffff81d8b5f8: nvmem_add_cells (STB_LOCAL)
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
In drivers/nvmem/core.c (ffffffff81dfad17)
Location: drivers/nvmem/core.c:553
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
In drivers/nvmem/core.c (ffffffff81eb1d89)
Location: drivers/nvmem/core.c:637
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
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
In drivers/nvmem/core.c (ffff800010b9fc84)
Location: drivers/nvmem/core.c:170
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c81610)
Location: drivers/nvmem/core.c:170
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c73360)
Location: drivers/nvmem/core.c:170
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000737d6e)
Location: drivers/nvmem/core.c:170
Inline: True
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
In drivers/nvmem/core.c (ffffffff818a2c6b)
Location: drivers/nvmem/core.c:170
Inline: True
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
In drivers/nvmem/core.c (ffffffff8185e3db)
Location: drivers/nvmem/core.c:170
Inline: True
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
In drivers/nvmem/core.c (ffffffff818f425b)
Location: drivers/nvmem/core.c:170
Inline: True
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
In drivers/nvmem/core.c (ffffffff819152fb)
Location: drivers/nvmem/core.c:170
Inline: True
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
</ul>
