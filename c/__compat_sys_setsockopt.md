# Function: <code>__compat_sys_setsockopt</code>

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
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818c92e0)
Location: net/compat.c:387
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
**Symbols:**

```
ffffffff818c92e0-ffffffff818c94d6: __compat_sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818f41a0)
Location: net/compat.c:387
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
**Symbols:**

```
ffffffff818f41a0-ffffffff818f43ab: __compat_sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81953cf0)
Location: net/compat.c:363
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
**Symbols:**

```
ffffffff81953cf0-ffffffff81953e0f: __compat_sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8198a240)
Location: net/compat.c:363
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
**Symbols:**

```
ffffffff8198a240-ffffffff8198a35f: __compat_sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a625d0)
Location: net/compat.c:382
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
**Symbols:**

```
ffffffff81a625d0-ffffffff81a626ef: __compat_sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffff800010c32cf0)
Location: net/compat.c:363
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__arm64_compat_sys_setsockopt
```
**Symbols:**

```
ffff800010c32cf0-ffff800010c32e38: __compat_sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (c000000000d2bc90)
Location: net/compat.c:363
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__se_compat_sys_setsockopt
```
**Symbols:**

```
c000000000d2bc90-c000000000d2be58: __compat_sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8192a0b0)
Location: net/compat.c:363
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
**Symbols:**

```
ffffffff8192a0b0-ffffffff8192a1cf: __compat_sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818e3e60)
Location: net/compat.c:363
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
**Symbols:**

```
ffffffff818e3e60-ffffffff818e3f7f: __compat_sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8197b240)
Location: net/compat.c:363
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
**Symbols:**

```
ffffffff8197b240-ffffffff8197b35f: __compat_sys_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __compat_sys_setsockopt(int fd, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8199d790)
Location: net/compat.c:363
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_setsockopt
  - net/compat.c:__ia32_compat_sys_setsockopt
```
**Symbols:**

```
ffffffff8199d790-ffffffff8199d8af: __compat_sys_setsockopt (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
