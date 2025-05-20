# Function: <code>ext4_file_read_iter</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff812d5260)
Location: fs/ext4/file.c:58
Inline: True
```
**Symbols:**

```
ffffffff812d5260-ffffffff812d530b: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff812f1340)
Location: fs/ext4/file.c:62
Inline: False
```
**Symbols:**

```
ffffffff812f1340-ffffffff812f1435: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81315f00)
Location: fs/ext4/file.c:65
Inline: False
```
**Symbols:**

```
ffffffff81315f00-ffffffff81315ff5: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81343b80)
Location: fs/ext4/file.c:65
Inline: False
```
**Symbols:**

```
ffffffff81343b80-ffffffff81343c67: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8135bcc0)
Location: fs/ext4/file.c:65
Inline: False
```
**Symbols:**

```
ffffffff8135bcc0-ffffffff8135bda7: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81384d80)
Location: fs/ext4/file.c:65
Inline: False
```
**Symbols:**

```
ffffffff81384d80-ffffffff81384e78: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8139d800)
Location: fs/ext4/file.c:66
Inline: False
```
**Symbols:**

```
ffffffff8139d800-ffffffff8139d8f5: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813e9880)
Location: fs/ext4/file.c:114
Inline: False
```
**Symbols:**

```
ffffffff813e9880-ffffffff813e99fd: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813fb980)
Location: fs/ext4/file.c:114
Inline: False
```
**Symbols:**

```
ffffffff813fb980-ffffffff813fbb03: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81401c80)
Location: fs/ext4/file.c:113
Inline: False
```
**Symbols:**

```
ffffffff81401c80-ffffffff81401df9: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff814543f0)
Location: fs/ext4/file.c:113
Inline: False
```
**Symbols:**

```
ffffffff814543f0-ffffffff81454569: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff814d1b30)
Location: fs/ext4/file.c:115
Inline: False
```
**Symbols:**

```
ffffffff814d1b30-ffffffff814d1cf4: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8156a5b0)
Location: fs/ext4/file.c:130
Inline: False
```
**Symbols:**

```
ffffffff8156a5b0-ffffffff8156a7ab: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815a2430)
Location: fs/ext4/file.c:130
Inline: False
```
**Symbols:**

```
ffffffff815a2430-ffffffff815a2634: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815db280)
Location: fs/ext4/file.c:130
Inline: False
```
**Symbols:**

```
ffffffff815db280-ffffffff815db484: ext4_file_read_iter (STB_LOCAL)
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
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffff800010470d38)
Location: fs/ext4/file.c:66
Inline: False
```
**Symbols:**

```
ffff800010470d38-ffff800010470e5c: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (c0631ac0)
Location: fs/ext4/file.c:66
Inline: False
```
**Symbols:**

```
c0631ac0-c0631b14: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (c000000000591420)
Location: fs/ext4/file.c:66
Inline: False
```
**Symbols:**

```
c000000000591420-c0000000005915f0: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffe0002fd088)
Location: fs/ext4/file.c:66
Inline: False
```
**Symbols:**

```
ffffffe0002fd088-ffffffe0002fd17c: ext4_file_read_iter (STB_LOCAL)
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
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81395de0)
Location: fs/ext4/file.c:66
Inline: False
```
**Symbols:**

```
ffffffff81395de0-ffffffff81395ed5: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81386870)
Location: fs/ext4/file.c:66
Inline: False
```
**Symbols:**

```
ffffffff81386870-ffffffff81386965: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81393740)
Location: fs/ext4/file.c:66
Inline: False
```
**Symbols:**

```
ffffffff81393740-ffffffff81393835: ext4_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t ext4_file_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813a77d0)
Location: fs/ext4/file.c:66
Inline: False
```
**Symbols:**

```
ffffffff813a77d0-ffffffff813a78c5: ext4_file_read_iter (STB_LOCAL)
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
