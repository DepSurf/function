# Function: <code>queue_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130da60)
Location: fs/fuse/dev.c:424
Inline: False
Direct callers:
  - fs/fuse/dev.c:request_wait_answer
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8130da60-ffffffff8130dad9: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81341d70)
Location: fs/fuse/dev.c:404
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81341d70-ffffffff81341dec: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81357ce0)
Location: fs/fuse/dev.c:404
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81357ce0-ffffffff81357d7a: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136c950)
Location: fs/fuse/dev.c:404
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff8136c950-ffffffff8136c9ea: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813915d0)
Location: fs/fuse/dev.c:404
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff813915d0-ffffffff8139166a: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c08b0)
Location: fs/fuse/dev.c:417
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff813c08b0-ffffffff813c094a: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813d9f00)
Location: fs/fuse/dev.c:473
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff813d9f00-ffffffff813d9f9a: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81405a90)
Location: fs/fuse/dev.c:484
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81405a90-ffffffff81405b6d: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81420610)
Location: fs/fuse/dev.c:332
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81420610-ffffffff814206d9: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146f390)
Location: fs/fuse/dev.c:332
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff8146f390-ffffffff8146f459: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81489af0)
Location: fs/fuse/dev.c:338
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81489af0-ffffffff81489bcf: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148f700)
Location: fs/fuse/dev.c:338
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff8148f700-ffffffff8148f7df: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e7170)
Location: fs/fuse/dev.c:338
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff814e7170-ffffffff814e724f: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81573d50)
Location: fs/fuse/dev.c:334
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81573d50-ffffffff81573e34: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81619410)
Location: fs/fuse/dev.c:334
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81619410-ffffffff816194f4: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81651560)
Location: fs/fuse/dev.c:334
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81651560-ffffffff81651644: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168ab70)
Location: fs/fuse/dev.c:334
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff8168ab70-ffffffff8168ac54: queue_interrupt (STB_LOCAL)
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
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff8000105020a8)
Location: fs/fuse/dev.c:332
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffff8000105020a8-ffff8000105021f8: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06be2a0)
Location: fs/fuse/dev.c:332
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
c06be2a0-c06be384: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c000000000645a60)
Location: fs/fuse/dev.c:332
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
c000000000645a60-c000000000645c48: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036ff94)
Location: fs/fuse/dev.c:332
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffe00036ff94-ffffffe0003700ee: queue_interrupt (STB_LOCAL)
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
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81418bf0)
Location: fs/fuse/dev.c:332
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81418bf0-ffffffff81418cb9: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81409670)
Location: fs/fuse/dev.c:332
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81409670-ffffffff81409739: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81414d90)
Location: fs/fuse/dev.c:332
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff81414d90-ffffffff81414e59: queue_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int queue_interrupt(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142ab30)
Location: fs/fuse/dev.c:332
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:request_wait_answer
```
**Symbols:**

```
ffffffff8142ab30-ffffffff8142abf3: queue_interrupt (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fuse_iqueue *fiq</code>
</li>
<li>
<b>Param reordered. </b>
<code>fiq, req</code> ➡️ <code>req</code>
</li>
</ul>
</details>
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
