# Function: <code>init_cache_random_seq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812066c0)
Location: mm/slub.c:1421
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff812066c0-ffffffff8120673b: init_cache_random_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812186e0)
Location: mm/slub.c:1420
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff812186e0-ffffffff81218769: init_cache_random_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812243b0)
Location: mm/slub.c:1422
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff812243b0-ffffffff81224439: init_cache_random_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8123fa10)
Location: mm/slub.c:1453
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff8123fa10-ffffffff8123fa99: init_cache_random_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1454
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff81263090-ffffffff8126310f: init_cache_random_seq (STB_LOCAL)
ffffffff8126a9b6-ffffffff8126a9cb: init_cache_random_seq.cold.87 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1512
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff81277920-ffffffff8127799f: init_cache_random_seq (STB_LOCAL)
ffffffff8127f246-ffffffff8127f25b: init_cache_random_seq.cold.89 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1529
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff81293120-ffffffff8129319f: init_cache_random_seq (STB_LOCAL)
ffffffff8129b0ee-ffffffff8129b103: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1509
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff812a2ea0-ffffffff812a2f1f: init_cache_random_seq (STB_LOCAL)
ffffffff812aafae-ffffffff812aafc3: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1559
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff812d7580-ffffffff812d75ff: init_cache_random_seq (STB_LOCAL)
ffffffff812df85b-ffffffff812df870: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1627
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff812e30e0-ffffffff812e315f: init_cache_random_seq (STB_LOCAL)
ffffffff81be900a-ffffffff81be901f: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1655
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff812ea870-ffffffff812ea8f1: init_cache_random_seq (STB_LOCAL)
ffffffff81bdb18f-ffffffff81bdb1a4: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1779
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff813327b0-ffffffff81332831: init_cache_random_seq (STB_LOCAL)
ffffffff81cc0cf8-ffffffff81cc0d0d: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1841
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff813a3d20-ffffffff813a3dc7: init_cache_random_seq (STB_LOCAL)
ffffffff81e7325a-ffffffff81e7326f: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81423de0)
Location: mm/slub.c:1870
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff81423de0-ffffffff81423e98: init_cache_random_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81459080)
Location: mm/slub.c:1881
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff81459080-ffffffff81459138: init_cache_random_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81454040)
Location: mm/slub.c:2206
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff81454040-ffffffff814540f8: init_cache_random_seq (STB_LOCAL)
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
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010343168)
Location: mm/slub.c:1509
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffff800010343168-ffff800010343218: init_cache_random_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c05486a0)
Location: mm/slub.c:1509
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
c05486a0-c054874c: init_cache_random_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0000000004207e0)
Location: mm/slub.c:1509
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
c0000000004207e0-c0000000004208f0: init_cache_random_seq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000236c8e)
Location: mm/slub.c:1509
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffe000236c8e-ffffffe000236d1c: init_cache_random_seq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1509
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff8129b480-ffffffff8129b4ff: init_cache_random_seq (STB_LOCAL)
ffffffff812a358e-ffffffff812a35a3: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1509
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff8128d040-ffffffff8128d0bf: init_cache_random_seq (STB_LOCAL)
ffffffff8129505e-ffffffff81295073: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1509
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff81299290-ffffffff8129930f: init_cache_random_seq (STB_LOCAL)
ffffffff812a139e-ffffffff812a13b3: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int init_cache_random_seq(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1509
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff812a90b0-ffffffff812a912f: init_cache_random_seq (STB_LOCAL)
ffffffff812b154e-ffffffff812b1563: init_cache_random_seq.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
