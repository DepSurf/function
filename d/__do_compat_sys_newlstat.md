# Function: <code>__do_compat_sys_newlstat</code>

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
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812a01a0)
Location: fs/stat.c:632
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff812a01a0-ffffffff812a0210: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b5180)
Location: fs/stat.c:635
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff812b5180-ffffffff812b51f0: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1f20)
Location: fs/stat.c:637
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff812d1f20-ffffffff812d1f92: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3ab0)
Location: fs/stat.c:637
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff812e3ab0-ffffffff812e3b22: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131acc0)
Location: fs/stat.c:664
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff8131acc0-ffffffff8131ad2d: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813262a0)
Location: fs/stat.c:652
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff813262a0-ffffffff8132630d: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c3b0)
Location: fs/stat.c:670
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff8132c3b0-ffffffff8132c41d: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379b20)
Location: fs/stat.c:688
Inline: False
Direct callers:
  - fs/stat.c:__x64_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff81379b20-ffffffff81379b8d: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f9580)
Location: fs/stat.c:710
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff813f9580-ffffffff813f960a: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482d40)
Location: fs/stat.c:727
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff81482d40-ffffffff81482dca: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7960)
Location: fs/stat.c:740
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff814b7960-ffffffff814b79ea: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e9bf0)
Location: fs/stat.c:762
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff814e9bf0-ffffffff814e9ca4: __do_compat_sys_newlstat (STB_LOCAL)
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
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038aeb8)
Location: fs/stat.c:637
Inline: False
Direct callers:
  - fs/stat.c:__arm64_compat_sys_newlstat
```
**Symbols:**

```
ffff80001038aeb8-ffff80001038af28: __do_compat_sys_newlstat (STB_LOCAL)
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
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000482980)
Location: fs/stat.c:637
Inline: False
Direct callers:
  - fs/stat.c:__se_compat_sys_newlstat
```
**Symbols:**

```
c000000000482980-c000000000482a08: __do_compat_sys_newlstat (STB_LOCAL)
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
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dc090)
Location: fs/stat.c:637
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff812dc090-ffffffff812dc102: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ccd10)
Location: fs/stat.c:637
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff812ccd10-ffffffff812ccd82: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9ea0)
Location: fs/stat.c:637
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff812d9ea0-ffffffff812d9f12: __do_compat_sys_newlstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_newlstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812eadb0)
Location: fs/stat.c:637
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newlstat
  - fs/stat.c:__ia32_compat_sys_newlstat
```
**Symbols:**

```
ffffffff812eadb0-ffffffff812eae22: __do_compat_sys_newlstat (STB_LOCAL)
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
