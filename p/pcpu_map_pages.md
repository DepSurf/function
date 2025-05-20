# Function: <code>pcpu_map_pages</code>

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
In mm/percpu.c (ffffffff811b0b51)
Location: mm/percpu-vm.c:212
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811c9d7d)
Location: mm/percpu-vm.c:212
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811d9e6f)
Location: mm/percpu-vm.c:212
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811e3595)
Location: mm/percpu-vm.c:211
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (ffffffff811f8e49)
Location: mm/percpu-vm.c:214
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:214
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:214
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:213
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:213
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcpu_map_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81279940)
Location: mm/percpu-vm.c:213
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81279940-ffffffff81279ae0: pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcpu_map_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812841d0)
Location: mm/percpu-vm.c:213
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff812841d0-ffffffff81284370: pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pcpu_map_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81288e10)
Location: mm/percpu-vm.c:214
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81288e10-ffffffff81288fbc: pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcpu_map_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c88b0)
Location: mm/percpu-vm.c:214
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff812c88b0-ffffffff812c8a3d: pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pcpu_map_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81326290)
Location: mm/percpu-vm.c:214
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff81326290-ffffffff81326425: pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pcpu_map_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139be50)
Location: mm/percpu-vm.c:214
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff8139be50-ffffffff8139c012: pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcpu_map_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cef30)
Location: mm/percpu-vm.c:214
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff813cef30-ffffffff813cf0f2: pcpu_map_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcpu_map_pages(struct pcpu_chunk *chunk, struct page **pages, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f9a90)
Location: mm/percpu-vm.c:214
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_populate_chunk
```
**Symbols:**

```
ffffffff813f9a90-ffffffff813f9c52: pcpu_map_pages (STB_LOCAL)
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:213
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:213
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:213
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
In mm/percpu.c (ffffffe0001f89ca)
Location: mm/percpu-vm.c:213
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:213
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:213
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:213
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
In mm/percpu.c (0)
Location: mm/percpu-vm.c:213
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_populate_chunk
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
