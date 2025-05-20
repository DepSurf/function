# Function: <code>unix_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff817bda60)
Location: net/unix/af_unix.c:2607
Inline: False
```
**Symbols:**

```
ffffffff817bda60-ffffffff817bdaba: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8182a9d0)
Location: net/unix/af_unix.c:2600
Inline: False
```
**Symbols:**

```
ffffffff8182a9d0-ffffffff8182aa2a: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8185c450)
Location: net/unix/af_unix.c:2595
Inline: False
```
**Symbols:**

```
ffffffff8185c450-ffffffff8185c4aa: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81880d20)
Location: net/unix/af_unix.c:2636
Inline: False
```
**Symbols:**

```
ffffffff81880d20-ffffffff81880ea2: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81901eb0)
Location: net/unix/af_unix.c:2615
Inline: False
```
**Symbols:**

```
ffffffff81901eb0-ffffffff81902032: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8195c500)
Location: net/unix/af_unix.c:2605
Inline: False
```
**Symbols:**

```
ffffffff8195c500-ffffffff8195c67b: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198e0e0)
Location: net/unix/af_unix.c:2621
Inline: False
```
**Symbols:**

```
ffffffff8198e0e0-ffffffff8198e248: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819f9670)
Location: net/unix/af_unix.c:2557
Inline: False
```
**Symbols:**

```
ffffffff819f9670-ffffffff819f97e4: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a302d0)
Location: net/unix/af_unix.c:2569
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81a302d0-ffffffff81a30444: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b240be)
Location: net/unix/af_unix.c:2620
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81b24040-ffffffff81b240ac: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b32b2e)
Location: net/unix/af_unix.c:2611
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81b32ab0-ffffffff81b32b20: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b207a0)
Location: net/unix/af_unix.c:2660
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81b207a0-ffffffff81b20917: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be5620)
Location: net/unix/af_unix.c:2984
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81be5620-ffffffff81be57f8: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d7c5c0)
Location: net/unix/af_unix.c:3068
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81d7c5c0-ffffffff81d7c79c: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f49630)
Location: net/unix/af_unix.c:3104
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81f49630-ffffffff81f4980c: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81fa92a0)
Location: net/unix/af_unix.c:3019
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81fa92a0-ffffffff81fa947c: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff82076730)
Location: net/unix/af_unix.c:3036
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff82076730-ffffffff8207690c: unix_ioctl (STB_LOCAL)
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
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffff800010ceff80)
Location: net/unix/af_unix.c:2569
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffff800010ceff80-ffff800010cf02d8: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c0df746c)
Location: net/unix/af_unix.c:2569
Inline: False
```
**Symbols:**

```
c0df746c-c0df7630: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c000000000e15be0)
Location: net/unix/af_unix.c:2569
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
c000000000e15be0-c000000000e15ec0: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffe00083c96e)
Location: net/unix/af_unix.c:2569
Inline: False
```
**Symbols:**

```
ffffffe00083c96e-ffffffe00083cacc: unix_ioctl (STB_LOCAL)
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
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819cf960)
Location: net/unix/af_unix.c:2569
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff819cf960-ffffffff819cfad4: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198c720)
Location: net/unix/af_unix.c:2569
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff8198c720-ffffffff8198c894: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a3a3e0)
Location: net/unix/af_unix.c:2569
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81a3a3e0-ffffffff81a3a554: unix_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unix_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a45ac0)
Location: net/unix/af_unix.c:2569
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_compat_ioctl
```
**Symbols:**

```
ffffffff81a45ac0-ffffffff81a45c34: unix_ioctl (STB_LOCAL)
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
