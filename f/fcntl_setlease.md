# Function: <code>fcntl_setlease</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812627a0)
Location: fs/locks.c:1849
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff812627a0-ffffffff81262880: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128e9a0)
Location: fs/locks.c:1875
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff8128e9a0-ffffffff8128ea80: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a3930)
Location: fs/locks.c:1913
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff812a3930-ffffffff812a3a10: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b25d0)
Location: fs/locks.c:1913
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812b25d0-ffffffff812b26b0: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d6130)
Location: fs/locks.c:1923
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff812d6130-ffffffff812d6210: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81300ef0)
Location: fs/locks.c:1921
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81300ef0-ffffffff81300fdc: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81316950)
Location: fs/locks.c:2037
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81316950-ffffffff81316a3c: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133e1a0)
Location: fs/locks.c:2055
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8133e1a0-ffffffff8133e2ad: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81356790)
Location: fs/locks.c:2143
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81356790-ffffffff8135689d: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139d950)
Location: fs/locks.c:2146
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8139d950-ffffffff8139da77: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813af300)
Location: fs/locks.c:2147
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff813af300-ffffffff813af427: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b65c0)
Location: fs/locks.c:2150
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff813b65c0-ffffffff813b66e7: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814062c0)
Location: fs/locks.c:2053
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff814062c0-ffffffff814063e7: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8147acc0)
Location: fs/locks.c:2028
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8147acc0-ffffffff8147aedf: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150d800)
Location: fs/locks.c:2014
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8150d800-ffffffff8150da1f: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81544fd0)
Location: fs/locks.c:1991
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81544fd0-ffffffff815451f2: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8157a4c0)
Location: fs/locks.c:1998
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8157a4c0-ffffffff8157a6e1: fcntl_setlease (STB_GLOBAL)
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
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff8000104192b0)
Location: fs/locks.c:2143
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffff8000104192b0-ffff8000104193c8: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e5240)
Location: fs/locks.c:2143
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
c05e5240-c05e5368: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000528d10)
Location: fs/locks.c:2143
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
c000000000528d10-c000000000528e98: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bfa1a)
Location: fs/locks.c:2143
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl
```
**Symbols:**

```
ffffffe0002bfa1a-ffffffe0002bfb12: fcntl_setlease (STB_GLOBAL)
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
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134ed70)
Location: fs/locks.c:2143
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8134ed70-ffffffff8134ee7d: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133fa50)
Location: fs/locks.c:2143
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8133fa50-ffffffff8133fb5d: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134c840)
Location: fs/locks.c:2143
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8134c840-ffffffff8134c94d: fcntl_setlease (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fcntl_setlease(unsigned int fd, struct file *filp, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135fd80)
Location: fs/locks.c:2143
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff8135fd80-ffffffff8135fe8d: fcntl_setlease (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int arg</code> ➡️ <code>int arg</code>
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
