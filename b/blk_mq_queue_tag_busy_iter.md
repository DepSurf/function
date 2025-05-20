# Function: <code>blk_mq_queue_tag_busy_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff813c7730)
Location: block/blk-mq-tag.c:477
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_rq_timer
```
**Symbols:**

```
ffffffff813c7730-ffffffff813c77e7: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8140b970)
Location: block/blk-mq-tag.c:514
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
**Symbols:**

```
ffffffff8140b970-ffffffff8140ba27: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81425f60)
Location: block/blk-mq-tag.c:330
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
**Symbols:**

```
ffffffff81425f60-ffffffff8142614d: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81433cc0)
Location: block/blk-mq-tag.c:320
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
```
**Symbols:**

```
ffffffff81433cc0-ffffffff81433ea5: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8145f980)
Location: block/blk-mq-tag.c:330
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff8145f980-ffffffff8145fbe0: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81493270)
Location: block/blk-mq-tag.c:317
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff81493270-ffffffff814934cb: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ad220)
Location: block/blk-mq-tag.c:378
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff814ad220-ffffffff814ad4f2: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814db490)
Location: block/blk-mq-tag.c:371
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff814db490-ffffffff814db778: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814f48c0)
Location: block/blk-mq-tag.c:403
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff814f48c0-ffffffff814f4ba8: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81555280)
Location: block/blk-mq-tag.c:450
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff81555280-ffffffff8155557b: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81571930)
Location: block/blk-mq-tag.c:410
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff81571930-ffffffff81571c3e: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81579970)
Location: block/blk-mq-tag.c:436
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff81579970-ffffffff81579c44: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:437
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff81cd8758-ffffffff81cd8807: blk_mq_queue_tag_busy_iter.cold (STB_LOCAL)
ffffffff815dec70-ffffffff815def8c: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:496
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff81e8bffb-ffffffff81e8c28d: blk_mq_queue_tag_busy_iter.cold (STB_LOCAL)
ffffffff8168cfd0-ffffffff8168d6f5: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:489
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff820765cd-ffffffff8207685f: blk_mq_queue_tag_busy_iter.cold (STB_LOCAL)
ffffffff8174b7f0-ffffffff8174beee: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:496
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff820f644f-ffffffff820f66e1: blk_mq_queue_tag_busy_iter.cold (STB_LOCAL)
ffffffff81787f10-ffffffff8178860e: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:496
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff821d3974-ffffffff821d3c06: blk_mq_queue_tag_busy_iter.cold (STB_LOCAL)
ffffffff817ca5e0-ffffffff817cacde: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffff8000105f4700)
Location: block/blk-mq-tag.c:403
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffff8000105f4700-ffff8000105f49f8: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c07a032c)
Location: block/blk-mq-tag.c:403
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
c07a032c-c07a0654: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c00000000078bfe0)
Location: block/blk-mq-tag.c:403
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
c00000000078bfe0-c00000000078c3a8: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffe0004326a0)
Location: block/blk-mq-tag.c:403
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffe0004326a0-ffffffe0004328fa: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ecea0)
Location: block/blk-mq-tag.c:403
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff814ecea0-ffffffff814ed188: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814dd3f0)
Location: block/blk-mq-tag.c:403
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff814dd3f0-ffffffff814dd6d8: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814e8f30)
Location: block/blk-mq-tag.c:403
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff814e8f30-ffffffff814e9218: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_queue_tag_busy_iter(struct request_queue *q, busy_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81501ed0)
Location: block/blk-mq-tag.c:403
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_timeout_work
  - block/blk-mq.c:blk_mq_queue_inflight
  - block/blk-mq.c:blk_mq_in_flight_rw
  - block/blk-mq.c:blk_mq_in_flight
```
**Symbols:**

```
ffffffff81501ed0-ffffffff815021d6: blk_mq_queue_tag_busy_iter (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>busy_iter_fn *fn</code> ➡️ <code>busy_tag_iter_fn *fn</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
