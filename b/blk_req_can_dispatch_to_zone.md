# Function: <code>blk_req_can_dispatch_to_zone</code>

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
In block/deadline-iosched.c (ffffffff814ad9dc)
Location: include/linux/blkdev.h:2003
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
In block/mq-deadline.c (ffffffff814c8143)
Location: include/linux/blkdev.h:1691
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff814f69e5)
Location: include/linux/blkdev.h:1715
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff81514895)
Location: include/linux/blkdev.h:1746
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff815758a3)
Location: include/linux/blkdev.h:1809
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
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
In block/mq-deadline.c (ffffffff8159269f)
Location: include/linux/blkdev.h:1909
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
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
In block/mq-deadline.c (ffffffff815994c1)
Location: include/linux/blkdev.h:1905
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_fifo_request
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
In block/mq-deadline.c (ffffffff816017dc)
Location: include/linux/blkdev.h:1903
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff816b40e7)
Location: include/linux/blk-mq.h:1155
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff81773b78)
Location: include/linux/blk-mq.h:1186
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff817b3137)
Location: include/linux/blk-mq.h:1198
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff817f6cc8)
Location: include/linux/blk-mq.h:1195
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffff800010619528)
Location: include/linux/blkdev.h:1746
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (c07c4044)
Location: include/linux/blkdev.h:1746
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (c0000000007b8d04)
Location: include/linux/blkdev.h:1746
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
Location: include/linux/blkdev.h:1746
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff8150ce75)
Location: include/linux/blkdev.h:1746
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff814fd2a5)
Location: include/linux/blkdev.h:1746
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff81508f05)
Location: include/linux/blkdev.h:1746
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
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
In block/mq-deadline.c (ffffffff815226a5)
Location: include/linux/blkdev.h:1746
Inline: True
Inline callers:
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
```
</details>
</li>
</ul>

## Differences
