# Function: <code>blk_mq_sched_alloc_tags</code>

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
In block/blk-mq-sched.c (ffffffff81435540)
Location: block/blk-mq-sched.c:432
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_init_hctx
```
**Symbols:**

```
ffffffff81435540-ffffffff814355bd: blk_mq_sched_alloc_tags.isra.10 (STB_LOCAL)
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
In block/blk-mq-sched.c (ffffffff81461310)
Location: block/blk-mq-sched.c:491
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_init_hctx
```
**Symbols:**

```
ffffffff81461310-ffffffff8146138d: blk_mq_sched_alloc_tags.isra.9 (STB_LOCAL)
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
In block/blk-mq-sched.c (ffffffff81494d20)
Location: block/blk-mq-sched.c:507
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_init_hctx
```
**Symbols:**

```
ffffffff81494d20-ffffffff81494dab: blk_mq_sched_alloc_tags.isra.12 (STB_LOCAL)
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
In block/blk-mq-sched.c (ffffffff814af4b5)
Location: block/blk-mq-sched.c:446
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffff814dd819)
Location: block/blk-mq-sched.c:460
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
In block/blk-mq-sched.c (ffffffff814f6ca9)
Location: block/blk-mq-sched.c:490
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
In block/blk-mq-sched.c (ffffffff81557779)
Location: block/blk-mq-sched.c:555
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
In block/blk-mq-sched.c (ffffffff81573d8d)
Location: block/blk-mq-sched.c:519
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
In block/blk-mq-sched.c (ffffffff8157be19)
Location: block/blk-mq-sched.c:521
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
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
In block/blk-mq-sched.c (ffffffff815e1279)
Location: block/blk-mq-sched.c:518
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
</details>
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
In block/blk-mq-sched.c (ffff8000105f73b8)
Location: block/blk-mq-sched.c:490
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
In block/blk-mq-sched.c (c07a2af0)
Location: block/blk-mq-sched.c:490
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
In block/blk-mq-sched.c (c00000000078fa54)
Location: block/blk-mq-sched.c:490
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
In block/blk-mq-sched.c (ffffffe000434a2e)
Location: block/blk-mq-sched.c:490
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
In block/blk-mq-sched.c (ffffffff814ef289)
Location: block/blk-mq-sched.c:490
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
In block/blk-mq-sched.c (ffffffff814df7c9)
Location: block/blk-mq-sched.c:490
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
In block/blk-mq-sched.c (ffffffff814eb319)
Location: block/blk-mq-sched.c:490
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
In block/blk-mq-sched.c (ffffffff81504329)
Location: block/blk-mq-sched.c:490
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
</details>
</li>
</ul>

## Differences
