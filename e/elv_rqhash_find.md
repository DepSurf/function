# Function: <code>elv_rqhash_find</code>

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
In block/elevator.c (ffffffff813b3af0)
Location: block/elevator.c:272
Inline: True
Direct callers:
  - block/elevator.c:elv_merge
  - block/elevator.c:__elv_add_request
```
**Symbols:**

```
ffffffff813b3af0-ffffffff813b3bba: elv_rqhash_find.isra.11 (STB_LOCAL)
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
In block/elevator.c (ffffffff813f7960)
Location: block/elevator.c:272
Inline: True
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff813f7960-ffffffff813f7a31: elv_rqhash_find.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411390)
Location: block/elevator.c:272
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff81411390-ffffffff8141146d: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141ee20)
Location: block/elevator.c:298
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff8141ee20-ffffffff8141ef12: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449900)
Location: block/elevator.c:315
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff81449900-ffffffff814499f3: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c650)
Location: block/elevator.c:284
Inline: False
Direct callers:
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff8147c650-ffffffff8147c736: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a640)
Location: block/elevator.c:219
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff8149a640-ffffffff8149a726: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8720)
Location: block/elevator.c:220
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff814c8720-ffffffff814c87ef: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1840)
Location: block/elevator.c:230
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff814e1840-ffffffff814e190f: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815403b0)
Location: block/elevator.c:230
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff815403b0-ffffffff8154047f: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155cb50)
Location: block/elevator.c:229
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff8155cb50-ffffffff8155cc1f: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815653e0)
Location: block/elevator.c:229
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff815653e0-ffffffff815654b2: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9780)
Location: block/elevator.c:229
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff815c9780-ffffffff815c984e: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674a10)
Location: block/elevator.c:234
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff81674a10-ffffffff81674b1e: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730750)
Location: block/elevator.c:202
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff81730750-ffffffff8173085e: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176c9b0)
Location: block/elevator.c:202
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff8176c9b0-ffffffff8176cabe: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817aebe0)
Location: block/elevator.c:202
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff817aebe0-ffffffff817aecee: elv_rqhash_find (STB_GLOBAL)
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
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de910)
Location: block/elevator.c:230
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffff8000105de910-ffff8000105dea14: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b8b4)
Location: block/elevator.c:230
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
c078b8b4-c078b9b4: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770650)
Location: block/elevator.c:230
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
c000000000770650-c000000000770778: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000421520)
Location: block/elevator.c:230
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffe000421520-ffffffe0004215f2: elv_rqhash_find (STB_GLOBAL)
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
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9e20)
Location: block/elevator.c:230
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff814d9e20-ffffffff814d9eef: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca7d0)
Location: block/elevator.c:230
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff814ca7d0-ffffffff814ca89f: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5eb0)
Location: block/elevator.c:230
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff814d5eb0-ffffffff814d5f7f: elv_rqhash_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request *elv_rqhash_find(struct request_queue *q, sector_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814eeab0)
Location: block/elevator.c:230
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_merge
```
**Symbols:**

```
ffffffff814eeab0-ffffffff814eeb7f: elv_rqhash_find (STB_GLOBAL)
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
