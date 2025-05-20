# Function: <code>compat_put_bitmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81111860)
Location: kernel/compat.c:932
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff81111860-ffffffff811118fd: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81118fb0)
Location: kernel/compat.c:932
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff81118fb0-ffffffff81119051: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811208e0)
Location: kernel/compat.c:940
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - mm/mempolicy.c:C_SYSC_get_mempolicy
```
**Symbols:**

```
ffffffff811208e0-ffffffff81120981: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811211f0)
Location: kernel/compat.c:483
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - mm/mempolicy.c:C_SYSC_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff811211f0-ffffffff81121290: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8112c860)
Location: kernel/compat.c:442
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_sched_getaffinity
  - mm/mempolicy.c:C_SYSC_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8112c860-ffffffff8112c900: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113af30)
Location: kernel/compat.c:407
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8113af30-ffffffff8113afcc: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811467b0)
Location: kernel/compat.c:377
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff811467b0-ffffffff8114683a: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811518f0)
Location: kernel/compat.c:310
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff811518f0-ffffffff8115197a: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115d540)
Location: kernel/compat.c:310
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8115d540-ffffffff8115d5ca: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116df80)
Location: kernel/compat.c:222
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8116df80-ffffffff8116e00a: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116a580)
Location: kernel/compat.c:222
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8116a580-ffffffff8116a618: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116b1f0)
Location: kernel/compat.c:222
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8116b1f0-ffffffff8116b277: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81190df0)
Location: kernel/compat.c:222
Inline: False
Direct callers:
  - kernel/compat.c:__x64_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81190df0-ffffffff81190e77: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811c05d0)
Location: kernel/compat.c:222
Inline: False
Direct callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:kernel_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff811c05d0-ffffffff811c0669: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff812029c0)
Location: kernel/compat.c:222
Inline: False
Direct callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:copy_nodes_to_user
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff812029c0-ffffffff81202a59: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81217d80)
Location: kernel/compat.c:222
Inline: False
Direct callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:copy_nodes_to_user
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81217d80-ffffffff81217e17: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8122f940)
Location: kernel/compat.c:222
Inline: False
Direct callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:copy_nodes_to_user
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8122f940-ffffffff8122f9d7: compat_put_bitmap (STB_GLOBAL)
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
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cd870)
Location: kernel/compat.c:310
Inline: False
Direct callers:
  - kernel/compat.c:__arm64_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__arm64_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffff8000101cd870-ffff8000101cdcb0: compat_put_bitmap (STB_GLOBAL)
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
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c0000000002373d0)
Location: kernel/compat.c:310
Inline: False
Direct callers:
  - kernel/compat.c:__do_compat_sys_sched_getaffinity
  - kernel/compat.c:__do_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__se_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
c0000000002373d0-c000000000237598: compat_put_bitmap (STB_GLOBAL)
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
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155b60)
Location: kernel/compat.c:310
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81155b60-ffffffff81155bea: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81148e80)
Location: kernel/compat.c:310
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81148e80-ffffffff81148f0a: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81153930)
Location: kernel/compat.c:310
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81153930-ffffffff811539ba: compat_put_bitmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int compat_put_bitmap(compat_ulong_t *umask, long unsigned int *mask, long unsigned int bitmap_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81160830)
Location: kernel/compat.c:310
Inline: False
Direct callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
  - mm/mempolicy.c:__do_compat_sys_get_mempolicy
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81160830-ffffffff811608ba: compat_put_bitmap (STB_GLOBAL)
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
