# Function: <code>ext4_init_io_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8129fac0)
Location: fs/ext4/page-io.c:265
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff8129fac0-ffffffff8129fb00: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812ce380)
Location: fs/ext4/page-io.c:251
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff812ce380-ffffffff812ce3b9: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff812e4170)
Location: fs/ext4/page-io.c:251
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff812e4170-ffffffff812e41a9: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8131ddb0)
Location: fs/ext4/page-io.c:250
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff8131ddb0-ffffffff8131dde9: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813423c0)
Location: fs/ext4/page-io.c:251
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813423c0-ffffffff813423f9: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81370250)
Location: fs/ext4/page-io.c:251
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff81370250-ffffffff81370289: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813886e0)
Location: fs/ext4/page-io.c:251
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813886e0-ffffffff81388719: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813b27c0)
Location: fs/ext4/page-io.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813b27c0-ffffffff813b27f9: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813cb810)
Location: fs/ext4/page-io.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813cb810-ffffffff813cb849: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81417a20)
Location: fs/ext4/page-io.c:277
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81417a20-ffffffff81417a68: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8142b520)
Location: fs/ext4/page-io.c:274
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff8142b520-ffffffff8142b568: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81432070)
Location: fs/ext4/page-io.c:274
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81432070-ffffffff814320b8: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff814858e0)
Location: fs/ext4/page-io.c:274
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff814858e0-ffffffff81485928: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81508d80)
Location: fs/ext4/page-io.c:276
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81508d80-ffffffff81508dd2: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815a38f0)
Location: fs/ext4/page-io.c:276
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff815a38f0-ffffffff815a3942: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815da380)
Location: fs/ext4/page-io.c:276
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
```
**Symbols:**

```
ffffffff815da380-ffffffff815da3d2: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81612b40)
Location: fs/ext4/page-io.c:276
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
```
**Symbols:**

```
ffffffff81612b40-ffffffff81612b92: ext4_init_io_end (STB_GLOBAL)
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
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffff8000104a3910)
Location: fs/ext4/page-io.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffff8000104a3910-ffff8000104a3960: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (c0665748)
Location: fs/ext4/page-io.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
c0665748-c0665790: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (c0000000005d0830)
Location: fs/ext4/page-io.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
c0000000005d0830-c0000000005d089c: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffe000325124)
Location: fs/ext4/page-io.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffe000325124-ffffffe00032516c: ext4_init_io_end (STB_GLOBAL)
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
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813c3df0)
Location: fs/ext4/page-io.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813c3df0-ffffffff813c3e29: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813b4870)
Location: fs/ext4/page-io.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813b4870-ffffffff813b48a9: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813c1280)
Location: fs/ext4/page-io.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813c1280-ffffffff813c12b9: ext4_init_io_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ext4_io_end_t *ext4_init_io_end(struct inode *inode, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff813d63e0)
Location: fs/ext4/page-io.c:243
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inode.c:ext4_dio_get_block_unwritten_async
```
**Symbols:**

```
ffffffff813d63e0-ffffffff813d6419: ext4_init_io_end (STB_GLOBAL)
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
