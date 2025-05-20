# Function: <code>skein_1024_process_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void skein_1024_process_block(struct skein_1024_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff816d9550)
Location: drivers/staging/skein/skein_block.c:624
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_1024_init
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_final_pad
  - drivers/staging/skein/skein_base.c:skein_1024_init_ext
  - drivers/staging/skein/skein_base.c:skein_1024_output
```
**Symbols:**

```
ffffffff816d9550-ffffffff816da0e5: skein_1024_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skein_1024_process_block(struct skein_1024_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8173d760)
Location: drivers/staging/skein/skein_block.c:629
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_1024_output
  - drivers/staging/skein/skein_base.c:skein_1024_final_pad
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_init_ext
  - drivers/staging/skein/skein_base.c:skein_1024_init
```
**Symbols:**

```
ffffffff8173d760-ffffffff8173e25d: skein_1024_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skein_1024_process_block(struct skein_1024_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff81770990)
Location: drivers/staging/skein/skein_block.c:629
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_1024_output
  - drivers/staging/skein/skein_base.c:skein_1024_final_pad
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_init_ext
  - drivers/staging/skein/skein_base.c:skein_1024_init
```
**Symbols:**

```
ffffffff81770990-ffffffff8177148d: skein_1024_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skein_1024_process_block(struct skein_1024_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8178ec50)
Location: drivers/staging/skein/skein_block.c:631
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_1024_output
  - drivers/staging/skein/skein_base.c:skein_1024_final_pad
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_init_ext
  - drivers/staging/skein/skein_base.c:skein_1024_init
```
**Symbols:**

```
ffffffff8178ec50-ffffffff8178f76b: skein_1024_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skein_1024_process_block(struct skein_1024_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff818052d0)
Location: drivers/staging/skein/skein_block.c:308
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_1024_output
  - drivers/staging/skein/skein_base.c:skein_1024_final_pad
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_init_ext
  - drivers/staging/skein/skein_base.c:skein_1024_init
```
**Symbols:**

```
ffffffff818052d0-ffffffff81805deb: skein_1024_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skein_1024_process_block(struct skein_1024_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8184f0b0)
Location: drivers/staging/skein/skein_block.c:308
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_1024_output
  - drivers/staging/skein/skein_base.c:skein_1024_final_pad
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_final
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_update
  - drivers/staging/skein/skein_base.c:skein_1024_init_ext
  - drivers/staging/skein/skein_base.c:skein_1024_init
```
**Symbols:**

```
ffffffff8184f0b0-ffffffff8184fc37: skein_1024_process_block (STB_GLOBAL)
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
