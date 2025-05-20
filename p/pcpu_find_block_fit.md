# Function: <code>pcpu_find_block_fit</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f9140)
Location: mm/percpu.c:921
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff811f9140-ffffffff811f928c: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121ad00)
Location: mm/percpu.c:918
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8121ad00-ffffffff8121ae4c: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122dcb0)
Location: mm/percpu.c:926
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8122dcb0-ffffffff8122ddfc: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123da30)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8123da30-ffffffff8123dba6: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124be80)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8124be80-ffffffff8124bff6: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81279c20)
Location: mm/percpu.c:1049
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81279c20-ffffffff81279da3: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81284510)
Location: mm/percpu.c:1058
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81284510-ffffffff81284696: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812890b0)
Location: mm/percpu.c:1059
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff812890b0-ffffffff81289256: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c8b30)
Location: mm/percpu.c:1106
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff812c8b30-ffffffff812c8cd6: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81326ec0)
Location: mm/percpu.c:1106
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81326ec0-ffffffff8132707b: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139c030)
Location: mm/percpu.c:1110
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8139c030-ffffffff8139c1d4: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cf110)
Location: mm/percpu.c:1110
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff813cf110-ffffffff813cf2b3: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f9c70)
Location: mm/percpu.c:1110
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff813f9c70-ffffffff813f9e13: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e11f8)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffff8000102e11f8-ffff8000102e1388: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0506130)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
c0506130-c05062e0: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a16a0)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
c0000000003a16a0-c0000000003a18d0: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f8c42)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffe0001f8c42-ffffffe0001f8d74: pcpu_find_block_fit (STB_LOCAL)
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
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812444d0)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff812444d0-ffffffff81244646: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812374a0)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff812374a0-ffffffff81237616: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81242270)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81242270-ffffffff812423e6: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pcpu_find_block_fit(struct pcpu_chunk *chunk, int alloc_bits, size_t align, bool pop_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81251a20)
Location: mm/percpu.c:1077
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81251a20-ffffffff81251b96: pcpu_find_block_fit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
