# Function: <code>pcpu_alloc_first_chunk</code>

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
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff826d99ca)
Location: mm/percpu.c:1078
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff826d99ca-ffffffff826d9bfb: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff82703ebe)
Location: mm/percpu.c:1075
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff82703ebe-ffffffff827040ce: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff828bb5ea)
Location: mm/percpu.c:1083
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff828bb5ea-ffffffff828bb7fa: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff828d2a63)
Location: mm/percpu.c:1308
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff828d2a63-ffffffff828d2ca4: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff828daed5)
Location: mm/percpu.c:1308
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff828daed5-ffffffff828db116: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff82cf8f05)
Location: mm/percpu.c:1280
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff82cf8f05-ffffffff82cf914c: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff82fe5bd0)
Location: mm/percpu.c:1296
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff82fe5bd0-ffffffff82fe5e4b: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff831f06a9)
Location: mm/percpu.c:1297
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff831f06a9-ffffffff831f0937: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff832d6034)
Location: mm/percpu.c:1341
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff832d6034-ffffffff832d62c2: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8348aa72)
Location: mm/percpu.c:1341
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff8348aa72-ffffffff8348ace6: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff83ebb5c0)
Location: mm/percpu.c:1345
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff83ebb5c0-ffffffff83ebb853: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff836e3bf0)
Location: mm/percpu.c:1345
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff836e3bf0-ffffffff836e3e83: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff83916480)
Location: mm/percpu.c:1345
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff83916480-ffffffff83916713: pcpu_alloc_first_chunk (STB_LOCAL)
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
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff800011453890)
Location: mm/percpu.c:1308
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffff800011453890-ffff800011453ac4: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c152e5e0)
Location: mm/percpu.c:1308
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
c152e5e0-c152e804: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c00000000137bde8)
Location: mm/percpu.c:1308
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
c00000000137bde8-c00000000137c108: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe000012bfe)
Location: mm/percpu.c:1308
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffe000012bfe-ffffffe000012e26: pcpu_alloc_first_chunk (STB_LOCAL)
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
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff828c3d89)
Location: mm/percpu.c:1308
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff828c3d89-ffffffff828c3fca: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff828bc4ae)
Location: mm/percpu.c:1308
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff828bc4ae-ffffffff828bc6ef: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff828d6b09)
Location: mm/percpu.c:1308
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff828d6b09-ffffffff828d6d4a: pcpu_alloc_first_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pcpu_chunk *pcpu_alloc_first_chunk(long unsigned int tmp_addr, int map_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff828dbf2a)
Location: mm/percpu.c:1308
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff828dbf2a-ffffffff828dc16b: pcpu_alloc_first_chunk (STB_LOCAL)
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
