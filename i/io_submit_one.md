# Function: <code>io_submit_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8125d4de)
Location: fs/aio.c:1496
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812861cf)
Location: fs/aio.c:1504
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812995ef)
Location: fs/aio.c:1536
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a72aa)
Location: fs/aio.c:1541
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812ca680)
Location: fs/aio.c:1555
Inline: True
Inline callers:
  - fs/aio.c:do_io_submit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f45f0)
Location: fs/aio.c:1595
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff812f45f0-ffffffff812f4996: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81309460)
Location: fs/aio.c:1893
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff81309460-ffffffff81309b3f: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8132b4f0)
Location: fs/aio.c:1832
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff8132b4f0-ffffffff8132ba09: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133e340)
Location: fs/aio.c:1848
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff8133e340-ffffffff8133e859: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813781b0)
Location: fs/aio.c:1855
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff813781b0-ffffffff81378535: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81385eb0)
Location: fs/aio.c:1853
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff81385eb0-ffffffff8138624f: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138d000)
Location: fs/aio.c:1850
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff8138d000-ffffffff8138d39f: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813da760)
Location: fs/aio.c:1968
Inline: False
Direct callers:
  - fs/aio.c:__x64_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff813da760-ffffffff813daaff: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81465140)
Location: fs/aio.c:1992
Inline: False
Direct callers:
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff81465140-ffffffff81465513: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f5180)
Location: fs/aio.c:1993
Inline: False
Direct callers:
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff814f5180-ffffffff814f5553: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8152bf50)
Location: fs/aio.c:1985
Inline: False
Direct callers:
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff8152bf50-ffffffff8152c2e2: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81560e30)
Location: fs/aio.c:2028
Inline: False
Direct callers:
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff81560e30-ffffffff815611c2: io_submit_one (STB_LOCAL)
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
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fd718)
Location: fs/aio.c:1848
Inline: False
Direct callers:
  - fs/aio.c:__arm64_compat_sys_io_submit
  - fs/aio.c:__arm64_sys_io_submit
```
**Symbols:**

```
ffff8000103fd718-ffff8000103fe208: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05d11e0)
Location: fs/aio.c:1848
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_submit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000506a90)
Location: fs/aio.c:1848
Inline: False
Direct callers:
  - fs/aio.c:__se_compat_sys_io_submit
  - fs/aio.c:__se_sys_io_submit
```
**Symbols:**

```
c000000000506a90-c000000000507964: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/aio.c (ffffffe0002ab208)
Location: fs/aio.c:1848
Inline: True
Direct callers:
  - fs/aio.c:__se_sys_io_submit
```
**Symbols:**

```
ffffffe0002ab208-ffffffe0002ab908: io_submit_one.isra.0 (STB_LOCAL)
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
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81336920)
Location: fs/aio.c:1848
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff81336920-ffffffff81336e39: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813272a0)
Location: fs/aio.c:1848
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff813272a0-ffffffff813277af: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813343f0)
Location: fs/aio.c:1848
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff813343f0-ffffffff81334909: io_submit_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_submit_one(struct kioctx *ctx, struct iocb *user_iocb, bool compat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81346850)
Location: fs/aio.c:1848
Inline: False
Direct callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
  - fs/aio.c:__ia32_sys_io_submit
  - fs/aio.c:__x64_sys_io_submit
```
**Symbols:**

```
ffffffff81346850-ffffffff81346e0e: io_submit_one (STB_LOCAL)
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
