# Function: <code>refill_reqs_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8125ba10)
Location: fs/aio.c:938
Inline: False
Direct callers:
  - fs/aio.c:aio_complete
  - fs/aio.c:do_io_submit
```
**Symbols:**

```
ffffffff8125ba10-ffffffff8125ba4c: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81284300)
Location: fs/aio.c:948
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff81284300-ffffffff81284342: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81297fc0)
Location: fs/aio.c:951
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff81297fc0-ffffffff81298002: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a69b0)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff812a69b0-ffffffff812a69f3: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c9850)
Location: fs/aio.c:980
Inline: False
Direct callers:
  - fs/aio.c:do_io_submit
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff812c9850-ffffffff812c9893: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f29b0)
Location: fs/aio.c:943
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff812f29b0-ffffffff812f29f2: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81307630)
Location: fs/aio.c:959
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffff81307630-ffffffff81307672: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328c20)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
**Symbols:**

```
ffffffff81328c20-ffffffff81328c62: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133b9d0)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
**Symbols:**

```
ffffffff8133b9d0-ffffffff8133ba12: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813783e8)
Location: fs/aio.c:956
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
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
In fs/aio.c (ffffffff813860ec)
Location: fs/aio.c:958
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
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
In fs/aio.c (ffffffff8138d23c)
Location: fs/aio.c:955
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
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
In fs/aio.c (ffffffff813da99c)
Location: fs/aio.c:956
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814653b3)
Location: fs/aio.c:982
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f53f3)
Location: fs/aio.c:983
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
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
In fs/aio.c (ffffffff8152c180)
Location: fs/aio.c:981
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
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
In fs/aio.c (ffffffff81561060)
Location: fs/aio.c:991
Inline: True
Inline callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
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
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103faab8)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffff8000103faab8-ffff8000103fab38: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05cdfa4)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:aio_complete
```
**Symbols:**

```
c05cdfa4-c05cdffc: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000502dc0)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
**Symbols:**

```
c000000000502dc0-c000000000502e10: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002a914e)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:aio_complete
```
**Symbols:**

```
ffffffe0002a914e-ffffffe0002a91c2: refill_reqs_available (STB_LOCAL)
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
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81333fb0)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
**Symbols:**

```
ffffffff81333fb0-ffffffff81333ff2: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81323ea0)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
**Symbols:**

```
ffffffff81323ea0-ffffffff81323ee2: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81331a80)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
**Symbols:**

```
ffffffff81331a80-ffffffff81331ac2: refill_reqs_available (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void refill_reqs_available(struct kioctx *ctx, unsigned int head, unsigned int tail);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813448a0)
Location: fs/aio.c:956
Inline: False
Direct callers:
  - fs/aio.c:io_submit_one
  - fs/aio.c:io_submit_one
  - fs/aio.c:aio_poll_wake
  - fs/aio.c:aio_poll_complete_work
  - fs/aio.c:aio_poll_put_work
  - fs/aio.c:aio_fsync_work
  - fs/aio.c:aio_complete_rw
```
**Symbols:**

```
ffffffff813448a0-ffffffff813448e2: refill_reqs_available (STB_LOCAL)
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
