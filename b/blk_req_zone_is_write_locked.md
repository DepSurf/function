# Function: <code>blk_req_zone_is_write_locked</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff814ad9e8)
Location: include/linux/blkdev.h:1997
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff814c8166)
Location: include/linux/blkdev.h:1685
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff814f6a07)
Location: include/linux/blkdev.h:1709
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff815148b7)
Location: include/linux/blkdev.h:1740
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff815758c8)
Location: include/linux/blkdev.h:1803
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
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
In block/mq-deadline.c (ffffffff815926c2)
Location: include/linux/blkdev.h:1903
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
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
In block/mq-deadline.c (ffffffff815994e4)
Location: include/linux/blkdev.h:1899
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
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
In block/mq-deadline.c (ffffffff816017f5)
Location: include/linux/blkdev.h:1897
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff816b4100)
Location: include/linux/blk-mq.h:1149
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff81773b92)
Location: include/linux/blk-mq.h:1180
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff817b3143)
Location: include/linux/blk-mq.h:1192
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff817f6cd8)
Location: include/linux/blk-mq.h:1189
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffff800010619530)
Location: include/linux/blkdev.h:1740
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (c07c4068)
Location: include/linux/blkdev.h:1740
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (c0000000007b8d10)
Location: include/linux/blkdev.h:1740
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffe00044f256)
Location: include/linux/blkdev.h:1740
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff8150ce97)
Location: include/linux/blkdev.h:1740
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff814fd2c7)
Location: include/linux/blkdev.h:1740
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff81508f27)
Location: include/linux/blkdev.h:1740
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff815226c7)
Location: include/linux/blkdev.h:1740
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
```
</details>
</li>
</ul>

## Differences
