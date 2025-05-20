# Function: <code>elv_rqhash_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff813b3bc0)
Location: block/elevator.c:257
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/elevator.c:__elv_add_request
```
**Symbols:**

```
ffffffff813b3bc0-ffffffff813b3c2f: elv_rqhash_add.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff813f77d0)
Location: block/elevator.c:257
Inline: True
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_rqhash_reposition
```
**Symbols:**

```
ffffffff813f77d0-ffffffff813f7832: elv_rqhash_add.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814112e0)
Location: block/elevator.c:257
Inline: True
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_rqhash_reposition
```
**Symbols:**

```
ffffffff814112e0-ffffffff8141133f: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141e9b0)
Location: block/elevator.c:282
Inline: True
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_rqhash_reposition
```
**Symbols:**

```
ffffffff8141e9b0-ffffffff8141ea0f: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449480)
Location: block/elevator.c:299
Inline: True
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_rqhash_reposition
```
**Symbols:**

```
ffffffff81449480-ffffffff814494de: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c0d0)
Location: block/elevator.c:268
Inline: True
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_rqhash_reposition
```
**Symbols:**

```
ffffffff8147c0d0-ffffffff8147c12b: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a140)
Location: block/elevator.c:203
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff8149a140-ffffffff8149a19b: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8210)
Location: block/elevator.c:204
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814c8210-ffffffff814c826c: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1300)
Location: block/elevator.c:214
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814e1300-ffffffff814e135c: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8153fd50)
Location: block/elevator.c:214
Inline: True
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff8153fd50-ffffffff8153fdac: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155c4f0)
Location: block/elevator.c:213
Inline: True
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff8155c4f0-ffffffff8155c54c: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81564d90)
Location: block/elevator.c:213
Inline: True
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81564d90-ffffffff81564dec: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9110)
Location: block/elevator.c:213
Inline: True
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
  - block/mq-deadline.c:dd_insert_request
```
**Symbols:**

```
ffffffff815c9110-ffffffff815c916c: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674300)
Location: block/elevator.c:218
Inline: True
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff81674300-ffffffff81674373: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8172ffe0)
Location: block/elevator.c:186
Inline: True
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff8172ffe0-ffffffff81730053: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176c210)
Location: block/elevator.c:186
Inline: True
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff8176c210-ffffffff8176c289: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817ae400)
Location: block/elevator.c:186
Inline: True
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_merged_request
```
**Symbols:**

```
ffffffff817ae400-ffffffff817ae479: elv_rqhash_add (STB_GLOBAL)
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
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de278)
Location: block/elevator.c:214
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffff8000105de278-ffff8000105de30c: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b364)
Location: block/elevator.c:214
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
c078b364-c078b3e0: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c00000000076f890)
Location: block/elevator.c:214
Inline: False
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
c00000000076f890-c00000000076f920: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000420ebc)
Location: block/elevator.c:214
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffe000420ebc-ffffffe000420f30: elv_rqhash_add (STB_GLOBAL)
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
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d98e0)
Location: block/elevator.c:214
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814d98e0-ffffffff814d993c: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca290)
Location: block/elevator.c:214
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814ca290-ffffffff814ca2ec: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5970)
Location: block/elevator.c:214
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814d5970-ffffffff814d59cc: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_add(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ee590)
Location: block/elevator.c:214
Inline: True
Direct callers:
  - block/elevator.c:elv_rqhash_reposition
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814ee590-ffffffff814ee5ec: elv_rqhash_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
