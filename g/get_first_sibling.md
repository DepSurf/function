# Function: <code>get_first_sibling</code>

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
In block/blk-mq-cpumap.c (ffffffff813c85ff)
Location: block/blk-mq-cpumap.c:23
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810e8e5b)
Location: kernel/irq/affinity.c:7
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_mask
```
```
In block/blk-mq-cpumap.c (ffffffff8140c85f)
Location: block/blk-mq-cpumap.c:23
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
  - block/blk-mq-cpumap.c:blk_mq_update_queue_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_first_sibling(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff81427b40)
Location: block/blk-mq-cpumap.c:23
Inline: False
Direct callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
**Symbols:**

```
ffffffff81427b40-ffffffff81427b7a: get_first_sibling (STB_LOCAL)
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
In block/blk-mq-cpumap.c (ffffffff81435041)
Location: block/blk-mq-cpumap.c:27
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff81460c51)
Location: block/blk-mq-cpumap.c:27
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff81494574)
Location: block/blk-mq-cpumap.c:22
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff814ae6a4)
Location: block/blk-mq-cpumap.c:23
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff814dc952)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff814f5dee)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff8155680e)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff8157305e)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff8157b093)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff815e039c)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff8168edca)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff8174d878)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
</details>
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
In block/blk-mq-cpumap.c (ffff8000105f6184)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (c07a1a80)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (c00000000078e280)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffe000433c6c)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff814ee3ce)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff814de91e)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff814ea45e)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
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
In block/blk-mq-cpumap.c (ffffffff8150342e)
Location: block/blk-mq-cpumap.c:24
Inline: True
Inline callers:
  - block/blk-mq-cpumap.c:blk_mq_map_queues
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
