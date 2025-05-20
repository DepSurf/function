# Function: <code>blk_insert_cloned_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813bade0)
Location: block/blk-core.c:2178
Inline: True
Direct callers:
  - drivers/md/dm.c:map_request
```
**Symbols:**

```
ffffffff813bade0-ffffffff813baf72: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813feb80)
Location: block/blk-core.c:2148
Inline: True
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff813feb80-ffffffff813fed22: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81418570)
Location: block/blk-core.c:2131
Inline: True
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81418570-ffffffff81418720: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81426560)
Location: block/blk-core.c:2318
Inline: True
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81426560-ffffffff8142670d: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814519b0)
Location: block/blk-core.c:2485
Inline: True
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814519b0-ffffffff81451b62: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:2628
Inline: True
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814857f2-ffffffff8148582c: blk_insert_cloned_request.cold.103 (STB_LOCAL)
ffffffff81484c30-ffffffff81484db2: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1247
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814a004e-ffffffff814a0088: blk_insert_cloned_request.cold.66 (STB_LOCAL)
ffffffff8149fba0-ffffffff8149fc9b: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1215
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff814ce0e6-ffffffff814ce126: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff814cdcf0-ffffffff814cddbf: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1250
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814e740a-ffffffff814e744a: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff814e7010-ffffffff814e70df: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1328
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8154637c-ffffffff815463bc: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff81545f70-ffffffff81546056: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-core.c (ffffffff81561e14)
Location: block/blk-core.c:1197
Inline: True
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81bf26af-ffffffff81bf26ef: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff81561d90-ffffffff81561e86: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-core.c (ffffffff8156a584)
Location: block/blk-core.c:1182
Inline: True
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81be4676-ffffffff81be46b6: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff8156a500-ffffffff8156a5f0: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-core.c (ffffffff815cea84)
Location: block/blk-core.c:1159
Inline: True
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81cd80c9-ffffffff81cd8109: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff815cea00-ffffffff815ceaf0: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2860
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81e8bc0b-ffffffff81e8bc44: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff81687f90-ffffffff8168818a: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
blk_status_t blk_insert_cloned_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81746370)
Location: block/blk-mq.c:3020
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81746370-ffffffff817465b3: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
blk_status_t blk_insert_cloned_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81783710)
Location: block/blk-mq.c:3030
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81783710-ffffffff81783989: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
blk_status_t blk_insert_cloned_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c5a80)
Location: block/blk-mq.c:3046
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff817c5a80-ffffffff817c5cf6: blk_insert_cloned_request (STB_GLOBAL)
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
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e49a8)
Location: block/blk-core.c:1250
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffff8000105e49a8-ffff8000105e4ac8: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0791be0)
Location: block/blk-core.c:1250
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
c0791be0-c0791cec: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007788a0)
Location: block/blk-core.c:1250
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
c0000000007788a0-c000000000778a40: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe00042606c)
Location: block/blk-core.c:1250
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffe00042606c-ffffffe00042618e: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1250
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814df9ea-ffffffff814dfa2a: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff814df5f0-ffffffff814df6bf: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1250
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814d038a-ffffffff814d03ca: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff814cff90-ffffffff814d005f: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1250
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814dba7a-ffffffff814dbaba: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff814db680-ffffffff814db74f: blk_insert_cloned_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
blk_status_t blk_insert_cloned_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:1250
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff814f48ef-ffffffff814f492f: blk_insert_cloned_request.cold (STB_LOCAL)
ffffffff814f44f0-ffffffff814f45bf: blk_insert_cloned_request (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
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
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, rq</code> ➡️ <code>rq</code>
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
