# Function: <code>pty_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff814ecbf0)
Location: drivers/tty/pty.c:41
Inline: True
```
**Symbols:**

```
ffffffff814ecbf0-ffffffff814ecd65: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8153dbd0)
Location: drivers/tty/pty.c:41
Inline: True
```
**Symbols:**

```
ffffffff8153dbd0-ffffffff8153dd51: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8156a220)
Location: drivers/tty/pty.c:41
Inline: True
```
**Symbols:**

```
ffffffff8156a220-ffffffff8156a3a1: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8157e790)
Location: drivers/tty/pty.c:44
Inline: True
```
**Symbols:**

```
ffffffff8157e790-ffffffff8157e904: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff815e3380)
Location: drivers/tty/pty.c:45
Inline: False
```
**Symbols:**

```
ffffffff815e3380-ffffffff815e34f2: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8161c650)
Location: drivers/tty/pty.c:45
Inline: False
```
**Symbols:**

```
ffffffff8161c650-ffffffff8161c7c2: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff816398d0)
Location: drivers/tty/pty.c:46
Inline: False
```
**Symbols:**

```
ffffffff816398d0-ffffffff81639a42: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/pty.c (0)
Location: drivers/tty/pty.c:46
Inline: False
```
**Symbols:**

```
ffffffff8166dbe0-ffffffff8166dd50: pty_close (STB_LOCAL)
ffffffff8166de49-ffffffff8166de5c: pty_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff816901d0)
Location: drivers/tty/pty.c:46
Inline: True
```
**Symbols:**

```
ffffffff816901d0-ffffffff81690342: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81742920)
Location: drivers/tty/pty.c:46
Inline: False
```
**Symbols:**

```
ffffffff81742920-ffffffff81742a8f: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8175e7c0)
Location: drivers/tty/pty.c:46
Inline: False
```
**Symbols:**

```
ffffffff8175e7c0-ffffffff8175e92f: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81742600)
Location: drivers/tty/pty.c:47
Inline: False
```
**Symbols:**

```
ffffffff81742600-ffffffff81742764: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff817c3040)
Location: drivers/tty/pty.c:47
Inline: True
```
**Symbols:**

```
ffffffff817c3040-ffffffff817c31a4: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff818ff450)
Location: drivers/tty/pty.c:47
Inline: True
```
**Symbols:**

```
ffffffff818ff450-ffffffff818ff5ca: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81a58810)
Location: drivers/tty/pty.c:47
Inline: False
```
**Symbols:**

```
ffffffff81a58810-ffffffff81a5898a: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81aa2e30)
Location: drivers/tty/pty.c:47
Inline: False
```
**Symbols:**

```
ffffffff81aa2e30-ffffffff81aa2faa: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81af57a0)
Location: drivers/tty/pty.c:47
Inline: False
```
**Symbols:**

```
ffffffff81af57a0-ffffffff81af591a: pty_close (STB_LOCAL)
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
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffff800010862ab0)
Location: drivers/tty/pty.c:46
Inline: False
```
**Symbols:**

```
ffff800010862ab0-ffff800010862ca4: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (c0968a0c)
Location: drivers/tty/pty.c:46
Inline: True
```
**Symbols:**

```
c0968a0c-c0968b9c: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (c000000000901bd0)
Location: drivers/tty/pty.c:46
Inline: False
```
**Symbols:**

```
c000000000901bd0-c000000000901e0c: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffe000539b2e)
Location: drivers/tty/pty.c:46
Inline: False
```
**Symbols:**

```
ffffffe000539b2e-ffffffe000539cb8: pty_close (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81655c50)
Location: drivers/tty/pty.c:46
Inline: True
```
**Symbols:**

```
ffffffff81655c50-ffffffff81655dc2: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81635ff0)
Location: drivers/tty/pty.c:46
Inline: True
```
**Symbols:**

```
ffffffff81635ff0-ffffffff8163615c: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81684010)
Location: drivers/tty/pty.c:46
Inline: True
```
**Symbols:**

```
ffffffff81684010-ffffffff81684182: pty_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pty_close(struct tty_struct *tty, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8169e230)
Location: drivers/tty/pty.c:46
Inline: True
```
**Symbols:**

```
ffffffff8169e230-ffffffff8169e399: pty_close (STB_LOCAL)
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
