# Function: <code>blk_mq_try_issue_list_directly</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814aae40)
Location: block/blk-mq.c:1880
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814aae40-ffffffff814aaf10: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8fa0)
Location: block/blk-mq.c:1887
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814d8fa0-ffffffff814d904b: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f2360)
Location: block/blk-mq.c:1907
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814f2360-ffffffff814f240c: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815529a0)
Location: block/blk-mq.c:1967
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff815529a0-ffffffff81552c9f: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156eab0)
Location: block/blk-mq.c:2064
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff8156eab0-ffffffff8156ed58: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81576690)
Location: block/blk-mq.c:2088
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff81576690-ffffffff81576934: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815db2e0)
Location: block/blk-mq.c:2099
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff815db2e0-ffffffff815db5e6: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81689480)
Location: block/blk-mq.c:2668
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff81689480-ffffffff8168970d: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81747a50)
Location: block/blk-mq.c:2811
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff81747a50-ffffffff81747baa: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81782c50)
Location: block/blk-mq.c:2820
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
```
**Symbols:**

```
ffffffff81782c50-ffffffff81782d5b: blk_mq_try_issue_list_directly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c4fa0)
Location: block/blk-mq.c:2837
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_insert_requests
  - block/blk-mq.c:blk_mq_insert_requests
```
**Symbols:**

```
ffffffff817c4fa0-ffffffff817c50ab: blk_mq_try_issue_list_directly (STB_LOCAL)
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
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f1bb0)
Location: block/blk-mq.c:1907
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffff8000105f1bb0-ffff8000105f1c88: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079dcac)
Location: block/blk-mq.c:1907
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
c079dcac-c079dd74: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000788ad0)
Location: block/blk-mq.c:1907
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
c000000000788ad0-c000000000788be8: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe0004305c0)
Location: block/blk-mq.c:1907
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffe0004305c0-ffffffe000430660: blk_mq_try_issue_list_directly (STB_GLOBAL)
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
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ea940)
Location: block/blk-mq.c:1907
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814ea940-ffffffff814ea9ec: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814dae90)
Location: block/blk-mq.c:1907
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814dae90-ffffffff814daf3c: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e69d0)
Location: block/blk-mq.c:1907
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814e69d0-ffffffff814e6a7c: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_try_issue_list_directly(struct blk_mq_hw_ctx *hctx, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ff980)
Location: block/blk-mq.c:1907
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_requests
```
**Symbols:**

```
ffffffff814ff980-ffffffff814ffa2c: blk_mq_try_issue_list_directly (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
