# Function: <code>do_epoll_create</code>

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
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812eb790)
Location: fs/eventpoll.c:1938
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff812eb790-ffffffff812eb8ea: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812ff260)
Location: fs/eventpoll.c:1964
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff812ff260-ffffffff812ff3b9: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81320400)
Location: fs/eventpoll.c:2042
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff81320400-ffffffff8132056e: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813331b0)
Location: fs/eventpoll.c:2042
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff813331b0-ffffffff8133331e: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8136dc48)
Location: fs/eventpoll.c:2040
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff8136d5a0-ffffffff8136d672: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137c8e8)
Location: fs/eventpoll.c:1951
Inline: True
Inline callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff8137aff0-ffffffff8137b0c2: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81381b40)
Location: fs/eventpoll.c:1957
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff81381b40-ffffffff81381ce4: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813ced90)
Location: fs/eventpoll.c:1958
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff813ced90-ffffffff813cef34: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81457960)
Location: fs/eventpoll.c:1987
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff81457960-ffffffff81457b10: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814e6c40)
Location: fs/eventpoll.c:1989
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff814e6c40-ffffffff814e6df0: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8151e750)
Location: fs/eventpoll.c:2038
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff8151e750-ffffffff8151e90a: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81552d30)
Location: fs/eventpoll.c:2029
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff81552d30-ffffffff81552f11: do_epoll_create (STB_LOCAL)
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
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffff8000103f04f0)
Location: fs/eventpoll.c:2042
Inline: False
Direct callers:
  - fs/eventpoll.c:__arm64_sys_epoll_create
  - fs/eventpoll.c:__arm64_sys_epoll_create1
```
**Symbols:**

```
ffff8000103f04f0-ffff8000103f0644: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c05c781c)
Location: fs/eventpoll.c:2042
Inline: False
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_create
  - fs/eventpoll.c:__se_sys_epoll_create1
```
**Symbols:**

```
c05c781c-c05c7960: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c0000000004f9c70)
Location: fs/eventpoll.c:2042
Inline: False
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_create
  - fs/eventpoll.c:__se_sys_epoll_create1
```
**Symbols:**

```
c0000000004f9c70-c0000000004f9e68: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffe0002a3e98)
Location: fs/eventpoll.c:2042
Inline: False
Direct callers:
  - fs/eventpoll.c:__se_sys_epoll_create
  - fs/eventpoll.c:__se_sys_epoll_create1
```
**Symbols:**

```
ffffffe0002a3e98-ffffffe0002a3ff2: do_epoll_create (STB_LOCAL)
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
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132b790)
Location: fs/eventpoll.c:2042
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff8132b790-ffffffff8132b8fe: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8131d0e0)
Location: fs/eventpoll.c:2042
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff8131d0e0-ffffffff8131d24e: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81329260)
Location: fs/eventpoll.c:2042
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff81329260-ffffffff813293ce: do_epoll_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_epoll_create(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8133b980)
Location: fs/eventpoll.c:2042
Inline: False
Direct callers:
  - fs/eventpoll.c:__ia32_sys_epoll_create
  - fs/eventpoll.c:__x64_sys_epoll_create
  - fs/eventpoll.c:__ia32_sys_epoll_create1
  - fs/eventpoll.c:__x64_sys_epoll_create1
```
**Symbols:**

```
ffffffff8133b980-ffffffff8133baee: do_epoll_create (STB_LOCAL)
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
