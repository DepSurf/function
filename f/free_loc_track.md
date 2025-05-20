# Function: <code>free_loc_track</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff811e8970)
Location: mm/slub.c:4196
Inline: True
Direct callers:
  - mm/slub.c:alloc_loc_track
  - mm/slub.c:list_locations
```
**Symbols:**

```
ffffffff811e8970-ffffffff811e89a8: free_loc_track.isra.57 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81207710)
Location: mm/slub.c:4423
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff81207710-ffffffff81207748: free_loc_track.isra.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81219740)
Location: mm/slub.c:4392
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff81219740-ffffffff81219777: free_loc_track.isra.65 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81225190)
Location: mm/slub.c:4434
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff81225190-ffffffff812251c8: free_loc_track.isra.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81240810)
Location: mm/slub.c:4450
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff81240810-ffffffff81240848: free_loc_track.isra.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81263ba0)
Location: mm/slub.c:4453
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff81263ba0-ffffffff81263bd7: free_loc_track.isra.69 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81278330)
Location: mm/slub.c:4503
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff81278330-ffffffff81278367: free_loc_track.isra.72 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81294640)
Location: mm/slub.c:4494
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff81294640-ffffffff81294677: free_loc_track.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812a4410)
Location: mm/slub.c:4512
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff812a4410-ffffffff812a4447: free_loc_track.isra.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff812d94b5)
Location: mm/slub.c:4577
Inline: True
Inline callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_loc_track(struct loc_track *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e3700)
Location: mm/slub.c:4626
Inline: False
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff812e3700-ffffffff812e3738: free_loc_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_loc_track(struct loc_track *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812eaeb0)
Location: mm/slub.c:4707
Inline: False
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff812eaeb0-ffffffff812eaee8: free_loc_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_loc_track(struct loc_track *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8133384e)
Location: mm/slub.c:5080
Inline: True
Inline callers:
  - mm/slub.c:slab_debug_trace_release
Direct callers:
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff81332fb0-ffffffff81332fe8: free_loc_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_loc_track(struct loc_track *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a524d)
Location: mm/slub.c:5113
Inline: True
Inline callers:
  - mm/slub.c:slab_debug_trace_release
Direct callers:
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff813a46f0-ffffffff813a4745: free_loc_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_loc_track(struct loc_track *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81425cfd)
Location: mm/slub.c:5230
Inline: True
Inline callers:
  - mm/slub.c:slab_debug_trace_release
Direct callers:
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff814247d0-ffffffff8142481c: free_loc_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_loc_track(struct loc_track *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145aebd)
Location: mm/slub.c:5245
Inline: True
Inline callers:
  - mm/slub.c:slab_debug_trace_release
Direct callers:
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff81459a70-ffffffff81459abc: free_loc_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_loc_track(struct loc_track *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814564dd)
Location: mm/slub.c:5856
Inline: True
Inline callers:
  - mm/slub.c:slab_debug_trace_release
Direct callers:
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff814549f0-ffffffff81454a3c: free_loc_track (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffff800010344068)
Location: mm/slub.c:4512
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffff800010344068-ffff8000103440b8: free_loc_track.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_loc_track(struct loc_track *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0549ea0)
Location: mm/slub.c:4512
Inline: False
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
c0549ea0-c0549ee4: free_loc_track (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (c000000000422a40)
Location: mm/slub.c:4512
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
c000000000422a40-c000000000422a98: free_loc_track.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffe0002387ea)
Location: mm/slub.c:4512
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffe0002387ea-ffffffe000238892: free_loc_track.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8129c9f0)
Location: mm/slub.c:4512
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff8129c9f0-ffffffff8129ca27: free_loc_track.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8128e580)
Location: mm/slub.c:4512
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff8128e580-ffffffff8128e5b7: free_loc_track.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8129a800)
Location: mm/slub.c:4512
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff8129a800-ffffffff8129a837: free_loc_track.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812aa6e0)
Location: mm/slub.c:4512
Inline: True
Direct callers:
  - mm/slub.c:list_locations
  - mm/slub.c:alloc_loc_track
```
**Symbols:**

```
ffffffff812aa6e0-ffffffff812aa717: free_loc_track.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
