# Function: <code>io_submit_state_start</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813303ba)
Location: fs/io_uring.c:2197
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff81343bf1)
Location: fs/io_uring.c:2602
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff81388d9b)
Location: fs/io_uring.c:5941
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff813996d8)
Location: fs/io_uring.c:6748
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff813a0a19)
Location: fs/io_uring.c:6691
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff813efa09)
Location: fs/io_uring.c:7274
Inline: True
Inline callers:
  - fs/io_uring.c:io_submit_sqes
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
In io_uring/io_uring.c (ffffffff816d614b)
Location: io_uring/io_uring.c:8576
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
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
In io_uring/io_uring.c (ffffffff817915d6)
Location: io_uring/io_uring.c:2312
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
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
In io_uring/io_uring.c (ffffffff817d2868)
Location: io_uring/io_uring.c:2336
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
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
In io_uring/io_uring.c (ffffffff81815b88)
Location: io_uring/io_uring.c:2364
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffff8000104059b8)
Location: fs/io_uring.c:2602
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (c05d5574)
Location: fs/io_uring.c:2602
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (c00000000050e5e4)
Location: fs/io_uring.c:2602
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffe0002af98c)
Location: fs/io_uring.c:2602
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff8133c1d1)
Location: fs/io_uring.c:2602
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff8132cea1)
Location: fs/io_uring.c:2602
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff81339ca1)
Location: fs/io_uring.c:2602
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
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
In fs/io_uring.c (ffffffff8134c8d1)
Location: fs/io_uring.c:2602
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_submit
  - fs/io_uring.c:io_submit_sqes
```
</details>
</li>
</ul>

## Differences
