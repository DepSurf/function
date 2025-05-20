# Function: <code>__do_sys_fstat</code>

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
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f770)
Location: fs/stat.c:270
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff8129f770-ffffffff8129f7d6: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4750)
Location: fs/stat.c:270
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff812b4750-ffffffff812b47b6: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d14e0)
Location: fs/stat.c:272
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff812d14e0-ffffffff812d1548: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3070)
Location: fs/stat.c:272
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff812e3070-ffffffff812e30d8: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131af50)
Location: fs/stat.c:292
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff8131af50-ffffffff8131afb3: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81326690)
Location: fs/stat.c:280
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff81326690-ffffffff813266ec: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c7a0)
Location: fs/stat.c:298
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff8132c7a0-ffffffff8132c7fc: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379f10)
Location: fs/stat.c:316
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff81379f10-ffffffff81379f6c: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f8eb0)
Location: fs/stat.c:330
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff813f8eb0-ffffffff813f8f2d: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814824f0)
Location: fs/stat.c:345
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff814824f0-ffffffff8148256d: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7110)
Location: fs/stat.c:351
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff814b7110-ffffffff814b718d: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e9490)
Location: fs/stat.c:379
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff814e9490-ffffffff814e950d: __do_sys_fstat (STB_LOCAL)
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
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812db650)
Location: fs/stat.c:272
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff812db650-ffffffff812db6b8: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cc2d0)
Location: fs/stat.c:272
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff812cc2d0-ffffffff812cc338: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9460)
Location: fs/stat.c:272
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff812d9460-ffffffff812d94c8: __do_sys_fstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_fstat(unsigned int fd, struct __old_kernel_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ea370)
Location: fs/stat.c:272
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_fstat
  - fs/stat.c:__x64_sys_fstat
```
**Symbols:**

```
ffffffff812ea370-ffffffff812ea3d8: __do_sys_fstat (STB_LOCAL)
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
