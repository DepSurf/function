# Function: <code>init_kmem_cache_nodes</code>

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
In mm/slub.c (ffffffff811edb01)
Location: mm/slub.c:3185
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
In mm/slub.c (ffffffff8120cfb1)
Location: mm/slub.c:3354
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
In mm/slub.c (ffffffff8121f011)
Location: mm/slub.c:3376
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
In mm/slub.c (ffffffff8122b6c7)
Location: mm/slub.c:3373
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
In mm/slub.c (ffffffff81246dd4)
Location: mm/slub.c:3386
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
In mm/slub.c (ffffffff81268198)
Location: mm/slub.c:3369
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
In mm/slub.c (ffffffff8127dcb7)
Location: mm/slub.c:3419
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
In mm/slub.c (ffffffff81299b05)
Location: mm/slub.c:3430
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
In mm/slub.c (ffffffff812a99c5)
Location: mm/slub.c:3440
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812de560)
Location: mm/slub.c:3498
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff812de560-ffffffff812de68f: init_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ea100)
Location: mm/slub.c:3585
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff812ea100-ffffffff812ea22f: init_kmem_cache_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f1f93)
Location: mm/slub.c:3618
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133af49)
Location: mm/slub.c:3955
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int init_kmem_cache_nodes(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4005
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_open
```
**Symbols:**

```
ffffffff813ad2c0-ffffffff813ad515: init_kmem_cache_nodes (STB_LOCAL)
ffffffff81e742b3-ffffffff81e742d2: init_kmem_cache_nodes.cold (STB_LOCAL)
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
In mm/slub.c (ffffffff8142dabc)
Location: mm/slub.c:4287
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff8146313c)
Location: mm/slub.c:4302
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffffffff8145f38c)
Location: mm/slub.c:4906
Inline: True
Inline callers:
  - mm/slub.c:kmem_cache_open
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
In mm/slub.c (ffff80001034b4bc)
Location: mm/slub.c:3440
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
In mm/slub.c (c054f4b4)
Location: mm/slub.c:3440
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
In mm/slub.c (c00000000042aa50)
Location: mm/slub.c:3440
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
In mm/slub.c (ffffffe00023cb6c)
Location: mm/slub.c:3440
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
In mm/slub.c (ffffffff812a1fa5)
Location: mm/slub.c:3440
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
In mm/slub.c (ffffffff81293a85)
Location: mm/slub.c:3440
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
In mm/slub.c (ffffffff8129fdb5)
Location: mm/slub.c:3440
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
In mm/slub.c (ffffffff812afef5)
Location: mm/slub.c:3440
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
</ul>
