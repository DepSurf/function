# Function: <code>do_handle_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81270220)
Location: fs/fhandle.c:214
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_open_by_handle_at
  - fs/fhandle.c:SyS_open_by_handle_at
```
**Symbols:**

```
ffffffff81270220-ffffffff812704ee: do_handle_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8129ba50)
Location: fs/fhandle.c:214
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_open_by_handle_at
  - fs/fhandle.c:SyS_open_by_handle_at
```
**Symbols:**

```
ffffffff8129ba50-ffffffff8129bd31: do_handle_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff812b0610)
Location: fs/fhandle.c:214
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_open_by_handle_at
  - fs/fhandle.c:SyS_open_by_handle_at
```
**Symbols:**

```
ffffffff812b0610-ffffffff812b08f1: do_handle_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff812bdaa0)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:compat_SyS_open_by_handle_at
  - fs/fhandle.c:SyS_open_by_handle_at
```
**Symbols:**

```
ffffffff812bdaa0-ffffffff812bdd8b: do_handle_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff812e1190)
Location: fs/fhandle.c:216
Inline: False
Direct callers:
  - fs/fhandle.c:compat_SyS_open_by_handle_at
  - fs/fhandle.c:SyS_open_by_handle_at
```
**Symbols:**

```
ffffffff812e1190-ffffffff812e147b: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8130d3a0)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff8130d3a0-ffffffff8130d6a1: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81322f90)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff81322f90-ffffffff813232a9: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8134a9a0)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff8134a9a0-ffffffff8134aca1: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81362ba0)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff81362ba0-ffffffff81362ebc: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff813a8940)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff813a8940-ffffffff813a8a8f: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff813b9c90)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff813b9c90-ffffffff813b9de5: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff813c0df0)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff813c0df0-ffffffff813c0f45: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81410eb0)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x64_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff81410eb0-ffffffff81411010: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81486870)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff81486870-ffffffff814869ed: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8151a1d0)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff8151a1d0-ffffffff8151a34d: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff815518d0)
Location: fs/fhandle.c:222
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff815518d0-ffffffff81551b7f: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81587a60)
Location: fs/fhandle.c:218
Inline: False
Direct callers:
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff81587a60-ffffffff81587b38: do_handle_open (STB_LOCAL)
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
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffff800010429408)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__arm64_compat_sys_open_by_handle_at
  - fs/fhandle.c:__arm64_sys_open_by_handle_at
```
**Symbols:**

```
ffff800010429408-ffff80001042972c: do_handle_open (STB_LOCAL)
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
In fs/fhandle.c (c05f2148)
Location: fs/fhandle.c:215
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (c0000000005398e0)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__se_compat_sys_open_by_handle_at
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
**Symbols:**

```
c0000000005398e0-c000000000539d10: do_handle_open (STB_LOCAL)
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
In fs/fhandle.c (ffffffe0002c744a)
Location: fs/fhandle.c:215
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
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
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8135b180)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff8135b180-ffffffff8135b49c: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8134be20)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff8134be20-ffffffff8134c13c: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81358c50)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff81358c50-ffffffff81358f6c: do_handle_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_handle_open(int mountdirfd, struct file_handle *ufh, int open_flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8136c350)
Location: fs/fhandle.c:215
Inline: False
Direct callers:
  - fs/fhandle.c:__x32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_compat_sys_open_by_handle_at
  - fs/fhandle.c:__ia32_sys_open_by_handle_at
  - fs/fhandle.c:__x64_sys_open_by_handle_at
```
**Symbols:**

```
ffffffff8136c350-ffffffff8136c66a: do_handle_open (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
