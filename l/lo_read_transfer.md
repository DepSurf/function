# Function: <code>lo_read_transfer</code>

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
In drivers/block/loop.c (ffffffff815708df)
Location: drivers/block/loop.c:364
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff815c6328)
Location: drivers/block/loop.c:364
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff815f48bc)
Location: drivers/block/loop.c:364
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff81608b2e)
Location: drivers/block/loop.c:364
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816713d7)
Location: drivers/block/loop.c:367
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816ad0f9)
Location: drivers/block/loop.c:369
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816cd5b0)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff81709873)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff8172dcf3)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int lo_read_transfer(struct loop_device *lo, struct request *rq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:382
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817e8e60-ffffffff817e913d: lo_read_transfer (STB_LOCAL)
ffffffff817eac8d-ffffffff817eacaf: lo_read_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int lo_read_transfer(struct loop_device *lo, struct request *rq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:379
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817fc4a0-ffffffff817fc757: lo_read_transfer (STB_LOCAL)
ffffffff81c0fa18-ffffffff81c0fa42: lo_read_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int lo_read_transfer(struct loop_device *lo, struct request *rq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:421
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817e24d0-ffffffff817e2790: lo_read_transfer (STB_LOCAL)
ffffffff81c01be2-ffffffff81c01c0f: lo_read_transfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int lo_read_transfer(struct loop_device *lo, struct request *rq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:411
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff8186e8b0-ffffffff8186eb70: lo_read_transfer (STB_LOCAL)
ffffffff81d058bc-ffffffff81d058e9: lo_read_transfer.cold (STB_LOCAL)
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
In drivers/block/loop.c (ffff8000109232c4)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (c0a08f10)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (c0000000009c9630)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffe0005a223c)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816f3ad3)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816cdbd3)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff817211b3)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff8173c575)
Location: drivers/block/loop.c:370
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
