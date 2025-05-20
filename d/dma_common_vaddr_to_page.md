# Function: <code>dma_common_vaddr_to_page</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *dma_common_vaddr_to_page(void *cpu_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff8113ab10)
Location: kernel/dma/ops_helpers.c:8
Inline: False
Direct callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
**Symbols:**

```
ffffffff8113ab10-ffffffff8113ab6e: dma_common_vaddr_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *dma_common_vaddr_to_page(void *cpu_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff8115da50)
Location: kernel/dma/ops_helpers.c:8
Inline: False
Direct callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
**Symbols:**

```
ffffffff8115da50-ffffffff8115daae: dma_common_vaddr_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *dma_common_vaddr_to_page(void *cpu_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811879e0)
Location: kernel/dma/ops_helpers.c:8
Inline: False
Direct callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
**Symbols:**

```
ffffffff811879e0-ffffffff81187a49: dma_common_vaddr_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *dma_common_vaddr_to_page(void *cpu_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811c3620)
Location: kernel/dma/ops_helpers.c:8
Inline: False
Direct callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
**Symbols:**

```
ffffffff811c3620-ffffffff811c3689: dma_common_vaddr_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *dma_common_vaddr_to_page(void *cpu_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811d6170)
Location: kernel/dma/ops_helpers.c:8
Inline: False
Direct callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
**Symbols:**

```
ffffffff811d6170-ffffffff811d61d9: dma_common_vaddr_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *dma_common_vaddr_to_page(void *cpu_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/ops_helpers.c (ffffffff811eb1a0)
Location: kernel/dma/ops_helpers.c:8
Inline: False
Direct callers:
  - kernel/dma/ops_helpers.c:dma_common_mmap
  - kernel/dma/ops_helpers.c:dma_common_get_sgtable
```
**Symbols:**

```
ffffffff811eb1a0-ffffffff811eb209: dma_common_vaddr_to_page (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
