# Function: <code>blk_integrity_merge_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff813e8270)
Location: block/blk-integrity.c:186
Inline: True
Direct callers:
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff813e8270-ffffffff813e834c: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff8142e510)
Location: block/blk-integrity.c:186
Inline: True
```
**Symbols:**

```
ffffffff8142e510-ffffffff8142e5c4: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff814482b0)
Location: block/blk-integrity.c:186
Inline: True
```
**Symbols:**

```
ffffffff814482b0-ffffffff8144835f: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff814564a0)
Location: block/blk-integrity.c:186
Inline: True
Direct callers:
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff814564a0-ffffffff81456553: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff81482100)
Location: block/blk-integrity.c:186
Inline: True
Direct callers:
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff81482100-ffffffff814821b3: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff814b6cd0)
Location: block/blk-integrity.c:186
Inline: True
```
**Symbols:**

```
ffffffff814b6cd0-ffffffff814b6d81: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff814ca4e0)
Location: block/blk-integrity.c:178
Inline: True
```
**Symbols:**

```
ffffffff814ca4e0-ffffffff814ca58f: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff814f8da0)
Location: block/blk-integrity.c:164
Inline: True
```
**Symbols:**

```
ffffffff814f8da0-ffffffff814f8e57: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff81516c50)
Location: block/blk-integrity.c:164
Inline: True
```
**Symbols:**

```
ffffffff81516c50-ffffffff81516d07: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (ffffffff81577420)
Location: block/blk-integrity.c:164
Inline: True
Direct callers:
  - block/blk-merge.c:ll_merge_requests_fn
```
**Symbols:**

```
ffffffff81577420-ffffffff815774c3: blk_integrity_merge_rq.part.0 (STB_LOCAL)
ffffffff815774d0-ffffffff815774ff: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff81594560)
Location: block/blk-integrity.c:164
Inline: False
Direct callers:
  - block/blk-merge.c:ll_merge_requests_fn
```
**Symbols:**

```
ffffffff81594560-ffffffff81594620: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff8159b340)
Location: block/blk-integrity.c:164
Inline: False
```
**Symbols:**

```
ffffffff8159b340-ffffffff8159b3fe: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff816035a0)
Location: block/blk-integrity.c:164
Inline: False
```
**Symbols:**

```
ffffffff816035a0-ffffffff8160365e: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff816b62f0)
Location: block/blk-integrity.c:164
Inline: False
Direct callers:
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff816b62f0-ffffffff816b63b9: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff81776120)
Location: block/blk-integrity.c:164
Inline: False
Direct callers:
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff81776120-ffffffff817761e9: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff817b5dd0)
Location: block/blk-integrity.c:164
Inline: False
Direct callers:
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff817b5dd0-ffffffff817b5e99: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff817fa7e0)
Location: block/blk-integrity.c:164
Inline: False
Direct callers:
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff817fa7e0-ffffffff817fa8a9: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffff80001061e090)
Location: block/blk-integrity.c:164
Inline: True
```
**Symbols:**

```
ffff80001061e090-ffff80001061e184: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (c07c5b78)
Location: block/blk-integrity.c:164
Inline: True
```
**Symbols:**

```
c07c5b78-c07c5c60: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (c0000000007bd1d0)
Location: block/blk-integrity.c:164
Inline: True
```
**Symbols:**

```
c0000000007bd1d0-c0000000007bd2c0: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffe000450d90)
Location: block/blk-integrity.c:164
Inline: True
```
**Symbols:**

```
ffffffe000450d90-ffffffe000450e4a: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff8150f230)
Location: block/blk-integrity.c:164
Inline: True
```
**Symbols:**

```
ffffffff8150f230-ffffffff8150f2e7: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff814ff660)
Location: block/blk-integrity.c:164
Inline: True
```
**Symbols:**

```
ffffffff814ff660-ffffffff814ff717: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff8150b2c0)
Location: block/blk-integrity.c:164
Inline: True
```
**Symbols:**

```
ffffffff8150b2c0-ffffffff8150b377: blk_integrity_merge_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool blk_integrity_merge_rq(struct request_queue *q, struct request *req, struct request *next);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff81524960)
Location: block/blk-integrity.c:164
Inline: True
```
**Symbols:**

```
ffffffff81524960-ffffffff81524a17: blk_integrity_merge_rq (STB_GLOBAL)
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
