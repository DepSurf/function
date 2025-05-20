# Function: <code>__rq_qos_done</code>

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
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814bd820)
Location: block/blk-rq-qos.c:39
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814bd820-ffffffff814bd857: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814ebeb0)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814ebeb0-ffffffff814ebee7: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81505270)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff81505270-ffffffff815052a7: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81565b40)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff81565b40-ffffffff81565b77: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81580ac0)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff81580ac0-ffffffff81580af7: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81588630)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff81588630-ffffffff81588667: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff815ee2d0)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff815ee2d0-ffffffff815ee307: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8169eaf0)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff8169eaf0-ffffffff8169eb31: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8175d300)
Location: block/blk-rq-qos.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_end_request
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff8175d300-ffffffff8175d341: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8179c060)
Location: block/blk-rq-qos.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff8179c060-ffffffff8179c0a1: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff817dfac0)
Location: block/blk-rq-qos.c:35
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff817dfac0-ffffffff817dfb01: __rq_qos_done (STB_GLOBAL)
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
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffff8000106072c8)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffff8000106072c8-ffff800010607314: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c07b2520)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
c07b2520-c07b2568: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c0000000007a3c90)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
c0000000007a3c90-c0000000007a3d0c: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffe000441fae)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffe000441fae-ffffffe000441fe4: __rq_qos_done (STB_GLOBAL)
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
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814fd850)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814fd850-ffffffff814fd887: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814edd60)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814edd60-ffffffff814edd97: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814f98e0)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814f98e0-ffffffff814f9917: __rq_qos_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __rq_qos_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81512940)
Location: block/blk-rq-qos.c:41
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff81512940-ffffffff81512977: __rq_qos_done (STB_GLOBAL)
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
