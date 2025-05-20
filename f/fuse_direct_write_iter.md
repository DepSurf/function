# Function: <code>fuse_direct_write_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t fuse_direct_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81318c10)
Location: fs/fuse/file.c:1412
Inline: False
```
**Symbols:**

```
ffffffff81318c10-ffffffff81318cf8: fuse_direct_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t fuse_direct_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134d650)
Location: fs/fuse/file.c:1425
Inline: False
```
**Symbols:**

```
ffffffff8134d650-ffffffff8134d738: fuse_direct_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t fuse_direct_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81362f60)
Location: fs/fuse/file.c:1426
Inline: False
```
**Symbols:**

```
ffffffff81362f60-ffffffff81363048: fuse_direct_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t fuse_direct_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81377900)
Location: fs/fuse/file.c:1421
Inline: False
```
**Symbols:**

```
ffffffff81377900-ffffffff813779ff: fuse_direct_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t fuse_direct_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139c6a0)
Location: fs/fuse/file.c:1430
Inline: False
```
**Symbols:**

```
ffffffff8139c6a0-ffffffff8139c7a0: fuse_direct_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t fuse_direct_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813cbac0)
Location: fs/fuse/file.c:1431
Inline: False
```
**Symbols:**

```
ffffffff813cbac0-ffffffff813cbbc0: fuse_direct_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t fuse_direct_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e4b70)
Location: fs/fuse/file.c:1435
Inline: False
```
**Symbols:**

```
ffffffff813e4b70-ffffffff813e4c70: fuse_direct_write_iter (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff814117c4)
Location: fs/fuse/file.c:1459
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff8142b4b4)
Location: fs/fuse/file.c:1540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fuse_direct_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8147b490)
Location: fs/fuse/file.c:1513
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8147b490-ffffffff8147b587: fuse_direct_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_direct_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496220)
Location: fs/fuse/file.c:1545
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81496220-ffffffff81496317: fuse_direct_write_iter (STB_LOCAL)
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
In fs/fuse/file.c (ffffffff8149b339)
Location: fs/fuse/file.c:1547
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff814f2d89)
Location: fs/fuse/file.c:1550
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff815827f5)
Location: fs/fuse/file.c:1567
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff8162866d)
Location: fs/fuse/file.c:1574
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff81660897)
Location: fs/fuse/file.c:1551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t fuse_direct_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8169a660)
Location: fs/fuse/file.c:1569
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8169a660-ffffffff8169a828: fuse_direct_write_iter (STB_LOCAL)
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
In fs/fuse/file.c (ffff80001050f35c)
Location: fs/fuse/file.c:1540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (c06cabac)
Location: fs/fuse/file.c:1540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (c000000000656868)
Location: fs/fuse/file.c:1540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffe000379d26)
Location: fs/fuse/file.c:1540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff81423a94)
Location: fs/fuse/file.c:1540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff81414514)
Location: fs/fuse/file.c:1540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff8141fc34)
Location: fs/fuse/file.c:1540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff814369b4)
Location: fs/fuse/file.c:1540
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
