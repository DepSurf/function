# Function: <code>__do_compat_sys_newfstatat</code>

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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812a0250)
Location: fs/stat.c:645
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff812a0250-ffffffff812a02b8: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b5230)
Location: fs/stat.c:648
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff812b5230-ffffffff812b5298: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d1fe0)
Location: fs/stat.c:650
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff812d1fe0-ffffffff812d204a: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e3b70)
Location: fs/stat.c:650
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff812e3b70-ffffffff812e3bda: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8131ad70)
Location: fs/stat.c:677
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff8131ad70-ffffffff8131add5: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81326400)
Location: fs/stat.c:665
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff81326400-ffffffff81326465: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132c510)
Location: fs/stat.c:683
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff8132c510-ffffffff8132c575: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81379c80)
Location: fs/stat.c:701
Inline: False
Direct callers:
  - fs/stat.c:__x64_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff81379c80-ffffffff81379ce5: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f9720)
Location: fs/stat.c:723
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff813f9720-ffffffff813f97a4: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81482f30)
Location: fs/stat.c:740
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff81482f30-ffffffff81482fb4: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b7b50)
Location: fs/stat.c:753
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff814b7b50-ffffffff814b7bd4: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814ea050)
Location: fs/stat.c:775
Inline: False
Direct callers:
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff814ea050-ffffffff814ea0d4: __do_compat_sys_newfstatat (STB_LOCAL)
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038af58)
Location: fs/stat.c:650
Inline: False
Direct callers:
  - fs/stat.c:__arm64_compat_sys_newfstatat
```
**Symbols:**

```
ffff80001038af58-ffff80001038afc0: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
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
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812dc150)
Location: fs/stat.c:650
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff812dc150-ffffffff812dc1ba: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812ccdd0)
Location: fs/stat.c:650
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff812ccdd0-ffffffff812cce3a: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d9f60)
Location: fs/stat.c:650
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff812d9f60-ffffffff812d9fca: __do_compat_sys_newfstatat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_newfstatat(unsigned int dfd, const char *filename, struct compat_stat *statbuf, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812eae70)
Location: fs/stat.c:650
Inline: False
Direct callers:
  - fs/stat.c:__x32_compat_sys_newfstatat
  - fs/stat.c:__ia32_compat_sys_newfstatat
```
**Symbols:**

```
ffffffff812eae70-ffffffff812eaeda: __do_compat_sys_newfstatat (STB_LOCAL)
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
