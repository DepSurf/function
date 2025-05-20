# Function: <code>compat_get_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81111710)
Location: kernel/compat.c:890
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - mm/mempolicy.c:compat_SyS_set_mempolicy
  - mm/mempolicy.c:compat_SyS_mbind
```
**Symbols:**

```
ffffffff81111710-ffffffff811117bc: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81118e60)
Location: kernel/compat.c:890
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_migrate_pages
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - mm/mempolicy.c:compat_SyS_mbind
  - mm/mempolicy.c:compat_SyS_set_mempolicy
```
**Symbols:**

```
ffffffff81118e60-ffffffff81118f0c: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120580)
Location: kernel/compat.c:898
Inline: False
Direct callers:
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
```
**Symbols:**

```
ffffffff81120580-ffffffff8112062c: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120e70)
Location: kernel/compat.c:453
Inline: False
Direct callers:
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffffffff81120e70-ffffffff81120f27: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112c4e0)
Location: kernel/compat.c:412
Inline: False
Direct callers:
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:C_SYSC_migrate_pages
  - kernel/compat.c:compat_SyS_sched_setaffinity
  - mm/mempolicy.c:C_SYSC_mbind
  - mm/mempolicy.c:C_SYSC_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffffffff8112c4e0-ffffffff8112c597: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113ace0)
Location: kernel/compat.c:377
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffffffff8113ace0-ffffffff8113ad90: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81146550)
Location: kernel/compat.c:348
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffffffff81146550-ffffffff81146603: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811516b0)
Location: kernel/compat.c:281
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffffffff811516b0-ffffffff81151757: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115d300)
Location: kernel/compat.c:281
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffffffff8115d300-ffffffff8115d3a7: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116dd40)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8116dd40-ffffffff8116dde8: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116a330)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8116a330-ffffffff8116a3e6: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116afd0)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8116afd0-ffffffff8116b05e: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81190bd0)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:get_bitmap
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81190bd0-ffffffff81190c5e: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811c0440)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - mm/mempolicy.c:get_nodes
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff811c0440-ffffffff811c04e0: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81202800)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - mm/mempolicy.c:get_nodes
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81202800-ffffffff812028a7: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81217bd0)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - mm/mempolicy.c:get_nodes
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - io_uring/io_uring.c:io_register_iowq_aff
```
**Symbols:**

```
ffffffff81217bd0-ffffffff81217c6e: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8122f790)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - kernel/compat.c:__ia32_compat_sys_sched_setaffinity
  - mm/mempolicy.c:get_nodes
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - io_uring/register.c:io_register_iowq_aff
```
**Symbols:**

```
ffffffff8122f790-ffffffff8122f82e: compat_get_bitmap (STB_GLOBAL)
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
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cd390)
Location: kernel/compat.c:281
Inline: False
Direct callers:
  - kernel/compat.c:__arm64_compat_sys_sched_setaffinity
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_migrate_pages
  - mm/mempolicy.c:__arm64_compat_sys_mbind
  - mm/mempolicy.c:__arm64_compat_sys_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffff8000101cd390-ffff8000101cd7d8: compat_get_bitmap (STB_GLOBAL)
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
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c000000000237120)
Location: kernel/compat.c:281
Inline: False
Direct callers:
  - kernel/compat.c:__do_compat_sys_sched_setaffinity
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
  - mm/mempolicy.c:__se_compat_sys_migrate_pages
  - mm/mempolicy.c:__se_compat_sys_mbind
  - mm/mempolicy.c:__se_compat_sys_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
c000000000237120-c0000000002372c8: compat_get_bitmap (STB_GLOBAL)
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
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155920)
Location: kernel/compat.c:281
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffffffff81155920-ffffffff811559c7: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148c40)
Location: kernel/compat.c:281
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffffffff81148c40-ffffffff81148ce7: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811536f0)
Location: kernel/compat.c:281
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffffffff811536f0-ffffffff81153797: compat_get_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int compat_get_bitmap(long unsigned int *mask, const compat_ulong_t *umask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811605f0)
Location: kernel/compat.c:281
Inline: False
Direct callers:
  - kernel/compat.c:compat_get_user_cpu_mask
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_migrate_pages
  - mm/mempolicy.c:__do_compat_sys_mbind
  - mm/mempolicy.c:__do_compat_sys_set_mempolicy
  - fs/select.c:compat_get_fd_set
```
**Symbols:**

```
ffffffff811605f0-ffffffff81160697: compat_get_bitmap (STB_GLOBAL)
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
