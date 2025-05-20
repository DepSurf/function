# Function: <code>__blk_mq_insert_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c34b0)
Location: block/blk-mq.c:986
Inline: False
Direct callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_insert_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff813c34b0-ffffffff813c3586: __blk_mq_insert_request (STB_LOCAL)
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
In block/blk-mq.c (ffffffff81409f13)
Location: block/blk-mq.c:1065
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_request
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
In block/blk-mq.c (ffffffff8142489d)
Location: block/blk-mq.c:1129
Inline: True
Inline callers:
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_insert_request
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8143163b)
Location: block/blk-mq.c:1349
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff81431bb0-ffffffff81431c87: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145d003)
Location: block/blk-mq.c:1484
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff8145d6d0-ffffffff8145d7aa: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81490ef0)
Location: block/blk-mq.c:1517
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff81490ef0-ffffffff81490fcd: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814aa050)
Location: block/blk-mq.c:1642
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814aa050-ffffffff814aa140: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8020)
Location: block/blk-mq.c:1640
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814d8020-ffffffff814d8110: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f13b0)
Location: block/blk-mq.c:1656
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814f13b0-ffffffff814f14a0: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81552460)
Location: block/blk-mq.c:1722
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff81552460-ffffffff81552543: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156e610)
Location: block/blk-mq.c:1813
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff8156e610-ffffffff8156e6d5: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815761f0)
Location: block/blk-mq.c:1832
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff815761f0-ffffffff815762b5: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dad90)
Location: block/blk-mq.c:1843
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff815dad90-ffffffff815daeb0: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81688c30)
Location: block/blk-mq.c:2357
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff81688c30-ffffffff81688d7a: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81747130)
Location: block/blk-mq.c:2500
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff81747130-ffffffff8174727a: __blk_mq_insert_request (STB_GLOBAL)
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f09b0)
Location: block/blk-mq.c:1656
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffff8000105f09b0-ffff8000105f0ad0: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079ca4c)
Location: block/blk-mq.c:1656
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
c079ca4c-c079cb44: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000787410)
Location: block/blk-mq.c:1656
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
c000000000787410-c00000000078758c: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042f778)
Location: block/blk-mq.c:1656
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffe00042f778-ffffffe00042f85e: __blk_mq_insert_request (STB_GLOBAL)
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
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e9990)
Location: block/blk-mq.c:1656
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814e9990-ffffffff814e9a80: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9ef0)
Location: block/blk-mq.c:1656
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814d9ef0-ffffffff814d9fe0: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5a20)
Location: block/blk-mq.c:1656
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814e5a20-ffffffff814e5b10: __blk_mq_insert_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __blk_mq_insert_request(struct blk_mq_hw_ctx *hctx, struct request *rq, bool at_head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fe980)
Location: block/blk-mq.c:1656
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_insert_request
```
**Symbols:**

```
ffffffff814fe980-ffffffff814fea89: __blk_mq_insert_request (STB_GLOBAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
