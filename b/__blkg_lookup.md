# Function: <code>__blkg_lookup</code>

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
In block/blk-core.c (ffffffff813b61e0)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff813d7ca2)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff813daa83)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:blk_throtl_drain
```
```
In block/cfq-iosched.c (ffffffff813e185d)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-core.c (ffffffff813fb016)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff8141de9f)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81421d5c)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:tg_conf_updated
```
```
In block/cfq-iosched.c (ffffffff81427a8d)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-core.c (ffffffff81414ae1)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff8143945f)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8143cebc)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:tg_conf_updated
```
```
In block/cfq-iosched.c (ffffffff8144168d)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-core.c (ffffffff8142478e)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff81447a01)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8144c1f0)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
```
In block/cfq-iosched.c (ffffffff8145097d)
Location: include/linux/blk-cgroup.h:266
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-core.c (ffffffff8144d8c5)
Location: include/linux/blk-cgroup.h:262
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8145bf14)
Location: include/linux/blk-cgroup.h:262
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/blk-cgroup.c (ffffffff81474601)
Location: include/linux/blk-cgroup.h:262
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814788f9)
Location: include/linux/blk-cgroup.h:262
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
```
In block/cfq-iosched.c (ffffffff8147bf8b)
Location: include/linux/blk-cgroup.h:262
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-core.c (ffffffff814827fb)
Location: include/linux/blk-cgroup.h:263
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-sysfs.c (ffffffff814870e7)
Location: include/linux/blk-cgroup.h:263
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
```
```
In block/blk-mq.c (ffffffff8148eae3)
Location: include/linux/blk-cgroup.h:263
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/blk-cgroup.c (ffffffff814a87f7)
Location: include/linux/blk-cgroup.h:263
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814ad020)
Location: include/linux/blk-cgroup.h:263
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
```
In block/cfq-iosched.c (ffffffff814b107b)
Location: include/linux/blk-cgroup.h:263
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c324e)
Location: include/linux/blk-cgroup.h:349
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814c73b0)
Location: include/linux/blk-cgroup.h:349
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f1924)
Location: include/linux/blk-cgroup.h:356
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f5bd5)
Location: include/linux/blk-cgroup.h:356
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8150af15)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8150f34e)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156bf73)
Location: include/linux/blk-cgroup.h:336
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff8156c3af)
Location: include/linux/blk-cgroup.h:336
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff8156ee49)
Location: include/linux/blk-cgroup.h:336
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:blk_throtl_update_limit_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81586c81)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff81587176)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff81589bfe)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158d9a7)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff8158dfc6)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff815905fe)
Location: include/linux/blk-cgroup.h:326
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f3417)
Location: include/linux/blk-cgroup.h:331
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff815f3b35)
Location: include/linux/blk-cgroup.h:331
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff815f75a0)
Location: include/linux/blk-cgroup.h:331
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a49da)
Location: block/blk-cgroup.h:240
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff816a525a)
Location: block/blk-cgroup.h:240
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff816aa2df)
Location: block/blk-cgroup.h:240
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:throtl_can_upgrade
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060e824)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffff800010612f38)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b9030)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c07bd8b4)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:blk_throtl_update_limit_valid
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007abd6c)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c0000000007b1594)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe000446cbe)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffe00044a478)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815034f5)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8150792e)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f39b5)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f7dee)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814ff585)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815039be)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8151870a)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_rwstat_recursive_sum
  - block/blk-cgroup.c:blkg_lookup_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8151cf73)
Location: include/linux/blk-cgroup.h:358
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_drain
  - block/blk-throttle.c:throtl_upgrade_state
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
</ul>

## Differences
