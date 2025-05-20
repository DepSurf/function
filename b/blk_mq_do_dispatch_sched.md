# Function: <code>blk_mq_do_dispatch_sched</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81460e70)
Location: block/blk-mq-sched.c:92
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff81460e70-ffffffff81460f67: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81494730)
Location: block/blk-mq-sched.c:92
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff81494730-ffffffff8149482c: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ae850)
Location: block/blk-mq-sched.c:87
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814ae850-ffffffff814ae946: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dcaf0)
Location: block/blk-mq-sched.c:88
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814dcaf0-ffffffff814dcbe9: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f5f60)
Location: block/blk-mq-sched.c:88
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814f5f60-ffffffff814f6059: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81556e50)
Location: block/blk-mq-sched.c:102
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff81556e50-ffffffff81556f89: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815736ed)
Location: block/blk-mq-sched.c:194
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8157b77d)
Location: block/blk-mq-sched.c:199
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815e0afe)
Location: block/blk-mq-sched.c:209
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8168f260)
Location: block/blk-mq-sched.c:181
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff8168f260-ffffffff8168f2db: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8174def0)
Location: block/blk-mq-sched.c:180
Inline: False
Direct callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff8174def0-ffffffff8174df6b: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8178a77c)
Location: block/blk-mq-sched.c:178
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff817ccedc)
Location: block/blk-mq-sched.c:178
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
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
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f62e0)
Location: block/blk-mq-sched.c:88
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffff8000105f62e0-ffff8000105f63e8: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a1ca0)
Location: block/blk-mq-sched.c:88
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
c07a1ca0-c07a1db4: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078e5b0)
Location: block/blk-mq-sched.c:88
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
c00000000078e5b0-c00000000078e718: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe000433ea4)
Location: block/blk-mq-sched.c:88
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffe000433ea4-ffffffe000433f40: blk_mq_do_dispatch_sched (STB_LOCAL)
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
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ee540)
Location: block/blk-mq-sched.c:88
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814ee540-ffffffff814ee639: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dea90)
Location: block/blk-mq-sched.c:88
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814dea90-ffffffff814deb89: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ea5d0)
Location: block/blk-mq-sched.c:88
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff814ea5d0-ffffffff814ea6c9: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_do_dispatch_sched(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815035c0)
Location: block/blk-mq-sched.c:88
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
**Symbols:**

```
ffffffff815035c0-ffffffff815036b9: blk_mq_do_dispatch_sched (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
