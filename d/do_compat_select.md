# Function: <code>do_compat_select</code>

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
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct compat_timeval *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b3020)
Location: fs/select.c:1258
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff812b3020-ffffffff812b311d: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c80e0)
Location: fs/select.c:1270
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff812c80e0-ffffffff812c81dd: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e4c50)
Location: fs/select.c:1245
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff812e4c50-ffffffff812e4d4b: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f6670)
Location: fs/select.c:1245
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff812f6670-ffffffff812f676b: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8132e520)
Location: fs/select.c:1255
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff8132e520-ffffffff8132e696: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81339db0)
Location: fs/select.c:1261
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff81339db0-ffffffff81339f26: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81340360)
Location: fs/select.c:1261
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff81340360-ffffffff813404d3: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138dd30)
Location: fs/select.c:1264
Inline: False
Direct callers:
  - fs/select.c:__x64_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x64_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff8138dd30-ffffffff8138dea3: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8140f0b0)
Location: fs/select.c:1265
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff8140f0b0-ffffffff8140f22c: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81499c60)
Location: fs/select.c:1265
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff81499c60-ffffffff81499ddc: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814ced30)
Location: fs/select.c:1265
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff814ced30-ffffffff814ceeac: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81501670)
Location: fs/select.c:1265
Inline: False
Direct callers:
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff81501670-ffffffff815017ec: do_compat_select (STB_LOCAL)
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
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a3948)
Location: fs/select.c:1245
Inline: False
Direct callers:
  - fs/select.c:__arm64_compat_sys_old_select
  - fs/select.c:__arm64_compat_sys_select
```
**Symbols:**

```
ffff8000103a3948-ffff8000103a3a60: do_compat_select (STB_LOCAL)
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
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049d7d0)
Location: fs/select.c:1245
Inline: False
Direct callers:
  - fs/select.c:__se_compat_sys_old_select
  - fs/select.c:__se_compat_sys_select
```
**Symbols:**

```
c00000000049d7d0-c00000000049d938: do_compat_select (STB_LOCAL)
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
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812eec50)
Location: fs/select.c:1245
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff812eec50-ffffffff812eed4b: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812df880)
Location: fs/select.c:1245
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff812df880-ffffffff812df97b: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812eca60)
Location: fs/select.c:1245
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff812eca60-ffffffff812ecb5b: do_compat_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_compat_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct old_timeval32 *tvp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fda60)
Location: fs/select.c:1245
Inline: False
Direct callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
**Symbols:**

```
ffffffff812fda60-ffffffff812fdb5b: do_compat_select (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct compat_timeval *tvp</code> ➡️ <code>struct old_timeval32 *tvp</code>
</li>
</ul>
</details>
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
