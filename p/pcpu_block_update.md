# Function: <code>pcpu_block_update</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811fa267)
Location: mm/percpu.c:619
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff811f8100-ffffffff811f8160: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121a3f0)
Location: mm/percpu.c:616
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff812193b0-ffffffff8121940f: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122d302)
Location: mm/percpu.c:624
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff8122c310-ffffffff8122c36f: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123bf80)
Location: mm/percpu.c:603
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff8123bf80-ffffffff8123c028: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124a3d0)
Location: mm/percpu.c:603
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff8124a3d0-ffffffff8124a478: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81278600)
Location: mm/percpu.c:577
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff81278600-ffffffff812786a8: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81282e90)
Location: mm/percpu.c:586
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff81282e90-ffffffff81282f38: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81287fb0)
Location: mm/percpu.c:587
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff81287fb0-ffffffff8128805a: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c76e0)
Location: mm/percpu.c:634
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff812c76e0-ffffffff812c778a: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81324ae0)
Location: mm/percpu.c:634
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff81324ae0-ffffffff81324bc1: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813995f0)
Location: mm/percpu.c:630
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff813995f0-ffffffff813996d1: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cc680)
Location: mm/percpu.c:630
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff813cc680-ffffffff813cc761: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f6ff0)
Location: mm/percpu.c:630
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff813f6ff0-ffffffff813f70d1: pcpu_block_update (STB_LOCAL)
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
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e03a8)
Location: mm/percpu.c:603
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffff8000102e03a8-ffff8000102e04ec: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0504b90)
Location: mm/percpu.c:603
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
c0504b90-c0504cb8: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c00000000039fbd0)
Location: mm/percpu.c:603
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
c00000000039fbd0-c00000000039fd2c: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f7a1e)
Location: mm/percpu.c:603
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffe0001f7a1e-ffffffe0001f7b74: pcpu_block_update (STB_LOCAL)
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
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81242a20)
Location: mm/percpu.c:603
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff81242a20-ffffffff81242ac8: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812359f0)
Location: mm/percpu.c:603
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff812359f0-ffffffff81235a98: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812407c0)
Location: mm/percpu.c:603
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff812407c0-ffffffff81240868: pcpu_block_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcpu_block_update(struct pcpu_block_md *block, int start, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124ff40)
Location: mm/percpu.c:603
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_chunk_refresh_hint
```
**Symbols:**

```
ffffffff8124ff40-ffffffff8124ffe8: pcpu_block_update (STB_LOCAL)
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
