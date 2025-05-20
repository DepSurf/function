# Function: <code>ext4_mark_bitmap_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81292fe0)
Location: fs/ext4/ialloc.c:52
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81292fe0-ffffffff81293030: ext4_mark_bitmap_end.part.16 (STB_LOCAL)
ffffffff81293bb0-ffffffff81293bc5: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812c0eae)
Location: fs/ext4/ialloc.c:52
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812c0590-ffffffff812c05e0: ext4_mark_bitmap_end.part.17 (STB_LOCAL)
ffffffff812c1160-ffffffff812c1175: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812d64de)
Location: fs/ext4/ialloc.c:52
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812d5bc0-ffffffff812d5c10: ext4_mark_bitmap_end.part.16 (STB_LOCAL)
ffffffff812d6790-ffffffff812d67a5: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff812f47a0)
Location: fs/ext4/ialloc.c:54
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812f3e40-ffffffff812f3e90: ext4_mark_bitmap_end.part.17 (STB_LOCAL)
ffffffff812f4a70-ffffffff812f4a86: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81318e12)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81318580-ffffffff813185ce: ext4_mark_bitmap_end.part.20 (STB_LOCAL)
ffffffff81319200-ffffffff81319216: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81346ce5)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff813469c0-ffffffff81346a0e: ext4_mark_bitmap_end.part.23 (STB_LOCAL)
ffffffff81347020-ffffffff81347035: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8135ee95)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:ext4_flex_group_add
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8135e6b0-ffffffff8135e6fe: ext4_mark_bitmap_end.part.24 (STB_LOCAL)
ffffffff8135f1d0-ffffffff8135f1e5: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813880e3)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff81387890-ffffffff813878df: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff813883c0-ffffffff813883d5: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813a0aa8)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813a0780-ffffffff813a07cf: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff813a0d80-ffffffff813a0d95: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813ecd81)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813ec1c0-ffffffff813ec20f: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff813ecff0-ffffffff813ed005: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813fef8c)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813fe380-ffffffff813fe3cf: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff813ff1c0-ffffffff813ff1d5: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81405298)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff81404870-ffffffff814048c0: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff81405550-ffffffff81405565: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81457aaf)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff81457020-ffffffff81457070: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff81457d80-ffffffff81457d95: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff814d54ac)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff814d5890-ffffffff814d5900: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff8156e443)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff8156dfb0-ffffffff8156e01c: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff8156e650-ffffffff8156e679: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815a6303)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff815a5ea0-ffffffff815a5f0c: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff815a6500-ffffffff815a6529: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff815df182)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_init_block_bitmap
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff815ded10-ffffffff815ded7c: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff815df380-ffffffff815df3a9: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffff8000104740ec)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffff800010473c28-ffff800010473cdc: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffff800010474550-ffff80001047459c: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (c0635590)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
c0635258-c06352d8: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
c0635ad4-c0635af8: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (c0000000005954b4)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
c0000000005951f0-c000000000595298: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
c000000000595b20-c000000000595b3c: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffe0002ffb4e)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffe0002ff94a-ffffffe0002ff9da: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffe000300016-ffffffe000300054: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81399088)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff81398d60-ffffffff81398daf: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff81399360-ffffffff81399375: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff81389b18)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813897f0-ffffffff8138983f: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff81389df0-ffffffff81389e05: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813968e8)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813965c0-ffffffff8139660f: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff81396bc0-ffffffff81396bd5: ext4_mark_bitmap_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ext4_mark_bitmap_end(int start_bit, int end_bit, char *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/ialloc.c (ffffffff813aab7a)
Location: fs/ext4/ialloc.c:55
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
Direct callers:
  - fs/ext4/balloc.c:ext4_read_block_bitmap_nowait
  - fs/ext4/ialloc.c:ext4_read_inode_bitmap
  - fs/ext4/resize.c:setup_new_flex_group_blocks
  - fs/ext4/resize.c:setup_new_flex_group_blocks
```
**Symbols:**

```
ffffffff813aa820-ffffffff813aa86f: ext4_mark_bitmap_end.part.0 (STB_LOCAL)
ffffffff813aaeb0-ffffffff813aaec5: ext4_mark_bitmap_end (STB_GLOBAL)
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
