# Function: <code>__do_compat_sys_newstat</code>

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
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812a00f0)
Location: fs/stat.c:620
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff812a00f0-ffffffff812a0160: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b50d0)
Location: fs/stat.c:623
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff812b50d0-ffffffff812b5140: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1e60)
Location: fs/stat.c:625
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff812d1e60-ffffffff812d1ed2: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e39f0)
Location: fs/stat.c:625
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff812e39f0-ffffffff812e3a62: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131ac10)
Location: fs/stat.c:652
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff8131ac10-ffffffff8131ac7d: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81326090)
Location: fs/stat.c:640
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff81326090-ffffffff813260fd: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c1a0)
Location: fs/stat.c:658
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff8132c1a0-ffffffff8132c20d: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379910)
Location: fs/stat.c:676
Inline: False
Direct callers:
  - fs/stat.c:__x64_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff81379910-ffffffff8137997d: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f9330)
Location: fs/stat.c:698
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff813f9330-ffffffff813f93b5: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482a70)
Location: fs/stat.c:715
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff81482a70-ffffffff81482af5: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7690)
Location: fs/stat.c:728
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff814b7690-ffffffff814b7715: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e9cf0)
Location: fs/stat.c:750
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff814e9cf0-ffffffff814e9da7: __do_compat_sys_newstat (STB_LOCAL)
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
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038ae18)
Location: fs/stat.c:625
Inline: False
Direct callers:
  - fs/stat.c:__arm64_compat_sys_newstat
```
**Symbols:**

```
ffff80001038ae18-ffff80001038ae88: __do_compat_sys_newstat (STB_LOCAL)
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
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0000000004828d0)
Location: fs/stat.c:625
Inline: False
Direct callers:
  - fs/stat.c:__se_compat_sys_newstat
```
**Symbols:**

```
c0000000004828d0-c000000000482958: __do_compat_sys_newstat (STB_LOCAL)
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
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dbfd0)
Location: fs/stat.c:625
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff812dbfd0-ffffffff812dc042: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ccc50)
Location: fs/stat.c:625
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff812ccc50-ffffffff812cccc2: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9de0)
Location: fs/stat.c:625
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff812d9de0-ffffffff812d9e52: __do_compat_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_newstat(const char *filename, struct compat_stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812eacf0)
Location: fs/stat.c:625
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newstat
  - fs/stat.c:__ia32_compat_sys_newstat
```
**Symbols:**

```
ffffffff812eacf0-ffffffff812ead62: __do_compat_sys_newstat (STB_LOCAL)
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
