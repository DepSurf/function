# Function: <code>blkg_lookup</code>

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
In block/blk-core.c (ffffffff813b61d0)
Location: include/linux/blk-cgroup.h:291
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff813e184e)
Location: include/linux/blk-cgroup.h:291
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
In block/blk-core.c (ffffffff813fb006)
Location: include/linux/blk-cgroup.h:291
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff81427a7e)
Location: include/linux/blk-cgroup.h:291
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
In block/blk-core.c (ffffffff81414ad1)
Location: include/linux/blk-cgroup.h:291
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff8144167e)
Location: include/linux/blk-cgroup.h:291
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
In block/blk-core.c (ffffffff8142477f)
Location: include/linux/blk-cgroup.h:291
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/cfq-iosched.c (ffffffff8145096e)
Location: include/linux/blk-cgroup.h:291
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
In block/blk-core.c (ffffffff8144d8b6)
Location: include/linux/blk-cgroup.h:287
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8145bf09)
Location: include/linux/blk-cgroup.h:287
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/cfq-iosched.c (ffffffff8147bf7c)
Location: include/linux/blk-cgroup.h:287
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
In block/blk-core.c (ffffffff814827ec)
Location: include/linux/blk-cgroup.h:288
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:get_request
```
```
In block/blk-sysfs.c (ffffffff814870dc)
Location: include/linux/blk-cgroup.h:288
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
```
```
In block/blk-mq.c (ffffffff8148ead8)
Location: include/linux/blk-cgroup.h:288
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/cfq-iosched.c (ffffffff814b106c)
Location: include/linux/blk-cgroup.h:288
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-cgroup.c (ffffffff814c324e)
Location: include/linux/blk-cgroup.h:373
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (ffffffff814f1924)
Location: include/linux/blk-cgroup.h:380
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (ffffffff8150af15)
Location: include/linux/blk-cgroup.h:382
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (ffffffff8156bf73)
Location: include/linux/blk-cgroup.h:360
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81586c81)
Location: include/linux/blk-cgroup.h:350
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (ffffffff8158d9a7)
Location: include/linux/blk-cgroup.h:350
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff815f3417)
Location: include/linux/blk-cgroup.h:355
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff816a49da)
Location: block/blk-cgroup.h:264
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8176376a)
Location: block/blk-cgroup.h:246
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff817640da)
Location: block/blk-cgroup.h:246
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff817693ac)
Location: block/blk-cgroup.h:246
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a2809)
Location: block/blk-cgroup.h:247
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff817a31a9)
Location: block/blk-cgroup.h:247
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff817a8562)
Location: block/blk-cgroup.h:247
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e634b)
Location: block/blk-cgroup.h:247
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-cgroup-rwstat.c (ffffffff817e6cf9)
Location: block/blk-cgroup.h:247
Inline: True
Inline callers:
  - block/blk-cgroup-rwstat.c:blkg_rwstat_recursive_sum
```
```
In block/blk-throttle.c (ffffffff817ec2df)
Location: block/blk-cgroup.h:247
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:blk_throtl_cancel_bios
  - block/blk-throttle.c:tg_conf_updated
  - block/blk-throttle.c:tg_conf_updated
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
In block/blk-cgroup.c (ffff80001060e824)
Location: include/linux/blk-cgroup.h:382
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (c07b9030)
Location: include/linux/blk-cgroup.h:382
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (c0000000007abd6c)
Location: include/linux/blk-cgroup.h:382
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (ffffffe000446cbe)
Location: include/linux/blk-cgroup.h:382
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (ffffffff815034f5)
Location: include/linux/blk-cgroup.h:382
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (ffffffff814f39b5)
Location: include/linux/blk-cgroup.h:382
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (ffffffff814ff585)
Location: include/linux/blk-cgroup.h:382
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
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
In block/blk-cgroup.c (ffffffff8151870a)
Location: include/linux/blk-cgroup.h:382
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_lookup_create
```
</details>
</li>
</ul>

## Differences
