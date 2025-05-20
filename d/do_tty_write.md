# Function: <code>do_tty_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e1a41)
Location: drivers/tty/tty_io.c:1103
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81531398)
Location: drivers/tty/tty_io.c:1111
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155dae8)
Location: drivers/tty/tty_io.c:1111
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffff815729f7)
Location: drivers/tty/tty_io.c:876
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffff815d6d77)
Location: drivers/tty/tty_io.c:888
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffff8160fd9a)
Location: drivers/tty/tty_io.c:902
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffff8162cc49)
Location: drivers/tty/tty_io.c:898
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffff81662dc9)
Location: drivers/tty/tty_io.c:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffff81685439)
Location: drivers/tty/tty_io.c:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t do_tty_write(ssize_t (*write)(struct tty_struct *, struct file *, const unsigned char *, size_t), struct tty_struct *tty, struct file *file, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81734520)
Location: drivers/tty/tty_io.c:901
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff81734520-ffffffff8173475f: do_tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t do_tty_write(ssize_t (*write)(struct tty_struct *, struct file *, const unsigned char *, size_t), struct tty_struct *tty, struct file *file, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81750e40)
Location: drivers/tty/tty_io.c:964
Inline: False
```
**Symbols:**

```
ffffffff81750e40-ffffffff817510a4: do_tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t do_tty_write(ssize_t (*write)(struct tty_struct *, struct file *, const unsigned char *, size_t), struct tty_struct *tty, struct file *file, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81734e60)
Location: drivers/tty/tty_io.c:980
Inline: False
```
**Symbols:**

```
ffffffff81734e60-ffffffff817350bd: do_tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t do_tty_write(ssize_t (*write)(struct tty_struct *, struct file *, const unsigned char *, size_t), struct tty_struct *tty, struct file *file, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b5860)
Location: drivers/tty/tty_io.c:974
Inline: False
```
**Symbols:**

```
ffffffff817b5860-ffffffff817b5abd: do_tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t do_tty_write(ssize_t (*write)(struct tty_struct *, struct file *, const unsigned char *, size_t), struct tty_struct *tty, struct file *file, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f19f0)
Location: drivers/tty/tty_io.c:963
Inline: False
```
**Symbols:**

```
ffffffff818f19f0-ffffffff818f1c44: do_tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t do_tty_write(ssize_t (*write)(struct tty_struct *, struct file *, const unsigned char *, size_t), struct tty_struct *tty, struct file *file, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a49a70)
Location: drivers/tty/tty_io.c:957
Inline: False
```
**Symbols:**

```
ffffffff81a49a70-ffffffff81a49cc6: do_tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t do_tty_write(ssize_t (*write)(struct tty_struct *, struct file *, const unsigned char *, size_t), struct tty_struct *tty, struct file *file, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a94100)
Location: drivers/tty/tty_io.c:966
Inline: False
```
**Symbols:**

```
ffffffff81a94100-ffffffff81a94345: do_tty_write (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/tty/tty_io.c (ffff8000108504c4)
Location: drivers/tty/tty_io.c:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (c095d7c4)
Location: drivers/tty/tty_io.c:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (c0000000008eeb34)
Location: drivers/tty/tty_io.c:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffe00052da4c)
Location: drivers/tty/tty_io.c:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffff8164aeb9)
Location: drivers/tty/tty_io.c:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffff8162b309)
Location: drivers/tty/tty_io.c:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffff81679279)
Location: drivers/tty/tty_io.c:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
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
In drivers/tty/tty_io.c (ffffffff816938c9)
Location: drivers/tty/tty_io.c:900
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iov_iter *from</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
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
</ul>
