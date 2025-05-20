# Function: <code>__sys_setsockopt</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818700e0)
Location: net/socket.c:1893
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
```
**Symbols:**

```
ffffffff818700e0-ffffffff818701c3: __sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890cb0)
Location: net/socket.c:1880
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
```
**Symbols:**

```
ffffffff81890cb0-ffffffff81890d93: __sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dc4a0)
Location: net/socket.c:2045
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
```
**Symbols:**

```
ffffffff818dc4a0-ffffffff818dc614: __sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190eef0)
Location: net/socket.c:2045
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
```
**Symbols:**

```
ffffffff8190eef0-ffffffff8190f064: __sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819df3d0)
Location: net/socket.c:2088
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
```
**Symbols:**

```
ffffffff819df3d0-ffffffff819df544: __sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *user_optval, int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1450)
Location: net/socket.c:2078
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e1450-ffffffff819e1624: __sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *user_optval, int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c74a0)
Location: net/socket.c:2069
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c74a0-ffffffff819c7674: __sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *user_optval, int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a767f0)
Location: net/socket.c:2142
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a767f0-ffffffff81a769c4: __sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *user_optval, int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be9990)
Location: net/socket.c:2217
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be9990-ffffffff81be9b87: __sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *user_optval, int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d96250)
Location: net/socket.c:2209
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d96250-ffffffff81d9641f: __sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *user_optval, int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e048a0)
Location: net/socket.c:2242
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e048a0-ffffffff81e04a70: __sys_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *user_optval, int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec1340)
Location: net/socket.c:2322
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ec1340-ffffffff81ec1415: __sys_setsockopt (STB_GLOBAL)
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
In net/socket.c (0)
Location: net/socket.c:2045
Inline: True
Inline callers:
  - net/socket.c:__arm64_sys_setsockopt
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
In net/socket.c (c0cc6c08)
Location: net/socket.c:2045
Inline: True
Inline callers:
  - net/socket.c:__se_sys_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c76520)
Location: net/socket.c:2045
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_setsockopt
```
**Symbols:**

```
c000000000c76520-c000000000c76730: __sys_setsockopt (STB_LOCAL)
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
In net/socket.c (ffffffe00073bab2)
Location: net/socket.c:2045
Inline: True
Inline callers:
  - net/socket.c:__se_sys_setsockopt
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
int __sys_setsockopt(int fd, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818aeef0)
Location: net/socket.c:2045
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
```
**Symbols:**

```
ffffffff818aeef0-ffffffff818af064: __sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81868e40)
Location: net/socket.c:2045
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
```
**Symbols:**

```
ffffffff81868e40-ffffffff81868fb4: __sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818ffef0)
Location: net/socket.c:2045
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
```
**Symbols:**

```
ffffffff818ffef0-ffffffff81900064: __sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_setsockopt(int fd, int level, int optname, char *optval, int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81920ee0)
Location: net/socket.c:2045
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_setsockopt
  - net/socket.c:__x64_sys_setsockopt
```
**Symbols:**

```
ffffffff81920ee0-ffffffff81921054: __sys_setsockopt (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>char *user_optval</code>
</li>
<li>
<b>Param removed. </b>
<code>char *optval</code>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
