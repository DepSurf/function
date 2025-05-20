# Function: <code>blkg_rwstat_recursive_sum</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct blkg_rwstat blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d80f0)
Location: block/blk-cgroup.c:740
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
  - block/cfq-iosched.c:cfqg_prfill_sectors_recursive
```
**Symbols:**

```
ffffffff813d80f0-ffffffff813d82a8: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct blkg_rwstat blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141de20)
Location: block/blk-cgroup.c:740
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
  - block/cfq-iosched.c:cfqg_prfill_sectors_recursive
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff8141de20-ffffffff8141dfea: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct blkg_rwstat blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814393e0)
Location: block/blk-cgroup.c:741
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
  - block/cfq-iosched.c:cfqg_prfill_sectors_recursive
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff814393e0-ffffffff814395aa: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct blkg_rwstat blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81446b70)
Location: block/blk-cgroup.c:742
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
  - block/cfq-iosched.c:cfqg_prfill_sectors_recursive
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff81446b70-ffffffff81446d28: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct blkg_rwstat blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81473750)
Location: block/blk-cgroup.c:742
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
  - block/cfq-iosched.c:cfqg_prfill_sectors_recursive
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff81473750-ffffffff81473908: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct blkg_rwstat blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a7780)
Location: block/blk-cgroup.c:753
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
  - block/cfq-iosched.c:cfqg_prfill_sectors_recursive
  - block/cfq-iosched.c:cfqg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff814a7780-ffffffff814a791f: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct blkg_rwstat blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c1910)
Location: block/blk-cgroup.c:746
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
ffffffff814c1910-ffffffff814c1aac: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814eff90)
Location: block/blk-cgroup.c:715
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
ffffffff814eff90-ffffffff814f00a6: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81509440)
Location: block/blk-cgroup.c:715
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
ffffffff81509440-ffffffff81509556: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff8156c350)
Location: block/blk-cgroup-rwstat.c:103
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff8156c350-ffffffff8156c466: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff815870f0)
Location: block/blk-cgroup-rwstat.c:103
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff815870f0-ffffffff8158723d: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup-rwstat.c (ffffffff8158df40)
Location: block/blk-cgroup-rwstat.c:103
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff8158df40-ffffffff8158e088: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-cgroup-rwstat.c (0)
Location: block/blk-cgroup-rwstat.c:103
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff81cd9c50-ffffffff81cd9c6d: blkg_rwstat_recursive_sum.cold (STB_LOCAL)
ffffffff815f3ab0-ffffffff815f3c47: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-cgroup-rwstat.c (0)
Location: block/blk-cgroup-rwstat.c:103
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff81e8d718-ffffffff81e8d735: blkg_rwstat_recursive_sum.cold (STB_LOCAL)
ffffffff816a51d0-ffffffff816a5385: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-cgroup-rwstat.c (0)
Location: block/blk-cgroup-rwstat.c:103
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff82076c9c-ffffffff82076cb9: blkg_rwstat_recursive_sum.cold (STB_LOCAL)
ffffffff81764050-ffffffff8176421b: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-cgroup-rwstat.c (0)
Location: block/blk-cgroup-rwstat.c:103
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff820f6b1f-ffffffff820f6b3c: blkg_rwstat_recursive_sum.cold (STB_LOCAL)
ffffffff817a3120-ffffffff817a3355: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-cgroup-rwstat.c (0)
Location: block/blk-cgroup-rwstat.c:103
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_prfill_rwstat_recursive
```
**Symbols:**

```
ffffffff821d3f6d-ffffffff821d3f8a: blkg_rwstat_recursive_sum.cold (STB_LOCAL)
ffffffff817e6c70-ffffffff817e6ea5: blkg_rwstat_recursive_sum (STB_GLOBAL)
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
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060c108)
Location: block/blk-cgroup.c:715
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
ffff80001060c108-ffff80001060c220: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b72d8)
Location: block/blk-cgroup.c:715
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
c07b72d8-c07b7420: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007a9010)
Location: block/blk-cgroup.c:715
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
c0000000007a9010-c0000000007a91c8: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe0004450ec)
Location: block/blk-cgroup.c:715
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
ffffffe0004450ec-ffffffe0004451e4: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81501a20)
Location: block/blk-cgroup.c:715
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
ffffffff81501a20-ffffffff81501b36: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f1f30)
Location: block/blk-cgroup.c:715
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
ffffffff814f1f30-ffffffff814f2046: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814fdab0)
Location: block/blk-cgroup.c:715
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
ffffffff814fdab0-ffffffff814fdbc6: blkg_rwstat_recursive_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blkg_rwstat_recursive_sum(struct blkcg_gq *blkg, struct blkcg_policy *pol, int off, struct blkg_rwstat_sample *sum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81517070)
Location: block/blk-cgroup.c:715
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkcg_print_stat
  - block/blk-cgroup.c:blkg_prfill_rwstat_field_recursive
```
**Symbols:**

```
ffffffff81517070-ffffffff81517191: blkg_rwstat_recursive_sum (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blkg_rwstat_sample *sum</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct blkg_rwstat</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
