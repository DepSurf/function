# Function: <code>rq_ioc</code>

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
In block/blk-core.c (ffffffff813b8eae)
Location: block/blk-core.c:1037
Inline: True
Inline callers:
  - block/blk-core.c:get_request
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
In block/blk-core.c (ffffffff813fccad)
Location: block/blk-core.c:1047
Inline: True
Inline callers:
  - block/blk-core.c:get_request
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
In block/blk-core.c (ffffffff81416638)
Location: block/blk-core.c:1049
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81426bd6)
Location: block/blk.h:296
Inline: True
Inline callers:
  - block/blk-core.c:blk_init_request_from_bio
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8142f36a)
Location: block/blk.h:296
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff814355c6)
Location: block/blk.h:296
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
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
In block/blk-core.c (ffffffff81451be6)
Location: block/blk.h:266
Inline: True
Inline callers:
  - block/blk-core.c:blk_init_request_from_bio
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8145a8bf)
Location: block/blk.h:266
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff81461396)
Location: block/blk.h:266
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
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
In block/blk-core.c (ffffffff81484e45)
Location: block/blk.h:347
Inline: True
Inline callers:
  - block/blk-core.c:blk_init_request_from_bio
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8148edff)
Location: block/blk.h:347
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-mq-sched.c (ffffffff81494dc6)
Location: block/blk.h:347
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_assign_ioc
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
