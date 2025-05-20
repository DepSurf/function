# Function: <code>blk_attempt_req_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff813c1b10)
Location: block/blk-merge.c:744
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:__elv_add_request
```
**Symbols:**

```
ffffffff813c1b10-ffffffff813c1b20: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81405af0)
Location: block/blk-merge.c:770
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:__elv_add_request
```
**Symbols:**

```
ffffffff81405af0-ffffffff81405b32: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8141fd90)
Location: block/blk-merge.c:761
Inline: False
Direct callers:
  - block/elevator.c:__elv_add_request
  - block/elevator.c:__elv_add_request
```
**Symbols:**

```
ffffffff8141fd90-ffffffff8141fdd2: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8142dcc0)
Location: block/blk-merge.c:757
Inline: False
```
**Symbols:**

```
ffffffff8142dcc0-ffffffff8142dd26: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81458ef0)
Location: block/blk-merge.c:758
Inline: False
```
**Symbols:**

```
ffffffff81458ef0-ffffffff81458f59: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8148c450)
Location: block/blk-merge.c:789
Inline: False
```
**Symbols:**

```
ffffffff8148c450-ffffffff8148c4b9: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814a6060)
Location: block/blk-merge.c:834
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff814a6060-ffffffff814a6086: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d3f40)
Location: block/blk-merge.c:781
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff814d3f40-ffffffff814d3f66: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814ed270)
Location: block/blk-merge.c:834
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff814ed270-ffffffff814ed296: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8154cda0)
Location: block/blk-merge.c:831
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff8154cda0-ffffffff8154ce1d: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815692c0)
Location: block/blk-merge.c:850
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff815692c0-ffffffff8156933d: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff81571220)
Location: block/blk-merge.c:853
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff81571220-ffffffff8157129d: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff815d58e0)
Location: block/blk-merge.c:844
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff815d58e0-ffffffff815d5960: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff816816f0)
Location: block/blk-merge.c:853
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff816816f0-ffffffff81681710: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173ecb0)
Location: block/blk-merge.c:918
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff8173ecb0-ffffffff8173ecd0: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177b220)
Location: block/blk-merge.c:914
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff8177b220-ffffffff8177b240: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bd610)
Location: block/blk-merge.c:910
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff817bd610-ffffffff817bd630: blk_attempt_req_merge (STB_GLOBAL)
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
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffff8000105ebca0)
Location: block/blk-merge.c:834
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffff8000105ebca0-ffff8000105ebd04: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c07981dc)
Location: block/blk-merge.c:834
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
c07981dc-c0798210: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (c000000000781160)
Location: block/blk-merge.c:834
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
c000000000781160-c0000000007811bc: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffe00042ba1c)
Location: block/blk-merge.c:834
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffe00042ba1c-ffffffe00042ba72: blk_attempt_req_merge (STB_GLOBAL)
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
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e5850)
Location: block/blk-merge.c:834
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff814e5850-ffffffff814e5876: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814d5e00)
Location: block/blk-merge.c:834
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff814d5e00-ffffffff814d5e26: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814e18e0)
Location: block/blk-merge.c:834
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff814e18e0-ffffffff814e1906: blk_attempt_req_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_attempt_req_merge(struct request_queue *q, struct request *rq, struct request *next);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff814fa7a0)
Location: block/blk-merge.c:834
Inline: False
Direct callers:
  - block/elevator.c:elv_attempt_insert_merge
  - block/elevator.c:elv_attempt_insert_merge
```
**Symbols:**

```
ffffffff814fa7a0-ffffffff814fa7c6: blk_attempt_req_merge (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
