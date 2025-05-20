# Function: <code>blkg_tryget</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498132)
Location: include/linux/blk-cgroup.h:500
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814c3285)
Location: include/linux/blk-cgroup.h:500
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (ffffffff814c5fd2)
Location: include/linux/blk-cgroup.h:507
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f1954)
Location: include/linux/blk-cgroup.h:507
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (ffffffff814de3d2)
Location: include/linux/blk-cgroup.h:509
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8150af49)
Location: include/linux/blk-cgroup.h:509
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (ffffffff8153d9ac)
Location: include/linux/blk-cgroup.h:478
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-cgroup.c (ffffffff8156bfd6)
Location: include/linux/blk-cgroup.h:478
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff81586ceb)
Location: include/linux/blk-cgroup.h:468
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff8158da31)
Location: include/linux/blk-cgroup.h:468
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
In block/blk-cgroup.c (ffffffff815f34a1)
Location: include/linux/blk-cgroup.h:473
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
In block/blk-cgroup.c (ffffffff816a4a1d)
Location: block/blk-cgroup.h:348
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff817637ad)
Location: block/blk-cgroup.h:332
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff817a284e)
Location: block/blk-cgroup.h:333
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff817e6390)
Location: block/blk-cgroup.h:332
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (ffff8000105db780)
Location: include/linux/blk-cgroup.h:509
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060e860)
Location: include/linux/blk-cgroup.h:509
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (c078835c)
Location: include/linux/blk-cgroup.h:509
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-cgroup.c (c07b906c)
Location: include/linux/blk-cgroup.h:509
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (c00000000076b690)
Location: include/linux/blk-cgroup.h:509
Inline: True
```
```
In block/blk-cgroup.c (c0000000007abdb0)
Location: include/linux/blk-cgroup.h:509
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (ffffffe00041e422)
Location: include/linux/blk-cgroup.h:509
Inline: True
```
```
In block/blk-cgroup.c (ffffffe000446cec)
Location: include/linux/blk-cgroup.h:509
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (ffffffff814d69b2)
Location: include/linux/blk-cgroup.h:509
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81503529)
Location: include/linux/blk-cgroup.h:509
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (ffffffff814c7372)
Location: include/linux/blk-cgroup.h:509
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f39e9)
Location: include/linux/blk-cgroup.h:509
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (ffffffff814d2a42)
Location: include/linux/blk-cgroup.h:509
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814ff5b9)
Location: include/linux/blk-cgroup.h:509
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (ffffffff814eb57a)
Location: include/linux/blk-cgroup.h:509
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8151873e)
Location: include/linux/blk-cgroup.h:509
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
```
</details>
</li>
</ul>

## Differences
