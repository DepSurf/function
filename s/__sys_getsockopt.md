# Function: <code>__sys_getsockopt</code>

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
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81870290)
Location: net/socket.c:1933
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
```
**Symbols:**

```
ffffffff81870290-ffffffff81870363: __sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81890e60)
Location: net/socket.c:1920
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
```
**Symbols:**

```
ffffffff81890e60-ffffffff81890f33: __sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dabc0)
Location: net/socket.c:2108
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
```
**Symbols:**

```
ffffffff818dabc0-ffffffff818dacd9: __sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190cd10)
Location: net/socket.c:2108
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
```
**Symbols:**

```
ffffffff8190cd10-ffffffff8190ce29: __sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dea80)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
```
**Symbols:**

```
ffffffff819dea80-ffffffff819deb99: __sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1690)
Location: net/socket.c:2133
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e1690-ffffffff819e180b: __sys_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c76e0)
Location: net/socket.c:2127
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c76e0-ffffffff819c78ae: __sys_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a76a30)
Location: net/socket.c:2200
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a76a30-ffffffff81a76bf7: __sys_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be9c10)
Location: net/socket.c:2275
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be9c10-ffffffff81be9ddc: __sys_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d964d0)
Location: net/socket.c:2267
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d964d0-ffffffff81d9669c: __sys_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e04b20)
Location: net/socket.c:2302
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e04b20-ffffffff81e04cec: __sys_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec14d0)
Location: net/socket.c:2390
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ec14d0-ffffffff81ec15a2: __sys_getsockopt (STB_GLOBAL)
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
In net/socket.c (ffff800010ba2a78)
Location: net/socket.c:2108
Inline: True
Inline callers:
  - net/socket.c:__arm64_sys_getsockopt
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
In net/socket.c (c0cc6dbc)
Location: net/socket.c:2108
Inline: True
Inline callers:
  - net/socket.c:__se_sys_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c787f0)
Location: net/socket.c:2108
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_getsockopt
```
**Symbols:**

```
c000000000c787f0-c000000000c78a14: __sys_getsockopt (STB_LOCAL)
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
In net/socket.c (ffffffe00073bbce)
Location: net/socket.c:2108
Inline: True
Inline callers:
  - net/socket.c:__se_sys_getsockopt
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
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818acd10)
Location: net/socket.c:2108
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
```
**Symbols:**

```
ffffffff818acd10-ffffffff818ace29: __sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81866c60)
Location: net/socket.c:2108
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
```
**Symbols:**

```
ffffffff81866c60-ffffffff81866d79: __sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818fdd10)
Location: net/socket.c:2108
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
```
**Symbols:**

```
ffffffff818fdd10-ffffffff818fde29: __sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8191eda0)
Location: net/socket.c:2108
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_getsockopt
  - net/socket.c:__x64_sys_getsockopt
```
**Symbols:**

```
ffffffff8191eda0-ffffffff8191eeb9: __sys_getsockopt (STB_LOCAL)
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
