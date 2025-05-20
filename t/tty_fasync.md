# Function: <code>tty_fasync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e12c0)
Location: drivers/tty/tty_io.c:2250
Inline: False
```
**Symbols:**

```
ffffffff814e12c0-ffffffff814e1310: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81531020)
Location: drivers/tty/tty_io.c:2254
Inline: False
```
**Symbols:**

```
ffffffff81531020-ffffffff8153107f: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155d770)
Location: drivers/tty/tty_io.c:2254
Inline: False
```
**Symbols:**

```
ffffffff8155d770-ffffffff8155d7cf: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572660)
Location: drivers/tty/tty_io.c:2012
Inline: False
```
**Symbols:**

```
ffffffff81572660-ffffffff815726c4: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d69e0)
Location: drivers/tty/tty_io.c:2119
Inline: False
```
**Symbols:**

```
ffffffff815d69e0-ffffffff815d6a44: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8160f9d0)
Location: drivers/tty/tty_io.c:2137
Inline: False
```
**Symbols:**

```
ffffffff8160f9d0-ffffffff8160fa39: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162c980)
Location: drivers/tty/tty_io.c:2149
Inline: False
```
**Symbols:**

```
ffffffff8162c980-ffffffff8162c9e9: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816608e0)
Location: drivers/tty/tty_io.c:2153
Inline: False
```
**Symbols:**

```
ffffffff816608e0-ffffffff8166094a: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81682f30)
Location: drivers/tty/tty_io.c:2153
Inline: False
```
**Symbols:**

```
ffffffff81682f30-ffffffff81682f9a: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2152
Inline: False
```
**Symbols:**

```
ffffffff81736ed0-ffffffff81737026: tty_fasync (STB_LOCAL)
ffffffff81738795-ffffffff817387eb: tty_fasync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2236
Inline: False
```
**Symbols:**

```
ffffffff81752770-ffffffff817528c6: tty_fasync (STB_LOCAL)
ffffffff81c0765d-ffffffff81c076b3: tty_fasync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2271
Inline: False
```
**Symbols:**

```
ffffffff81735fb0-ffffffff81736106: tty_fasync (STB_LOCAL)
ffffffff81bf91c9-ffffffff81bf921f: tty_fasync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2267
Inline: False
```
**Symbols:**

```
ffffffff817b6970-ffffffff817b6ac6: tty_fasync (STB_LOCAL)
ffffffff81cf8966-ffffffff81cf89bc: tty_fasync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:2252
Inline: False
```
**Symbols:**

```
ffffffff818f39d0-ffffffff818f3b31: tty_fasync (STB_LOCAL)
ffffffff81ec0a11-ffffffff81ec0a61: tty_fasync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4b8d0)
Location: drivers/tty/tty_io.c:2247
Inline: False
```
**Symbols:**

```
ffffffff81a4b8d0-ffffffff81a4b943: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a95ad0)
Location: drivers/tty/tty_io.c:2256
Inline: False
```
**Symbols:**

```
ffffffff81a95ad0-ffffffff81a95b46: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae8530)
Location: drivers/tty/tty_io.c:2254
Inline: False
```
**Symbols:**

```
ffffffff81ae8530-ffffffff81ae85a6: tty_fasync (STB_LOCAL)
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
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010851098)
Location: drivers/tty/tty_io.c:2153
Inline: False
```
**Symbols:**

```
ffff800010851098-ffff800010851120: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095b3a0)
Location: drivers/tty/tty_io.c:2153
Inline: False
```
**Symbols:**

```
c095b3a0-c095b414: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ee690)
Location: drivers/tty/tty_io.c:2153
Inline: False
```
**Symbols:**

```
c0000000008ee690-c0000000008ee748: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052d79e)
Location: drivers/tty/tty_io.c:2153
Inline: False
```
**Symbols:**

```
ffffffe00052d79e-ffffffe00052d810: tty_fasync (STB_LOCAL)
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
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816489b0)
Location: drivers/tty/tty_io.c:2153
Inline: False
```
**Symbols:**

```
ffffffff816489b0-ffffffff81648a1a: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81628e10)
Location: drivers/tty/tty_io.c:2153
Inline: False
```
**Symbols:**

```
ffffffff81628e10-ffffffff81628e7a: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81676d70)
Location: drivers/tty/tty_io.c:2153
Inline: False
```
**Symbols:**

```
ffffffff81676d70-ffffffff81676dda: tty_fasync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_fasync(int fd, struct file *filp, int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81691490)
Location: drivers/tty/tty_io.c:2153
Inline: False
```
**Symbols:**

```
ffffffff81691490-ffffffff816914fa: tty_fasync (STB_LOCAL)
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
