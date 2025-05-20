# Function: <code>do_readlinkat</code>

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
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812a03b0)
Location: fs/stat.c:382
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff812a03b0-ffffffff812a04ce: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b5390)
Location: fs/stat.c:385
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff812b5390-ffffffff812b54ae: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d2140)
Location: fs/stat.c:387
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff812d2140-ffffffff812d225e: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3cd0)
Location: fs/stat.c:387
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff812e3cd0-ffffffff812e3dee: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131a5b0)
Location: fs/stat.c:407
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff8131a5b0-ffffffff8131a6ce: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81325c40)
Location: fs/stat.c:395
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff81325c40-ffffffff81325d5e: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132bd70)
Location: fs/stat.c:413
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff8132bd70-ffffffff8132be8e: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813794e0)
Location: fs/stat.c:431
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff813794e0-ffffffff813795fe: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f89a0)
Location: fs/stat.c:444
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff813f89a0-ffffffff813f8ad6: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81481f20)
Location: fs/stat.c:459
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff81481f20-ffffffff81482056: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b6b30)
Location: fs/stat.c:465
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff814b6b30-ffffffff814b6c66: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e8e60)
Location: fs/stat.c:487
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff814e8e60-ffffffff814e8f96: do_readlinkat (STB_LOCAL)
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
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038a758)
Location: fs/stat.c:387
Inline: False
Direct callers:
  - fs/stat.c:__arm64_sys_readlink
  - fs/stat.c:__arm64_sys_readlinkat
```
**Symbols:**

```
ffff80001038a758-ffff80001038a8a0: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0572ce4)
Location: fs/stat.c:387
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_readlink
  - fs/stat.c:__se_sys_readlinkat
```
**Symbols:**

```
c0572ce4-c0572e18: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000482ae0)
Location: fs/stat.c:387
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_readlink
  - fs/stat.c:__se_sys_readlinkat
```
**Symbols:**

```
c000000000482ae0-c000000000482cb0: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025ca9e)
Location: fs/stat.c:387
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_readlink
  - fs/stat.c:__se_sys_readlinkat
```
**Symbols:**

```
ffffffe00025ca9e-ffffffe00025cba0: do_readlinkat (STB_LOCAL)
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
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dc2b0)
Location: fs/stat.c:387
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff812dc2b0-ffffffff812dc3ce: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ccf30)
Location: fs/stat.c:387
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff812ccf30-ffffffff812cd04e: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812da0c0)
Location: fs/stat.c:387
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff812da0c0-ffffffff812da1de: do_readlinkat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char *pathname, char *buf, int bufsiz);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812eafd0)
Location: fs/stat.c:387
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_readlink
  - fs/stat.c:__x64_sys_readlink
  - fs/stat.c:__ia32_sys_readlinkat
  - fs/stat.c:__x64_sys_readlinkat
```
**Symbols:**

```
ffffffff812eafd0-ffffffff812eb0ee: do_readlinkat (STB_LOCAL)
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
