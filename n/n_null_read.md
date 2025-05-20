# Function: <code>n_null_read</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff8157da30)
Location: drivers/tty/n_null.c:34
Inline: True
```
**Symbols:**

```
ffffffff8157da30-ffffffff8157da42: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff815e2560)
Location: drivers/tty/n_null.c:22
Inline: True
```
**Symbols:**

```
ffffffff815e2560-ffffffff815e2572: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff8161b800)
Location: drivers/tty/n_null.c:22
Inline: True
```
**Symbols:**

```
ffffffff8161b800-ffffffff8161b812: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff81638a80)
Location: drivers/tty/n_null.c:22
Inline: True
```
**Symbols:**

```
ffffffff81638a80-ffffffff81638a92: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff8166cd20)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff8166cd20-ffffffff8166cd32: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff8168f390)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff8168f390-ffffffff8168f3a2: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff81741a20)
Location: drivers/tty/n_null.c:22
Inline: True
```
**Symbols:**

```
ffffffff81741a20-ffffffff81741a32: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr, void **cookie, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff8175d8e0)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff8175d8e0-ffffffff8175d8f2: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr, void **cookie, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff817416b0)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff817416b0-ffffffff817416c2: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr, void **cookie, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff817c2110)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff817c2110-ffffffff817c2122: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr, void **cookie, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff818feb90)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff818feb90-ffffffff818feba6: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr, void **cookie, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff81a58400)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff81a58400-ffffffff81a58416: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr, void **cookie, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff81aa2a20)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff81aa2a20-ffffffff81aa2a36: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, u8 *buf, size_t nr, void **cookie, long unsigned int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff81af53b0)
Location: drivers/tty/n_null.c:13
Inline: False
```
**Symbols:**

```
ffffffff81af53b0-ffffffff81af53c6: n_null_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffff800010861398)
Location: drivers/tty/n_null.c:22
Inline: True
```
**Symbols:**

```
ffff800010861398-ffff8000108613b4: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (c0967db0)
Location: drivers/tty/n_null.c:22
Inline: True
```
**Symbols:**

```
c0967db0-c0967dcc: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (c0000000009004a0)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
c0000000009004a0-c0000000009004b0: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffe000538a8e)
Location: drivers/tty/n_null.c:22
Inline: True
```
**Symbols:**

```
ffffffe000538a8e-ffffffe000538aac: n_null_read (STB_LOCAL)
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
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff81654e10)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff81654e10-ffffffff81654e22: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff816351d0)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff816351d0-ffffffff816351e2: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff816831d0)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff816831d0-ffffffff816831e2: n_null_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t n_null_read(struct tty_struct *tty, struct file *file, unsigned char *buf, size_t nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/n_null.c (ffffffff8169d800)
Location: drivers/tty/n_null.c:22
Inline: False
```
**Symbols:**

```
ffffffff8169d800-ffffffff8169d812: n_null_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void **cookie</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int offset</code>
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
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned char *buf</code> ➡️ <code>u8 *buf</code>
</li>
</ul>
</details>
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
