# Function: <code>blk_plug_queued_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_plug_queued_count(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba0b0)
Location: block/blk-core.c:1664
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813ba0b0-ffffffff813ba101: blk_plug_queued_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_plug_queued_count(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ff617)
Location: block/blk-core.c:1625
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
Direct callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_sq_make_request
```
**Symbols:**

```
ffffffff813fde70-ffffffff813fdec1: blk_plug_queued_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_plug_queued_count(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8141902f)
Location: block/blk-core.c:1598
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
Direct callers:
  - block/blk-mq.c:blk_sq_make_request
```
**Symbols:**

```
ffffffff814177b0-ffffffff81417801: blk_plug_queued_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_plug_queued_count(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81426f47)
Location: block/blk-core.c:1730
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81425600-ffffffff8142564e: blk_plug_queued_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_plug_queued_count(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81451f57)
Location: block/blk-core.c:1850
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff814507a0-ffffffff814507ee: blk_plug_queued_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int blk_plug_queued_count(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81485179)
Location: block/blk-core.c:1947
Inline: True
Inline callers:
  - block/blk-core.c:blk_queue_bio
Direct callers:
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81483aa0-ffffffff81483afa: blk_plug_queued_count (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
