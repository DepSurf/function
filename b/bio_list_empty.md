# Function: <code>bio_list_empty</code>

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
In block/bio.c (0)
Location: include/linux/bio.h:601
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:601
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:553
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:553
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:555
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:555
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:574
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:574
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:578
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:578
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:621
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:621
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:583
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:583
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:579
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:579
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:579
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:580
Inline: True
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
In block/bio.c (ffffffff8153f0fc)
Location: include/linux/bio.h:570
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-cgroup.c (ffffffff8156ace2)
Location: include/linux/bio.h:570
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8156d738)
Location: include/linux/bio.h:570
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff8155b8ec)
Location: include/linux/bio.h:572
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-cgroup.c (ffffffff81585ad2)
Location: include/linux/bio.h:572
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff81587d88)
Location: include/linux/bio.h:572
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff81563f64)
Location: include/linux/bio.h:575
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-cgroup.c (ffffffff8158c4a2)
Location: include/linux/bio.h:575
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8158ebd8)
Location: include/linux/bio.h:575
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff815c8144)
Location: include/linux/bio.h:536
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-cgroup.c (ffffffff815f1ad2)
Location: include/linux/bio.h:536
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff815f4c38)
Location: include/linux/bio.h:536
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff81672e52)
Location: include/linux/bio.h:529
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-cgroup.c (ffffffff816a3212)
Location: include/linux/bio.h:529
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff816a6687)
Location: include/linux/bio.h:529
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff8172e972)
Location: include/linux/bio.h:529
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-cgroup.c (ffffffff81761e72)
Location: include/linux/bio.h:529
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff81765697)
Location: include/linux/bio.h:529
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff8176aba2)
Location: include/linux/bio.h:542
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-cgroup.c (ffffffff817a0ff8)
Location: include/linux/bio.h:542
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff817a4757)
Location: include/linux/bio.h:542
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff817ad032)
Location: include/linux/bio.h:557
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-cgroup.c (ffffffff817e4b48)
Location: include/linux/bio.h:557
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff817e8327)
Location: include/linux/bio.h:557
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
```
</details>
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
In block/bio.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:580
Inline: True
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
In block/bio.c (c078963c)
Location: include/linux/bio.h:580
Inline: True
Inline callers:
  - block/bio.c:bio_alloc_bioset
  - block/bio.c:bio_alloc_bioset
```
```
In block/blk-cgroup.c (c07b7ee8)
Location: include/linux/bio.h:580
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c07ba5a0)
Location: include/linux/bio.h:580
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:580
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:580
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:580
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:580
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:580
Inline: True
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
In block/bio.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:580
Inline: True
```
```
In block/blk-throttle.c (0)
Location: include/linux/bio.h:580
Inline: True
```
</details>
</li>
</ul>

## Differences
