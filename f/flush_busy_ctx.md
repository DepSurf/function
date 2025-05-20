# Function: <code>flush_busy_ctx</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81422570)
Location: block/blk-mq.c:780
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_process_rq_list
```
**Symbols:**

```
ffffffff81422570-ffffffff814225ff: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81430a00)
Location: block/blk-mq.c:821
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff81430a00-ffffffff81430a8e: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145c180)
Location: block/blk-mq.c:894
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff8145c180-ffffffff8145c20e: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148fba0)
Location: block/blk-mq.c:892
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff8148fba0-ffffffff8148fc3e: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9380)
Location: block/blk-mq.c:964
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff814a9380-ffffffff814a9449: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d70f0)
Location: block/blk-mq.c:963
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff814d70f0-ffffffff814d71b7: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0470)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff814f0470-ffffffff814f0537: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815507a0)
Location: block/blk-mq.c:978
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff815507a0-ffffffff81550858: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156cee0)
Location: block/blk-mq.c:1028
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff8156cee0-ffffffff8156cf98: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81574f10)
Location: block/blk-mq.c:986
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff81574f10-ffffffff81574fc8: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:992
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff815d9350-ffffffff815d944d: flush_busy_ctx (STB_LOCAL)
ffffffff81cd8363-ffffffff81cd83a7: flush_busy_ctx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1531
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff81685ec0-ffffffff81685fbf: flush_busy_ctx (STB_LOCAL)
ffffffff81e8b986-ffffffff81e8b9c6: flush_busy_ctx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1692
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff81743ff0-ffffffff817440ef: flush_busy_ctx (STB_LOCAL)
ffffffff82076057-ffffffff82076097: flush_busy_ctx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1685
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff8177fa10-ffffffff8177fb0f: flush_busy_ctx (STB_LOCAL)
ffffffff820f5ed0-ffffffff820f5f10: flush_busy_ctx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1700
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff817c24f0-ffffffff817c25ef: flush_busy_ctx (STB_LOCAL)
ffffffff821d341d-ffffffff821d345d: flush_busy_ctx.cold (STB_LOCAL)
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
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105edf70)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffff8000105edf70-ffff8000105ee0b8: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0799e90)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
c0799e90-c0799f50: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000785580)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
c000000000785580-c0000000007856f0: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042e82a)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffe00042e82a-ffffffe00042e94a: flush_busy_ctx (STB_LOCAL)
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
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8a50)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff814e8a50-ffffffff814e8b17: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d8fc0)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff814d8fc0-ffffffff814d9087: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e4ae0)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff814e4ae0-ffffffff814e4ba7: flush_busy_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool flush_busy_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fdae0)
Location: block/blk-mq.c:979
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_flush_busy_ctxs
```
**Symbols:**

```
ffffffff814fdae0-ffffffff814fdba6: flush_busy_ctx (STB_LOCAL)
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
