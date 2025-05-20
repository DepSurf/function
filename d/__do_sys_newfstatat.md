# Function: <code>__do_sys_newfstatat</code>

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
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129fb00)
Location: fs/stat.c:358
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff8129fb00-ffffffff8129fb68: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4ae0)
Location: fs/stat.c:360
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff812b4ae0-ffffffff812b4b48: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1890)
Location: fs/stat.c:362
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff812d1890-ffffffff812d18fa: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3420)
Location: fs/stat.c:362
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff812e3420-ffffffff812e348a: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131ab60)
Location: fs/stat.c:382
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff8131ab60-ffffffff8131abc5: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81326350)
Location: fs/stat.c:370
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff81326350-ffffffff813263b5: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c460)
Location: fs/stat.c:388
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff8132c460-ffffffff8132c4c5: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379bd0)
Location: fs/stat.c:406
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff81379bd0-ffffffff81379c35: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f9630)
Location: fs/stat.c:419
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff813f9630-ffffffff813f96b4: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482e10)
Location: fs/stat.c:434
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff81482e10-ffffffff81482e94: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7a30)
Location: fs/stat.c:440
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff814b7a30-ffffffff814b7ab4: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e9f30)
Location: fs/stat.c:462
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff814e9f30-ffffffff814e9fb4: __do_sys_newfstatat (STB_LOCAL)
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
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038b358)
Location: fs/stat.c:362
Inline: False
Direct callers:
  - fs/stat.c:__arm64_sys_newfstatat
```
**Symbols:**

```
ffff80001038b358-ffff80001038b3c0: __do_sys_newfstatat (STB_LOCAL)
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
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000481e80)
Location: fs/stat.c:362
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_newfstatat
```
**Symbols:**

```
c000000000481e80-c000000000481f00: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c8a6)
Location: fs/stat.c:362
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_newfstatat
```
**Symbols:**

```
ffffffe00025c8a6-ffffffe00025c8e8: __do_sys_newfstatat (STB_LOCAL)
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
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dba00)
Location: fs/stat.c:362
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff812dba00-ffffffff812dba6a: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cc680)
Location: fs/stat.c:362
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff812cc680-ffffffff812cc6ea: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9810)
Location: fs/stat.c:362
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff812d9810-ffffffff812d987a: __do_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_newfstatat(int dfd, const char *filename, struct stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ea720)
Location: fs/stat.c:362
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newfstatat
  - fs/stat.c:__x64_sys_newfstatat
```
**Symbols:**

```
ffffffff812ea720-ffffffff812ea78a: __do_sys_newfstatat (STB_LOCAL)
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
