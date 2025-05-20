# Function: <code>guard_bio_eod</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void guard_bio_eod(int rw, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812448f0)
Location: fs/buffer.c:2963
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:mpage_readpage
```
**Symbols:**

```
ffffffff812448f0-ffffffff812449d8: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void guard_bio_eod(int op, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126ce40)
Location: fs/buffer.c:3019
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_bio_submit
```
**Symbols:**

```
ffffffff8126ce40-ffffffff8126cf20: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void guard_bio_eod(int op, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812800d0)
Location: fs/buffer.c:3060
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812800d0-ffffffff812801ad: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void guard_bio_eod(int op, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128d9d0)
Location: fs/buffer.c:3054
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8128d9d0-ffffffff8128da8c: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void guard_bio_eod(int op, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b0560)
Location: fs/buffer.c:3014
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812b0560-ffffffff812b0645: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void guard_bio_eod(int op, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d8340)
Location: fs/buffer.c:2985
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812d8340-ffffffff812d8433: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void guard_bio_eod(int op, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ed810)
Location: fs/buffer.c:2997
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff812ed810-ffffffff812ed903: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void guard_bio_eod(int op, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130efa0)
Location: fs/buffer.c:2994
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8130efa0-ffffffff8130f0d6: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81321fe0)
Location: fs/buffer.c:2994
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81321fe0-ffffffff8132203f: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153f430)
Location: block/bio.c:606
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8153f430-ffffffff8153f497: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155bc30)
Location: block/bio.c:608
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8155bc30-ffffffff8155bca6: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815642c0)
Location: block/bio.c:572
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff815642c0-ffffffff81564303: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c8750)
Location: block/bio.c:601
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff815c8750-ffffffff815c8793: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff816734b0)
Location: block/bio.c:657
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_read_folio
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff816734b0-ffffffff8167361c: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172f050)
Location: block/bio.c:682
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_read_folio
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8172f050-ffffffff8172f1cf: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176b2a0)
Location: block/bio.c:681
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_read_folio
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8176b2a0-ffffffff8176b423: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ad730)
Location: block/bio.c:681
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_read_folio
  - fs/mpage.c:mpage_readahead
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff817ad730-ffffffff817ad8b3: guard_bio_eod (STB_GLOBAL)
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
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dacf8)
Location: fs/buffer.c:2994
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffff8000103dacf8-ffff8000103dad70: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b405c)
Location: fs/buffer.c:2994
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
c05b405c-c05b4138: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004dff00)
Location: fs/buffer.c:2994
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
c0000000004dff00-c0000000004dffa4: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000293754)
Location: fs/buffer.c:2994
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffe000293754-ffffffe0002937b0: guard_bio_eod (STB_GLOBAL)
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
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131a5c0)
Location: fs/buffer.c:2994
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8131a5c0-ffffffff8131a61f: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130b160)
Location: fs/buffer.c:2994
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff8130b160-ffffffff8130b1bf: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318090)
Location: fs/buffer.c:2994
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81318090-ffffffff813180ef: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void guard_bio_eod(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81329ca0)
Location: fs/buffer.c:2994
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:mpage_writepage
  - fs/mpage.c:mpage_writepages
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:__mpage_writepage
  - fs/mpage.c:mpage_readpage
  - fs/mpage.c:mpage_readpages
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
**Symbols:**

```
ffffffff81329ca0-ffffffff81329d10: guard_bio_eod (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param reordered. </b>
<code>op, bio</code> ➡️ <code>bio</code>
</li>
</ul>
</details>
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
