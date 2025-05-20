# Function: <code>bio_queue_enter</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81544f43)
Location: block/blk-core.c:459
Inline: True
Inline callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:direct_make_request
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
In block/blk-core.c (ffffffff8156185b)
Location: block/blk-core.c:477
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct_mq
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
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
In block/blk-core.c (ffffffff81569c92)
Location: block/blk-core.c:478
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
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
In block/blk-core.c (ffffffff815cd423)
Location: block/blk-core.c:467
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81679f1f)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
```
```
In block/blk-mq.c (ffffffff8168415b)
Location: block/blk.h:75
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817363b9)
Location: block/blk.h:65
Inline: True
Inline callers:
  - block/blk-core.c:bio_poll
  - block/blk-core.c:__submit_bio
```
```
In block/blk-mq.c (ffffffff8174193b)
Location: block/blk.h:65
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8177152b)
Location: block/blk.h:65
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
```
```
In block/blk-mq.c (ffffffff81781e5b)
Location: block/blk.h:65
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_new_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b386b)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio
```
```
In block/blk-mq.c (ffffffff817c65fe)
Location: block/blk.h:64
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
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
