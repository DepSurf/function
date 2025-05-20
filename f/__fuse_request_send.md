# Function: <code>__fuse_request_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130dd70)
Location: fs/fuse/dev.c:485
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_request_send
  - fs/fuse/dev.c:fuse_force_forget
```
**Symbols:**

```
ffffffff8130dd70-ffffffff8130ddfd: __fuse_request_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81342040)
Location: fs/fuse/dev.c:460
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_request_send
```
**Symbols:**

```
ffffffff81342040-ffffffff813420cd: __fuse_request_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81357f90)
Location: fs/fuse/dev.c:464
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_request_send
```
**Symbols:**

```
ffffffff81357f90-ffffffff8135801d: __fuse_request_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136cbf0)
Location: fs/fuse/dev.c:464
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_request_send
```
**Symbols:**

```
ffffffff8136cbf0-ffffffff8136cc7d: __fuse_request_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813944a0)
Location: fs/fuse/dev.c:464
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_request_send
```
**Symbols:**

```
ffffffff813944a0-ffffffff8139452f: __fuse_request_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c34e0)
Location: fs/fuse/dev.c:477
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_request_send
```
**Symbols:**

```
ffffffff813c34e0-ffffffff813c356f: __fuse_request_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813db0e0)
Location: fs/fuse/dev.c:533
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_request_send
```
**Symbols:**

```
ffffffff813db0e0-ffffffff813db16f: __fuse_request_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __fuse_request_send(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81407550)
Location: fs/fuse/dev.c:557
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_force_forget
  - fs/fuse/dev.c:fuse_request_send
```
**Symbols:**

```
ffffffff81407550-ffffffff814075e9: __fuse_request_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81422c28)
Location: fs/fuse/dev.c:405
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff81471e0a)
Location: fs/fuse/dev.c:405
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __fuse_request_send(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81489de0)
Location: fs/fuse/dev.c:414
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_request
```
**Symbols:**

```
ffffffff81489de0-ffffffff81489e92: __fuse_request_send (STB_LOCAL)
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
In fs/fuse/dev.c (ffffffff81491f81)
Location: fs/fuse/dev.c:414
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff814e9a71)
Location: fs/fuse/dev.c:414
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff815782a0)
Location: fs/fuse/dev.c:410
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8161d833)
Location: fs/fuse/dev.c:410
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8165592d)
Location: fs/fuse/dev.c:410
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
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
In fs/fuse/dev.c (ffffffff8168f08d)
Location: fs/fuse/dev.c:410
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010505a28)
Location: fs/fuse/dev.c:405
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06c1db0)
Location: fs/fuse/dev.c:405
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c00000000064b0a4)
Location: fs/fuse/dev.c:405
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00037232a)
Location: fs/fuse/dev.c:405
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141b208)
Location: fs/fuse/dev.c:405
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8140bc88)
Location: fs/fuse/dev.c:405
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814173a8)
Location: fs/fuse/dev.c:405
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142e138)
Location: fs/fuse/dev.c:405
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
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
</ul>
