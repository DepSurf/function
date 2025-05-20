# Function: <code>kern_select</code>

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
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b3e10)
Location: fs/select.c:673
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff812b3e10-ffffffff812b3f13: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c9090)
Location: fs/select.c:698
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff812c9090-ffffffff812c9190: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e5aa0)
Location: fs/select.c:700
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff812e5aa0-ffffffff812e5ba1: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f7550)
Location: fs/select.c:700
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff812f7550-ffffffff812f7651: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct __kernel_old_timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81330080)
Location: fs/select.c:700
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff81330080-ffffffff813301f3: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct __kernel_old_timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133b9e0)
Location: fs/select.c:700
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff8133b9e0-ffffffff8133bb53: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct __kernel_old_timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81341ed0)
Location: fs/select.c:700
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff81341ed0-ffffffff8134203d: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct __kernel_old_timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138f890)
Location: fs/select.c:703
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff8138f890-ffffffff8138f9fd: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct __kernel_old_timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814109f0)
Location: fs/select.c:704
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff814109f0-ffffffff81410b70: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct __kernel_old_timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8149b6d0)
Location: fs/select.c:704
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff8149b6d0-ffffffff8149b850: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct __kernel_old_timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814d0960)
Location: fs/select.c:704
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff814d0960-ffffffff814d0ae0: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct __kernel_old_timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff815032a0)
Location: fs/select.c:704
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff815032a0-ffffffff81503420: kern_select (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a4948)
Location: fs/select.c:700
Inline: True
Inline callers:
  - fs/select.c:__arm64_sys_select
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c0586428)
Location: fs/select.c:700
Inline: False
Direct callers:
  - fs/select.c:__se_sys_old_select
  - fs/select.c:__se_sys_select
```
**Symbols:**

```
c0586428-c0586588: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049e670)
Location: fs/select.c:700
Inline: True
Inline callers:
  - fs/select.c:__se_sys_select
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
In fs/select.c (ffffffe00026b7ca)
Location: fs/select.c:700
Inline: True
Inline callers:
  - fs/select.c:__se_sys_select
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
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812efb30)
Location: fs/select.c:700
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff812efb30-ffffffff812efc31: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e0760)
Location: fs/select.c:700
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff812e0760-ffffffff812e0861: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ed940)
Location: fs/select.c:700
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff812ed940-ffffffff812eda41: kern_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kern_select(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fe940)
Location: fs/select.c:700
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_select
  - fs/select.c:__x64_sys_select
```
**Symbols:**

```
ffffffff812fe940-ffffffff812fea41: kern_select (STB_LOCAL)
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
<b>Param type changed. </b>
<code>struct timeval *tvp</code> ➡️ <code>struct __kernel_old_timeval *tvp</code>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
