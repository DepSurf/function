# Function: <code>blkg_rwstat_reset</code>

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
In block/blk-cgroup.c (ffffffff813d8afb)
Location: include/linux/blk-cgroup.h:656
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
```
```
In block/cfq-iosched.c (ffffffff813ddf14)
Location: include/linux/blk-cgroup.h:656
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
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
In block/blk-cgroup.c (ffffffff8141e85c)
Location: include/linux/blk-cgroup.h:657
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
```
```
In block/cfq-iosched.c (ffffffff81424050)
Location: include/linux/blk-cgroup.h:657
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
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
In block/blk-cgroup.c (ffffffff81439e1c)
Location: include/linux/blk-cgroup.h:647
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
```
```
In block/cfq-iosched.c (ffffffff8143fa60)
Location: include/linux/blk-cgroup.h:647
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
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
In block/blk-cgroup.c (ffffffff8144768d)
Location: include/linux/blk-cgroup.h:647
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
```
```
In block/cfq-iosched.c (ffffffff8144ecc0)
Location: include/linux/blk-cgroup.h:647
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
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
In block/blk-cgroup.c (ffffffff8147427d)
Location: include/linux/blk-cgroup.h:643
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
```
```
In block/cfq-iosched.c (ffffffff8147ae00)
Location: include/linux/blk-cgroup.h:643
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
  - block/cfq-iosched.c:cfqg_stats_reset
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
Location: include/linux/blk-cgroup.h:661
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
```
```
In block/cfq-iosched.c (ffffffff814b0305)
Location: include/linux/blk-cgroup.h:661
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
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:727
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
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
Location: include/linux/blk-cgroup.h:670
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
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
Location: include/linux/blk-cgroup.h:672
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (0)
Location: include/linux/blk-cgroup.h:672
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
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
In block/blk-cgroup.c (c07b71d0)
Location: include/linux/blk-cgroup.h:672
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
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
In block/blk-cgroup.c (c0000000007aa1ac)
Location: include/linux/blk-cgroup.h:672
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
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
In block/blk-cgroup.c (ffffffe000445c42)
Location: include/linux/blk-cgroup.h:672
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
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
Location: include/linux/blk-cgroup.h:672
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
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
Location: include/linux/blk-cgroup.h:672
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
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
Location: include/linux/blk-cgroup.h:672
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
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
Location: include/linux/blk-cgroup.h:672
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_reset_stats
  - block/blk-cgroup.c:blkcg_reset_stats
```
</details>
</li>
</ul>

## Differences
