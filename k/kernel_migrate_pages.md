# Function: <code>kernel_migrate_pages</code>

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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81259f40)
Location: mm/mempolicy.c:1369
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff81259f40-ffffffff8125a355: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126ddd0)
Location: mm/mempolicy.c:1409
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff8126ddd0-ffffffff8126e1e5: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812893d0)
Location: mm/mempolicy.c:1455
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff812893d0-ffffffff8128981f: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81298f60)
Location: mm/mempolicy.c:1459
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff81298f60-ffffffff81299382: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cd0b0)
Location: mm/mempolicy.c:1528
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff812cd0b0-ffffffff812cd55a: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d9940)
Location: mm/mempolicy.c:1504
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff812d9940-ffffffff812d9de7: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e11c0)
Location: mm/mempolicy.c:1518
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff812e11c0-ffffffff812e1659: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81328490)
Location: mm/mempolicy.c:1513
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff81328490-ffffffff81328929: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff813976d0)
Location: mm/mempolicy.c:1577
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff813976d0-ffffffff81397b5a: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814172b0)
Location: mm/mempolicy.c:1592
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff814172b0-ffffffff8141773a: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144a840)
Location: mm/mempolicy.c:1603
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff8144a840-ffffffff8144acca: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81484250)
Location: mm/mempolicy.c:1589
Inline: False
Direct callers:
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff81484250-ffffffff81484709: kernel_migrate_pages (STB_LOCAL)
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff800010337c10)
Location: mm/mempolicy.c:1459
Inline: False
Direct callers:
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_sys_migrate_pages
```
**Symbols:**

```
ffff800010337c10-ffff800010337de8: kernel_migrate_pages (STB_LOCAL)
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c0000000004129f0)
Location: mm/mempolicy.c:1459
Inline: False
Direct callers:
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
  - mm/mempolicy.c:__se_sys_migrate_pages
```
**Symbols:**

```
c0000000004129f0-c000000000412cd8: kernel_migrate_pages (STB_LOCAL)
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
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81291540)
Location: mm/mempolicy.c:1459
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff81291540-ffffffff81291962: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812831c0)
Location: mm/mempolicy.c:1459
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff812831c0-ffffffff812835e2: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128f350)
Location: mm/mempolicy.c:1459
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff8128f350-ffffffff8128f772: kernel_migrate_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_migrate_pages(pid_t pid, long unsigned int maxnode, const long unsigned int *old_nodes, const long unsigned int *new_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129f7d0)
Location: mm/mempolicy.c:1459
Inline: False
Direct callers:
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__ia32_sys_migrate_pages
  - mm/mempolicy.c:__x64_sys_migrate_pages
```
**Symbols:**

```
ffffffff8129f7d0-ffffffff8129fc04: kernel_migrate_pages (STB_LOCAL)
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
