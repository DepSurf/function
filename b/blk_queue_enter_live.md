# Function: <code>blk_queue_enter_live</code>

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
In block/blk-mq.c (ffffffff813c4bd5)
Location: block/blk.h:77
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
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
In block/blk-mq.c (ffffffff81408db0)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
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
In block/blk-mq.c (ffffffff814221af)
Location: block/blk.h:70
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_map_request
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
In block/blk-mq.c (ffffffff8142f0f7)
Location: block/blk.h:71
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81451fe4)
Location: block/blk.h:71
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff8145a636)
Location: block/blk.h:71
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814832b0)
Location: block/blk.h:141
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:blk_queue_bio
```
```
In block/blk-mq.c (ffffffff8148eb96)
Location: block/blk.h:141
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149ea80)
Location: block/blk.h:58
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
```
```
In block/blk-mq.c (ffffffff814a859f)
Location: block/blk.h:58
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814d5fdf)
Location: block/blk.h:56
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814ef313)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
In block/blk-mq.c (ffff8000105ef7c4)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (c079a874)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (c0000000007845e0)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffe00042d8e0)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814e78f3)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814d7e63)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814e3983)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
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
In block/blk-mq.c (ffffffff814fced3)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
</details>
</li>
</ul>

## Differences
