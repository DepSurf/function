# Function: <code>get_epoll_tfile_raw_ptr</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8129ed80)
Location: fs/eventpoll.c:1105
Inline: False
Direct callers:
  - kernel/kcmp.c:SyS_kcmp
```
**Symbols:**

```
ffffffff8129ed80-ffffffff8129ee1e: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812c21f0)
Location: fs/eventpoll.c:1085
Inline: False
Direct callers:
  - kernel/kcmp.c:SyS_kcmp
```
**Symbols:**

```
ffffffff812c21f0-ffffffff812c2286: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812ecaa0)
Location: fs/eventpoll.c:1087
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
**Symbols:**

```
ffffffff812ecaa0-ffffffff812ecb34: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813014b0)
Location: fs/eventpoll.c:1091
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
**Symbols:**

```
ffffffff813014b0-ffffffff81301540: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813229e0)
Location: fs/eventpoll.c:1092
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff813229e0-ffffffff81322a72: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81335780)
Location: fs/eventpoll.c:1092
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff81335780-ffffffff81335812: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8136ecb0)
Location: fs/eventpoll.c:1085
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
**Symbols:**

```
ffffffff8136ecb0-ffffffff8136ed42: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8137cac0)
Location: fs/eventpoll.c:1002
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
**Symbols:**

```
ffffffff8137cac0-ffffffff8137cb52: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81383460)
Location: fs/eventpoll.c:1008
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff81383460-ffffffff813834f2: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff813d0700)
Location: fs/eventpoll.c:1008
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff813d0700-ffffffff813d0792: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814596c0)
Location: fs/eventpoll.c:1015
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff814596c0-ffffffff81459764: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff814e8b20)
Location: fs/eventpoll.c:1017
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff814e8b20-ffffffff814e8bc4: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8151f880)
Location: fs/eventpoll.c:1056
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff8151f880-ffffffff8151f927: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81553e90)
Location: fs/eventpoll.c:1047
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff81553e90-ffffffff81553f37: get_epoll_tfile_raw_ptr (STB_GLOBAL)
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
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffff8000103f2e90)
Location: fs/eventpoll.c:1092
Inline: False
Direct callers:
  - kernel/kcmp.c:kcmp_epoll_target
```
**Symbols:**

```
ffff8000103f2e90-ffff8000103f2f48: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c05c8438)
Location: fs/eventpoll.c:1092
Inline: False
Direct callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
**Symbols:**

```
c05c8438-c05c84d4: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (c0000000004fade0)
Location: fs/eventpoll.c:1092
Inline: False
Direct callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
**Symbols:**

```
c0000000004fade0-c0000000004faed4: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffe0002a44ea)
Location: fs/eventpoll.c:1092
Inline: False
Direct callers:
  - kernel/kcmp.c:__se_sys_kcmp
```
**Symbols:**

```
ffffffe0002a44ea-ffffffe0002a4574: get_epoll_tfile_raw_ptr (STB_GLOBAL)
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
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132dd60)
Location: fs/eventpoll.c:1092
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff8132dd60-ffffffff8132ddf2: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8131e9c0)
Location: fs/eventpoll.c:1092
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff8131e9c0-ffffffff8131ea52: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8132b830)
Location: fs/eventpoll.c:1092
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff8132b830-ffffffff8132b8c2: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *get_epoll_tfile_raw_ptr(struct file *file, int tfd, long unsigned int toff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8133e1f0)
Location: fs/eventpoll.c:1092
Inline: False
Direct callers:
  - kernel/kcmp.c:__do_sys_kcmp
```
**Symbols:**

```
ffffffff8133e1f0-ffffffff8133e278: get_epoll_tfile_raw_ptr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
