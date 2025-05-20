# Function: <code>blkg_rwstat_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d7a7f)
Location: include/linux/blk-cgroup.h:566
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/cfq-iosched.c (ffffffff813df885)
Location: include/linux/blk-cgroup.h:566
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141d77f)
Location: include/linux/blk-cgroup.h:566
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/cfq-iosched.c (ffffffff814251ef)
Location: include/linux/blk-cgroup.h:566
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81438d3f)
Location: include/linux/blk-cgroup.h:557
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/cfq-iosched.c (ffffffff814424cf)
Location: include/linux/blk-cgroup.h:557
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8144653a)
Location: include/linux/blk-cgroup.h:557
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/cfq-iosched.c (ffffffff814516eb)
Location: include/linux/blk-cgroup.h:557
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8147310a)
Location: include/linux/blk-cgroup.h:553
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/cfq-iosched.c (ffffffff8147c619)
Location: include/linux/blk-cgroup.h:553
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:571
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/cfq-iosched.c (ffffffff814b0d24)
Location: include/linux/blk-cgroup.h:571
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:635
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:579
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:581
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkg_rwstat_init(struct blkg_rwstat *rwstat, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff8156c120)
Location: block/blk-cgroup-rwstat.c:8
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff8156c120-ffffffff8156c1bc: blkg_rwstat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkg_rwstat_init(struct blkg_rwstat *rwstat, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff81586ec0)
Location: block/blk-cgroup-rwstat.c:8
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff81586ec0-ffffffff81586f5c: blkg_rwstat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkg_rwstat_init(struct blkg_rwstat *rwstat, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff8158dd10)
Location: block/blk-cgroup-rwstat.c:8
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff8158dd10-ffffffff8158ddac: blkg_rwstat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkg_rwstat_init(struct blkg_rwstat *rwstat, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff815f37f0)
Location: block/blk-cgroup-rwstat.c:8
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff815f37f0-ffffffff815f38c5: blkg_rwstat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkg_rwstat_init(struct blkg_rwstat *rwstat, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff816a4ee0)
Location: block/blk-cgroup-rwstat.c:8
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff816a4ee0-ffffffff816a4fc4: blkg_rwstat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkg_rwstat_init(struct blkg_rwstat *rwstat, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff81763d20)
Location: block/blk-cgroup-rwstat.c:8
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff81763d20-ffffffff81763e04: blkg_rwstat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkg_rwstat_init(struct blkg_rwstat *rwstat, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff817a2d90)
Location: block/blk-cgroup-rwstat.c:8
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff817a2d90-ffffffff817a2e95: blkg_rwstat_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkg_rwstat_init(struct blkg_rwstat *rwstat, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff817e68d0)
Location: block/blk-cgroup-rwstat.c:8
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_alloc
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff817e68d0-ffffffff817e69e2: blkg_rwstat_init (STB_GLOBAL)
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:581
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:581
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:581
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (ffffffe000444df2)
Location: include/linux/blk-cgroup.h:581
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:581
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:581
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:581
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:581
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
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
