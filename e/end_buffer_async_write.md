# Function: <code>end_buffer_async_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81244110)
Location: fs/buffer.c:344
Inline: False
```
**Symbols:**

```
ffffffff81244110-ffffffff81244215: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126bdf0)
Location: fs/buffer.c:340
Inline: False
```
**Symbols:**

```
ffffffff8126bdf0-ffffffff8126befc: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127f160)
Location: fs/buffer.c:341
Inline: False
```
**Symbols:**

```
ffffffff8127f160-ffffffff8127f26c: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128cb00)
Location: fs/buffer.c:341
Inline: False
```
**Symbols:**

```
ffffffff8128cb00-ffffffff8128cc06: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812af5a0)
Location: fs/buffer.c:320
Inline: False
```
**Symbols:**

```
ffffffff812af5a0-ffffffff812af6a6: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d6ce0)
Location: fs/buffer.c:312
Inline: False
```
**Symbols:**

```
ffffffff812d6ce0-ffffffff812d6df6: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ec460)
Location: fs/buffer.c:313
Inline: False
```
**Symbols:**

```
ffffffff812ec460-ffffffff812ec577: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130dbe0)
Location: fs/buffer.c:314
Inline: False
```
**Symbols:**

```
ffffffff8130dbe0-ffffffff8130dcef: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81320bc0)
Location: fs/buffer.c:314
Inline: False
```
**Symbols:**

```
ffffffff81320bc0-ffffffff81320ce1: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:343
Inline: False
```
**Symbols:**

```
ffffffff8135e7e6-ffffffff8135e806: end_buffer_async_write.cold (STB_LOCAL)
ffffffff8135af40-ffffffff8135b055: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:342
Inline: False
```
**Symbols:**

```
ffffffff81beaa8a-ffffffff81beaaaa: end_buffer_async_write.cold (STB_LOCAL)
ffffffff81368f00-ffffffff81369015: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:342
Inline: False
```
**Symbols:**

```
ffffffff81bdcab9-ffffffff81bdcad9: end_buffer_async_write.cold (STB_LOCAL)
ffffffff8136f440-ffffffff8136f555: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:342
Inline: False
```
**Symbols:**

```
ffffffff81cc44ef-ffffffff81cc450f: end_buffer_async_write.cold (STB_LOCAL)
ffffffff813be040-ffffffff813be155: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:342
Inline: False
```
**Symbols:**

```
ffffffff81e76f41-ffffffff81e76f61: end_buffer_async_write.cold (STB_LOCAL)
ffffffff814450b0-ffffffff814451ff: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d42e0)
Location: fs/buffer.c:342
Inline: False
```
**Symbols:**

```
ffffffff814d42e0-ffffffff814d441a: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150aa20)
Location: fs/buffer.c:383
Inline: False
```
**Symbols:**

```
ffffffff8150aa20-ffffffff8150ab0e: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153f890)
Location: fs/buffer.c:378
Inline: False
```
**Symbols:**

```
ffffffff8153f890-ffffffff8153f97e: end_buffer_async_write (STB_LOCAL)
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
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103da570)
Location: fs/buffer.c:314
Inline: False
```
**Symbols:**

```
ffff8000103da570-ffff8000103da770: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b2c58)
Location: fs/buffer.c:314
Inline: False
```
**Symbols:**

```
c05b2c58-c05b2e40: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004de1e0)
Location: fs/buffer.c:314
Inline: False
```
**Symbols:**

```
c0000000004de1e0-c0000000004de420: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000291f7a)
Location: fs/buffer.c:314
Inline: False
```
**Symbols:**

```
ffffffe000291f7a-ffffffe0002920b2: end_buffer_async_write (STB_GLOBAL)
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
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813191a0)
Location: fs/buffer.c:314
Inline: False
```
**Symbols:**

```
ffffffff813191a0-ffffffff813192c1: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81309d10)
Location: fs/buffer.c:314
Inline: False
```
**Symbols:**

```
ffffffff81309d10-ffffffff81309e12: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81316c70)
Location: fs/buffer.c:314
Inline: False
```
**Symbols:**

```
ffffffff81316c70-ffffffff81316d91: end_buffer_async_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void end_buffer_async_write(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328ca0)
Location: fs/buffer.c:314
Inline: False
```
**Symbols:**

```
ffffffff81328ca0-ffffffff81328dff: end_buffer_async_write (STB_GLOBAL)
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
