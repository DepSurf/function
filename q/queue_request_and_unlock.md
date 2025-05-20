# Function: <code>queue_request_and_unlock</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141f120)
Location: fs/fuse/dev.c:221
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8141f120-ffffffff8141f184: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146dcf0)
Location: fs/fuse/dev.c:221
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8146dcf0-ffffffff8146dd54: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814884a0)
Location: fs/fuse/dev.c:225
Inline: False
Direct callers:
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff814884a0-ffffffff81488504: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148de90)
Location: fs/fuse/dev.c:225
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8148de90-ffffffff8148def4: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e5900)
Location: fs/fuse/dev.c:225
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff814e5900-ffffffff814e5964: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81573a10)
Location: fs/fuse/dev.c:225
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81573a10-ffffffff81573a82: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81619060)
Location: fs/fuse/dev.c:225
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81619060-ffffffff816190d2: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81651120)
Location: fs/fuse/dev.c:225
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81651120-ffffffff81651192: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168a730)
Location: fs/fuse/dev.c:225
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8168a730-ffffffff8168a7a2: queue_request_and_unlock (STB_LOCAL)
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
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff8000105013a8)
Location: fs/fuse/dev.c:221
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffff8000105013a8-ffff800010501438: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06be038)
Location: fs/fuse/dev.c:221
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_retrieve
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
c06be038-c06be0ac: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c000000000645730)
Location: fs/fuse/dev.c:221
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
c000000000645730-c000000000645824: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036e9fa)
Location: fs/fuse/dev.c:221
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffe00036e9fa-ffffffe00036ea6a: queue_request_and_unlock (STB_LOCAL)
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
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81417700)
Location: fs/fuse/dev.c:221
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81417700-ffffffff81417764: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81408180)
Location: fs/fuse/dev.c:221
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81408180-ffffffff814081e4: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814138a0)
Location: fs/fuse/dev.c:221
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff814138a0-ffffffff81413904: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void queue_request_and_unlock(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142a6d0)
Location: fs/fuse/dev.c:221
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8142a6d0-ffffffff8142a734: queue_request_and_unlock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
