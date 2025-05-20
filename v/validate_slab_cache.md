# Function: <code>validate_slab_cache</code>

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
In mm/slub.c (ffffffff811ecec4)
Location: mm/slub.c:4156
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8120c624)
Location: mm/slub.c:4383
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8121e684)
Location: mm/slub.c:4352
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8122a214)
Location: mm/slub.c:4394
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812453c4)
Location: mm/slub.c:4410
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812694e7)
Location: mm/slub.c:4412
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8127c5c7)
Location: mm/slub.c:4464
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff81298198)
Location: mm/slub.c:4455
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812a7ff8)
Location: mm/slub.c:4473
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812dd4f7)
Location: mm/slub.c:4542
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812e62e7)
Location: mm/slub.c:4591
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812ed9bb)
Location: mm/slub.c:4672
Inline: True
Inline callers:
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int validate_slab_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5032
Inline: False
Direct callers:
  - mm/slub.c:validate_store
```
**Symbols:**

```
ffffffff81cc1855-ffffffff81cc188b: validate_slab_cache.cold (STB_LOCAL)
ffffffff81335d10-ffffffff81335e73: validate_slab_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int validate_slab_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5064
Inline: False
Direct callers:
  - mm/slub.c:validate_store
```
**Symbols:**

```
ffffffff81e73d18-ffffffff81e73d4e: validate_slab_cache.cold (STB_LOCAL)
ffffffff813a7530-ffffffff813a769e: validate_slab_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int validate_slab_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142b360)
Location: mm/slub.c:5180
Inline: False
Direct callers:
  - mm/slub.c:validate_store
```
**Symbols:**

```
ffffffff8142b360-ffffffff8142b4ec: validate_slab_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int validate_slab_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814608b0)
Location: mm/slub.c:5195
Inline: False
Direct callers:
  - mm/slub.c:validate_store
```
**Symbols:**

```
ffffffff814608b0-ffffffff81460a5d: validate_slab_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int validate_slab_cache(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81458870)
Location: mm/slub.c:5806
Inline: False
Direct callers:
  - mm/slub.c:validate_store
```
**Symbols:**

```
ffffffff81458870-ffffffff81458a1d: validate_slab_cache (STB_GLOBAL)
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
In mm/slub.c (ffff80001034963c)
Location: mm/slub.c:4473
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (c054d7dc)
Location: mm/slub.c:4473
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (c000000000428308)
Location: mm/slub.c:4473
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffe00023b36a)
Location: mm/slub.c:4473
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812a05d8)
Location: mm/slub.c:4473
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812920e8)
Location: mm/slub.c:4473
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8129e3e8)
Location: mm/slub.c:4473
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812ae498)
Location: mm/slub.c:4473
Inline: True
Inline callers:
  - mm/slub.c:validate_store
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
