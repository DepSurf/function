# Function: <code>kill_ioctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8125b460)
Location: fs/aio.c:799
Inline: False
Direct callers:
  - fs/aio.c:exit_aio
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:SyS_io_destroy
```
**Symbols:**

```
ffffffff8125b460-ffffffff8125b542: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81284050)
Location: fs/aio.c:809
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff81284050-ffffffff8128413b: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81297cc0)
Location: fs/aio.c:812
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:compat_SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff81297cc0-ffffffff81297dab: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a5b50)
Location: fs/aio.c:817
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:compat_SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff812a5b50-ffffffff812a5c25: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c9070)
Location: fs/aio.c:840
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:compat_SyS_io_setup
  - fs/aio.c:SyS_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff812c9070-ffffffff812c9147: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f5060)
Location: fs/aio.c:803
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff812f5060-ffffffff812f5137: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8130a150)
Location: fs/aio.c:819
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff8130a150-ffffffff8130a227: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff8132bfb0-ffffffff8132c091: kill_ioctx (STB_LOCAL)
ffffffff8132d08c-ffffffff8132d0ac: kill_ioctx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133ee00)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff8133ee00-ffffffff8133eee1: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81378d30)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff81378d30-ffffffff81378e18: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81386a70)
Location: fs/aio.c:818
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff81386a70-ffffffff81386b4f: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138def0)
Location: fs/aio.c:815
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff8138def0-ffffffff8138dfcf: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813db720)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x64_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff813db720-ffffffff813db83c: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81461580)
Location: fs/aio.c:842
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff81461580-ffffffff8146169a: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f1540)
Location: fs/aio.c:846
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff814f1540-ffffffff814f165a: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81528ae0)
Location: fs/aio.c:844
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff81528ae0-ffffffff81528bfa: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155dbe0)
Location: fs/aio.c:854
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff8155dbe0-ffffffff8155dcfa: kill_ioctx (STB_LOCAL)
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
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fac08)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__arm64_sys_io_destroy
  - fs/aio.c:__arm64_compat_sys_io_setup
  - fs/aio.c:__arm64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffff8000103fac08-ffff8000103fad40: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05cedf0)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
c05cedf0-c05cef10: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c0000000005029c0)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_compat_sys_io_setup
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
c0000000005029c0-c000000000502b40: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002aa658)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_destroy
  - fs/aio.c:__se_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffe0002aa658-ffffffe0002aa784: kill_ioctx (STB_LOCAL)
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
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813373e0)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff813373e0-ffffffff813374c1: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328110)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff81328110-ffffffff813281f1: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81334eb0)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff81334eb0-ffffffff81334f91: kill_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kill_ioctx(struct mm_struct *mm, struct kioctx *ctx, struct ctx_rq_wait *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813437b0)
Location: fs/aio.c:816
Inline: False
Direct callers:
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
  - fs/aio.c:__ia32_sys_io_setup
  - fs/aio.c:__x64_sys_io_setup
  - fs/aio.c:exit_aio
```
**Symbols:**

```
ffffffff813437b0-ffffffff8134388d: kill_ioctx (STB_LOCAL)
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
