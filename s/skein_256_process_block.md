# Function: <code>skein_256_process_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void skein_256_process_block(struct skein_256_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff816d7c50)
Location: drivers/staging/skein/skein_block.c:345
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_256_init
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_final_pad
  - drivers/staging/skein/skein_base.c:skein_256_init_ext
  - drivers/staging/skein/skein_base.c:skein_256_output
```
**Symbols:**

```
ffffffff816d7c50-ffffffff816d8481: skein_256_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skein_256_process_block(struct skein_256_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8173be50)
Location: drivers/staging/skein/skein_block.c:347
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_256_output
  - drivers/staging/skein/skein_base.c:skein_256_final_pad
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_init_ext
  - drivers/staging/skein/skein_base.c:skein_256_init
```
**Symbols:**

```
ffffffff8173be50-ffffffff8173c689: skein_256_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skein_256_process_block(struct skein_256_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8176f080)
Location: drivers/staging/skein/skein_block.c:347
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_256_output
  - drivers/staging/skein/skein_base.c:skein_256_final_pad
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_init_ext
  - drivers/staging/skein/skein_base.c:skein_256_init
```
**Symbols:**

```
ffffffff8176f080-ffffffff8176f8b9: skein_256_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skein_256_process_block(struct skein_256_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8178d3e0)
Location: drivers/staging/skein/skein_block.c:349
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_256_output
  - drivers/staging/skein/skein_base.c:skein_256_final_pad
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_init_ext
  - drivers/staging/skein/skein_base.c:skein_256_init
```
**Symbols:**

```
ffffffff8178d3e0-ffffffff8178dc08: skein_256_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skein_256_process_block(struct skein_256_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff81803a60)
Location: drivers/staging/skein/skein_block.c:26
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_256_output
  - drivers/staging/skein/skein_base.c:skein_256_final_pad
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_init_ext
  - drivers/staging/skein/skein_base.c:skein_256_init
```
**Symbols:**

```
ffffffff81803a60-ffffffff81804288: skein_256_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skein_256_process_block(struct skein_256_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8184d660)
Location: drivers/staging/skein/skein_block.c:26
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_256_output
  - drivers/staging/skein/skein_base.c:skein_256_final_pad
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_final
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_update
  - drivers/staging/skein/skein_base.c:skein_256_init_ext
  - drivers/staging/skein/skein_base.c:skein_256_init
```
**Symbols:**

```
ffffffff8184d660-ffffffff8184ded5: skein_256_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
