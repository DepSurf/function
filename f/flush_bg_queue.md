# Function: <code>flush_bg_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130d980)
Location: fs/fuse/dev.c:361
Inline: False
Direct callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:fuse_request_send_background_locked
```
**Symbols:**

```
ffffffff8130d980-ffffffff8130da54: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81341c80)
Location: fs/fuse/dev.c:341
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:request_end
```
**Symbols:**

```
ffffffff81341c80-ffffffff81341d6f: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81357ad0)
Location: fs/fuse/dev.c:341
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:request_end
```
**Symbols:**

```
ffffffff81357ad0-ffffffff81357bbf: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136c630)
Location: fs/fuse/dev.c:341
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:request_end
```
**Symbols:**

```
ffffffff8136c630-ffffffff8136c720: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81391210)
Location: fs/fuse/dev.c:341
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:request_end
```
**Symbols:**

```
ffffffff81391210-ffffffff81391300: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c0710)
Location: fs/fuse/dev.c:354
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:request_end
```
**Symbols:**

```
ffffffff813c0710-ffffffff813c07ff: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813d9a50)
Location: fs/fuse/dev.c:402
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:request_end
```
**Symbols:**

```
ffffffff813d9a50-ffffffff813d9b3e: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81405600)
Location: fs/fuse/dev.c:404
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:request_end
```
**Symbols:**

```
ffffffff81405600-ffffffff814056d0: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141f190)
Location: fs/fuse/dev.c:251
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff8141f190-ffffffff8141f256: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146dd60)
Location: fs/fuse/dev.c:251
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff8146dd60-ffffffff8146de26: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81488510)
Location: fs/fuse/dev.c:255
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff81488510-ffffffff814885d6: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148df00)
Location: fs/fuse/dev.c:255
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff8148df00-ffffffff8148dfc6: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e5970)
Location: fs/fuse/dev.c:255
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff814e5970-ffffffff814e5a36: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81573a90)
Location: fs/fuse/dev.c:255
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff81573a90-ffffffff81573b6d: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff816190f0)
Location: fs/fuse/dev.c:255
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff816190f0-ffffffff816191cd: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff816511b0)
Location: fs/fuse/dev.c:255
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff816511b0-ffffffff8165128d: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168a7c0)
Location: fs/fuse/dev.c:255
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff8168a7c0-ffffffff8168a89d: flush_bg_queue (STB_LOCAL)
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
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010501958)
Location: fs/fuse/dev.c:251
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffff800010501958-ffff800010501a68: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06be0ac)
Location: fs/fuse/dev.c:251
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
c06be0ac-c06be15c: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c000000000645830)
Location: fs/fuse/dev.c:251
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
c000000000645830-c000000000645958: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036ea6a)
Location: fs/fuse/dev.c:251
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffe00036ea6a-ffffffe00036eb18: flush_bg_queue (STB_LOCAL)
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
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81417770)
Location: fs/fuse/dev.c:251
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff81417770-ffffffff81417836: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814081f0)
Location: fs/fuse/dev.c:251
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff814081f0-ffffffff814082b6: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81413910)
Location: fs/fuse/dev.c:251
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff81413910-ffffffff814139d6: flush_bg_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flush_bg_queue(struct fuse_conn *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142a740)
Location: fs/fuse/dev.c:251
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_request_end
```
**Symbols:**

```
ffffffff8142a740-ffffffff8142a806: flush_bg_queue (STB_LOCAL)
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
