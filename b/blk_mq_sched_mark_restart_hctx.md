# Function: <code>blk_mq_sched_mark_restart_hctx</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81435750)
Location: block/blk-mq-sched.c:57
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8146150a)
Location: block/blk-mq-sched.c:57
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81494f2a)
Location: block/blk-mq-sched.c:57
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814aefb7)
Location: block/blk-mq-sched.c:64
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff814aedf0-ffffffff814aee09: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dd271)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff814dd0a0-ffffffff814dd0b8: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f66e1)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff814f6510-ffffffff814f6528: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8155704c)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff81556b10-ffffffff81556b28: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815736a3)
Location: block/blk-mq-sched.c:51
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff81573580-ffffffff81573598: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8157b733)
Location: block/blk-mq-sched.c:51
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff8157b480-ffffffff8157b498: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815e0ad2)
Location: block/blk-mq-sched.c:51
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff815e0800-ffffffff815e0818: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8168f6da)
Location: block/blk-mq-sched.c:25
Inline: True
Inline callers:
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff8168f440-ffffffff8168f460: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8174da10)
Location: block/blk-mq-sched.c:24
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff8174da10-ffffffff8174da30: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81789f90)
Location: block/blk-mq-sched.c:22
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff81789f90-ffffffff81789fb0: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff817cc710)
Location: block/blk-mq-sched.c:22
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_mark_tag_wait
  - block/blk-mq-sched.c:__blk_mq_sched_dispatch_requests
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff817cc710-ffffffff817cc730: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f6c84)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffff8000105f69d0-ffff8000105f6a34: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a2474)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
c07a1bd4-c07a1c04: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078f0b0)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
c00000000078ee00-c00000000078ee30: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe0004344d2)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffe000433d86-ffffffe000433db8: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
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
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eecc1)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff814eeaf0-ffffffff814eeb08: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814df201)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff814df040-ffffffff814df058: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ead51)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff814eab80-ffffffff814eab98: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_mark_restart_hctx(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81503d2f)
Location: block/blk-mq-sched.c:65
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
  - block/blk-mq-sched.c:blk_mq_sched_dispatch_requests
Direct callers:
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/mq-deadline.c:dd_finish_request
```
**Symbols:**

```
ffffffff81503b70-ffffffff81503b88: blk_mq_sched_mark_restart_hctx (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
