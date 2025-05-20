# Function: <code>end_buffer_async_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81243f00)
Location: fs/buffer.c:283
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff81243f00-ffffffff8124400c: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126baf0)
Location: fs/buffer.c:279
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff8126baf0-ffffffff8126bc00: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127ec30)
Location: fs/buffer.c:280
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff8127ec30-ffffffff8127ed40: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128c440)
Location: fs/buffer.c:280
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff8128c440-ffffffff8128c550: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812af050)
Location: fs/buffer.c:259
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff812af050-ffffffff812af160: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d6bb0)
Location: fs/buffer.c:251
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff812d6bb0-ffffffff812d6cd4: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ebf30)
Location: fs/buffer.c:252
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff812ebf30-ffffffff812ec056: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130da40)
Location: fs/buffer.c:253
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff8130da40-ffffffff8130db63: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81320a10)
Location: fs/buffer.c:253
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff81320a10-ffffffff81320b50: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:244
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
```
**Symbols:**

```
ffffffff8135b440-ffffffff8135b585: end_buffer_async_read (STB_LOCAL)
ffffffff8135e806-ffffffff8135e826: end_buffer_async_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:244
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
```
**Symbols:**

```
ffffffff81369560-ffffffff813696a5: end_buffer_async_read (STB_LOCAL)
ffffffff81beaaaa-ffffffff81beaaca: end_buffer_async_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:244
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
```
**Symbols:**

```
ffffffff8136f6c0-ffffffff8136f805: end_buffer_async_read (STB_LOCAL)
ffffffff81bdcad9-ffffffff81bdcaf9: end_buffer_async_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:244
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
```
**Symbols:**

```
ffffffff813be160-ffffffff813be2a5: end_buffer_async_read (STB_LOCAL)
ffffffff81cc450f-ffffffff81cc452f: end_buffer_async_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:244
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
```
**Symbols:**

```
ffffffff81445cc0-ffffffff81445e7b: end_buffer_async_read (STB_LOCAL)
ffffffff81e77038-ffffffff81e77058: end_buffer_async_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d4430)
Location: fs/buffer.c:244
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
```
**Symbols:**

```
ffffffff814d4430-ffffffff814d4597: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150ab20)
Location: fs/buffer.c:244
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
  - fs/buffer.c:verify_bh
```
**Symbols:**

```
ffffffff8150ab20-ffffffff8150ac24: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153f990)
Location: fs/buffer.c:245
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_folio
  - fs/buffer.c:end_buffer_async_read_io
  - fs/buffer.c:decrypt_bh
  - fs/buffer.c:verify_bh
```
**Symbols:**

```
ffffffff8153f990-ffffffff8153fa8d: end_buffer_async_read (STB_LOCAL)
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
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103da950)
Location: fs/buffer.c:253
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffff8000103da950-ffff8000103dab90: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b284c)
Location: fs/buffer.c:253
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
c05b284c-c05b2a68: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dd6a0)
Location: fs/buffer.c:253
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
c0000000004dd6a0-c0000000004dd938: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe0002914aa)
Location: fs/buffer.c:253
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffe0002914aa-ffffffe000291608: end_buffer_async_read (STB_LOCAL)
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
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318ff0)
Location: fs/buffer.c:253
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff81318ff0-ffffffff81319130: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81309be0)
Location: fs/buffer.c:253
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff81309be0-ffffffff81309d05: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81316ac0)
Location: fs/buffer.c:253
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff81316ac0-ffffffff81316c00: end_buffer_async_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void end_buffer_async_read(struct buffer_head *bh, int uptodate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813289f0)
Location: fs/buffer.c:253
Inline: False
Direct callers:
  - fs/buffer.c:block_read_full_page
```
**Symbols:**

```
ffffffff813289f0-ffffffff81328b75: end_buffer_async_read (STB_LOCAL)
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
