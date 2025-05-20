# Function: <code>__do_compat_sys_newfstat</code>

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
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812a0300)
Location: fs/stat.c:659
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff812a0300-ffffffff812a0366: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b52e0)
Location: fs/stat.c:662
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff812b52e0-ffffffff812b5346: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d2090)
Location: fs/stat.c:664
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff812d2090-ffffffff812d20f8: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3c20)
Location: fs/stat.c:664
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff812e3c20-ffffffff812e3c88: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131b0b0)
Location: fs/stat.c:691
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff8131b0b0-ffffffff8131b113: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813267d0)
Location: fs/stat.c:679
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff813267d0-ffffffff8132682c: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c8e0)
Location: fs/stat.c:697
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff8132c8e0-ffffffff8132c93c: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8137a050)
Location: fs/stat.c:715
Inline: False
Direct callers:
  - fs/stat.c:__x64_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff8137a050-ffffffff8137a0ac: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f9030)
Location: fs/stat.c:737
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff813f9030-ffffffff813f90ad: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814826d0)
Location: fs/stat.c:754
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff814826d0-ffffffff8148274d: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b72f0)
Location: fs/stat.c:767
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff814b72f0-ffffffff814b736d: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e9670)
Location: fs/stat.c:789
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff814e9670-ffffffff814e96ed: __do_compat_sys_newfstat (STB_LOCAL)
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
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038aff8)
Location: fs/stat.c:664
Inline: False
Direct callers:
  - fs/stat.c:__arm64_compat_sys_newfstat
```
**Symbols:**

```
ffff80001038aff8-ffff80001038b064: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000482a30)
Location: fs/stat.c:664
Inline: False
Direct callers:
  - fs/stat.c:__se_compat_sys_newfstat
```
**Symbols:**

```
c000000000482a30-c000000000482ab8: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
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
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dc200)
Location: fs/stat.c:664
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff812dc200-ffffffff812dc268: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cce80)
Location: fs/stat.c:664
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff812cce80-ffffffff812ccee8: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812da010)
Location: fs/stat.c:664
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff812da010-ffffffff812da078: __do_compat_sys_newfstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_newfstat(unsigned int fd, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812eaf20)
Location: fs/stat.c:664
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstat
  - fs/stat.c:__ia32_compat_sys_newfstat
```
**Symbols:**

```
ffffffff812eaf20-ffffffff812eaf88: __do_compat_sys_newfstat (STB_LOCAL)
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
