# Function: <code>bsg_sg_io</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814ee140)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814ee140-ffffffff814ee3c3: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff815075a0)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff815075a0-ffffffff81507823: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff815686c0)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff815686c0-ffffffff81568941: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81583000)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81583000-ffffffff81583275: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81589e30)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81589e30-ffffffff8158a0a7: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bsg_sg_io(struct bsg_device *bd, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff815ef4a0)
Location: block/bsg.c:57
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff815ef4a0-ffffffff815ef59d: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bsg_sg_io(struct bsg_device *bd, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff816a0450)
Location: block/bsg.c:57
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff816a0450-ffffffff816a0565: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bsg_sg_io(struct bsg_device *bd, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8175ef50)
Location: block/bsg.c:57
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff8175ef50-ffffffff8175f065: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bsg_sg_io(struct bsg_device *bd, bool open_for_write, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8179de50)
Location: block/bsg.c:57
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff8179de50-ffffffff8179df60: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bsg_sg_io(struct bsg_device *bd, bool open_for_write, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff817e18d0)
Location: block/bsg.c:57
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff817e18d0-ffffffff817e19e0: bsg_sg_io (STB_LOCAL)
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
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffff800010609cd8)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffff800010609cd8-ffff80001060a00c: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (c07b4d24)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
c07b4d24-c07b4fe8: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (c0000000007a6070)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
c0000000007a6070-c0000000007a635c: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffe0004432aa)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffe0004432aa-ffffffe00044344e: bsg_sg_io (STB_LOCAL)
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
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814ffb80)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814ffb80-ffffffff814ffe03: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814f0090)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814f0090-ffffffff814f0313: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814fbc10)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814fbc10-ffffffff814fbe93: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bsg_sg_io(struct request_queue *q, fmode_t mode, void *uarg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81514cc0)
Location: block/bsg.c:135
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81514cc0-ffffffff81514f43: bsg_sg_io (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bsg_device *bd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool open_for_write</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
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
