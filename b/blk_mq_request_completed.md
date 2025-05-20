# Function: <code>blk_mq_request_completed</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee260)
Location: block/blk-mq.c:672
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
```
**Symbols:**

```
ffffffff814ee260-ffffffff814ee27a: blk_mq_request_completed (STB_GLOBAL)
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
In block/blk-mq-tag.c (ffffffff81554815)
Location: include/linux/blk-mq.h:494
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
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
In block/blk-mq-tag.c (ffffffff81570ef5)
Location: include/linux/blk-mq.h:492
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
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
In block/blk-mq-tag.c (ffffffff81578d55)
Location: include/linux/blk-mq.h:497
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
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
In block/blk-mq-tag.c (ffffffff815ddf85)
Location: include/linux/blk-mq.h:507
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
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
In block/blk-mq-tag.c (ffffffff8168bf45)
Location: include/linux/blk-mq.h:784
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
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
In block/blk-mq-tag.c (ffffffff8174a695)
Location: include/linux/blk-mq.h:804
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
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
In block/blk-mq-tag.c (ffffffff81786d75)
Location: include/linux/blk-mq.h:800
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
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
In block/blk-mq.c (ffffffff817bec5b)
Location: include/linux/blk-mq.h:791
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_inflight
```
```
In block/blk-mq-tag.c (ffffffff817c9455)
Location: include/linux/blk-mq.h:791
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
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
int blk_mq_request_completed(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ece18)
Location: block/blk-mq.c:672
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
```
**Symbols:**

```
ffff8000105ece18-ffff8000105ece48: blk_mq_request_completed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079936c)
Location: block/blk-mq.c:672
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
```
**Symbols:**

```
c079936c-c0799394: blk_mq_request_completed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000782920)
Location: block/blk-mq.c:672
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
```
**Symbols:**

```
c000000000782920-c00000000078293c: blk_mq_request_completed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042c8de)
Location: block/blk-mq.c:672
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
```
**Symbols:**

```
ffffffe00042c8de-ffffffe00042c90a: blk_mq_request_completed (STB_GLOBAL)
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
int blk_mq_request_completed(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6840)
Location: block/blk-mq.c:672
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
  - drivers/nvme/host/core.c:nvme_cancel_request
```
**Symbols:**

```
ffffffff814e6840-ffffffff814e685a: blk_mq_request_completed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d6db0)
Location: block/blk-mq.c:672
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
  - drivers/nvme/host/core.c:nvme_cancel_request
```
**Symbols:**

```
ffffffff814d6db0-ffffffff814d6dca: blk_mq_request_completed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e28d0)
Location: block/blk-mq.c:672
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
```
**Symbols:**

```
ffffffff814e28d0-ffffffff814e28ea: blk_mq_request_completed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_mq_request_completed(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fb750)
Location: block/blk-mq.c:672
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_count_completed_rqs
```
**Symbols:**

```
ffffffff814fb750-ffffffff814fb76a: blk_mq_request_completed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
