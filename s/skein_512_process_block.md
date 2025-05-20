# Function: <code>skein_512_process_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void skein_512_process_block(struct skein_512_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff816d8490)
Location: drivers/staging/skein/skein_block.c:475
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_512_init
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_final_pad
  - drivers/staging/skein/skein_base.c:skein_512_init_ext
  - drivers/staging/skein/skein_base.c:skein_512_output
```
**Symbols:**

```
ffffffff816d8490-ffffffff816d9541: skein_512_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skein_512_process_block(struct skein_512_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8173c690)
Location: drivers/staging/skein/skein_block.c:478
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_512_output
  - drivers/staging/skein/skein_base.c:skein_512_final_pad
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_init_ext
  - drivers/staging/skein/skein_base.c:skein_512_init
```
**Symbols:**

```
ffffffff8173c690-ffffffff8173d754: skein_512_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skein_512_process_block(struct skein_512_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8176f8c0)
Location: drivers/staging/skein/skein_block.c:478
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_512_output
  - drivers/staging/skein/skein_base.c:skein_512_final_pad
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_init_ext
  - drivers/staging/skein/skein_base.c:skein_512_init
```
**Symbols:**

```
ffffffff8176f8c0-ffffffff81770984: skein_512_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skein_512_process_block(struct skein_512_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8178dc10)
Location: drivers/staging/skein/skein_block.c:480
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_512_output
  - drivers/staging/skein/skein_base.c:skein_512_final_pad
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_init_ext
  - drivers/staging/skein/skein_base.c:skein_512_init
```
**Symbols:**

```
ffffffff8178dc10-ffffffff8178ec4e: skein_512_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skein_512_process_block(struct skein_512_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff81804290)
Location: drivers/staging/skein/skein_block.c:157
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_512_output
  - drivers/staging/skein/skein_base.c:skein_512_final_pad
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_init_ext
  - drivers/staging/skein/skein_base.c:skein_512_init
```
**Symbols:**

```
ffffffff81804290-ffffffff818052ce: skein_512_process_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skein_512_process_block(struct skein_512_ctx *ctx, const u8 *blk_ptr, size_t blk_cnt, size_t byte_cnt_add);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/skein/skein_block.c (ffffffff8184dee0)
Location: drivers/staging/skein/skein_block.c:157
Inline: False
Direct callers:
  - drivers/staging/skein/skein_base.c:skein_512_output
  - drivers/staging/skein/skein_base.c:skein_512_final_pad
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_final
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_update
  - drivers/staging/skein/skein_base.c:skein_512_init_ext
  - drivers/staging/skein/skein_base.c:skein_512_init
```
**Symbols:**

```
ffffffff8184dee0-ffffffff8184f0a5: skein_512_process_block (STB_GLOBAL)
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
