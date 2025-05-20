# Function: <code>nvmem_cell_add</code>

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
In drivers/nvmem/core.c (ffffffff817a600f)
Location: drivers/nvmem/core.c:323
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
In drivers/nvmem/core.c (ffffffff8181d1a8)
Location: drivers/nvmem/core.c:323
Inline: True
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
In drivers/nvmem/core.c (ffffffff81867124)
Location: drivers/nvmem/core.c:323
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818862f0)
Location: drivers/nvmem/core.c:342
Inline: False
```
**Symbols:**

```
ffffffff818862f0-ffffffff81886353: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d0830)
Location: drivers/nvmem/core.c:130
Inline: False
```
**Symbols:**

```
ffffffff818d0830-ffffffff818d0899: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81902c90)
Location: drivers/nvmem/core.c:125
Inline: False
```
**Symbols:**

```
ffffffff81902c90-ffffffff81902cf9: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819daaec)
Location: drivers/nvmem/core.c:350
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells_from_table
  - drivers/nvmem/core.c:nvmem_add_cells
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d99e6)
Location: drivers/nvmem/core.c:440
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells_from_table
  - drivers/nvmem/core.c:nvmem_add_cells
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c036a)
Location: drivers/nvmem/core.c:440
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6fad0)
Location: drivers/nvmem/core.c:446
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9e988)
Location: drivers/nvmem/core.c:125
Inline: False
```
**Symbols:**

```
ffff800010b9e988-ffff800010b9ea00: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c807d0)
Location: drivers/nvmem/core.c:125
Inline: False
```
**Symbols:**

```
c0c807d0-c0c80838: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c719e0)
Location: drivers/nvmem/core.c:125
Inline: False
```
**Symbols:**

```
c000000000c719e0-c000000000c71a7c: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000736cb6)
Location: drivers/nvmem/core.c:125
Inline: False
```
**Symbols:**

```
ffffffe000736cb6-ffffffe000736d22: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a20c0)
Location: drivers/nvmem/core.c:125
Inline: False
```
**Symbols:**

```
ffffffff818a20c0-ffffffff818a2129: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185d830)
Location: drivers/nvmem/core.c:125
Inline: False
```
**Symbols:**

```
ffffffff8185d830-ffffffff8185d899: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f36b0)
Location: drivers/nvmem/core.c:125
Inline: False
```
**Symbols:**

```
ffffffff818f36b0-ffffffff818f3719: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvmem_cell_add(struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81914750)
Location: drivers/nvmem/core.c:125
Inline: False
```
**Symbols:**

```
ffffffff81914750-ffffffff819147b9: nvmem_cell_add (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
