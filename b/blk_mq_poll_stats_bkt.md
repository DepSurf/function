# Function: <code>blk_mq_poll_stats_bkt</code>

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
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142f090)
Location: block/blk-mq.c:43
Inline: False
```
**Symbols:**

```
ffffffff8142f090-ffffffff8142f0c1: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145a5d0)
Location: block/blk-mq.c:44
Inline: False
```
**Symbols:**

```
ffffffff8145a5d0-ffffffff8145a601: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148dbb0)
Location: block/blk-mq.c:44
Inline: False
```
**Symbols:**

```
ffffffff8148dbb0-ffffffff8148dbe1: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7480)
Location: block/blk-mq.c:44
Inline: False
```
**Symbols:**

```
ffffffff814a7480-ffffffff814a74b1: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d53d0)
Location: block/blk-mq.c:45
Inline: False
```
**Symbols:**

```
ffffffff814d53d0-ffffffff814d540a: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee6b0)
Location: block/blk-mq.c:46
Inline: False
```
**Symbols:**

```
ffffffff814ee6b0-ffffffff814ee6ef: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154e320)
Location: block/blk-mq.c:47
Inline: False
```
**Symbols:**

```
ffffffff8154e320-ffffffff8154e35f: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156cbfd)
Location: block/blk-mq.c:49
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff8156ab80-ffffffff8156abbf: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81574a9d)
Location: block/blk-mq.c:49
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff81572ae0-ffffffff81572b1f: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d8fc2)
Location: block/blk-mq.c:49
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff815d7110-ffffffff815d714f: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81686d4f)
Location: block/blk-mq.c:51
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff81683120-ffffffff81683160: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81744a1f)
Location: block/blk-mq.c:52
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff817409d0-ffffffff81740a10: blk_mq_poll_stats_bkt (STB_LOCAL)
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
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ed4a0)
Location: block/blk-mq.c:46
Inline: False
```
**Symbols:**

```
ffff8000105ed4a0-ffff8000105ed4f4: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a024)
Location: block/blk-mq.c:46
Inline: False
```
**Symbols:**

```
c079a024-c079a06c: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007839c0)
Location: block/blk-mq.c:46
Inline: False
```
**Symbols:**

```
c0000000007839c0-c000000000783a0c: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042dfea)
Location: block/blk-mq.c:46
Inline: False
```
**Symbols:**

```
ffffffe00042dfea-ffffffe00042e070: blk_mq_poll_stats_bkt (STB_LOCAL)
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
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6c90)
Location: block/blk-mq.c:46
Inline: False
```
**Symbols:**

```
ffffffff814e6c90-ffffffff814e6ccf: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7200)
Location: block/blk-mq.c:46
Inline: False
```
**Symbols:**

```
ffffffff814d7200-ffffffff814d723f: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e2d20)
Location: block/blk-mq.c:46
Inline: False
```
**Symbols:**

```
ffffffff814e2d20-ffffffff814e2d5f: blk_mq_poll_stats_bkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_mq_poll_stats_bkt(const struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fbba0)
Location: block/blk-mq.c:46
Inline: False
```
**Symbols:**

```
ffffffff814fbba0-ffffffff814fbbdf: blk_mq_poll_stats_bkt (STB_LOCAL)
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
