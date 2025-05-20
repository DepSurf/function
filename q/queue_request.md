# Function: <code>queue_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void queue_request(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130d900)
Location: fs/fuse/dev.c:332
Inline: False
Direct callers:
  - fs/fuse/dev.c:flush_bg_queue
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff8130d900-ffffffff8130d97f: queue_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void queue_request(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81341c00)
Location: fs/fuse/dev.c:312
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81341c00-ffffffff81341c7f: queue_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void queue_request(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81357a50)
Location: fs/fuse/dev.c:312
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81357a50-ffffffff81357acf: queue_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void queue_request(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136c5b0)
Location: fs/fuse/dev.c:312
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8136c5b0-ffffffff8136c62d: queue_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void queue_request(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81391190)
Location: fs/fuse/dev.c:312
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81391190-ffffffff8139120d: queue_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void queue_request(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c0120)
Location: fs/fuse/dev.c:325
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff813c0120-ffffffff813c019d: queue_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void queue_request(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813d9830)
Location: fs/fuse/dev.c:373
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff813d9830-ffffffff813d98ad: queue_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void queue_request(struct fuse_iqueue *fiq, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814053e0)
Location: fs/fuse/dev.c:375
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff814053e0-ffffffff8140545d: queue_request (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
