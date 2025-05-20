# Function: <code>early_kmem_cache_node_alloc</code>

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
In mm/slub.c (ffffffff811edb17)
Location: mm/slub.c:3138
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff8120cfc7)
Location: mm/slub.c:3299
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff8121f027)
Location: mm/slub.c:3321
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff8122b81a)
Location: mm/slub.c:3318
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
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
In mm/slub.c (ffffffff81246f26)
Location: mm/slub.c:3331
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
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
In mm/slub.c (ffffffff81268245)
Location: mm/slub.c:3314
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff8127dd64)
Location: mm/slub.c:3364
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff81299bb6)
Location: mm/slub.c:3375
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff812a9a76)
Location: mm/slub.c:3385
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void early_kmem_cache_node_alloc(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3443
Inline: False
Direct callers:
  - mm/slub.c:init_kmem_cache_nodes
```
**Symbols:**

```
ffffffff812d9e10-ffffffff812d9fdd: early_kmem_cache_node_alloc (STB_LOCAL)
ffffffff812dfe7e-ffffffff812dfe9e: early_kmem_cache_node_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void early_kmem_cache_node_alloc(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3530
Inline: False
Direct callers:
  - mm/slub.c:init_kmem_cache_nodes
```
**Symbols:**

```
ffffffff812e5140-ffffffff812e530f: early_kmem_cache_node_alloc (STB_LOCAL)
ffffffff81be9290-ffffffff81be92b0: early_kmem_cache_node_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void early_kmem_cache_node_alloc(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3564
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff812ecd10-ffffffff812ecedf: early_kmem_cache_node_alloc (STB_LOCAL)
ffffffff81bdb40a-ffffffff81bdb42a: early_kmem_cache_node_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void early_kmem_cache_node_alloc(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3901
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff81334f20-ffffffff813350ef: early_kmem_cache_node_alloc (STB_LOCAL)
ffffffff81cc12d6-ffffffff81cc12f6: early_kmem_cache_node_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ad387)
Location: mm/slub.c:3951
Inline: True
Inline callers:
  - mm/slub.c:init_kmem_cache_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void early_kmem_cache_node_alloc(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81427be0)
Location: mm/slub.c:4231
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff81427be0-ffffffff81427d8c: early_kmem_cache_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void early_kmem_cache_node_alloc(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145d150)
Location: mm/slub.c:4246
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff8145d150-ffffffff8145d359: early_kmem_cache_node_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void early_kmem_cache_node_alloc(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81457850)
Location: mm/slub.c:4850
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff81457850-ffffffff81457a60: early_kmem_cache_node_alloc (STB_LOCAL)
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
In mm/slub.c (ffff80001034b568)
Location: mm/slub.c:3385
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (c054f5bc)
Location: mm/slub.c:3385
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (c00000000042ab70)
Location: mm/slub.c:3385
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffe00023cc36)
Location: mm/slub.c:3385
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff812a2056)
Location: mm/slub.c:3385
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff81293b36)
Location: mm/slub.c:3385
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff8129fe66)
Location: mm/slub.c:3385
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff812affa6)
Location: mm/slub.c:3385
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
