# Function: <code>__blk_queue_bounce</code>

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
In block/bounce.c (ffffffff813d4f58)
Location: block/bounce.c:182
Inline: True
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
In block/bounce.c (ffffffff8141ac13)
Location: block/bounce.c:182
Inline: True
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
In block/bounce.c (ffffffff81436147)
Location: block/bounce.c:182
Inline: True
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
In block/bounce.c (ffffffff81442d68)
Location: block/bounce.c:192
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
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
In block/bounce.c (ffffffff8146f7d8)
Location: block/bounce.c:193
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
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
In block/bounce.c (ffffffff814a3af5)
Location: block/bounce.c:198
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
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
In block/bounce.c (ffffffff814be1c0)
Location: block/bounce.c:286
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue *q, struct bio **bio_orig, mempool_t *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814ec8b0)
Location: block/bounce.c:286
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff814ec8b0-ffffffff814ed021: __blk_queue_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue *q, struct bio **bio_orig, mempool_t *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81505d00)
Location: block/bounce.c:286
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff81505d00-ffffffff8150646e: __blk_queue_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue *q, struct bio **bio_orig, mempool_t *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81566a10)
Location: block/bounce.c:288
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff81566a10-ffffffff81566dbb: __blk_queue_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue *q, struct bio **bio_orig, mempool_t *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff815818b0)
Location: block/bounce.c:287
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff815818b0-ffffffff81581be4: __blk_queue_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Global

**Inline:** Full

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue *q, struct bio **bio_orig, mempool_t *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (c07b3090)
Location: block/bounce.c:286
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
c07b3090-c07b38cc: __blk_queue_bounce (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue *q, struct bio **bio_orig, mempool_t *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814fe2e0)
Location: block/bounce.c:286
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff814fe2e0-ffffffff814fea4e: __blk_queue_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue *q, struct bio **bio_orig, mempool_t *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814ee7f0)
Location: block/bounce.c:286
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff814ee7f0-ffffffff814eef5e: __blk_queue_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue *q, struct bio **bio_orig, mempool_t *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814fa370)
Location: block/bounce.c:286
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff814fa370-ffffffff814faade: __blk_queue_bounce (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __blk_queue_bounce(struct request_queue *q, struct bio **bio_orig, mempool_t *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff815133d0)
Location: block/bounce.c:286
Inline: False
Direct callers:
  - block/bounce.c:blk_queue_bounce
```
**Symbols:**

```
ffffffff815133d0-ffffffff81513b86: __blk_queue_bounce (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
