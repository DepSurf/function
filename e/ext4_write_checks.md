# Function: <code>ext4_write_checks</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff812d4a10)
Location: fs/ext4/file.c:150
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff812d4a10-ffffffff812d4a8f: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff812f12c0)
Location: fs/ext4/file.c:157
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff812f12c0-ffffffff812f133f: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81315e80)
Location: fs/ext4/file.c:160
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81315e80-ffffffff81315eff: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81343af0)
Location: fs/ext4/file.c:160
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81343af0-ffffffff81343b73: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8135bc30)
Location: fs/ext4/file.c:160
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff8135bc30-ffffffff8135bcb3: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81384c20)
Location: fs/ext4/file.c:160
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81384c20-ffffffff81384cb3: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8139d6a0)
Location: fs/ext4/file.c:161
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff8139d6a0-ffffffff8139d733: ext4_write_checks (STB_LOCAL)
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
In fs/ext4/file.c (ffffffff813e9154)
Location: fs/ext4/file.c:241
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
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
In fs/ext4/file.c (ffffffff813fb554)
Location: fs/ext4/file.c:240
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
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
In fs/ext4/file.c (ffffffff81401a24)
Location: fs/ext4/file.c:239
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
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
In fs/ext4/file.c (ffffffff81453fb4)
Location: fs/ext4/file.c:239
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
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
In fs/ext4/file.c (ffffffff814d1534)
Location: fs/ext4/file.c:241
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
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
In fs/ext4/file.c (ffffffff8156a304)
Location: fs/ext4/file.c:256
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
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
In fs/ext4/file.c (ffffffff815a2267)
Location: fs/ext4/file.c:271
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
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
In fs/ext4/file.c (ffffffff815daf97)
Location: fs/ext4/file.c:271
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_buffered_write_iter
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
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffff800010470ba0)
Location: fs/ext4/file.c:161
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffff800010470ba0-ffff800010470c64: ext4_write_checks (STB_LOCAL)
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
In fs/ext4/file.c (c063205c)
Location: fs/ext4/file.c:161
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (c000000000591210)
Location: fs/ext4/file.c:161
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
c000000000591210-c000000000591310: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffe0002fcf54)
Location: fs/ext4/file.c:161
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffe0002fcf54-ffffffe0002fcff0: ext4_write_checks (STB_LOCAL)
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
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81395c80)
Location: fs/ext4/file.c:161
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81395c80-ffffffff81395d13: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81386710)
Location: fs/ext4/file.c:161
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81386710-ffffffff813867a3: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813935e0)
Location: fs/ext4/file.c:161
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff813935e0-ffffffff81393673: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t ext4_write_checks(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813a7670)
Location: fs/ext4/file.c:161
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff813a7670-ffffffff813a7703: ext4_write_checks (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
