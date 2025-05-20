# Function: <code>fuse_direct_read_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t fuse_direct_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81318350)
Location: fs/fuse/file.c:1406
Inline: False
```
**Symbols:**

```
ffffffff81318350-ffffffff813183ad: fuse_direct_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t fuse_direct_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134cd60)
Location: fs/fuse/file.c:1419
Inline: False
```
**Symbols:**

```
ffffffff8134cd60-ffffffff8134cdbd: fuse_direct_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t fuse_direct_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81362670)
Location: fs/fuse/file.c:1420
Inline: False
```
**Symbols:**

```
ffffffff81362670-ffffffff813626cd: fuse_direct_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t fuse_direct_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81376ff0)
Location: fs/fuse/file.c:1415
Inline: False
```
**Symbols:**

```
ffffffff81376ff0-ffffffff8137705d: fuse_direct_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t fuse_direct_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139bda0)
Location: fs/fuse/file.c:1424
Inline: False
```
**Symbols:**

```
ffffffff8139bda0-ffffffff8139be09: fuse_direct_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t fuse_direct_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813cad50)
Location: fs/fuse/file.c:1425
Inline: False
```
**Symbols:**

```
ffffffff813cad50-ffffffff813cadb9: fuse_direct_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t fuse_direct_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e4570)
Location: fs/fuse/file.c:1429
Inline: False
```
**Symbols:**

```
ffffffff813e4570-ffffffff813e45d9: fuse_direct_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814108ea)
Location: fs/fuse/file.c:1444
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff8142a4fa)
Location: fs/fuse/file.c:1525
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff8147a648)
Location: fs/fuse/file.c:1498
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff8149538c)
Location: fs/fuse/file.c:1530
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff8149a3ec)
Location: fs/fuse/file.c:1532
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff814f1e5c)
Location: fs/fuse/file.c:1535
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff815818b3)
Location: fs/fuse/file.c:1552
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff81627723)
Location: fs/fuse/file.c:1551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff8165faf7)
Location: fs/fuse/file.c:1528
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff81699957)
Location: fs/fuse/file.c:1546
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffff80001050e4c0)
Location: fs/fuse/file.c:1525
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (c06c9c70)
Location: fs/fuse/file.c:1525
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (c000000000655574)
Location: fs/fuse/file.c:1525
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffe0003790e2)
Location: fs/fuse/file.c:1525
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff81422ada)
Location: fs/fuse/file.c:1525
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff8141355a)
Location: fs/fuse/file.c:1525
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff8141ec7a)
Location: fs/fuse/file.c:1525
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
In fs/fuse/file.c (ffffffff814359da)
Location: fs/fuse/file.c:1525
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_read_iter
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
</ul>
