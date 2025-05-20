# Function: <code>blkg_rwstat_add</code>

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
In block/blk-core.c (ffffffff813b622d)
Location: include/linux/blk-cgroup.h:599
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/cfq-iosched.c (ffffffff813deeb7)
Location: include/linux/blk-cgroup.h:599
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_remove_request
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
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
In block/blk-core.c (ffffffff813fb067)
Location: include/linux/blk-cgroup.h:600
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/cfq-iosched.c (ffffffff8142b29f)
Location: include/linux/blk-cgroup.h:600
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_remove_request
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
In block/blk-core.c (ffffffff81414b32)
Location: include/linux/blk-cgroup.h:590
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/cfq-iosched.c (ffffffff81445142)
Location: include/linux/blk-cgroup.h:590
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_remove_request
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
In block/blk-core.c (ffffffff814247e0)
Location: include/linux/blk-cgroup.h:590
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/cfq-iosched.c (ffffffff81454376)
Location: include/linux/blk-cgroup.h:590
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_remove_request
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
In block/blk-core.c (ffffffff8144d917)
Location: include/linux/blk-cgroup.h:586
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/cfq-iosched.c (ffffffff8147fc6e)
Location: include/linux/blk-cgroup.h:586
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_remove_request
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
In block/blk-core.c (ffffffff8148284d)
Location: include/linux/blk-cgroup.h:604
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
```
In block/cfq-iosched.c (ffffffff814b462d)
Location: include/linux/blk-cgroup.h:604
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_merged_requests
  - block/cfq-iosched.c:cfq_bio_merged
  - block/cfq-iosched.c:cfq_remove_request
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
In block/blk-core.c (ffffffff8149d5c1)
Location: include/linux/blk-cgroup.h:668
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814cb803)
Location: include/linux/blk-cgroup.h:612
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814e4ac6)
Location: include/linux/blk-cgroup.h:614
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-throttle.c (ffffffff8156fed7)
Location: block/blk-cgroup-rwstat.h:61
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff8158ad1a)
Location: block/blk-cgroup-rwstat.h:61
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff81591805)
Location: block/blk-cgroup-rwstat.h:61
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff815f8a48)
Location: block/blk-cgroup-rwstat.h:61
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff816aabc2)
Location: block/blk-cgroup-rwstat.h:61
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817695c3)
Location: block/blk-cgroup-rwstat.h:61
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817720d2)
Location: block/blk-cgroup-rwstat.h:61
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b437c)
Location: block/blk-cgroup-rwstat.h:61
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
  - block/blk-core.c:submit_bio_noacct
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
In block/blk-core.c (ffff8000105e2e08)
Location: include/linux/blk-cgroup.h:614
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (c078f188)
Location: include/linux/blk-cgroup.h:614
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (c0000000007753e0)
Location: include/linux/blk-cgroup.h:614
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffe0004240ce)
Location: include/linux/blk-cgroup.h:614
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814dd0a6)
Location: include/linux/blk-cgroup.h:614
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814cda51)
Location: include/linux/blk-cgroup.h:614
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814d9136)
Location: include/linux/blk-cgroup.h:614
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
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
In block/blk-core.c (ffffffff814f1d4f)
Location: include/linux/blk-cgroup.h:614
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:generic_make_request_checks
```
</details>
</li>
</ul>

## Differences
