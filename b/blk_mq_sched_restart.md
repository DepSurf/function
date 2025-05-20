# Function: <code>blk_mq_sched_restart</code>

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
void blk_mq_sched_restart(const struct blk_mq_hw_ctx * hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814359c0)
Location: block/blk-mq-sched.c:302
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814359c0-ffffffff81435b25: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_sched_restart(const struct blk_mq_hw_ctx * hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81461760)
Location: block/blk-mq-sched.c:390
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff81461760-ffffffff814618c5: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_sched_restart(const struct blk_mq_hw_ctx * hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814950c0)
Location: block/blk-mq-sched.c:406
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814950c0-ffffffff8149520e: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814aeeb0)
Location: block/blk-mq-sched.c:73
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814aeeb0-ffffffff814aeed3: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dd160)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814dd160-ffffffff814dd183: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f65d0)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814f65d0-ffffffff814f65f3: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815571a0)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff815571a0-ffffffff815571c9: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81573830)
Location: block/blk-mq-sched.c:60
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff81573830-ffffffff81573859: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8157b8c0)
Location: block/blk-mq-sched.c:60
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff8157b8c0-ffffffff8157b8e9: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815e0c20)
Location: block/blk-mq-sched.c:60
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff815e0c20-ffffffff815e0c49: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8167c034)
Location: block/blk-mq-sched.h:32
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
```
```
In block/blk-mq.c (ffffffff81682bc8)
Location: block/blk-mq-sched.h:32
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817388b4)
Location: block/blk-mq-sched.h:32
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
```
```
In block/blk-mq.c (ffffffff81740248)
Location: block/blk-mq-sched.h:32
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81774ef4)
Location: block/blk-mq-sched.h:25
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
```
```
In block/blk-mq.c (ffffffff8177eb42)
Location: block/blk-mq-sched.h:25
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817b7214)
Location: block/blk-mq-sched.h:25
Inline: True
Inline callers:
  - block/blk-flush.c:mq_flush_data_end_io
```
```
In block/blk-mq.c (ffffffff817c00c8)
Location: block/blk-mq-sched.h:25
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_free_request
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
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f6b20)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffff8000105f6b20-ffff8000105f6b8c: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a233c)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
c07a233c-c07a237c: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078ef30)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
c00000000078ef30-c00000000078ef8c: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe0004343be)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffe0004343be-ffffffe0004343fc: blk_mq_sched_restart (STB_GLOBAL)
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
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eebb0)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814eebb0-ffffffff814eebd3: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814df0f0)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814df0f0-ffffffff814df113: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eac40)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814eac40-ffffffff814eac63: blk_mq_sched_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_sched_restart(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81503c20)
Location: block/blk-mq-sched.c:74
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff81503c20-ffffffff81503c43: blk_mq_sched_restart (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct blk_mq_hw_ctx * hctx</code> ➡️ <code>struct blk_mq_hw_ctx *hctx</code>
</li>
</ul>
</details>
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
