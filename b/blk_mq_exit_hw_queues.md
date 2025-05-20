# Function: <code>blk_mq_exit_hw_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff813c38e0)
Location: block/blk-mq.c:1649
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_free_queue
```
**Symbols:**

```
ffffffff813c38e0-ffffffff813c39c7: blk_mq_exit_hw_queues.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8140ac31)
Location: block/blk-mq.c:1703
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814256a9)
Location: block/blk-mq.c:1734
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81433459)
Location: block/blk-mq.c:1901
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145f039)
Location: block/blk-mq.c:2036
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81492975)
Location: block/blk-mq.c:2105
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
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
In block/blk-mq.c (ffffffff814ac85b)
Location: block/blk-mq.c:2269
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_queue
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
In block/blk-mq.c (ffffffff814dab0b)
Location: block/blk-mq.c:2267
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff814f3ecb)
Location: block/blk-mq.c:2293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff815544fd)
Location: block/blk-mq.c:2482
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff81570c1c)
Location: block/blk-mq.c:2583
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff81578af7)
Location: block/blk-mq.c:2644
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff815ddc17)
Location: block/blk-mq.c:2700
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff8168b9a2)
Location: block/blk-mq.c:3458
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff8174a072)
Location: block/blk-mq.c:3622
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff81786770)
Location: block/blk-mq.c:3634
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff817c8e50)
Location: block/blk-mq.c:3650
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffff8000105f3748)
Location: block/blk-mq.c:2293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (c079f880)
Location: block/blk-mq.c:2293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (c00000000078b074)
Location: block/blk-mq.c:2293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffe000431d48)
Location: block/blk-mq.c:2293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff814ec4ab)
Location: block/blk-mq.c:2293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff814dc9fb)
Location: block/blk-mq.c:2293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff814e853b)
Location: block/blk-mq.c:2293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
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
In block/blk-mq.c (ffffffff815014db)
Location: block/blk-mq.c:2293
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
```
</details>
</li>
</ul>

## Differences
