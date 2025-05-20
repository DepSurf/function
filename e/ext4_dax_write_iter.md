# Function: <code>ext4_dax_write_iter</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff812d54d2)
Location: fs/ext4/file.c:174
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff812f1bb5)
Location: fs/ext4/file.c:181
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813162ea)
Location: fs/ext4/file.c:184
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81344090)
Location: fs/ext4/file.c:184
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8135c1f1)
Location: fs/ext4/file.c:184
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff813854aa)
Location: fs/ext4/file.c:188
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff8139dec8)
Location: fs/ext4/file.c:189
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t ext4_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813e9110)
Location: fs/ext4/file.c:592
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff813e9110-ffffffff813e92f1: ext4_dax_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t ext4_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813fb510)
Location: fs/ext4/file.c:597
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff813fb510-ffffffff813fb6f1: ext4_dax_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t ext4_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff814019e0)
Location: fs/ext4/file.c:613
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff814019e0-ffffffff81401bbb: ext4_dax_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t ext4_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81453f70)
Location: fs/ext4/file.c:613
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81453f70-ffffffff8145414b: ext4_dax_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t ext4_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff814d14f0)
Location: fs/ext4/file.c:612
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff814d14f0-ffffffff814d16b9: ext4_dax_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t ext4_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8156a2c0)
Location: fs/ext4/file.c:633
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff8156a2c0-ffffffff8156a4b7: ext4_dax_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t ext4_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815a2220)
Location: fs/ext4/file.c:655
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff815a2220-ffffffff815a2416: ext4_dax_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t ext4_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815daf50)
Location: fs/ext4/file.c:629
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff815daf50-ffffffff815db146: ext4_dax_write_iter (STB_LOCAL)
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
In fs/ext4/file.c (ffff800010471440)
Location: fs/ext4/file.c:189
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (c000000000591bd0)
Location: fs/ext4/file.c:189
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffe0002fd5ba)
Location: fs/ext4/file.c:189
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff813964a8)
Location: fs/ext4/file.c:189
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff81386f38)
Location: fs/ext4/file.c:189
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff81393e08)
Location: fs/ext4/file.c:189
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/ext4/file.c (ffffffff813a7e98)
Location: fs/ext4/file.c:189
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
