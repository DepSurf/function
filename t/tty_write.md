# Function: <code>tty_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e19a0)
Location: drivers/tty/tty_io.c:1228
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff814e19a0-ffffffff814e1c70: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815312f0)
Location: drivers/tty/tty_io.c:1236
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff815312f0-ffffffff815315dc: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155da40)
Location: drivers/tty/tty_io.c:1236
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff8155da40-ffffffff8155dd27: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572950)
Location: drivers/tty/tty_io.c:1001
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81572950-ffffffff81572c63: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d6cd0)
Location: drivers/tty/tty_io.c:1013
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff815d6cd0-ffffffff815d6fe1: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1031
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff8160fcf0-ffffffff8161001e: tty_write (STB_LOCAL)
ffffffff816130c0-ffffffff816130ee: tty_write.cold.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1023
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff8162cba0-ffffffff8162cea0: tty_write (STB_LOCAL)
ffffffff81630160-ffffffff8163018e: tty_write.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1025
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81662d20-ffffffff81662fba: tty_write (STB_LOCAL)
ffffffff81664338-ffffffff81664366: tty_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1025
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81685390-ffffffff8168562a: tty_write (STB_LOCAL)
ffffffff8168697f-ffffffff816869ad: tty_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1026
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81734760-ffffffff81734825: tty_write (STB_LOCAL)
ffffffff81738492-ffffffff817384c2: tty_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t tty_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817519f5)
Location: drivers/tty/tty_io.c:1122
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81751170-ffffffff81751183: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t tty_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81735c65)
Location: drivers/tty/tty_io.c:1138
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81735180-ffffffff81735193: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t tty_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b6625)
Location: drivers/tty/tty_io.c:1129
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff817b5b80-ffffffff817b5b93: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t tty_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f1d81)
Location: drivers/tty/tty_io.c:1114
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff818f1db0-ffffffff818f1dcb: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t tty_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4a361)
Location: drivers/tty/tty_io.c:1108
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81a4a3a0-ffffffff81a4a3bb: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t tty_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a94581)
Location: drivers/tty/tty_io.c:1117
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81a945c0-ffffffff81a945db: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t tty_write(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae7141)
Location: drivers/tty/tty_io.c:1115
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81ae7180-ffffffff81ae719b: tty_write (STB_LOCAL)
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
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010850430)
Location: drivers/tty/tty_io.c:1025
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffff800010850430-ffff8000108507c8: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095d718)
Location: drivers/tty/tty_io.c:1025
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
c095d718-c095d9ec: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008eea70)
Location: drivers/tty/tty_io.c:1025
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
c0000000008eea70-c0000000008eed84: tty_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052d9c2)
Location: drivers/tty/tty_io.c:1025
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffe00052d9c2-ffffffe00052dbc2: tty_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1025
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff8164ae10-ffffffff8164b0aa: tty_write (STB_LOCAL)
ffffffff8164c3ff-ffffffff8164c42d: tty_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1025
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff8162b260-ffffffff8162b4fa: tty_write (STB_LOCAL)
ffffffff8162c84f-ffffffff8162c87d: tty_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1025
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff816791d0-ffffffff8167946a: tty_write (STB_LOCAL)
ffffffff8167a7bf-ffffffff8167a7ed: tty_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t tty_write(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1025
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:redirected_tty_write
```
**Symbols:**

```
ffffffff81693820-ffffffff81693ab1: tty_write (STB_LOCAL)
ffffffff81694e27-ffffffff81694e55: tty_write.cold (STB_LOCAL)
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
<code>struct kiocb *iocb</code>
</li>
<li>
<b>Param added. </b>
<code>struct iov_iter *from</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t *ppos</code>
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
