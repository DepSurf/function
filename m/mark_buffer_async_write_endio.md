# Function: <code>mark_buffer_async_write_endio</code>

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
In fs/buffer.c (ffffffff81242566)
Location: fs/buffer.c:417
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_async_write
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
In fs/buffer.c (ffffffff8126d194)
Location: fs/buffer.c:413
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
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
In fs/buffer.c (ffffffff812803ec)
Location: fs/buffer.c:414
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
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
In fs/buffer.c (ffffffff8128dd4b)
Location: fs/buffer.c:413
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
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
In fs/buffer.c (ffffffff812b093e)
Location: fs/buffer.c:392
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff812d875d)
Location: fs/buffer.c:384
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
**Symbols:**

```
ffffffff812d63f0-ffffffff812d6400: mark_buffer_async_write_endio.part.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff812edc2d)
Location: fs/buffer.c:385
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
**Symbols:**

```
ffffffff812eb7c0-ffffffff812eb7d0: mark_buffer_async_write_endio.part.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_async_write_endio(struct buffer_head *bh, bh_end_io_t *handler);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130d670)
Location: fs/buffer.c:386
Inline: True
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
**Symbols:**

```
ffffffff8130d670-ffffffff8130d68e: mark_buffer_async_write_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_async_write_endio(struct buffer_head *bh, bh_end_io_t *handler);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81320680)
Location: fs/buffer.c:386
Inline: True
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
**Symbols:**

```
ffffffff81320680-ffffffff8132069e: mark_buffer_async_write_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135c5ba)
Location: fs/buffer.c:412
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136aa33)
Location: fs/buffer.c:411
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81370147)
Location: fs/buffer.c:411
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813becd0)
Location: fs/buffer.c:411
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8144744d)
Location: fs/buffer.c:411
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
  - fs/buffer.c:mark_buffer_async_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_async_write_endio(struct buffer_head *bh, bh_end_io_t *handler);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d2ff5)
Location: fs/buffer.c:411
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_async_write
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
```
**Symbols:**

```
ffffffff814d1800-ffffffff814d1824: mark_buffer_async_write_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_async_write_endio(struct buffer_head *bh, bh_end_io_t *handler);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81509c15)
Location: fs/buffer.c:452
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_async_write
Direct callers:
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
```
**Symbols:**

```
ffffffff81507f90-ffffffff81507fb4: mark_buffer_async_write_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/buffer.c (ffffffff8153ea45)
Location: fs/buffer.c:446
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_async_write
Direct callers:
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
```
**Symbols:**

```
ffffffff8153d590-ffffffff8153d5b6: mark_buffer_async_write_endio.constprop.0 (STB_LOCAL)
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
In fs/buffer.c (ffff8000103db2bc)
Location: fs/buffer.c:386
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
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
In fs/buffer.c (c05b4588)
Location: fs/buffer.c:386
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
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
In fs/buffer.c (c0000000004e042c)
Location: fs/buffer.c:386
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
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
In fs/buffer.c (ffffffe000293a40)
Location: fs/buffer.c:386
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_async_write_endio(struct buffer_head *bh, bh_end_io_t *handler);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318c60)
Location: fs/buffer.c:386
Inline: True
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
**Symbols:**

```
ffffffff81318c60-ffffffff81318c7e: mark_buffer_async_write_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_async_write_endio(struct buffer_head *bh, bh_end_io_t *handler);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81309850)
Location: fs/buffer.c:386
Inline: True
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
**Symbols:**

```
ffffffff81309850-ffffffff8130986e: mark_buffer_async_write_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_async_write_endio(struct buffer_head *bh, bh_end_io_t *handler);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81316730)
Location: fs/buffer.c:386
Inline: True
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
**Symbols:**

```
ffffffff81316730-ffffffff8131674e: mark_buffer_async_write_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mark_buffer_async_write_endio(struct buffer_head *bh, bh_end_io_t *handler);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328660)
Location: fs/buffer.c:386
Inline: True
Direct callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
**Symbols:**

```
ffffffff81328660-ffffffff8132867e: mark_buffer_async_write_endio (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
