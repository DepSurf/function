# Function: <code>__sys_shutdown</code>

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
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81873590)
Location: net/socket.c:1969
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81873590-ffffffff81873621: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81893ee0)
Location: net/socket.c:1956
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81893ee0-ffffffff81893f71: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818de200)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818de200-ffffffff818de291: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81910260)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81910260-ffffffff819102f1: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e1c00)
Location: net/socket.c:2194
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e1c00-ffffffff819e1c91: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e18b0)
Location: net/socket.c:2189
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e18b0-ffffffff819e193e: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c7950)
Location: net/socket.c:2183
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c7950-ffffffff819c79de: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a76ca0)
Location: net/socket.c:2256
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a76ca0-ffffffff81a76d2e: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be9ea0)
Location: net/socket.c:2331
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be9ea0-ffffffff81be9f44: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d967a0)
Location: net/socket.c:2323
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d967a0-ffffffff81d96844: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e04df0)
Location: net/socket.c:2360
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e04df0-ffffffff81e04e94: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec16b0)
Location: net/socket.c:2430
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ec16b0-ffffffff81ec1754: __sys_shutdown (STB_GLOBAL)
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
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba82b0)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff800010ba82b0-ffff800010ba8360: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6f08)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__se_sys_shutdown
```
**Symbols:**

```
c0cc6f08-c0cc6fb8: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7ca30)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000c7ca30-c000000000c7cb08: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073bcc4)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__se_sys_shutdown
```
**Symbols:**

```
ffffffe00073bcc4-ffffffe00073bd42: __sys_shutdown (STB_GLOBAL)
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
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818b0260)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818b0260-ffffffff818b02f1: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8186a1b0)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8186a1b0-ffffffff8186a241: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81901260)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81901260-ffffffff819012f1: __sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_shutdown(int fd, int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81922250)
Location: net/socket.c:2151
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81922250-ffffffff819222e1: __sys_shutdown (STB_GLOBAL)
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
