# Function: <code>blk_mq_debugfs_register_sched_hctx</code>

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
int blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8145a4a0)
Location: block/blk-mq-debugfs.c:954
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_init_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8145a4a0-ffffffff8145a514: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81486220)
Location: block/blk-mq-debugfs.c:955
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_init_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81486220-ffffffff81486294: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814bb150)
Location: block/blk-mq-debugfs.c:981
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_sched_init_hctx
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814bb150-ffffffff814bb1c4: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814cf470)
Location: block/blk-mq-debugfs.c:1064
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814cf470-ffffffff814cf4ec: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fdc20)
Location: block/blk-mq-debugfs.c:972
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814fdc20-ffffffff814fdc7f: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151bb60)
Location: block/blk-mq-debugfs.c:972
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8151bb60-ffffffff8151bbbf: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157c37c)
Location: block/blk-mq-debugfs.c:976
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8157c400-ffffffff8157c452: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8159940c)
Location: block/blk-mq-debugfs.c:972
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81599490-ffffffff815994e2: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815a020c)
Location: block/blk-mq-debugfs.c:970
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815a0290-ffffffff815a02e7: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81608a2c)
Location: block/blk-mq-debugfs.c:986
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81608ab0-ffffffff81608b07: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bc763)
Location: block/blk-mq-debugfs.c:846
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff816bc810-ffffffff816bc8b5: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177d173)
Location: block/blk-mq-debugfs.c:844
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8177d230-ffffffff8177d2d5: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bcb03)
Location: block/blk-mq-debugfs.c:816
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff817bcbc0-ffffffff817bcc65: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff818011c6)
Location: block/blk-mq-debugfs.c:797
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81801280-ffffffff81801325: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
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
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff8000106241d8)
Location: block/blk-mq-debugfs.c:972
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffff8000106241d8-ffff80001062423c: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07cb7e8)
Location: block/blk-mq-debugfs.c:972
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
c07cb7e8-c07cb848: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c4d80)
Location: block/blk-mq-debugfs.c:972
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
c0000000007c4d80-c0000000007c4e28: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000455d8a)
Location: block/blk-mq-debugfs.c:972
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffe000455d8a-ffffffe000455dec: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
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
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81514140)
Location: block/blk-mq-debugfs.c:972
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81514140-ffffffff8151419f: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81504450)
Location: block/blk-mq-debugfs.c:972
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81504450-ffffffff815044af: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815101d0)
Location: block/blk-mq-debugfs.c:972
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff815101d0-ffffffff8151022f: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched_hctx(struct request_queue *q, struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81529990)
Location: block/blk-mq-debugfs.c:972
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81529990-ffffffff815299ef: blk_mq_debugfs_register_sched_hctx (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
