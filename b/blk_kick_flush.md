# Function: <code>blk_kick_flush</code>

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
In block/blk-flush.c (ffffffff813bd5ac)
Location: block/blk-flush.c:290
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814014d8)
Location: block/blk-flush.c:291
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff8141b114)
Location: block/blk-flush.c:288
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814290ec)
Location: block/blk-flush.c:289
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814541dc)
Location: block/blk-flush.c:294
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff81487620)
Location: block/blk-flush.c:297
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814a17c1)
Location: block/blk-flush.c:258
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814cf8f3)
Location: block/blk-flush.c:257
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814e8c53)
Location: block/blk-flush.c:268
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_kick_flush(struct request_queue *q, struct blk_flush_queue *fq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81547b00)
Location: block/blk-flush.c:277
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff81547b00-ffffffff81547c2d: blk_kick_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_kick_flush(struct request_queue *q, struct blk_flush_queue *fq, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81563840)
Location: block/blk-flush.c:279
Inline: False
Direct callers:
  - block/blk-flush.c:blk_flush_complete_seq
```
**Symbols:**

```
ffffffff81563840-ffffffff8156394d: blk_kick_flush (STB_LOCAL)
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
In block/blk-flush.c (ffffffff8156c071)
Location: block/blk-flush.c:278
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff815d05a2)
Location: block/blk-flush.c:285
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff8167bd92)
Location: block/blk-flush.c:292
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff81738612)
Location: block/blk-flush.c:293
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff81774c17)
Location: block/blk-flush.c:289
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff817b6f70)
Location: block/blk-flush.c:289
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffff8000105e6be4)
Location: block/blk-flush.c:268
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (c0793948)
Location: block/blk-flush.c:268
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (c00000000077b448)
Location: block/blk-flush.c:268
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffe000427d0a)
Location: block/blk-flush.c:268
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814e1233)
Location: block/blk-flush.c:268
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814d1bc3)
Location: block/blk-flush.c:268
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814dd2c3)
Location: block/blk-flush.c:268
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
In block/blk-flush.c (ffffffff814f6123)
Location: block/blk-flush.c:268
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
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
</ul>
