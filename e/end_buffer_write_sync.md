# Function: <code>end_buffer_write_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812431a0)
Location: fs/buffer.c:176
Inline: False
```
**Symbols:**

```
ffffffff812431a0-ffffffff812431db: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126b280)
Location: fs/buffer.c:174
Inline: False
```
**Symbols:**

```
ffffffff8126b280-ffffffff8126b2bb: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127e3c0)
Location: fs/buffer.c:175
Inline: False
```
**Symbols:**

```
ffffffff8127e3c0-ffffffff8127e3fb: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128c630)
Location: fs/buffer.c:175
Inline: False
```
**Symbols:**

```
ffffffff8128c630-ffffffff8128c66e: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812af240)
Location: fs/buffer.c:175
Inline: False
```
**Symbols:**

```
ffffffff812af240-ffffffff812af27e: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d6b10)
Location: fs/buffer.c:168
Inline: False
```
**Symbols:**

```
ffffffff812d6b10-ffffffff812d6b55: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ec150)
Location: fs/buffer.c:168
Inline: False
```
**Symbols:**

```
ffffffff812ec150-ffffffff812ec195: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130d7a0)
Location: fs/buffer.c:169
Inline: False
```
**Symbols:**

```
ffffffff8130d7a0-ffffffff8130d7e7: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81320770)
Location: fs/buffer.c:169
Inline: False
```
**Symbols:**

```
ffffffff81320770-ffffffff813207b7: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:164
Inline: False
```
**Symbols:**

```
ffffffff8135e7c6-ffffffff8135e7e6: end_buffer_write_sync.cold (STB_LOCAL)
ffffffff8135ab00-ffffffff8135ab69: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:164
Inline: False
```
**Symbols:**

```
ffffffff81beaa6a-ffffffff81beaa8a: end_buffer_write_sync.cold (STB_LOCAL)
ffffffff81368940-ffffffff813689a9: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:164
Inline: False
```
**Symbols:**

```
ffffffff81bdca99-ffffffff81bdcab9: end_buffer_write_sync.cold (STB_LOCAL)
ffffffff8136f1e0-ffffffff8136f249: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:164
Inline: False
```
**Symbols:**

```
ffffffff81cc44cf-ffffffff81cc44ef: end_buffer_write_sync.cold (STB_LOCAL)
ffffffff813bde80-ffffffff813bdee9: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:164
Inline: False
```
**Symbols:**

```
ffffffff81e76e5f-ffffffff81e76e7f: end_buffer_write_sync.cold (STB_LOCAL)
ffffffff814441e0-ffffffff81444251: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d3330)
Location: fs/buffer.c:164
Inline: False
```
**Symbols:**

```
ffffffff814d3330-ffffffff814d338b: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150a4e0)
Location: fs/buffer.c:164
Inline: False
```
**Symbols:**

```
ffffffff8150a4e0-ffffffff8150a53b: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153f570)
Location: fs/buffer.c:165
Inline: False
```
**Symbols:**

```
ffffffff8153f570-ffffffff8153f5cb: end_buffer_write_sync (STB_GLOBAL)
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
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d8ef0)
Location: fs/buffer.c:169
Inline: False
```
**Symbols:**

```
ffff8000103d8ef0-ffff8000103d8fb4: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b2370)
Location: fs/buffer.c:169
Inline: False
```
**Symbols:**

```
c05b2370-c05b23f8: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004ddba0)
Location: fs/buffer.c:169
Inline: False
```
**Symbols:**

```
c0000000004ddba0-c0000000004ddcbc: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000291efa)
Location: fs/buffer.c:169
Inline: False
```
**Symbols:**

```
ffffffe000291efa-ffffffe000291f7a: end_buffer_write_sync (STB_GLOBAL)
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
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318d50)
Location: fs/buffer.c:169
Inline: False
```
**Symbols:**

```
ffffffff81318d50-ffffffff81318d97: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81309940)
Location: fs/buffer.c:169
Inline: False
```
**Symbols:**

```
ffffffff81309940-ffffffff81309987: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81316820)
Location: fs/buffer.c:169
Inline: False
```
**Symbols:**

```
ffffffff81316820-ffffffff81316867: end_buffer_write_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void end_buffer_write_sync(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328770)
Location: fs/buffer.c:169
Inline: False
```
**Symbols:**

```
ffffffff81328770-ffffffff813287b7: end_buffer_write_sync (STB_GLOBAL)
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
