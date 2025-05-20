# Function: <code>blk_mq_sched_request_inserted</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81435180)
Location: block/blk-mq-sched.c:256
Inline: False
```
**Symbols:**

```
ffffffff81435180-ffffffff814351de: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81460d80)
Location: block/blk-mq-sched.c:344
Inline: False
```
**Symbols:**

```
ffffffff81460d80-ffffffff81460de5: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81494640)
Location: block/blk-mq-sched.c:360
Inline: False
```
**Symbols:**

```
ffffffff81494640-ffffffff814946a4: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ae770)
Location: block/blk-mq-sched.c:352
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814ae770-ffffffff814ae7d4: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dca90)
Location: block/blk-mq-sched.c:354
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814dca90-ffffffff814dcaee: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f5f00)
Location: block/blk-mq-sched.c:354
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814f5f00-ffffffff814f5f5e: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81556b30)
Location: block/blk-mq-sched.c:419
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81556b30-ffffffff81556b8e: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815735a0)
Location: block/blk-mq-sched.c:387
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff815735a0-ffffffff815735e1: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f6928)
Location: block/blk-mq-sched.c:354
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffff8000105f6928-ffff8000105f69d0: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a1c04)
Location: block/blk-mq-sched.c:354
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
c07a1c04-c07a1ca0: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078e3f0)
Location: block/blk-mq-sched.c:354
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
c00000000078e3f0-c00000000078e4b4: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe000433e20)
Location: block/blk-mq-sched.c:354
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffe000433e20-ffffffe000433ea4: blk_mq_sched_request_inserted (STB_GLOBAL)
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
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ee4e0)
Location: block/blk-mq-sched.c:354
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814ee4e0-ffffffff814ee53e: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dea30)
Location: block/blk-mq-sched.c:354
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814dea30-ffffffff814dea8e: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ea570)
Location: block/blk-mq-sched.c:354
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814ea570-ffffffff814ea5ce: blk_mq_sched_request_inserted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_sched_request_inserted(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81503540)
Location: block/blk-mq-sched.c:354
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81503540-ffffffff815035b5: blk_mq_sched_request_inserted (STB_GLOBAL)
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
