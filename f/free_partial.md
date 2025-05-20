# Function: <code>free_partial</code>

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
In mm/slub.c (ffffffff811edf1b)
Location: mm/slub.c:3447
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
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
In mm/slub.c (ffffffff8120d3eb)
Location: mm/slub.c:3630
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff8121f44b)
Location: mm/slub.c:3652
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff8122abe7)
Location: mm/slub.c:3656
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812462e7)
Location: mm/slub.c:3672
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812697da)
Location: mm/slub.c:3652
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff8127e0a9)
Location: mm/slub.c:3703
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff81299ed9)
Location: mm/slub.c:3710
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812a9d99)
Location: mm/slub.c:3720
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void free_partial(struct kmem_cache *s, struct kmem_cache_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3797
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff812db210-ffffffff812db345: free_partial (STB_LOCAL)
ffffffff812dff8e-ffffffff812dffaf: free_partial.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void free_partial(struct kmem_cache *s, struct kmem_cache_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:3885
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff812e9b90-ffffffff812e9cc5: free_partial (STB_LOCAL)
ffffffff81be99b0-ffffffff81be99d1: free_partial.cold (STB_LOCAL)
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
In mm/slub.c (ffffffff812f22e6)
Location: mm/slub.c:3912
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff8133b209)
Location: mm/slub.c:4250
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void free_partial(struct kmem_cache *s, struct kmem_cache_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4287
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff813acda0-ffffffff813acee2: free_partial (STB_LOCAL)
ffffffff81e740fd-ffffffff81e7429f: free_partial.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_partial(struct kmem_cache *s, struct kmem_cache_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4573
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff8142cda0-ffffffff8142d051: free_partial (STB_LOCAL)
ffffffff8206777a-ffffffff820677e7: free_partial.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_partial(struct kmem_cache *s, struct kmem_cache_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4588
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff814623b0-ffffffff81462658: free_partial (STB_LOCAL)
ffffffff820e7067-ffffffff820e70d4: free_partial.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void free_partial(struct kmem_cache *s, struct kmem_cache_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5192
Inline: False
Direct callers:
  - mm/slub.c:__kmem_cache_shutdown
```
**Symbols:**

```
ffffffff8145e8f0-ffffffff8145eb79: free_partial (STB_LOCAL)
ffffffff821c20c2-ffffffff821c212f: free_partial.cold (STB_LOCAL)
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
In mm/slub.c (ffff80001034b954)
Location: mm/slub.c:3720
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (c054f814)
Location: mm/slub.c:3720
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (c00000000042b0a4)
Location: mm/slub.c:3720
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffe00023ce18)
Location: mm/slub.c:3720
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812a2379)
Location: mm/slub.c:3720
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff81293e59)
Location: mm/slub.c:3720
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812a0189)
Location: mm/slub.c:3720
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
In mm/slub.c (ffffffff812b02c9)
Location: mm/slub.c:3720
Inline: True
Inline callers:
  - mm/slub.c:__kmem_cache_shutdown
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
