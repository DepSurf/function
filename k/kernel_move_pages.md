# Function: <code>kernel_move_pages</code>

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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812717d0)
Location: mm/migrate.c:1725
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff812717d0-ffffffff812720b4: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81285df0)
Location: mm/migrate.c:1758
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff81285df0-ffffffff812866ce: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a0a60)
Location: mm/migrate.c:1753
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff812a0a60-ffffffff812a0ca0: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b1e70)
Location: mm/migrate.c:1786
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff812b1e70-ffffffff812b20b0: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e7360)
Location: mm/migrate.c:1793
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff812e7360-ffffffff812e764e: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f28b0)
Location: mm/migrate.c:1961
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff812f28b0-ffffffff812f2a09: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f8c60)
Location: mm/migrate.c:1944
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff812f8c60-ffffffff812f8db9: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81343320)
Location: mm/migrate.c:2012
Inline: False
Direct callers:
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff81343320-ffffffff81343479: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b5b50)
Location: mm/migrate.c:1950
Inline: False
Direct callers:
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff813b5b50-ffffffff813b5cc1: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81435c70)
Location: mm/migrate.c:2066
Inline: False
Direct callers:
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff81435c70-ffffffff81435de1: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8146b940)
Location: mm/migrate.c:2400
Inline: False
Direct callers:
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff8146b940-ffffffff8146bab1: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8149a910)
Location: mm/migrate.c:2426
Inline: False
Direct callers:
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff8149a910-ffffffff8149aa81: kernel_move_pages (STB_LOCAL)
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff8000103525c8)
Location: mm/migrate.c:1786
Inline: False
Direct callers:
  - mm/migrate.c:__arm64_compat_sys_move_pages
  - mm/migrate.c:__arm64_sys_move_pages
```
**Symbols:**

```
ffff8000103525c8-ffff800010352788: kernel_move_pages (STB_LOCAL)
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000438f20)
Location: mm/migrate.c:1786
Inline: False
Direct callers:
  - mm/migrate.c:__se_compat_sys_move_pages
  - mm/migrate.c:__se_sys_move_pages
```
**Symbols:**

```
c000000000438f20-c000000000439210: kernel_move_pages (STB_LOCAL)
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
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812aa450)
Location: mm/migrate.c:1786
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff812aa450-ffffffff812aa690: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129bdb0)
Location: mm/migrate.c:1786
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff8129bdb0-ffffffff8129bff0: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a8260)
Location: mm/migrate.c:1786
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff812a8260-ffffffff812a84a0: kernel_move_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_move_pages(pid_t pid, long unsigned int nr_pages, const void **pages, const int *nodes, int *status, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b8560)
Location: mm/migrate.c:1786
Inline: False
Direct callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
  - mm/migrate.c:__ia32_sys_move_pages
  - mm/migrate.c:__x64_sys_move_pages
```
**Symbols:**

```
ffffffff812b8560-ffffffff812b87b7: kernel_move_pages (STB_LOCAL)
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
