# Function: <code>blk_mq_mark_tag_wait</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145d49f)
Location: block/blk-mq.c:1019
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff81490c18)
Location: block/blk-mq.c:1019
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814a9e23)
Location: block/blk-mq.c:1098
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814d7db9)
Location: block/blk-mq.c:1097
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814f114b)
Location: block/blk-mq.c:1113
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_mq_mark_tag_wait(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815519a0)
Location: block/blk-mq.c:1082
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff815519a0-ffffffff81551b80: blk_mq_mark_tag_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_mq_mark_tag_wait(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156daf0)
Location: block/blk-mq.c:1172
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff8156daf0-ffffffff8156dcad: blk_mq_mark_tag_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_mq_mark_tag_wait(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815755d0)
Location: block/blk-mq.c:1130
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff815755d0-ffffffff8157578d: blk_mq_mark_tag_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_mq_mark_tag_wait(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815da2d0)
Location: block/blk-mq.c:1136
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff815da2d0-ffffffff815da48d: blk_mq_mark_tag_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_mq_mark_tag_wait(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816883a0)
Location: block/blk-mq.c:1665
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff816883a0-ffffffff81688590: blk_mq_mark_tag_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_mq_mark_tag_wait(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81746840)
Location: block/blk-mq.c:1826
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff81746840-ffffffff81746a5b: blk_mq_mark_tag_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_mq_mark_tag_wait(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81783aa0)
Location: block/blk-mq.c:1819
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff81783aa0-ffffffff81783cbb: blk_mq_mark_tag_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_mq_mark_tag_wait(struct blk_mq_hw_ctx *hctx, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c5e20)
Location: block/blk-mq.c:1821
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
```
**Symbols:**

```
ffffffff817c5e20-ffffffff817c5ffb: blk_mq_mark_tag_wait (STB_LOCAL)
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
In block/blk-mq.c (ffff8000105f0470)
Location: block/blk-mq.c:1113
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (c079c5a8)
Location: block/blk-mq.c:1113
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (c000000000786f60)
Location: block/blk-mq.c:1113
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffe00042f270)
Location: block/blk-mq.c:1113
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814e972b)
Location: block/blk-mq.c:1113
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814d9c9b)
Location: block/blk-mq.c:1113
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814e57bb)
Location: block/blk-mq.c:1113
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
In block/blk-mq.c (ffffffff814fe721)
Location: block/blk-mq.c:1113
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
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
