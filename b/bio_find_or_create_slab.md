# Function: <code>bio_find_or_create_slab</code>

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
In block/bio.c (ffffffff813b0ce6)
Location: block/bio.c:71
Inline: True
Inline callers:
  - block/bio.c:__bioset_create
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
In block/bio.c (ffffffff813f46d6)
Location: block/bio.c:71
Inline: True
Inline callers:
  - block/bio.c:__bioset_create
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
In block/bio.c (ffffffff8140e0c6)
Location: block/bio.c:71
Inline: True
Inline callers:
  - block/bio.c:__bioset_create
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
In block/bio.c (ffffffff8141bcdc)
Location: block/bio.c:72
Inline: True
Inline callers:
  - block/bio.c:bioset_create
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
In block/bio.c (ffffffff8144698c)
Location: block/bio.c:72
Inline: True
Inline callers:
  - block/bio.c:bioset_create
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
In block/bio.c (ffffffff8147984a)
Location: block/bio.c:72
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff814978aa)
Location: block/bio.c:74
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff814c5249)
Location: block/bio.c:62
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff814de159)
Location: block/bio.c:62
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kmem_cache *bio_find_or_create_slab(unsigned int extra_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153d660)
Location: block/bio.c:64
Inline: False
Direct callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff8153d660-ffffffff8153d7c4: bio_find_or_create_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kmem_cache *bio_find_or_create_slab(unsigned int extra_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155a250)
Location: block/bio.c:64
Inline: False
Direct callers:
  - block/bio.c:bioset_init
```
**Symbols:**

```
ffffffff8155a250-ffffffff8155a3b4: bio_find_or_create_slab (STB_LOCAL)
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
In block/bio.c (ffffffff81563445)
Location: block/bio.c:107
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff815c7d75)
Location: block/bio.c:112
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff81672aa0)
Location: block/bio.c:113
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff8172e560)
Location: block/bio.c:119
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff8176a830)
Location: block/bio.c:118
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff817acc90)
Location: block/bio.c:118
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffff8000105da7fc)
Location: block/bio.c:62
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (c0787b60)
Location: block/bio.c:62
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (c00000000076ac88)
Location: block/bio.c:62
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffe00041dddc)
Location: block/bio.c:62
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff814d6739)
Location: block/bio.c:62
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff814c70f9)
Location: block/bio.c:62
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff814d27c9)
Location: block/bio.c:62
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
In block/bio.c (ffffffff814eb2e9)
Location: block/bio.c:62
Inline: True
Inline callers:
  - block/bio.c:bioset_init
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
