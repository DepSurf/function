# Function: <code>do_shrink_slab</code>

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
In mm/vmscan.c (ffffffff811a05e5)
Location: mm/vmscan.c:266
Inline: True
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
In mm/vmscan.c (ffffffff811b69b5)
Location: mm/vmscan.c:280
Inline: True
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
In mm/vmscan.c (ffffffff811c6f68)
Location: mm/vmscan.c:307
Inline: True
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
In mm/vmscan.c (ffffffff811cf705)
Location: mm/vmscan.c:308
Inline: True
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
In mm/vmscan.c (ffffffff811e4b25)
Location: mm/vmscan.c:312
Inline: True
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
In mm/vmscan.c (ffffffff812062ff)
Location: mm/vmscan.c:360
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:452
Inline: False
```
**Symbols:**

```
ffffffff81218a40-ffffffff81218cf2: do_shrink_slab (STB_LOCAL)
ffffffff8121fc06-ffffffff8121fc29: do_shrink_slab.cold.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:464
Inline: False
```
**Symbols:**

```
ffffffff81228480-ffffffff81228714: do_shrink_slab (STB_LOCAL)
ffffffff8122f3a9-ffffffff8122f3d1: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:462
Inline: False
```
**Symbols:**

```
ffffffff81236320-ffffffff812365b4: do_shrink_slab (STB_LOCAL)
ffffffff8123d539-ffffffff8123d561: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:419
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
**Symbols:**

```
ffffffff81264e90-ffffffff81265123: do_shrink_slab (STB_LOCAL)
ffffffff8126ad9a-ffffffff8126adc5: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:412
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
**Symbols:**

```
ffffffff8126f810-ffffffff8126fa4b: do_shrink_slab (STB_LOCAL)
ffffffff81be6e6c-ffffffff81be6e97: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812734f0)
Location: mm/vmscan.c:646
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
**Symbols:**

```
ffffffff812734f0-ffffffff81273794: do_shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:692
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
**Symbols:**

```
ffffffff812b07c0-ffffffff812b0a78: do_shrink_slab (STB_LOCAL)
ffffffff81cba62d-ffffffff81cba670: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:704
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
**Symbols:**

```
ffffffff8130c040-ffffffff8130c353: do_shrink_slab (STB_LOCAL)
ffffffff81e6bf5e-ffffffff81e6bfa7: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:781
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
**Symbols:**

```
ffffffff81378310-ffffffff81378615: do_shrink_slab (STB_LOCAL)
ffffffff820628f2-ffffffff8206293b: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:834
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
  - mm/vmscan.c:shrink_slab_memcg
```
**Symbols:**

```
ffffffff813ac610-ffffffff813ac913: do_shrink_slab (STB_LOCAL)
ffffffff820e20b3-ffffffff820e20ed: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/shrinker.c (0)
Location: mm/shrinker.c:369
Inline: False
Direct callers:
  - mm/shrinker.c:shrink_slab
  - mm/shrinker.c:shrink_slab_memcg
  - mm/shrinker.c:shrink_slab_memcg
```
**Symbols:**

```
ffffffff813e3ec0-ffffffff813e429b: do_shrink_slab (STB_LOCAL)
ffffffff821bedaa-ffffffff821bede4: do_shrink_slab.cold (STB_LOCAL)
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
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c7bc0)
Location: mm/vmscan.c:462
Inline: False
```
**Symbols:**

```
ffff8000102c7bc0-ffff8000102c7f10: do_shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f1620)
Location: mm/vmscan.c:462
Inline: False
```
**Symbols:**

```
c04f1620-c04f1a24: do_shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c0000000003827f0)
Location: mm/vmscan.c:462
Inline: False
```
**Symbols:**

```
c0000000003827f0-c000000000382b98: do_shrink_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e6938)
Location: mm/vmscan.c:462
Inline: False
```
**Symbols:**

```
ffffffe0001e6938-ffffffe0001e6bd4: do_shrink_slab (STB_LOCAL)
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
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:462
Inline: False
```
**Symbols:**

```
ffffffff8122e970-ffffffff8122ec04: do_shrink_slab (STB_LOCAL)
ffffffff81235b89-ffffffff81235bb1: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:462
Inline: False
```
**Symbols:**

```
ffffffff81221a30-ffffffff81221cc4: do_shrink_slab (STB_LOCAL)
ffffffff81228bed-ffffffff81228c15: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:462
Inline: False
```
**Symbols:**

```
ffffffff8122c710-ffffffff8122c9a4: do_shrink_slab (STB_LOCAL)
ffffffff81233929-ffffffff81233951: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long unsigned int do_shrink_slab(struct shrink_control *shrinkctl, struct shrinker *shrinker, int priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:462
Inline: False
```
**Symbols:**

```
ffffffff8123bb00-ffffffff8123bdd3: do_shrink_slab (STB_LOCAL)
ffffffff81242e57-ffffffff81242e7f: do_shrink_slab.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
