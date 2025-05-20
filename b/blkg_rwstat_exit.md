# Function: <code>blkg_rwstat_exit</code>

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
In block/blk-cgroup.c (ffffffff813d6fd5)
Location: include/linux/blk-cgroup.h:582
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
```
```
In block/cfq-iosched.c (ffffffff813ddfed)
Location: include/linux/blk-cgroup.h:582
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
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
In block/blk-cgroup.c (ffffffff8141cd0c)
Location: include/linux/blk-cgroup.h:582
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
```
```
In block/cfq-iosched.c (ffffffff8142413b)
Location: include/linux/blk-cgroup.h:582
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
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
In block/blk-cgroup.c (ffffffff814382dc)
Location: include/linux/blk-cgroup.h:573
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_free
  - block/blk-cgroup.c:blkg_free
```
```
In block/cfq-iosched.c (ffffffff8143fb4b)
Location: include/linux/blk-cgroup.h:573
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
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
In block/blk-cgroup.c (ffffffff814462db)
Location: include/linux/blk-cgroup.h:573
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8144ed9d)
Location: include/linux/blk-cgroup.h:573
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
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
In block/blk-cgroup.c (ffffffff81472e91)
Location: include/linux/blk-cgroup.h:569
Inline: True
```
```
In block/cfq-iosched.c (ffffffff8147aedd)
Location: include/linux/blk-cgroup.h:569
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
  - block/cfq-iosched.c:cfqg_stats_exit
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
In block/blk-cgroup.c (ffffffff814a7261)
Location: include/linux/blk-cgroup.h:587
Inline: True
```
```
In block/cfq-iosched.c (ffffffff814b03e5)
Location: include/linux/blk-cgroup.h:587
Inline: True
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
In block/blk-cgroup.c (ffffffff814c1373)
Location: include/linux/blk-cgroup.h:651
Inline: True
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
In block/blk-cgroup.c (ffffffff814efb0a)
Location: include/linux/blk-cgroup.h:595
Inline: True
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
In block/blk-cgroup.c (ffffffff81508fba)
Location: include/linux/blk-cgroup.h:597
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkg_rwstat_exit(struct blkg_rwstat *rwstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff8156c1c0)
Location: block/blk-cgroup-rwstat.c:25
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff8156c1c0-ffffffff8156c1ec: blkg_rwstat_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkg_rwstat_exit(struct blkg_rwstat *rwstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff81586f60)
Location: block/blk-cgroup-rwstat.c:25
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff81586f60-ffffffff81586f8c: blkg_rwstat_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blkg_rwstat_exit(struct blkg_rwstat *rwstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff8158ddb0)
Location: block/blk-cgroup-rwstat.c:25
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff8158ddb0-ffffffff8158dddc: blkg_rwstat_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blkg_rwstat_exit(struct blkg_rwstat *rwstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff815f38d0)
Location: block/blk-cgroup-rwstat.c:25
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff815f38d0-ffffffff815f3911: blkg_rwstat_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blkg_rwstat_exit(struct blkg_rwstat *rwstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff816a4fd0)
Location: block/blk-cgroup-rwstat.c:25
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff816a4fd0-ffffffff816a5019: blkg_rwstat_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkg_rwstat_exit(struct blkg_rwstat *rwstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff81763e20)
Location: block/blk-cgroup-rwstat.c:25
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff81763e20-ffffffff81763e69: blkg_rwstat_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkg_rwstat_exit(struct blkg_rwstat *rwstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff817a2eb0)
Location: block/blk-cgroup-rwstat.c:25
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff817a2eb0-ffffffff817a2ef9: blkg_rwstat_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkg_rwstat_exit(struct blkg_rwstat *rwstat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff817e6a00)
Location: block/blk-cgroup-rwstat.c:25
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_free
  - block/blk-throttle.c:throtl_pd_alloc
```
**Symbols:**

```
ffffffff817e6a00-ffffffff817e6a4e: blkg_rwstat_exit (STB_GLOBAL)
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
In block/blk-cgroup.c (ffff80001060be6c)
Location: include/linux/blk-cgroup.h:597
Inline: True
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
In block/blk-cgroup.c (c07b700c)
Location: include/linux/blk-cgroup.h:597
Inline: True
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
In block/blk-cgroup.c (c0000000007a89a4)
Location: include/linux/blk-cgroup.h:597
Inline: True
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
In block/blk-cgroup.c (ffffffe000444bc4)
Location: include/linux/blk-cgroup.h:597
Inline: True
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
In block/blk-cgroup.c (ffffffff8150159a)
Location: include/linux/blk-cgroup.h:597
Inline: True
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
In block/blk-cgroup.c (ffffffff814f1aaa)
Location: include/linux/blk-cgroup.h:597
Inline: True
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
In block/blk-cgroup.c (ffffffff814fd62a)
Location: include/linux/blk-cgroup.h:597
Inline: True
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
In block/blk-cgroup.c (ffffffff81516afa)
Location: include/linux/blk-cgroup.h:597
Inline: True
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
