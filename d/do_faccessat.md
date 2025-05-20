# Function: <code>do_faccessat</code>

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
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81295fc0)
Location: fs/open.c:362
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff81295fc0-ffffffff812961fc: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812aadb0)
Location: fs/open.c:351
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff812aadb0-ffffffff812aafec: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c75a0)
Location: fs/open.c:352
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff812c75a0-ffffffff812c77e6: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d8fb0)
Location: fs/open.c:352
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff812d8fb0-ffffffff812d91f6: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130eda0)
Location: fs/open.c:398
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat2
  - fs/open.c:__x64_sys_faccessat2
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff8130eda0-ffffffff8130ef75: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81319720)
Location: fs/open.c:398
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat2
  - fs/open.c:__x64_sys_faccessat2
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff81319720-ffffffff813198f5: do_faccessat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131f760)
Location: fs/open.c:399
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat2
  - fs/open.c:__x64_sys_faccessat2
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff8131f760-ffffffff8131f9ba: do_faccessat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136cd00)
Location: fs/open.c:396
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat2
  - fs/open.c:__x64_sys_faccessat2
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff8136cd00-ffffffff8136cf5a: do_faccessat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813eafe0)
Location: fs/open.c:420
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat2
  - fs/open.c:__x64_sys_faccessat2
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff813eafe0-ffffffff813eb258: do_faccessat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81473230)
Location: fs/open.c:420
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat2
  - fs/open.c:__x64_sys_faccessat2
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff81473230-ffffffff814734aa: do_faccessat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a79a0)
Location: fs/open.c:457
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat2
  - fs/open.c:__x64_sys_faccessat2
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff814a79a0-ffffffff814a7c93: do_faccessat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d8c60)
Location: fs/open.c:462
Inline: False
Direct callers:
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat2
  - fs/open.c:__x64_sys_faccessat2
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff814d8c60-ffffffff814d8f4d: do_faccessat (STB_LOCAL)
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
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037e338)
Location: fs/open.c:352
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__arm64_sys_access
  - fs/open.c:__arm64_sys_faccessat
```
**Symbols:**

```
ffff80001037e338-ffff80001037e594: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0568ca4)
Location: fs/open.c:352
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__se_sys_access
  - fs/open.c:__se_sys_faccessat
```
**Symbols:**

```
c0568ca4-c0568eec: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000473d90)
Location: fs/open.c:352
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__se_sys_access
  - fs/open.c:__se_sys_faccessat
```
**Symbols:**

```
c000000000473d90-c000000000474108: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe00025400e)
Location: fs/open.c:352
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__se_sys_access
  - fs/open.c:__se_sys_faccessat
```
**Symbols:**

```
ffffffe00025400e-ffffffe000254216: do_faccessat (STB_GLOBAL)
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
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1590)
Location: fs/open.c:352
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff812d1590-ffffffff812d17d6: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c2210)
Location: fs/open.c:352
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff812c2210-ffffffff812c2456: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cf3a0)
Location: fs/open.c:352
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff812cf3a0-ffffffff812cf5e6: do_faccessat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_faccessat(int dfd, const char *filename, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e01b0)
Location: fs/open.c:352
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - fs/open.c:__ia32_sys_access
  - fs/open.c:__x64_sys_access
  - fs/open.c:__ia32_sys_faccessat
  - fs/open.c:__x64_sys_faccessat
```
**Symbols:**

```
ffffffff812e01b0-ffffffff812e03f6: do_faccessat (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
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
