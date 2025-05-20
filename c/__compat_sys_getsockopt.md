# Function: <code>__compat_sys_getsockopt</code>

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
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818c90c0)
Location: net/compat.c:514
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
**Symbols:**

```
ffffffff818c90c0-ffffffff818c9280: __compat_sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818f3f70)
Location: net/compat.c:519
Inline: False
Direct callers:
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
**Symbols:**

```
ffffffff818f3f70-ffffffff818f413c: __compat_sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff819538e0)
Location: net/compat.c:400
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
**Symbols:**

```
ffffffff819538e0-ffffffff819539b4: __compat_sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81989e30)
Location: net/compat.c:400
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
**Symbols:**

```
ffffffff81989e30-ffffffff81989f04: __compat_sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a621f0)
Location: net/compat.c:419
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
**Symbols:**

```
ffffffff81a621f0-ffffffff81a622c4: __compat_sys_getsockopt (STB_LOCAL)
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
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffff800010c32618)
Location: net/compat.c:400
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__arm64_compat_sys_getsockopt
```
**Symbols:**

```
ffff800010c32618-ffff800010c32710: __compat_sys_getsockopt (STB_LOCAL)
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
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (c000000000d2b8d0)
Location: net/compat.c:400
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__se_compat_sys_getsockopt
```
**Symbols:**

```
c000000000d2b8d0-c000000000d2ba1c: __compat_sys_getsockopt (STB_LOCAL)
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
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81929ca0)
Location: net/compat.c:400
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
**Symbols:**

```
ffffffff81929ca0-ffffffff81929d74: __compat_sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818e3a50)
Location: net/compat.c:400
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
**Symbols:**

```
ffffffff818e3a50-ffffffff818e3b24: __compat_sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8197ae30)
Location: net/compat.c:400
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
**Symbols:**

```
ffffffff8197ae30-ffffffff8197af04: __compat_sys_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __compat_sys_getsockopt(int fd, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8199d380)
Location: net/compat.c:400
Inline: False
Direct callers:
  - net/compat.c:__do_compat_sys_socketcall
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
**Symbols:**

```
ffffffff8199d380-ffffffff8199d454: __compat_sys_getsockopt (STB_LOCAL)
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
