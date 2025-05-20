# Function: <code>__sys_listen</code>

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
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81872980)
Location: net/socket.c:1515
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81872980-ffffffff81872a26: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818932d0)
Location: net/socket.c:1502
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818932d0-ffffffff81893376: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dd5e0)
Location: net/socket.c:1667
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818dd5e0-ffffffff818dd686: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190f640)
Location: net/socket.c:1667
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8190f640-ffffffff8190f6e6: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0f40)
Location: net/socket.c:1677
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0f40-ffffffff819e0fe6: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0790)
Location: net/socket.c:1655
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0790-ffffffff819e0836: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c67e0)
Location: net/socket.c:1646
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c67e0-ffffffff819c6886: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a75b00)
Location: net/socket.c:1716
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a75b00-ffffffff81a75ba6: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8af0)
Location: net/socket.c:1796
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be8af0-ffffffff81be8bae: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95260)
Location: net/socket.c:1796
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d95260-ffffffff81d9531e: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e03880)
Location: net/socket.c:1825
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e03880-ffffffff81e03939: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec02b0)
Location: net/socket.c:1867
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ec02b0-ffffffff81ec0369: __sys_listen (STB_GLOBAL)
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
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba7828)
Location: net/socket.c:1667
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff800010ba7828-ffff800010ba78ec: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6250)
Location: net/socket.c:1667
Inline: False
Direct callers:
  - net/socket.c:__se_sys_listen
```
**Symbols:**

```
c0cc6250-c0cc6314: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7bd10)
Location: net/socket.c:1667
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000c7bd10-c000000000c7be08: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073b1b0)
Location: net/socket.c:1667
Inline: False
Direct callers:
  - net/socket.c:__se_sys_listen
```
**Symbols:**

```
ffffffe00073b1b0-ffffffe00073b23e: __sys_listen (STB_GLOBAL)
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
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818af640)
Location: net/socket.c:1667
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818af640-ffffffff818af6e6: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869590)
Location: net/socket.c:1667
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81869590-ffffffff81869636: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81900640)
Location: net/socket.c:1667
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81900640-ffffffff819006e6: __sys_listen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_listen(int fd, int backlog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81921630)
Location: net/socket.c:1667
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_listen
  - net/socket.c:__x64_sys_listen
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81921630-ffffffff819216d6: __sys_listen (STB_GLOBAL)
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
