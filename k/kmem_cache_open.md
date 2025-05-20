# Function: <code>kmem_cache_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eda30)
Location: mm/slub.c:3333
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff811eda30-ffffffff811edea8: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120cec0)
Location: mm/slub.c:3510
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8120cec0-ffffffff8120d334: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121ef20)
Location: mm/slub.c:3532
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8121ef20-ffffffff8121f39f: kmem_cache_open (STB_LOCAL)
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
In mm/slub.c (ffffffff8122b5dc)
Location: mm/slub.c:3562
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
In mm/slub.c (ffffffff81246cdc)
Location: mm/slub.c:3575
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3558
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff81268070-ffffffff81268485: kmem_cache_open (STB_LOCAL)
ffffffff8126b1a2-ffffffff8126b1e2: kmem_cache_open.cold.97 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3611
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8127db90-ffffffff8127df94: kmem_cache_open (STB_LOCAL)
ffffffff8127fa66-ffffffff8127faaa: kmem_cache_open.cold.100 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3622
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812999d0-ffffffff81299dd5: kmem_cache_open (STB_LOCAL)
ffffffff8129b9d6-ffffffff8129b9f6: kmem_cache_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3632
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812a9890-ffffffff812a9c95: kmem_cache_open (STB_LOCAL)
ffffffff812ab84f-ffffffff812ab86f: kmem_cache_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812de8d0)
Location: mm/slub.c:3710
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812de8d0-ffffffff812deb06: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ea6e0)
Location: mm/slub.c:3798
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812ea6e0-ffffffff812ea909: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f1e80)
Location: mm/slub.c:3825
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812f1e80-ffffffff812f21a2: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133ae30)
Location: mm/slub.c:4162
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8133ae30-ffffffff8133b14e: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813ad700)
Location: mm/slub.c:4198
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff813ad700-ffffffff813ad978: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142d970)
Location: mm/slub.c:4486
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8142d970-ffffffff8142dcc5: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81462ff0)
Location: mm/slub.c:4501
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff81462ff0-ffffffff814633bf: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145f240)
Location: mm/slub.c:5105
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8145f240-ffffffff8145f60f: kmem_cache_open (STB_LOCAL)
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
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034b390)
Location: mm/slub.c:3632
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffff80001034b390-ffff80001034b814: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054f380)
Location: mm/slub.c:3632
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
c054f380-c054f71c: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042a950)
Location: mm/slub.c:3632
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
c00000000042a950-c00000000042aeb8: kmem_cache_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023c9e2)
Location: mm/slub.c:3632
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffe00023c9e2-ffffffe00023cd38: kmem_cache_open (STB_LOCAL)
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
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3632
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812a1e70-ffffffff812a2275: kmem_cache_open (STB_LOCAL)
ffffffff812a3e2f-ffffffff812a3e4f: kmem_cache_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3632
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff81293950-ffffffff81293d55: kmem_cache_open (STB_LOCAL)
ffffffff812958ff-ffffffff8129591f: kmem_cache_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3632
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff8129fc80-ffffffff812a0085: kmem_cache_open (STB_LOCAL)
ffffffff812a1c3f-ffffffff812a1c5f: kmem_cache_open.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kmem_cache_open(struct kmem_cache *s, slab_flags_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3632
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_create
```
**Symbols:**

```
ffffffff812afdc0-ffffffff812b01c5: kmem_cache_open (STB_LOCAL)
ffffffff812b1dfa-ffffffff812b1e1a: kmem_cache_open.cold (STB_LOCAL)
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
