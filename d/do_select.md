# Function: <code>do_select</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81221020)
Location: fs/select.c:399
Inline: False
Direct callers:
  - fs/select.c:core_sys_select
  - fs/compat.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81221020-ffffffff8122182c: do_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81248ca0)
Location: fs/select.c:403
Inline: False
Direct callers:
  - fs/select.c:core_sys_select
  - fs/compat.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff81248ca0-ffffffff812494a2: do_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125bcd0)
Location: fs/select.c:404
Inline: False
Direct callers:
  - fs/select.c:core_sys_select
  - fs/compat.c:compat_core_sys_select
```
**Symbols:**

```
ffffffff8125bcd0-ffffffff8125c4a8: do_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81268bf0)
Location: fs/select.c:451
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff81268bf0-ffffffff812693d0: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128b4b0)
Location: fs/select.c:450
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff8128b4b0-ffffffff8128bc7e: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b1cd0)
Location: fs/select.c:449
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812b1cd0-ffffffff812b2443: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c6df0)
Location: fs/select.c:474
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812c6df0-ffffffff812c7555: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e3970)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812e3970-ffffffff812e40dd: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f53b0)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812f53b0-ffffffff812f5b1d: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8132d970)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff8132d970-ffffffff8132e171: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff813391d0)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff813391d0-ffffffff813399f3: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133f790)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff8133f790-ffffffff8133ff85: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138d120)
Location: fs/select.c:478
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff8138d120-ffffffff8138d960: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8140e490)
Location: fs/select.c:479
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff8140e490-ffffffff8140ecd7: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81499020)
Location: fs/select.c:479
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff81499020-ffffffff81499862: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814ce0b0)
Location: fs/select.c:479
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff814ce0b0-ffffffff814ce938: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff815009f0)
Location: fs/select.c:479
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff815009f0-ffffffff81501278: do_select (STB_LOCAL)
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
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a26f8)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffff8000103a26f8-ffff8000103a2ce4: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c0585158)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:core_sys_select
```
**Symbols:**

```
c0585158-c0585830: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049c0c0)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
c00000000049c0c0-c00000000049c918: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffe00026aada)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffe00026aada-ffffffe00026b026: do_select (STB_LOCAL)
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
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ed990)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812ed990-ffffffff812ee0fd: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812de5c0)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812de5c0-ffffffff812ded2d: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812eb7a0)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812eb7a0-ffffffff812ebf0d: do_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_select(int n, fd_set_bits *fds, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fc790)
Location: fs/select.c:476
Inline: False
Direct callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
```
**Symbols:**

```
ffffffff812fc790-ffffffff812fcf00: do_select (STB_LOCAL)
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
