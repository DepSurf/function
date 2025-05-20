# Function: <code>f_setown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8121ebf0)
Location: fs/fcntl.c:109
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff8121ebf0-ffffffff8121ec41: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81246580)
Location: fs/fcntl.c:113
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81246580-ffffffff812465d1: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81259570)
Location: fs/fcntl.c:113
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81259570-ffffffff812595c1: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81265650)
Location: fs/fcntl.c:115
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81265650-ffffffff812656c9: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81288260)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81288260-ffffffff812882d9: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ae5b0)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812ae5b0-ffffffff812ae629: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c36a0)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812c36a0-ffffffff812c3719: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e00c0)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812e00c0-ffffffff812e013c: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f1b60)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812f1b60-ffffffff812f1bdc: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81329dd0)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81329dd0-ffffffff81329e4c: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81335330)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81335330-ffffffff813353b6: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8133b400)
Location: fs/fcntl.c:114
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff8133b400-ffffffff8133b486: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81389040)
Location: fs/fcntl.c:117
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81389040-ffffffff813890c6: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81409fa0)
Location: fs/fcntl.c:113
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81409fa0-ffffffff8140a04b: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81494730)
Location: fs/fcntl.c:114
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff81494730-ffffffff814947db: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814c9790)
Location: fs/fcntl.c:115
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff814c9790-ffffffff814c983b: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int f_setown(struct file *filp, int who, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814fc050)
Location: fs/fcntl.c:115
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff814fc050-ffffffff814fc0eb: f_setown (STB_GLOBAL)
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
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039b568)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffff80001039b568-ffff80001039b608: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0581798)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
c0581798-c058181c: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0000000004963d0)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
c0000000004963d0-c0000000004964c0: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffe00026867c)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffe00026867c-ffffffe000268700: f_setown (STB_GLOBAL)
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
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ea140)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812ea140-ffffffff812ea1bc: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dab10)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812dab10-ffffffff812dab8c: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e7f50)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812e7f50-ffffffff812e7fcc: f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int f_setown(struct file *filp, long unsigned int arg, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f8dc0)
Location: fs/fcntl.c:116
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - net/socket.c:sock_ioctl
```
**Symbols:**

```
ffffffff812f8dc0-ffffffff812f8e56: f_setown (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>int who</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int arg</code>
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
