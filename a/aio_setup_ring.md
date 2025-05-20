# Function: <code>aio_setup_ring</code>

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
In fs/aio.c (ffffffff8125caf6)
Location: fs/aio.c:436
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81284c30)
Location: fs/aio.c:441
Inline: False
Direct callers:
  - fs/aio.c:SyS_io_setup
```
**Symbols:**

```
ffffffff81284c30-ffffffff8128506c: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81298e40)
Location: fs/aio.c:444
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81298e40-ffffffff81299275: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812a6530)
Location: fs/aio.c:444
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff812a6530-ffffffff812a6936: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812c9a70)
Location: fs/aio.c:453
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff812c9a70-ffffffff812c9e6f: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f2d40)
Location: fs/aio.c:447
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff812f2d40-ffffffff812f315e: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81307ab0)
Location: fs/aio.c:463
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81307ab0-ffffffff81307e73: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8132c2a0)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff8132c2a0-ffffffff8132c673: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133f0f0)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff8133f0f0-ffffffff8133f4c3: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81377700)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81377700-ffffffff81377b21: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81385060)
Location: fs/aio.c:462
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81385060-ffffffff813854a6: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138be10)
Location: fs/aio.c:459
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff8138be10-ffffffff8138c250: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d93c0)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff813d93c0-ffffffff813d9806: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81463470)
Location: fs/aio.c:487
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81463470-ffffffff814638aa: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f2560)
Location: fs/aio.c:491
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff814f2560-ffffffff814f299a: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81529190)
Location: fs/aio.c:491
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81529190-ffffffff815295ae: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155e060)
Location: fs/aio.c:490
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff8155e060-ffffffff8155e47f: aio_setup_ring (STB_LOCAL)
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
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffff8000103fb0b8)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffff8000103fb0b8-ffff8000103fb468: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05d03f8)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_setup
```
**Symbols:**

```
c05d03f8-c05d07a4: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000507fb0)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
c000000000507fb0-c000000000508484: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffe0002aa9d4)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:__se_sys_io_setup
```
**Symbols:**

```
ffffffe0002aa9d4-ffffffe0002aacf4: aio_setup_ring (STB_LOCAL)
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
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813376d0)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff813376d0-ffffffff81337aa3: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81328400)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81328400-ffffffff813287d3: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813351a0)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff813351a0-ffffffff81335573: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aio_setup_ring(struct kioctx *ctx, unsigned int nr_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81348190)
Location: fs/aio.c:460
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81348190-ffffffff81348581: aio_setup_ring (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_events</code>
</li>
</ul>
</details>
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
