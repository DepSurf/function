# Function: <code>__io_uring_register</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81331cb0)
Location: fs/io_uring.c:3439
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff81331cb0-ffffffff813321cc: __io_uring_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81345870)
Location: fs/io_uring.c:4009
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff81345870-ffffffff81345d8c: __io_uring_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813812a0)
Location: fs/io_uring.c:8380
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff813812a0-ffffffff813816ca: __io_uring_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138f170)
Location: fs/io_uring.c:10031
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff8138f170-ffffffff8138f79f: __io_uring_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139e270)
Location: fs/io_uring.c:10021
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff8139e270-ffffffff8139edd8: __io_uring_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:10845
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff813ee350-ffffffff813ef0b5: __io_uring_register (STB_LOCAL)
ffffffff81cc5d04-ffffffff81cc5d58: __io_uring_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:12582
Inline: False
Direct callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff816d83f0-ffffffff816d8b97: __io_uring_register (STB_LOCAL)
ffffffff81e928c0-ffffffff81e929c0: __io_uring_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:4015
Inline: False
Direct callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_register
  - io_uring/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff8178c190-ffffffff8178c782: __io_uring_register (STB_LOCAL)
ffffffff8207755e-ffffffff82077573: __io_uring_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:4341
Inline: False
Direct callers:
  - io_uring/io_uring.c:__do_sys_io_uring_register
```
**Symbols:**

```
ffffffff817cd2d0-ffffffff817cd93a: __io_uring_register (STB_LOCAL)
ffffffff820f759d-ffffffff820f75b2: __io_uring_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/register.c (0)
Location: io_uring/register.c:389
Inline: False
Direct callers:
  - io_uring/register.c:__do_sys_io_uring_register
```
**Symbols:**

```
ffffffff8182b810-ffffffff8182be5b: __io_uring_register (STB_LOCAL)
ffffffff821d5563-ffffffff821d5578: __io_uring_register.cold (STB_LOCAL)
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
In fs/io_uring.c (ffff800010403a74)
Location: fs/io_uring.c:4009
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_register
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
In fs/io_uring.c (c05d7700)
Location: fs/io_uring.c:4009
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
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
In fs/io_uring.c (c00000000051080c)
Location: fs/io_uring.c:4009
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
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
In fs/io_uring.c (ffffffe0002b1138)
Location: fs/io_uring.c:4009
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_register
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
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133de50)
Location: fs/io_uring.c:4009
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff8133de50-ffffffff8133e36c: __io_uring_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132eb10)
Location: fs/io_uring.c:4009
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff8132eb10-ffffffff8132f02c: __io_uring_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8133b920)
Location: fs/io_uring.c:4009
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff8133b920-ffffffff8133be3c: __io_uring_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __io_uring_register(struct io_ring_ctx *ctx, unsigned int opcode, void *arg, unsigned int nr_args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134ead0)
Location: fs/io_uring.c:4009
Inline: False
Direct callers:
  - fs/io_uring.c:__ia32_sys_io_uring_register
  - fs/io_uring.c:__x64_sys_io_uring_register
```
**Symbols:**

```
ffffffff8134ead0-ffffffff8134efec: __io_uring_register (STB_LOCAL)
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
