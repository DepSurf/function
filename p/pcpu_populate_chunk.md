# Function: <code>pcpu_populate_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811b0a50)
Location: mm/percpu-vm.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_balance_workfn
```
**Symbols:**

```
ffffffff811b0a50-ffffffff811b0dbc: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811c9c70)
Location: mm/percpu-vm.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff811c9c70-ffffffff811c9fe9: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811d9d60)
Location: mm/percpu-vm.c:273
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff811d9d60-ffffffff811da0fa: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e33e0)
Location: mm/percpu-vm.c:272
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff811e33e0-ffffffff811e3755: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f8cb0)
Location: mm/percpu-vm.c:276
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff811f8cb0-ffffffff811f8fef: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121a6b0)
Location: mm/percpu-vm.c:276
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8121a6b0-ffffffff8121a9fc: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122d660)
Location: mm/percpu-vm.c:276
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8122d660-ffffffff8122d9ac: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123d390)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8123d390-ffffffff8123d6de: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124b7e0)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8124b7e0-ffffffff8124bb2e: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81279ae0)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81279ae0-ffffffff81279b89: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81284370)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81284370-ffffffff81284419: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81288fc0)
Location: mm/percpu-vm.c:276
Inline: False
Direct callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81288fc0-ffffffff8128906b: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c8a40)
Location: mm/percpu-vm.c:276
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff812c8a40-ffffffff812c8aeb: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81326430)
Location: mm/percpu-vm.c:276
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81326430-ffffffff813264e1: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139c9d0)
Location: mm/percpu-vm.c:276
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff8139c9d0-ffffffff8139ca81: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cfab0)
Location: mm/percpu-vm.c:276
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff813cfab0-ffffffff813cfb61: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813fa6b0)
Location: mm/percpu-vm.c:276
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_populated
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff813fa6b0-ffffffff813fa761: pcpu_populate_chunk (STB_LOCAL)
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
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e1a98)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffff8000102e1a98-ffff8000102e1f08: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0505c7c)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
c0505c7c-c0505fd4: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a18d0)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
c0000000003a18d0-c0000000003a1de0: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f884e)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffe0001f884e-ffffffe0001f8aea: pcpu_populate_chunk (STB_LOCAL)
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
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81243e30)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81243e30-ffffffff8124417e: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81236e00)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81236e00-ffffffff8123714e: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81241bd0)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81241bd0-ffffffff81241f1e: pcpu_populate_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pcpu_populate_chunk(struct pcpu_chunk *chunk, int page_start, int page_end, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81251370)
Location: mm/percpu-vm.c:275
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_alloc
```
**Symbols:**

```
ffffffff81251370-ffffffff812516be: pcpu_populate_chunk (STB_LOCAL)
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
<code>gfp_t gfp</code>
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
