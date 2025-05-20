# Function: <code>elv_rqhash_reposition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3c30)
Location: block/elevator.c:266
Inline: False
Direct callers:
  - block/elevator.c:elv_merged_request
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merge_requests
```
**Symbols:**

```
ffffffff813b3c30-ffffffff813b3c81: elv_rqhash_reposition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7840)
Location: block/elevator.c:266
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff813f7840-ffffffff813f788b: elv_rqhash_reposition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411340)
Location: block/elevator.c:266
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff81411340-ffffffff81411386: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141edd0)
Location: block/elevator.c:292
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff8141edd0-ffffffff8141ee16: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814498b0)
Location: block/elevator.c:309
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff814498b0-ffffffff814498f6: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c610)
Location: block/elevator.c:278
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff8147c610-ffffffff8147c650: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a600)
Location: block/elevator.c:213
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff8149a600-ffffffff8149a640: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c86e0)
Location: block/elevator.c:214
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff814c86e0-ffffffff814c8720: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1800)
Location: block/elevator.c:224
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff814e1800-ffffffff814e1840: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815406a7)
Location: block/elevator.c:224
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff81540320-ffffffff815403a4: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155ce47)
Location: block/elevator.c:223
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff8155cac0-ffffffff8155cb44: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815656d7)
Location: block/elevator.c:223
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff81565350-ffffffff815653d4: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9ac7)
Location: block/elevator.c:223
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff815c96f0-ffffffff815c9774: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674de7)
Location: block/elevator.c:228
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff81674960-ffffffff81674a07: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730b67)
Location: block/elevator.c:196
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff81730690-ffffffff81730737: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176cdc7)
Location: block/elevator.c:196
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff8176c8f0-ffffffff8176c9a0: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817aeff7)
Location: block/elevator.c:196
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff817aeb20-ffffffff817aebd0: elv_rqhash_reposition (STB_GLOBAL)
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
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de8b0)
Location: block/elevator.c:224
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffff8000105de8b0-ffff8000105de90c: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b864)
Location: block/elevator.c:224
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
c078b864-c078b8b4: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770600)
Location: block/elevator.c:224
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
c000000000770600-c00000000077064c: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe0004214d0)
Location: block/elevator.c:224
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffe0004214d0-ffffffe000421520: elv_rqhash_reposition (STB_GLOBAL)
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
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9de0)
Location: block/elevator.c:224
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff814d9de0-ffffffff814d9e20: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca790)
Location: block/elevator.c:224
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff814ca790-ffffffff814ca7d0: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5e70)
Location: block/elevator.c:224
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff814d5e70-ffffffff814d5eb0: elv_rqhash_reposition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void elv_rqhash_reposition(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814eea70)
Location: block/elevator.c:224
Inline: False
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff814eea70-ffffffff814eeab0: elv_rqhash_reposition (STB_GLOBAL)
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
