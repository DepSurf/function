# Function: <code>__sys_socketpair</code>

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
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81872590)
Location: net/socket.c:1375
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81872590-ffffffff818727c6: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81892ee0)
Location: net/socket.c:1362
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__x32_compat_sys_socketcall
  - net/compat.c:__ia32_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81892ee0-ffffffff81893116: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818dd1d0)
Location: net/socket.c:1527
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818dd1d0-ffffffff818dd421: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8190f230)
Location: net/socket.c:1527
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff8190f230-ffffffff8190f481: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0b30)
Location: net/socket.c:1537
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0b30-ffffffff819e0d81: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0380)
Location: net/socket.c:1515
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819e0380-ffffffff819e05d7: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c63e0)
Location: net/socket.c:1506
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff819c63e0-ffffffff819c664b: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a75700)
Location: net/socket.c:1576
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81a75700-ffffffff81a7596b: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8680)
Location: net/socket.c:1656
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81be8680-ffffffff81be8914: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d94d90)
Location: net/socket.c:1656
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81d94d90-ffffffff81d95024: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e033d0)
Location: net/socket.c:1685
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81e033d0-ffffffff81e03647: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebfe00)
Location: net/socket.c:1727
Inline: False
Direct callers:
  - net/socket.c:__do_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81ebfe00-ffffffff81ec0077: __sys_socketpair (STB_GLOBAL)
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
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba7360)
Location: net/socket.c:1527
Inline: False
Direct callers:
  - net/socket.c:__arm64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffff800010ba7360-ffff800010ba76a4: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc5e4c)
Location: net/socket.c:1527
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketpair
```
**Symbols:**

```
c0cc5e4c-c0cc6138: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7b710)
Location: net/socket.c:1527
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketcall
  - net/socket.c:__se_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
c000000000c7b710-c000000000c7bb38: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073ae54)
Location: net/socket.c:1527
Inline: False
Direct callers:
  - net/socket.c:__se_sys_socketpair
```
**Symbols:**

```
ffffffe00073ae54-ffffffe00073b074: __sys_socketpair (STB_GLOBAL)
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
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818af230)
Location: net/socket.c:1527
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff818af230-ffffffff818af481: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81869180)
Location: net/socket.c:1527
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81869180-ffffffff818693d1: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81900230)
Location: net/socket.c:1527
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81900230-ffffffff81900481: __sys_socketpair (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sys_socketpair(int family, int type, int protocol, int *usockvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81921220)
Location: net/socket.c:1527
Inline: False
Direct callers:
  - net/socket.c:__ia32_sys_socketcall
  - net/socket.c:__x64_sys_socketcall
  - net/socket.c:__ia32_sys_socketpair
  - net/socket.c:__x64_sys_socketpair
  - net/compat.c:__do_compat_sys_socketcall
```
**Symbols:**

```
ffffffff81921220-ffffffff81921471: __sys_socketpair (STB_GLOBAL)
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
