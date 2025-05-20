# Function: <code>blk_mq_sched_free_tags</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814354a0)
Location: block/blk-mq-sched.c:421
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_exit_hctx
  - block/blk-mq-sched.c:blk_mq_sched_init_hctx
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
ffffffff814354a0-ffffffff814354d1: blk_mq_sched_free_tags.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81461270)
Location: block/blk-mq-sched.c:480
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_exit_hctx
  - block/blk-mq-sched.c:blk_mq_sched_init_hctx
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
ffffffff81461270-ffffffff814612a1: blk_mq_sched_free_tags.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81494c90)
Location: block/blk-mq-sched.c:496
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_exit_hctx
  - block/blk-mq-sched.c:blk_mq_sched_init_hctx
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
```
**Symbols:**

```
ffffffff81494c90-ffffffff81494cc0: blk_mq_sched_free_tags.isra.11 (STB_LOCAL)
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
In block/blk-mq-sched.c (ffffffff814af4e9)
Location: block/blk-mq-sched.c:435
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_tags_teardown
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
In block/blk-mq-sched.c (ffffffff814dd84f)
Location: block/blk-mq-sched.c:449
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffff814f6cdf)
Location: block/blk-mq-sched.c:479
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffff815577af)
Location: block/blk-mq-sched.c:544
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffff81573dc7)
Location: block/blk-mq-sched.c:506
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffff8157be53)
Location: block/blk-mq-sched.c:508
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
</details>
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
In block/blk-mq-sched.c (ffff8000105f73e0)
Location: block/blk-mq-sched.c:479
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (c07a2b1c)
Location: block/blk-mq-sched.c:479
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (c00000000078fa8c)
Location: block/blk-mq-sched.c:479
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffe000434a64)
Location: block/blk-mq-sched.c:479
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffff814ef2bf)
Location: block/blk-mq-sched.c:479
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffff814df7ff)
Location: block/blk-mq-sched.c:479
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffff814eb34f)
Location: block/blk-mq-sched.c:479
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffff8150435f)
Location: block/blk-mq-sched.c:479
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
</details>
</li>
</ul>

## Differences
