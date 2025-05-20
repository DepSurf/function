# Function: <code>elv_rqhash_del</code>

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
In block/elevator.c (ffffffff813b38e0)
Location: block/elevator.c:251
Inline: True
Inline callers:
  - block/elevator.c:elv_dispatch_sort
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_merge_requests
Direct callers:
  - block/elevator.c:elv_dispatch_sort
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_merge_requests
```
**Symbols:**

```
ffffffff813b38e0-ffffffff813b3928: elv_rqhash_del.isra.6.part.7 (STB_LOCAL)
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
In block/elevator.c (ffffffff813f7b9a)
Location: block/elevator.c:251
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_dispatch_sort
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_dispatch_sort
```
**Symbols:**

```
ffffffff813f75e0-ffffffff813f7622: elv_rqhash_del.isra.7.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff814115ca)
Location: block/elevator.c:251
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_dispatch_sort
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_dispatch_sort
```
**Symbols:**

```
ffffffff81411080-ffffffff814110c1: elv_rqhash_del.part.13 (STB_LOCAL)
ffffffff814112c0-ffffffff814112da: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff8141f17e)
Location: block/elevator.c:275
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_dispatch_sort
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_dispatch_sort
```
**Symbols:**

```
ffffffff8141e770-ffffffff8141e7b1: elv_rqhash_del.part.10 (STB_LOCAL)
ffffffff8141e7c0-ffffffff8141e7db: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff81449c64)
Location: block/elevator.c:292
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_dispatch_sort
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_dispatch_sort
```
**Symbols:**

```
ffffffff81448d90-ffffffff81448dd1: elv_rqhash_del.part.11 (STB_LOCAL)
ffffffff81448de0-ffffffff81448dfb: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff8147c9da)
Location: block/elevator.c:261
Inline: True
Inline callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_dispatch_sort
Direct callers:
  - block/elevator.c:elv_merge_requests
  - block/elevator.c:elv_dispatch_add_tail
  - block/elevator.c:elv_dispatch_sort
```
**Symbols:**

```
ffffffff8147bdc0-ffffffff8147bdfb: elv_rqhash_del.part.15 (STB_LOCAL)
ffffffff8147be00-ffffffff8147be1a: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a0b0)
Location: block/elevator.c:196
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff8149a0b0-ffffffff8149a0f9: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8170)
Location: block/elevator.c:197
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814c8170-ffffffff814c81b9: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1260)
Location: block/elevator.c:207
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814e1260-ffffffff814e12a9: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81540020)
Location: block/elevator.c:207
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff81540020-ffffffff8154006b: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155c7c0)
Location: block/elevator.c:206
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff8155c7c0-ffffffff8155c80b: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81565050)
Location: block/elevator.c:206
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff81565050-ffffffff8156509b: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c93d0)
Location: block/elevator.c:206
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff815c93d0-ffffffff815c941b: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674890)
Location: block/elevator.c:211
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff81674890-ffffffff816748fb: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817305a0)
Location: block/elevator.c:179
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff817305a0-ffffffff8173060b: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176c800)
Location: block/elevator.c:179
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff8176c800-ffffffff8176c86b: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817aea30)
Location: block/elevator.c:179
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff817aea30-ffffffff817aea9b: elv_rqhash_del (STB_GLOBAL)
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
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de1b8)
Location: block/elevator.c:207
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffff8000105de1b8-ffff8000105de20c: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b2b8)
Location: block/elevator.c:207
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
c078b2b8-c078b310: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (c00000000076fad0)
Location: block/elevator.c:207
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
c00000000076fad0-c00000000076fb20: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000420e2e)
Location: block/elevator.c:207
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffe000420e2e-ffffffe000420e76: elv_rqhash_del (STB_GLOBAL)
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
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9840)
Location: block/elevator.c:207
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814d9840-ffffffff814d9889: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca1f0)
Location: block/elevator.c:207
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814ca1f0-ffffffff814ca239: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d58d0)
Location: block/elevator.c:207
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814d58d0-ffffffff814d5919: elv_rqhash_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void elv_rqhash_del(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ee4f0)
Location: block/elevator.c:207
Inline: True
Direct callers:
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814ee4f0-ffffffff814ee539: elv_rqhash_del (STB_GLOBAL)
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
