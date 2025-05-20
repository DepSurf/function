# Function: <code>blkcg_css</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8149835a)
Location: include/linux/blk-cgroup.h:240
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In block/bio.c (ffffffff814c61da)
Location: include/linux/blk-cgroup.h:247
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In block/bio.c (ffffffff814de5da)
Location: include/linux/blk-cgroup.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In block/bio.c (ffffffff8153eac6)
Location: include/linux/blk-cgroup.h:227
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In fs/io_uring.c (ffffffff81396980)
Location: include/linux/blk-cgroup.h:217
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:io_grab_identity
  - fs/io_uring.c:io_grab_identity
  - fs/io_uring.c:io_init_identity
  - fs/io_uring.c:io_init_identity
```
```
In block/blk-cgroup.c (ffffffff815864af)
Location: include/linux/blk-cgroup.h:217
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_associate_blkg
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
In block/blk-cgroup.c (ffffffff8158cebf)
Location: include/linux/blk-cgroup.h:217
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_associate_blkg
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
In block/blk-cgroup.c (ffffffff815f271f)
Location: include/linux/blk-cgroup.h:222
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_associate_blkg
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
In block/blk-cgroup.c (ffffffff816a4e6f)
Location: block/blk-cgroup.c:69
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff81763c9f)
Location: block/blk-cgroup.c:101
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff817a2d0f)
Location: block/blk-cgroup.c:103
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/blk-cgroup.c (ffffffff817e684f)
Location: block/blk-cgroup.c:103
Inline: True
Inline callers:
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:blk_cgroup_congested
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
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
In block/bio.c (ffff8000105dba34)
Location: include/linux/blk-cgroup.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In block/bio.c (c07885c8)
Location: include/linux/blk-cgroup.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In block/bio.c (c00000000076b9e0)
Location: include/linux/blk-cgroup.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In block/bio.c (ffffffe00041e652)
Location: include/linux/blk-cgroup.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In block/bio.c (ffffffff814d6bba)
Location: include/linux/blk-cgroup.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In block/bio.c (ffffffff814c757a)
Location: include/linux/blk-cgroup.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In block/bio.c (ffffffff814d2c4a)
Location: include/linux/blk-cgroup.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
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
In block/bio.c (ffffffff814eb7d7)
Location: include/linux/blk-cgroup.h:249
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
```
</details>
</li>
</ul>

## Differences
