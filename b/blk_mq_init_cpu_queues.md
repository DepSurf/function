# Function: <code>blk_mq_init_cpu_queues</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c5287)
Location: block/blk-mq.c:1767
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff8140933e)
Location: block/blk-mq.c:1796
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff81423d30)
Location: block/blk-mq.c:1828
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff81432dfa)
Location: block/blk-mq.c:1988
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff8145e9c1)
Location: block/blk-mq.c:2126
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff81492314)
Location: block/blk-mq.c:2193
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff814abe05)
Location: block/blk-mq.c:2353
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff814da06a)
Location: block/blk-mq.c:2390
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff814f3411)
Location: block/blk-mq.c:2416
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_init_cpu_queues(struct request_queue *q, unsigned int nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154e720)
Location: block/blk-mq.c:2607
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8154e720-ffffffff8154e80b: blk_mq_init_cpu_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_init_cpu_queues(struct request_queue *q, unsigned int nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156ac00)
Location: block/blk-mq.c:2709
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8156ac00-ffffffff8156aceb: blk_mq_init_cpu_queues (STB_LOCAL)
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
In block/blk-mq.c (ffffffff81577f6a)
Location: block/blk-mq.c:2769
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff815dcee2)
Location: block/blk-mq.c:2825
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff8168aac8)
Location: block/blk-mq.c:3573
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff81749ca4)
Location: block/blk-mq.c:3737
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff817863b6)
Location: block/blk-mq.c:3749
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff817c8a8d)
Location: block/blk-mq.c:3765
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffff8000105f2c58)
Location: block/blk-mq.c:2416
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (c079ed84)
Location: block/blk-mq.c:2416
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (c00000000078a180)
Location: block/blk-mq.c:2416
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffe000431478)
Location: block/blk-mq.c:2416
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff814eb9f1)
Location: block/blk-mq.c:2416
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff814dbf41)
Location: block/blk-mq.c:2416
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff814e7a81)
Location: block/blk-mq.c:2416
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff81500a21)
Location: block/blk-mq.c:2416
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
