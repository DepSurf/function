# Function: <code>__blk_mq_try_issue_directly</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81431100)
Location: block/blk-mq.c:1486
Inline: False
```
**Symbols:**

```
ffffffff81431100-ffffffff8143122a: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool may_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145ca70)
Location: block/blk-mq.c:1618
Inline: False
```
**Symbols:**

```
ffffffff8145ca70-ffffffff8145cc20: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81490310)
Location: block/blk-mq.c:1678
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff81490310-ffffffff81490477: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8180)
Location: block/blk-mq.c:1813
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff814d8180-ffffffff814d8332: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f1530)
Location: block/blk-mq.c:1833
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff814f1530-ffffffff814f16e4: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154fcf0)
Location: block/blk-mq.c:1881
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff8154fcf0-ffffffff8154ff00: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156c330)
Location: block/blk-mq.c:1978
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff8156c330-ffffffff8156c505: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573a70)
Location: block/blk-mq.c:1998
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff81573a70-ffffffff81573c5f: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da490)
Location: block/blk-mq.c:2009
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff815da490-ffffffff815da67f: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81687db0)
Location: block/blk-mq.c:2476
Inline: False
Direct callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff81687db0-ffffffff81687f8e: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81746180)
Location: block/blk-mq.c:2619
Inline: False
Direct callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff81746180-ffffffff8174635e: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f0bb8)
Location: block/blk-mq.c:1833
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffff8000105f0bb8-ffff8000105f0d74: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079cbd4)
Location: block/blk-mq.c:1833
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
c079cbd4-c079cdb4: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007876d0)
Location: block/blk-mq.c:1833
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
c0000000007876d0-c000000000787990: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042f926)
Location: block/blk-mq.c:1833
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffe00042f926-ffffffe00042fa74: __blk_mq_try_issue_directly (STB_LOCAL)
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
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9b10)
Location: block/blk-mq.c:1833
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff814e9b10-ffffffff814e9cc4: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814da070)
Location: block/blk-mq.c:1833
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff814da070-ffffffff814da224: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5ba0)
Location: block/blk-mq.c:1833
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff814e5ba0-ffffffff814e5d54: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_status_t __blk_mq_try_issue_directly(struct blk_mq_hw_ctx *hctx, struct request *rq, blk_qc_t *cookie, bool bypass_insert, bool last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814feb30)
Location: block/blk-mq.c:1833
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_request_issue_directly
  - block/blk-mq.c:blk_mq_try_issue_directly
```
**Symbols:**

```
ffffffff814feb30-ffffffff814fece4: __blk_mq_try_issue_directly (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool bypass_insert</code>
</li>
<li>
<b>Param removed. </b>
<code>bool may_sleep</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
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
<code>blk_qc_t *cookie</code>
</li>
<li>
<b>Param reordered. </b>
<code>hctx, rq, cookie, bypass_insert, last</code> ➡️ <code>hctx, rq, bypass_insert, last</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
