# Function: <code>do_recvmmsg</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81892a90)
Location: net/socket.c:2343
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff81892a90-ffffffff81892d7b: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dcd70)
Location: net/socket.c:2554
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff818dcd70-ffffffff818dd061: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190da70)
Location: net/socket.c:2634
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8190da70-ffffffff8190dd80: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1ff0)
Location: net/socket.c:2668
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff819e1ff0-ffffffff819e22f0: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1c90)
Location: net/socket.c:2663
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff819e1c90-ffffffff819e1f6f: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c7cf0)
Location: net/socket.c:2647
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff819c7cf0-ffffffff819c7fd3: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a77040)
Location: net/socket.c:2720
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff81a77040-ffffffff81a77323: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81bea300)
Location: net/socket.c:2796
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff81bea300-ffffffff81bea643: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d96bb0)
Location: net/socket.c:2784
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff81d96bb0-ffffffff81d96ef3: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e05220)
Location: net/socket.c:2822
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff81e05220-ffffffff81e05563: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec1ae0)
Location: net/socket.c:2892
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__x64_sys_recvmmsg_time32
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__ia32_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
  - net/socket.c:__x64_sys_recvmmsg
```
**Symbols:**

```
ffffffff81ec1ae0-ffffffff81ec1e23: do_recvmmsg (STB_LOCAL)
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
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba4b28)
Location: net/socket.c:2634
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffff800010ba4b28-ffff800010ba4f94: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc5a48)
Location: net/socket.c:2634
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
c0cc5a48-c0cc5d20: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c783a0)
Location: net/socket.c:2634
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
c000000000c783a0-c000000000c787f0: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073a8f2)
Location: net/socket.c:2634
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffe00073a8f2-ffffffe00073aade: do_recvmmsg (STB_LOCAL)
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
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ada70)
Location: net/socket.c:2634
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff818ada70-ffffffff818add80: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818679c0)
Location: net/socket.c:2634
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff818679c0-ffffffff81867cd0: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fea70)
Location: net/socket.c:2634
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff818fea70-ffffffff818fed80: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_recvmmsg(int fd, struct mmsghdr *mmsg, unsigned int vlen, unsigned int flags, struct timespec64 *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191faf0)
Location: net/socket.c:2634
Inline: False
Direct callers:
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
  - net/socket.c:__sys_recvmmsg
```
**Symbols:**

```
ffffffff8191faf0-ffffffff8191fdc3: do_recvmmsg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
