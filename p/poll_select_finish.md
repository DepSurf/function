# Function: <code>poll_select_finish</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/select.c (0)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:__do_sys_pselect6
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812e34d0-ffffffff812e36d5: poll_select_finish (STB_LOCAL)
ffffffff812e5da8-ffffffff812e5dbb: poll_select_finish.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f4f60)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812f4f60-ffffffff812f516c: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8132d5c0)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff8132d5c0-ffffffff8132d7cc: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81338eb0)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff81338eb0-ffffffff813390c7: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133f470)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff8133f470-ffffffff8133f687: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138ce00)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x64_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x64_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff8138ce00-ffffffff8138d017: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8140e110)
Location: fs/select.c:298
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff8140e110-ffffffff8140e355: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81498c70)
Location: fs/select.c:298
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff81498c70-ffffffff81498ec9: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814cdd00)
Location: fs/select.c:298
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff814cdd00-ffffffff814cdf53: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81500640)
Location: fs/select.c:298
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff81500640-ffffffff81500893: poll_select_finish (STB_LOCAL)
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
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a2238)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__arm64_compat_sys_ppoll_time64
  - fs/select.c:__arm64_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__arm64_sys_ppoll
  - fs/select.c:__arm64_sys_pselect6
  - fs/select.c:__arm64_sys_select
```
**Symbols:**

```
ffff8000103a2238-ffff8000103a25e4: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c0584d6c)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__se_sys_ppoll_time32
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:do_pselect
  - fs/select.c:kern_select
```
**Symbols:**

```
c0584d6c-c0584fd0: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049bb40)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__se_compat_sys_ppoll_time64
  - fs/select.c:__se_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_select
```
**Symbols:**

```
c00000000049bb40-c00000000049bdf4: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffe00026a86c)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__se_sys_ppoll
  - fs/select.c:__se_sys_pselect6
  - fs/select.c:__se_sys_select
```
**Symbols:**

```
ffffffe00026a86c-ffffffe00026a986: poll_select_finish (STB_LOCAL)
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
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ed540)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812ed540-ffffffff812ed74c: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812de170)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812de170-ffffffff812de37c: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812eb350)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812eb350-ffffffff812eb55c: poll_select_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int poll_select_finish(struct timespec64 *end_time, void *p, enum poll_time_type pt_type, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fc340)
Location: fs/select.c:297
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_ppoll_time64
  - fs/select.c:__ia32_compat_sys_ppoll_time64
  - fs/select.c:__x32_compat_sys_ppoll_time32
  - fs/select.c:__ia32_compat_sys_ppoll_time32
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
  - fs/select.c:__ia32_sys_ppoll
  - fs/select.c:__x64_sys_ppoll
  - fs/select.c:kern_select
```
**Symbols:**

```
ffffffff812fc340-ffffffff812fc54c: poll_select_finish (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
