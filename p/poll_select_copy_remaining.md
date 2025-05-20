# Function: <code>poll_select_copy_remaining</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
int poll_select_copy_remaining(struct timespec *end_time, void *p, int timeval, int ret);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81220cb0)
Location: fs/select.c:289
Inline: False
Direct callers:
  - fs/select.c:SyS_select
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_ppoll
```
```
In fs/compat.c (ffffffff81263da0)
Location: fs/compat.c:1106
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_old_select
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_ppoll
```
**Symbols:**

```
ffffffff81220cb0-ffffffff81220def: poll_select_copy_remaining (STB_LOCAL)
ffffffff81263da0-ffffffff81263ebf: poll_select_copy_remaining (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int poll_select_copy_remaining(struct timespec *end_time, void *p, int timeval, int ret);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81248930)
Location: fs/select.c:289
Inline: False
Direct callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
```
```
In fs/compat.c (ffffffff8128ff30)
Location: fs/compat.c:1109
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff81248930-ffffffff81248a73: poll_select_copy_remaining (STB_LOCAL)
ffffffff8128ff30-ffffffff81290047: poll_select_copy_remaining (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int poll_select_copy_remaining(struct timespec *end_time, void *p, int timeval, int ret);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125b960)
Location: fs/select.c:290
Inline: False
Direct callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
```
```
In fs/compat.c (ffffffff812a4f70)
Location: fs/compat.c:1020
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_ppoll
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff8125b960-ffffffff8125baa3: poll_select_copy_remaining (STB_LOCAL)
ffffffff812a4f70-ffffffff812a5087: poll_select_copy_remaining (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int poll_select_copy_remaining(struct timespec *end_time, void *p, int timeval, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812687b0)
Location: fs/select.c:290
Inline: False
Direct callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
```
**Symbols:**

```
ffffffff812687b0-ffffffff812688ee: poll_select_copy_remaining (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int poll_select_copy_remaining(struct timespec *end_time, void *p, int timeval, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128b060)
Location: fs/select.c:291
Inline: False
Direct callers:
  - fs/select.c:SyS_ppoll
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_pselect6
  - fs/select.c:SyS_select
```
**Symbols:**

```
ffffffff8128b060-ffffffff8128b191: poll_select_copy_remaining (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int poll_select_copy_remaining(struct timespec64 *end_time, void *p, int timeval, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b17b0)
Location: fs/select.c:290
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:do_pselect
  - fs/select.c:do_pselect
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812b17b0-ffffffff812b18f1: poll_select_copy_remaining (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int poll_select_copy_remaining(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c6a00)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll
  - fs/select.c:__ia32_compat_sys_ppoll
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812c6a00-ffffffff812c6baa: poll_select_copy_remaining (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *end_time</code> ➡️ <code>struct timespec64 *end_time</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum poll_time_type pt_type</code>
</li>
<li>
<b>Param removed. </b>
<code>int timeval</code>
</li>
</ul>
</details>
</li>
</ul>
