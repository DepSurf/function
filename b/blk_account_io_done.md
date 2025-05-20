# Function: <code>blk_account_io_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_account_io_done(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba540)
Location: block/blk-core.c:2279
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff813ba540-ffffffff813ba6bc: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_account_io_done(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe2d0)
Location: block/blk-core.c:2249
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff813fe2d0-ffffffff813fe439: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_account_io_done(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81417c70)
Location: block/blk-core.c:2232
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff81417c70-ffffffff81417dd0: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_account_io_done(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425a30)
Location: block/blk-core.c:2421
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff81425a30-ffffffff81425baf: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_account_io_done(struct request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450bc0)
Location: block/blk-core.c:2588
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff81450bc0-ffffffff81450d1f: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81483e70)
Location: block/blk-core.c:2730
Inline: True
Direct callers:
  - block/blk-core.c:blk_finish_request
```
**Symbols:**

```
ffffffff81483e70-ffffffff81483fb4: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149f3b0)
Location: block/blk-core.c:1324
Inline: False
```
**Symbols:**

```
ffffffff8149f3b0-ffffffff8149f5d3: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd4b0)
Location: block/blk-core.c:1290
Inline: False
```
**Symbols:**

```
ffffffff814cd4b0-ffffffff814cd6d0: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e67a0)
Location: block/blk-core.c:1325
Inline: False
```
**Symbols:**

```
ffffffff814e67a0-ffffffff814e69c0: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81545dd0)
Location: block/blk-core.c:1421
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff81545dd0-ffffffff81545f1b: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81561c20)
Location: block/blk-core.c:1292
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff81561c20-ffffffff81561d37: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8156a380)
Location: block/blk-core.c:1277
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff8156a380-ffffffff8156a497: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ce880)
Location: block/blk-core.c:1254
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
```
**Symbols:**

```
ffffffff815ce880-ffffffff815ce991: blk_account_io_done (STB_GLOBAL)
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
In block/blk-mq.c (ffffffff816880aa)
Location: block/blk-mq.c:881
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_end_request_batch
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
In block/blk-mq.c (ffffffff8174648c)
Location: block/blk-mq.c:990
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_end_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177ebe0)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
```
**Symbols:**

```
ffffffff8177ebe0-ffffffff8177ed3d: blk_account_io_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c1430)
Location: block/blk-mq.c:989
Inline: False
Direct callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
```
**Symbols:**

```
ffffffff817c1430-ffffffff817c158d: blk_account_io_done (STB_LOCAL)
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
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e3f50)
Location: block/blk-core.c:1325
Inline: False
```
**Symbols:**

```
ffff8000105e3f50-ffff8000105e41d4: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c079122c)
Location: block/blk-core.c:1325
Inline: False
```
**Symbols:**

```
c079122c-c07914e0: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000777c10)
Location: block/blk-core.c:1325
Inline: False
```
**Symbols:**

```
c000000000777c10-c000000000777f00: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe0004258c4)
Location: block/blk-core.c:1325
Inline: False
```
**Symbols:**

```
ffffffe0004258c4-ffffffe000425a9c: blk_account_io_done (STB_GLOBAL)
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
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ded80)
Location: block/blk-core.c:1325
Inline: False
```
**Symbols:**

```
ffffffff814ded80-ffffffff814defa0: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cf720)
Location: block/blk-core.c:1325
Inline: False
```
**Symbols:**

```
ffffffff814cf720-ffffffff814cf940: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dae10)
Location: block/blk-core.c:1325
Inline: False
```
**Symbols:**

```
ffffffff814dae10-ffffffff814db030: blk_account_io_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_account_io_done(struct request *req, u64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f3ba0)
Location: block/blk-core.c:1325
Inline: False
```
**Symbols:**

```
ffffffff814f3ba0-ffffffff814f3e06: blk_account_io_done (STB_GLOBAL)
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
