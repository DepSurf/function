# Function: <code>__do_sys_newstat</code>

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
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f9a0)
Location: fs/stat.c:333
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff8129f9a0-ffffffff8129fa10: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4980)
Location: fs/stat.c:335
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff812b4980-ffffffff812b49f0: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1710)
Location: fs/stat.c:337
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff812d1710-ffffffff812d1782: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e32a0)
Location: fs/stat.c:337
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff812e32a0-ffffffff812e3312: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131aa00)
Location: fs/stat.c:357
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff8131aa00-ffffffff8131aa6d: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81325fe0)
Location: fs/stat.c:345
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff81325fe0-ffffffff8132604d: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c0f0)
Location: fs/stat.c:363
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff8132c0f0-ffffffff8132c15d: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379860)
Location: fs/stat.c:381
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff81379860-ffffffff813798cd: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f9260)
Location: fs/stat.c:394
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff813f9260-ffffffff813f92e5: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482970)
Location: fs/stat.c:409
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff81482970-ffffffff814829f5: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7590)
Location: fs/stat.c:415
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff814b7590-ffffffff814b7615: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e9990)
Location: fs/stat.c:437
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff814e9990-ffffffff814e9a47: __do_sys_newstat (STB_LOCAL)
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
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038b218)
Location: fs/stat.c:337
Inline: False
Direct callers:
  - fs/stat.c:__arm64_sys_newstat
```
**Symbols:**

```
ffff80001038b218-ffff80001038b288: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0572b78)
Location: fs/stat.c:337
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_newstat
```
**Symbols:**

```
c0572b78-c0572bf4: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000481d20)
Location: fs/stat.c:337
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_newstat
```
**Symbols:**

```
c000000000481d20-c000000000481da8: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c822)
Location: fs/stat.c:337
Inline: False
Direct callers:
  - fs/stat.c:__se_sys_newstat
```
**Symbols:**

```
ffffffe00025c822-ffffffe00025c864: __do_sys_newstat (STB_LOCAL)
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
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812db880)
Location: fs/stat.c:337
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff812db880-ffffffff812db8f2: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cc500)
Location: fs/stat.c:337
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff812cc500-ffffffff812cc572: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9690)
Location: fs/stat.c:337
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff812d9690-ffffffff812d9702: __do_sys_newstat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_newstat(const char *filename, struct stat *statbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ea5a0)
Location: fs/stat.c:337
Inline: False
Direct callers:
  - fs/stat.c:__ia32_sys_newstat
  - fs/stat.c:__x64_sys_newstat
```
**Symbols:**

```
ffffffff812ea5a0-ffffffff812ea612: __do_sys_newstat (STB_LOCAL)
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
