# Function: <code>blkg_stat_read</code>

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
In block/blk-cgroup.c (ffffffff813d716f)
Location: include/linux/blk-cgroup.h:537
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_prfill_stat
  - block/blk-cgroup.c:blkg_stat_recursive_sum
```
```
In block/cfq-iosched.c (ffffffff813e2c4a)
Location: include/linux/blk-cgroup.h:537
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
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
In block/blk-cgroup.c (ffffffff8141ddb5)
Location: include/linux/blk-cgroup.h:537
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
```
```
In block/cfq-iosched.c (ffffffff81428e9a)
Location: include/linux/blk-cgroup.h:537
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
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
In block/blk-cgroup.c (ffffffff81439375)
Location: include/linux/blk-cgroup.h:528
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
```
```
In block/cfq-iosched.c (ffffffff81440e9a)
Location: include/linux/blk-cgroup.h:528
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
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
In block/blk-cgroup.c (ffffffff81446af7)
Location: include/linux/blk-cgroup.h:528
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
```
```
In block/cfq-iosched.c (ffffffff81450178)
Location: include/linux/blk-cgroup.h:528
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
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
In block/blk-cgroup.c (ffffffff814736d7)
Location: include/linux/blk-cgroup.h:524
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
```
```
In block/cfq-iosched.c (ffffffff8147eb38)
Location: include/linux/blk-cgroup.h:524
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
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
In block/blk-cgroup.c (ffffffff814a7716)
Location: include/linux/blk-cgroup.h:542
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
```
```
In block/cfq-iosched.c (ffffffff814b2c30)
Location: include/linux/blk-cgroup.h:542
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_pd_offline
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
In block/blk-cgroup.c (ffffffff814c18a3)
Location: include/linux/blk-cgroup.h:606
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_stat_recursive_sum
  - block/blk-cgroup.c:blkg_prfill_stat
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
