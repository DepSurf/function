# Function: <code>__pcpu_map_pages</code>

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
In mm/percpu.c (ffffffff811b0ccb)
Location: mm/percpu-vm.c:191
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff811c9ef8)
Location: mm/percpu-vm.c:191
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff811da003)
Location: mm/percpu-vm.c:191
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff811e368c)
Location: mm/percpu-vm.c:190
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff811f8f28)
Location: mm/percpu-vm.c:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff8121a98e)
Location: mm/percpu-vm.c:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff8122d93e)
Location: mm/percpu-vm.c:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff8123d66a)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff8124baba)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __pcpu_map_pages(long unsigned int addr, struct page **pages, int nr_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812799de)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
Direct callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
**Symbols:**

```
ffffffff81278870-ffffffff812788a4: __pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __pcpu_map_pages(long unsigned int addr, struct page **pages, int nr_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8128426e)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
Direct callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
**Symbols:**

```
ffffffff812830e0-ffffffff81283114: __pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __pcpu_map_pages(long unsigned int addr, struct page **pages, int nr_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81288eb2)
Location: mm/percpu-vm.c:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
Direct callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
**Symbols:**

```
ffffffff812881e0-ffffffff8128821e: __pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __pcpu_map_pages(long unsigned int addr, struct page **pages, int nr_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c8952)
Location: mm/percpu-vm.c:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
Direct callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
**Symbols:**

```
ffffffff812c7920-ffffffff812c795e: __pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __pcpu_map_pages(long unsigned int addr, struct page **pages, int nr_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81326334)
Location: mm/percpu-vm.c:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
Direct callers:
  - mm/percpu.c:pcpu_page_first_chunk
```
**Symbols:**

```
ffffffff81324d60-ffffffff81324db0: __pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139bef1)
Location: mm/percpu-vm.c:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff813cefd1)
Location: mm/percpu-vm.c:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff813f9b31)
Location: mm/percpu-vm.c:193
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_map_pages
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffff8000102e1cf0)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (c0505f18)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (c0000000003a1bd0)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffe0001f89d2)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff8124410a)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff812370da)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff81241eaa)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
In mm/percpu.c (ffffffff8125164a)
Location: mm/percpu-vm.c:192
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
  - mm/percpu.c:pcpu_page_first_chunk
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
</ul>
