# Function: <code>free_slab</code>

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
In mm/slub.c (ffffffff811e923d)
Location: mm/slub.c:1547
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff81208d1d)
Location: mm/slub.c:1682
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff8121ad9d)
Location: mm/slub.c:1685
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff812267dd)
Location: mm/slub.c:1688
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff8124181d)
Location: mm/slub.c:1701
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff8126547d)
Location: mm/slub.c:1696
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff8127a1ae)
Location: mm/slub.c:1755
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff81295b1d)
Location: mm/slub.c:1762
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff812a58fd)
Location: mm/slub.c:1741
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812da5bd)
Location: mm/slub.c:1791
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e6e7d)
Location: mm/slub.c:1856
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff812ee66d)
Location: mm/slub.c:1884
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff813368ad)
Location: mm/slub.c:2005
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff813a81fd)
Location: mm/slub.c:2063
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81428ab0)
Location: mm/slub.c:2079
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
**Symbols:**

```
ffffffff81428ab0-ffffffff81428bce: free_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145de30)
Location: mm/slub.c:2089
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
**Symbols:**

```
ffffffff8145de30-ffffffff8145df3c: free_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_slab(struct kmem_cache *s, struct slab *slab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81459800)
Location: mm/slub.c:2434
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_do_shrink
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:discard_slab
```
**Symbols:**

```
ffffffff81459800-ffffffff8145990c: free_slab (STB_LOCAL)
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
In mm/slub.c (ffff8000103467bc)
Location: mm/slub.c:1741
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (c054b364)
Location: mm/slub.c:1741
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (c0000000004247e0)
Location: mm/slub.c:1741
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_slab(struct kmem_cache *s, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe0002395bc)
Location: mm/slub.c:1741
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shrink
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffe0002395bc-ffffffe000239618: free_slab (STB_LOCAL)
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
In mm/slub.c (ffffffff8129dedd)
Location: mm/slub.c:1741
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff8128fa5d)
Location: mm/slub.c:1741
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff8129bced)
Location: mm/slub.c:1741
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
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
In mm/slub.c (ffffffff812abbfd)
Location: mm/slub.c:1741
Inline: True
Inline callers:
  - mm/slub.c:discard_slab
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
