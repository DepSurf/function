# Function: <code>do_renameat2</code>

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
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ac6e0)
Location: fs/namei.c:4526
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
```
**Symbols:**

```
ffffffff812ac6e0-ffffffff812acc60: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c17e0)
Location: fs/namei.c:4515
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
```
**Symbols:**

```
ffffffff812c17e0-ffffffff812c1d60: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ddd60)
Location: fs/namei.c:4516
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
```
**Symbols:**

```
ffffffff812ddd60-ffffffff812de2c6: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ef880)
Location: fs/namei.c:4511
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
```
**Symbols:**

```
ffffffff812ef880-ffffffff812efde6: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81327b70)
Location: fs/namei.c:4342
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
```
**Symbols:**

```
ffffffff81327b70-ffffffff813280a6: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_renameat2(int olddfd, struct filename *from, int newdfd, struct filename *to, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334680)
Location: fs/namei.c:4342
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff81334680-ffffffff81334b9a: do_renameat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_renameat2(int olddfd, struct filename *from, int newdfd, struct filename *to, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8133a760)
Location: fs/namei.c:4580
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff8133a760-ffffffff8133ad26: do_renameat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_renameat2(int olddfd, struct filename *from, int newdfd, struct filename *to, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813883c0)
Location: fs/namei.c:4667
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - fs/io_uring.c:io_issue_sqe
```
**Symbols:**

```
ffffffff813883c0-ffffffff8138894a: do_renameat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_renameat2(int olddfd, struct filename *from, int newdfd, struct filename *to, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81409360)
Location: fs/namei.c:4762
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - io_uring/io_uring.c:io_renameat
```
**Symbols:**

```
ffffffff81409360-ffffffff81409980: do_renameat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_renameat2(int olddfd, struct filename *from, int newdfd, struct filename *to, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81493a10)
Location: fs/namei.c:4818
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - io_uring/fs.c:io_renameat
```
**Symbols:**

```
ffffffff81493a10-ffffffff81494032: do_renameat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_renameat2(int olddfd, struct filename *from, int newdfd, struct filename *to, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c8a50)
Location: fs/namei.c:4895
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - io_uring/fs.c:io_renameat
```
**Symbols:**

```
ffffffff814c8a50-ffffffff814c90a2: do_renameat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_renameat2(int olddfd, struct filename *from, int newdfd, struct filename *to, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fb300)
Location: fs/namei.c:4922
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
  - io_uring/fs.c:io_renameat
```
**Symbols:**

```
ffffffff814fb300-ffffffff814fb96e: do_renameat2 (STB_GLOBAL)
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
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010399058)
Location: fs/namei.c:4511
Inline: False
Direct callers:
  - fs/namei.c:__arm64_sys_rename
  - fs/namei.c:__arm64_sys_renameat
  - fs/namei.c:__arm64_sys_renameat2
```
**Symbols:**

```
ffff800010399058-ffff80001039952c: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057f6cc)
Location: fs/namei.c:4511
Inline: False
Direct callers:
  - fs/namei.c:__se_sys_rename
  - fs/namei.c:__se_sys_renameat
  - fs/namei.c:__se_sys_renameat2
```
**Symbols:**

```
c057f6cc-c057fba8: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000493740)
Location: fs/namei.c:4511
Inline: False
Direct callers:
  - fs/namei.c:__se_sys_rename
  - fs/namei.c:__se_sys_renameat
  - fs/namei.c:__se_sys_renameat2
```
**Symbols:**

```
c000000000493740-c000000000493e1c: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000266b26)
Location: fs/namei.c:4511
Inline: False
Direct callers:
  - fs/namei.c:__se_sys_rename
  - fs/namei.c:__se_sys_renameat
  - fs/namei.c:__se_sys_renameat2
```
**Symbols:**

```
ffffffe000266b26-ffffffe000266fae: do_renameat2 (STB_LOCAL)
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
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7e60)
Location: fs/namei.c:4511
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
```
**Symbols:**

```
ffffffff812e7e60-ffffffff812e83c6: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8aa0)
Location: fs/namei.c:4511
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
```
**Symbols:**

```
ffffffff812d8aa0-ffffffff812d9006: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5c70)
Location: fs/namei.c:4511
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
```
**Symbols:**

```
ffffffff812e5c70-ffffffff812e61d6: do_renameat2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_renameat2(int olddfd, const char *oldname, int newdfd, const char *newname, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f6bf0)
Location: fs/namei.c:4511
Inline: False
Direct callers:
  - fs/namei.c:__ia32_sys_rename
  - fs/namei.c:__x64_sys_rename
  - fs/namei.c:__ia32_sys_renameat
  - fs/namei.c:__x64_sys_renameat
  - fs/namei.c:__ia32_sys_renameat2
  - fs/namei.c:__x64_sys_renameat2
```
**Symbols:**

```
ffffffff812f6bf0-ffffffff812f7156: do_renameat2 (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct filename *from</code>
</li>
<li>
<b>Param added. </b>
<code>struct filename *to</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *oldname</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *newname</code>
</li>
</ul>
</details>
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
