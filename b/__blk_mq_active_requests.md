# Function: <code>__blk_mq_active_requests</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156b646)
Location: block/blk-mq.h:219
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff81570fb6)
Location: block/blk-mq.h:219
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8157330b)
Location: block/blk-mq.h:237
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff81578e19)
Location: block/blk-mq.h:237
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da26b)
Location: block/blk-mq.h:239
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff815de049)
Location: block/blk-mq.h:239
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq.c (ffffffff81687d54)
Location: block/blk-mq.h:245
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff8168c0c3)
Location: block/blk-mq.h:245
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
```
```
In block/blk-mq-debugfs.c (ffffffff816bb279)
Location: block/blk-mq.h:245
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:hctx_active_show
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
In block/blk-mq.c (ffffffff817460fd)
Location: block/blk-mq.h:246
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff8174a843)
Location: block/blk-mq.h:246
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
```
```
In block/blk-mq-debugfs.c (ffffffff8177b9b9)
Location: block/blk-mq.h:246
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:hctx_active_show
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
In block/blk-mq.c (ffffffff81782940)
Location: block/blk-mq.h:296
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff81786f26)
Location: block/blk-mq.h:296
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
```
```
In block/blk-mq-debugfs.c (ffffffff817bb4c9)
Location: block/blk-mq.h:296
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:hctx_active_show
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
In block/blk-mq.c (ffffffff817c4c5a)
Location: block/blk-mq.h:328
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff817c9603)
Location: block/blk-mq.h:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
```
```
In block/blk-mq-debugfs.c (ffffffff817ffbc9)
Location: block/blk-mq.h:328
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:hctx_active_show
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
