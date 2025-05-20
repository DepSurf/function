# Function: <code>compat_core_sys_select</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81265100)
Location: fs/compat.c:1234
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_old_select
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
```
**Symbols:**

```
ffffffff81265100-ffffffff8126539e: compat_core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81291420)
Location: fs/compat.c:1237
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff81291420-ffffffff812916bc: compat_core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec *end_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a61b0)
Location: fs/compat.c:1148
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_pselect6
  - fs/compat.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff812a61b0-ffffffff812a6447: compat_core_sys_select (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812693d0)
Location: fs/select.c:1195
Inline: False
Direct callers:
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff812693d0-ffffffff812696a2: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128bc80)
Location: fs/select.c:1186
Inline: False
Direct callers:
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_pselect6
  - fs/select.c:compat_SyS_old_select
```
**Symbols:**

```
ffffffff8128bc80-ffffffff8128bf52: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b2450)
Location: fs/select.c:1187
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff812b2450-ffffffff812b274c: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c7560)
Location: fs/select.c:1199
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff812c7560-ffffffff812c785c: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e40e0)
Location: fs/select.c:1174
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff812e40e0-ffffffff812e43ee: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f5b20)
Location: fs/select.c:1174
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff812f5b20-ffffffff812f5e2e: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8132e180)
Location: fs/select.c:1184
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff8132e180-ffffffff8132e513: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81339a00)
Location: fs/select.c:1190
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff81339a00-ffffffff81339da4: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8133ff90)
Location: fs/select.c:1190
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff8133ff90-ffffffff8134035c: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8138d960)
Location: fs/select.c:1193
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff8138d960-ffffffff8138dd2c: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8140ece0)
Location: fs/select.c:1194
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff8140ece0-ffffffff8140f0a9: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81499880)
Location: fs/select.c:1194
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff81499880-ffffffff81499c49: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff814ce950)
Location: fs/select.c:1194
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff814ce950-ffffffff814ced19: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81501290)
Location: fs/select.c:1194
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff81501290-ffffffff81501659: compat_core_sys_select (STB_LOCAL)
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
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffff8000103a2ce8)
Location: fs/select.c:1174
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffff8000103a2ce8-ffff8000103a2f40: compat_core_sys_select (STB_LOCAL)
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
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049c920)
Location: fs/select.c:1174
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
c00000000049c920-c00000000049cc84: compat_core_sys_select (STB_LOCAL)
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
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ee100)
Location: fs/select.c:1174
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff812ee100-ffffffff812ee40e: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ded30)
Location: fs/select.c:1174
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff812ded30-ffffffff812df03e: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ebf10)
Location: fs/select.c:1174
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff812ebf10-ffffffff812ec21e: compat_core_sys_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_core_sys_select(int n, compat_ulong_t *inp, compat_ulong_t *outp, compat_ulong_t *exp, struct timespec64 *end_time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fcf00)
Location: fs/select.c:1174
Inline: False
Direct callers:
  - fs/select.c:do_compat_pselect
  - fs/select.c:do_compat_select
```
**Symbols:**

```
ffffffff812fcf00-ffffffff812fd219: compat_core_sys_select (STB_LOCAL)
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
