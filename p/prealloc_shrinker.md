# Function: <code>prealloc_shrinker</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812081f0)
Location: mm/vmscan.c:306
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff812081f0-ffffffff8120824e: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121ad70)
Location: mm/vmscan.c:375
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff8121ad70-ffffffff8121ae81: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122aa00)
Location: mm/vmscan.c:387
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff8122aa00-ffffffff8122ab13: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812388d0)
Location: mm/vmscan.c:385
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff812388d0-ffffffff812389e3: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812671f0)
Location: mm/vmscan.c:342
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff812671f0-ffffffff812672e9: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81271c40)
Location: mm/vmscan.c:335
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff81271c40-ffffffff81271d39: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81276ea0)
Location: mm/vmscan.c:568
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff81276ea0-ffffffff8127706c: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b47e0)
Location: mm/vmscan.c:614
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff812b47e0-ffffffff812b49a9: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813107c0)
Location: mm/vmscan.c:611
Inline: False
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff813107c0-ffffffff8131096b: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81383e40)
Location: mm/vmscan.c:670
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff81383e40-ffffffff81383e56: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b58f0)
Location: mm/vmscan.c:722
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff813b58f0-ffffffff813b5906: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c9660)
Location: mm/vmscan.c:385
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffff8000102c9660-ffff8000102c9794: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f3644)
Location: mm/vmscan.c:385
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
c04f3644-c04f3748: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000385b80)
Location: mm/vmscan.c:385
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
c000000000385b80-c000000000385d3c: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e8a8e)
Location: mm/vmscan.c:385
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffe0001e8a8e-ffffffe0001e8b8a: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81230f20)
Location: mm/vmscan.c:385
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff81230f20-ffffffff81231033: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81223fe0)
Location: mm/vmscan.c:385
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff81223fe0-ffffffff812240f3: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122ecc0)
Location: mm/vmscan.c:385
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff8122ecc0-ffffffff8122edd3: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int prealloc_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123e0d0)
Location: mm/vmscan.c:385
Inline: True
Direct callers:
  - mm/vmscan.c:register_shrinker
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff8123e0d0-ffffffff8123e1e3: prealloc_shrinker (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *fmt</code>
</li>
<li>
<b>Param added. </b>
<code>void (anon)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
