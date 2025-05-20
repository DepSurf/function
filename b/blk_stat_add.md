# Function: <code>blk_stat_add</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_stat_add(struct blk_rq_stat *stat, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81426bc0)
Location: block/blk-stat.c:195
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff81426bc0-ffffffff81426cea: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814345a0)
Location: block/blk-stat.c:81
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-mq.c:__blk_mq_complete_request
```
**Symbols:**

```
ffffffff814345a0-ffffffff814346b4: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81460220)
Location: block/blk-stat.c:50
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-mq.c:__blk_mq_complete_request
```
**Symbols:**

```
ffffffff81460220-ffffffff814602ce: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81493b00)
Location: block/blk-stat.c:50
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff81493b00-ffffffff81493ba4: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814ada00)
Location: block/blk-stat.c:50
Inline: False
```
**Symbols:**

```
ffffffff814ada00-ffffffff814adaa4: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814dbc90)
Location: block/blk-stat.c:51
Inline: False
```
**Symbols:**

```
ffffffff814dbc90-ffffffff814dbd36: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814f50c0)
Location: block/blk-stat.c:51
Inline: False
```
**Symbols:**

```
ffffffff814f50c0-ffffffff814f5166: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81555ab0)
Location: block/blk-stat.c:51
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff81555ab0-ffffffff81555b64: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81572300)
Location: block/blk-stat.c:51
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff81572300-ffffffff815723b9: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8157a320)
Location: block/blk-stat.c:51
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff8157a320-ffffffff8157a3d7: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff815df680)
Location: block/blk-stat.c:51
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff815df680-ffffffff815df766: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8168dd90)
Location: block/blk-stat.c:51
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_end_request_batch
```
**Symbols:**

```
ffffffff8168dd90-ffffffff8168de9c: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff8174c680)
Location: block/blk-stat.c:51
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_end_request
```
**Symbols:**

```
ffffffff8174c680-ffffffff8174c78c: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff81788dc0)
Location: block/blk-stat.c:50
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
```
**Symbols:**

```
ffffffff81788dc0-ffffffff81788ecc: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff817cb4e0)
Location: block/blk-stat.c:50
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
```
**Symbols:**

```
ffffffff817cb4e0-ffffffff817cb5f2: blk_stat_add (STB_GLOBAL)
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
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffff8000105f5100)
Location: block/blk-stat.c:51
Inline: False
```
**Symbols:**

```
ffff8000105f5100-ffff8000105f51cc: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (c07a0c24)
Location: block/blk-stat.c:51
Inline: False
```
**Symbols:**

```
c07a0c24-c07a0d1c: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (c00000000078cbf0)
Location: block/blk-stat.c:51
Inline: False
```
**Symbols:**

```
c00000000078cbf0-c00000000078ccfc: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffe000432ea8)
Location: block/blk-stat.c:51
Inline: False
```
**Symbols:**

```
ffffffe000432ea8-ffffffe000432f50: blk_stat_add (STB_GLOBAL)
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
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814ed6a0)
Location: block/blk-stat.c:51
Inline: False
```
**Symbols:**

```
ffffffff814ed6a0-ffffffff814ed746: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814ddbf0)
Location: block/blk-stat.c:51
Inline: False
```
**Symbols:**

```
ffffffff814ddbf0-ffffffff814ddc96: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff814e9730)
Location: block/blk-stat.c:51
Inline: False
```
**Symbols:**

```
ffffffff814e9730-ffffffff814e97d6: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_stat_add(struct request *rq, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-stat.c (ffffffff815026e0)
Location: block/blk-stat.c:51
Inline: False
```
**Symbols:**

```
ffffffff815026e0-ffffffff815027a6: blk_stat_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct blk_rq_stat *stat</code>
</li>
<li>
<b>Param reordered. </b>
<code>stat, rq</code> ➡️ <code>rq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 now</code>
</li>
</ul>
</details>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
