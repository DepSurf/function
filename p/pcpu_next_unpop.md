# Function: <code>pcpu_next_unpop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcpu_next_unpop(struct pcpu_chunk *chunk, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811b02f0)
Location: mm/percpu.c:250
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
```
**Symbols:**

```
ffffffff811b02f0-ffffffff811b033c: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcpu_next_unpop(struct pcpu_chunk *chunk, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811c9440)
Location: mm/percpu.c:255
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
```
**Symbols:**

```
ffffffff811c9440-ffffffff811c948c: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcpu_next_unpop(struct pcpu_chunk *chunk, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811d9520)
Location: mm/percpu.c:255
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
```
**Symbols:**

```
ffffffff811d9520-ffffffff811d956c: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcpu_next_unpop(struct pcpu_chunk *chunk, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e2b60)
Location: mm/percpu.c:242
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc_area
```
**Symbols:**

```
ffffffff811e2b60-ffffffff811e2bac: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f8200)
Location: mm/percpu.c:260
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff811f8200-ffffffff811f8248: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812194b0)
Location: mm/percpu.c:261
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff812194b0-ffffffff812194f8: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122c420)
Location: mm/percpu.c:269
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff8122c420-ffffffff8122c468: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123c1c0)
Location: mm/percpu.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff8123c1c0-ffffffff8123c206: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124a610)
Location: mm/percpu.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff8124a610-ffffffff8124a656: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e05f0)
Location: mm/percpu.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffff8000102e05f0-ffff8000102e0654: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0504db0)
Location: mm/percpu.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
c0504db0-c0504e00: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c00000000039fe70)
Location: mm/percpu.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
c00000000039fe70-c00000000039fefc: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f7d60)
Location: mm/percpu.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffe0001f7d60-ffffffe0001f7dbc: pcpu_next_unpop (STB_LOCAL)
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
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81242c60)
Location: mm/percpu.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff81242c60-ffffffff81242ca6: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81235c30)
Location: mm/percpu.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff81235c30-ffffffff81235c76: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81240a00)
Location: mm/percpu.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff81240a00-ffffffff81240a46: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcpu_next_unpop(long unsigned int *bitmap, int *rs, int *re, int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81250180)
Location: mm/percpu.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_find_block_fit
  - mm/percpu.c:pcpu_block_refresh_hint
  - mm/percpu.c:pcpu_block_refresh_hint
```
**Symbols:**

```
ffffffff81250180-ffffffff812501c6: pcpu_next_unpop (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *bitmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pcpu_chunk *chunk</code>
</li>
</ul>
</details>
</li>
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
