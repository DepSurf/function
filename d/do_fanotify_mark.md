# Function: <code>do_fanotify_mark</code>

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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e8760)
Location: fs/notify/fanotify/fanotify_user.c:823
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff812e8760-ffffffff812e8e21: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fdb50)
Location: fs/notify/fanotify/fanotify_user.c:804
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff812fdb50-ffffffff812fe00a: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e6b0)
Location: fs/notify/fanotify/fanotify_user.c:939
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff8131e6b0-ffffffff8131ed77: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813314f0)
Location: fs/notify/fanotify/fanotify_user.c:947
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff813314f0-ffffffff81331b26: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136bff0)
Location: fs/notify/fanotify/fanotify_user.c:1016
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff8136bff0-ffffffff8136c554: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81379890)
Location: fs/notify/fanotify/fanotify_user.c:1109
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff81379890-ffffffff81379e6a: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380440)
Location: fs/notify/fanotify/fanotify_user.c:1248
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff81380440-ffffffff81380991: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd2a0)
Location: fs/notify/fanotify/fanotify_user.c:1356
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x64_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff813cd2a0-ffffffff813cd7eb: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81456880)
Location: fs/notify/fanotify/fanotify_user.c:1549
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff81456880-ffffffff81456f3b: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e5900)
Location: fs/notify/fanotify/fanotify_user.c:1589
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff814e5900-ffffffff814e6107: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151c3e0)
Location: fs/notify/fanotify/fanotify_user.c:1651
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff8151c3e0-ffffffff8151cc64: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81550910)
Location: fs/notify/fanotify/fanotify_user.c:1739
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff81550910-ffffffff81551246: do_fanotify_mark (STB_LOCAL)
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee8a8)
Location: fs/notify/fanotify/fanotify_user.c:947
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__arm64_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_mark
```
**Symbols:**

```
ffff8000103ee8a8-ffff8000103eee28: do_fanotify_mark (STB_LOCAL)
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
In fs/notify/fanotify/fanotify_user.c (c05c5940)
Location: fs/notify/fanotify/fanotify_user.c:947
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (c0000000004f70e0)
Location: fs/notify/fanotify/fanotify_user.c:947
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__se_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
**Symbols:**

```
c0000000004f70e0-c0000000004f7884: do_fanotify_mark (STB_LOCAL)
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
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a2872)
Location: fs/notify/fanotify/fanotify_user.c:947
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
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
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81329ad0)
Location: fs/notify/fanotify/fanotify_user.c:947
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff81329ad0-ffffffff8132a106: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a670)
Location: fs/notify/fanotify/fanotify_user.c:947
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff8131a670-ffffffff8131aca6: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813275a0)
Location: fs/notify/fanotify/fanotify_user.c:947
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff813275a0-ffffffff81327bd6: do_fanotify_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_fanotify_mark(int fanotify_fd, unsigned int flags, __u64 mask, int dfd, const char *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813399c0)
Location: fs/notify/fanotify/fanotify_user.c:947
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__x32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_compat_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_mark
```
**Symbols:**

```
ffffffff813399c0-ffffffff81339ff6: do_fanotify_mark (STB_LOCAL)
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
