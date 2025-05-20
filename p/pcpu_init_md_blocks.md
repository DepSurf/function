# Function: <code>pcpu_init_md_blocks</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f933b)
Location: mm/percpu.c:1052
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
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
In mm/percpu.c (ffffffff8121af0b)
Location: mm/percpu.c:1049
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
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
In mm/percpu.c (ffffffff8122debb)
Location: mm/percpu.c:1057
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123c0f0)
Location: mm/percpu.c:1282
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff8123c0f0-ffffffff8123c16c: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124a540)
Location: mm/percpu.c:1282
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff8124a540-ffffffff8124a5bc: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81278770)
Location: mm/percpu.c:1254
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff81278770-ffffffff812787ec: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81283000)
Location: mm/percpu.c:1270
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff81283000-ffffffff8128307c: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81288150)
Location: mm/percpu.c:1271
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff81288150-ffffffff812881cc: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c7880)
Location: mm/percpu.c:1315
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff812c7880-ffffffff812c790a: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81324cc0)
Location: mm/percpu.c:1315
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff81324cc0-ffffffff81324d56: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81399540)
Location: mm/percpu.c:1319
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff81399540-ffffffff813995d6: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cc5d0)
Location: mm/percpu.c:1319
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff813cc5d0-ffffffff813cc666: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f6f40)
Location: mm/percpu.c:1319
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff813f6f40-ffffffff813f6fd6: pcpu_init_md_blocks (STB_LOCAL)
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
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e0270)
Location: mm/percpu.c:1282
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffff8000102e0270-ffff8000102e02e4: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0504a94)
Location: mm/percpu.c:1282
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
c0504a94-c0504b1c: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c00000000039fa60)
Location: mm/percpu.c:1282
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
c00000000039fa60-c00000000039fb1c: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f7c18)
Location: mm/percpu.c:1282
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffe0001f7c18-ffffffe0001f7c7c: pcpu_init_md_blocks (STB_LOCAL)
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
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81242b90)
Location: mm/percpu.c:1282
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff81242b90-ffffffff81242c0c: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81235b60)
Location: mm/percpu.c:1282
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff81235b60-ffffffff81235bdc: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81240930)
Location: mm/percpu.c:1282
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff81240930-ffffffff812409ac: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcpu_init_md_blocks(struct pcpu_chunk *chunk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812500b0)
Location: mm/percpu.c:1282
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_alloc_first_chunk
```
**Symbols:**

```
ffffffff812500b0-ffffffff8125012c: pcpu_init_md_blocks (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
