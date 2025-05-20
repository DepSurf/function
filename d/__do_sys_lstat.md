# Function: <code>__do_sys_lstat</code>

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
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f6c0)
Location: fs/stat.c:257
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff8129f6c0-ffffffff8129f730: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b46a0)
Location: fs/stat.c:257
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff812b46a0-ffffffff812b4710: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1420)
Location: fs/stat.c:259
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff812d1420-ffffffff812d1492: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e2fb0)
Location: fs/stat.c:259
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff812e2fb0-ffffffff812e3022: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131a950)
Location: fs/stat.c:279
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff8131a950-ffffffff8131a9bd: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81326140)
Location: fs/stat.c:267
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff81326140-ffffffff813261ad: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c250)
Location: fs/stat.c:285
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff8132c250-ffffffff8132c2bd: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813799c0)
Location: fs/stat.c:303
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff813799c0-ffffffff81379a2d: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f93e0)
Location: fs/stat.c:317
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff813f93e0-ffffffff813f946a: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482b40)
Location: fs/stat.c:332
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff81482b40-ffffffff81482bca: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7760)
Location: fs/stat.c:338
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff814b7760-ffffffff814b77ea: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e9730)
Location: fs/stat.c:366
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff814e9730-ffffffff814e97e4: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812db590)
Location: fs/stat.c:259
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff812db590-ffffffff812db602: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cc210)
Location: fs/stat.c:259
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff812cc210-ffffffff812cc282: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d93a0)
Location: fs/stat.c:259
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff812d93a0-ffffffff812d9412: __do_sys_lstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_lstat(const char *filename, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ea2b0)
Location: fs/stat.c:259
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_lstat
  - fs/stat.c:__x64_sys_lstat
```
**Symbols:**

```
ffffffff812ea2b0-ffffffff812ea322: __do_sys_lstat (STB_LOCAL)
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
