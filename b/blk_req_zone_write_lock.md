# Function: <code>blk_req_zone_write_lock</code>

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
In block/deadline-iosched.c (ffffffff814addb1)
Location: include/linux/blkdev.h:1985
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
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
In block/mq-deadline.c (ffffffff814c84d5)
Location: include/linux/blkdev.h:1673
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff814f6dd5)
Location: include/linux/blkdev.h:1697
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff81514bdb)
Location: include/linux/blkdev.h:1728
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff81575c5f)
Location: include/linux/blkdev.h:1791
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
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
In block/mq-deadline.c (ffffffff81592a5f)
Location: include/linux/blkdev.h:1891
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
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
In block/mq-deadline.c (ffffffff8159987f)
Location: include/linux/blkdev.h:1887
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
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
In block/mq-deadline.c (ffffffff81601c9a)
Location: include/linux/blkdev.h:1885
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
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
In block/mq-deadline.c (ffffffff816b4916)
Location: include/linux/blk-mq.h:1137
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
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
In block/mq-deadline.c (ffffffff817743c6)
Location: include/linux/blk-mq.h:1168
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
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
In block/mq-deadline.c (ffffffff817b33e0)
Location: include/linux/blk-mq.h:1180
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
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
In block/mq-deadline.c (ffffffff817f732e)
Location: include/linux/blk-mq.h:1177
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
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
In block/mq-deadline.c (ffff800010619c14)
Location: include/linux/blkdev.h:1728
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (c07c4374)
Location: include/linux/blkdev.h:1728
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (c0000000007b910c)
Location: include/linux/blkdev.h:1728
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffe00044f65c)
Location: include/linux/blkdev.h:1728
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff8150d1bb)
Location: include/linux/blkdev.h:1728
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff814fd5eb)
Location: include/linux/blkdev.h:1728
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff8150924b)
Location: include/linux/blkdev.h:1728
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
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
In block/mq-deadline.c (ffffffff8152295b)
Location: include/linux/blkdev.h:1728
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_dispatch_request
```
</details>
</li>
</ul>

## Differences
