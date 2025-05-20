# Function: <code>trace_block_rq_issue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813bb18b)
Location: include/trace/events/block.h:238
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
```
```
In block/blk-mq.c (ffffffff813c30a5)
Location: include/trace/events/block.h:238
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ff05f)
Location: include/trace/events/block.h:240
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
```
```
In block/blk-mq.c (ffffffff81406cc5)
Location: include/trace/events/block.h:240
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418a9d)
Location: include/trace/events/block.h:238
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
```
```
In block/blk-mq.c (ffffffff814210d5)
Location: include/trace/events/block.h:238
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-core.c (ffffffff8142697a)
Location: include/trace/events/block.h:206
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
```
```
In block/blk-mq.c (ffffffff8142f971)
Location: include/trace/events/block.h:206
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-core.c (ffffffff81451111)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
```
```
In block/blk-mq.c (ffffffff8145aef4)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-core.c (ffffffff81484381)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-core.c:blk_peek_request
```
```
In block/blk-mq.c (ffffffff8148df21)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff814a77b1)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff814d57f4)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff814eead4)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff8154fbe4)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff8156c022)
Location: include/trace/events/block.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff815738a2)
Location: include/trace/events/block.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff815d7ea2)
Location: include/trace/events/block.h:204
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff81685432)
Location: include/trace/events/block.h:227
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff81743232)
Location: include/trace/events/block.h:227
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff8177e872)
Location: include/trace/events/block.h:227
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff817c12d2)
Location: include/trace/events/block.h:229
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffff8000105ee9a8)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (c0799cc8)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (c000000000783780)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffe00042d09c)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff814e70b4)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff814d7624)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff814e3144)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
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
In block/blk-mq.c (ffffffff814fbfd4)
Location: include/trace/events/block.h:207
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
```
</details>
</li>
</ul>

## Differences
