# Function: <code>lookup_ioctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8125ba50)
Location: fs/aio.c:1029
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_destroy
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:SyS_io_getevents
```
**Symbols:**

```
ffffffff8125ba50-ffffffff8125bab6: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81284510)
Location: fs/aio.c:1039
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
```
**Symbols:**

```
ffffffff81284510-ffffffff81284572: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812981d0)
Location: fs/aio.c:1042
Inline: False
Direct callers:
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
```
**Symbols:**

```
ffffffff812981d0-ffffffff81298232: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a5aa0)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:compat_SyS_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
```
**Symbols:**

```
ffffffff812a5aa0-ffffffff812a5b02: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c8fc0)
Location: fs/aio.c:1071
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:SyS_io_cancel
  - fs/aio.c:do_io_submit
  - fs/aio.c:SyS_io_destroy
```
**Symbols:**

```
ffffffff812c8fc0-ffffffff812c9025: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f28a0)
Location: fs/aio.c:1025
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff812f28a0-ffffffff812f293f: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813069a0)
Location: fs/aio.c:1042
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff813069a0-ffffffff81306a2c: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81327f90)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff81327f90-ffffffff81328030: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133ad30)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff8133ad30-ffffffff8133add0: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81374e30)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff81374e30-ffffffff81374ecf: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81382db0)
Location: fs/aio.c:1049
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff81382db0-ffffffff81382e72: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81389e20)
Location: fs/aio.c:1046
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff81389e20-ffffffff81389ee5: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d7100)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x64_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff813d7100-ffffffff813d71c5: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81460c80)
Location: fs/aio.c:1073
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff81460c80-ffffffff81460d59: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f0c30)
Location: fs/aio.c:1074
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff814f0c30-ffffffff814f0d09: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff815279d0)
Location: fs/aio.c:1071
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff815279d0-ffffffff81527aa9: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155c760)
Location: fs/aio.c:1081
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff8155c760-ffffffff8155c839: lookup_ioctx (STB_LOCAL)
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
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fbdd8)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__arm64_sys_io_cancel
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
  - fs/aio.c:__arm64_sys_io_destroy
```
**Symbols:**

```
ffff8000103fbdd8-ffff8000103fc038: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05cecbc)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_destroy
```
**Symbols:**

```
c05cecbc-c05cedf0: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000503ee0)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_destroy
```
**Symbols:**

```
c000000000503ee0-c000000000504088: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002a9238)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__se_sys_io_cancel
  - fs/aio.c:__se_sys_io_submit
  - fs/aio.c:__se_sys_io_destroy
```
**Symbols:**

```
ffffffe0002a9238-ffffffe0002a9324: lookup_ioctx (STB_LOCAL)
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
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81333310)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff81333310-ffffffff813333b0: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81323f80)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff81323f80-ffffffff81324020: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81330de0)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff81330de0-ffffffff81330e80: lookup_ioctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kioctx *lookup_ioctx(long unsigned int ctx_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813439a0)
Location: fs/aio.c:1047
Inline: False
Direct callers:
  - fs/aio.c:do_io_getevents
  - fs/aio.c:__ia32_sys_io_cancel
  - fs/aio.c:__x64_sys_io_cancel
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
  - fs/aio.c:__ia32_sys_io_destroy
  - fs/aio.c:__x64_sys_io_destroy
```
**Symbols:**

```
ffffffff813439a0-ffffffff81343a83: lookup_ioctx (STB_LOCAL)
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
