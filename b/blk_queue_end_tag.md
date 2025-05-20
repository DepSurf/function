# Function: <code>blk_queue_end_tag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_end_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff813bbd70)
Location: block/blk-tag.c:265
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff813bbd70-ffffffff813bbe27: blk_queue_end_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_end_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff813ffb80)
Location: block/blk-tag.c:265
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff813ffb80-ffffffff813ffc39: blk_queue_end_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_end_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff81419430)
Location: block/blk-tag.c:265
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff81419430-ffffffff814194e5: blk_queue_end_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_end_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff81427360)
Location: block/blk-tag.c:262
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_requeue_request
```
**Symbols:**

```
ffffffff81427360-ffffffff81427416: blk_queue_end_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_end_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff81452960)
Location: block/blk-tag.c:263
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_requeue_request
```
**Symbols:**

```
ffffffff81452960-ffffffff81452a16: blk_queue_end_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void blk_queue_end_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-tag.c (0)
Location: block/blk-tag.c:262
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_requeue_request
```
**Symbols:**

```
ffffffff81485e29-ffffffff81485e65: blk_queue_end_tag.cold.10 (STB_LOCAL)
ffffffff81485d40-ffffffff81485dce: blk_queue_end_tag (STB_GLOBAL)
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
