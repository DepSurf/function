# Function: <code>bio_associate_blkg_from_css</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814982d0)
Location: block/bio.c:2022
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff814982d0-ffffffff81498321: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6150)
Location: block/bio.c:2056
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff814c6150-ffffffff814c61a1: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de550)
Location: block/bio.c:2098
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff814de550-ffffffff814de5a1: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153ea80)
Location: block/bio.c:1677
Inline: True
Inline callers:
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
  - fs/ext4/page-io.c:io_submit_init_bio
```
**Symbols:**

```
ffffffff8153da20-ffffffff8153da77: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81586340)
Location: block/blk-cgroup.c:1838
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_alloc_ioend
  - fs/ext4/page-io.c:io_submit_init_bio
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:bio_associate_blkg
```
**Symbols:**

```
ffffffff81586340-ffffffff81586472: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158cb80)
Location: block/blk-cgroup.c:1847
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:bio_associate_blkg
```
**Symbols:**

```
ffffffff8158cb80-ffffffff8158ce8a: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f23e0)
Location: block/blk-cgroup.c:1841
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/blk-cgroup.c:bio_associate_blkg
  - block/blk-cgroup.c:bio_associate_blkg
```
**Symbols:**

```
ffffffff815f23e0-ffffffff815f26ea: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a3ba0)
Location: block/blk-cgroup.c:1929
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:bio_associate_blkg
```
**Symbols:**

```
ffffffff816a3ba0-ffffffff816a3ebf: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817628d0)
Location: block/blk-cgroup.c:1935
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:bio_associate_blkg
```
**Symbols:**

```
ffffffff817628d0-ffffffff81762bff: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a1590)
Location: block/blk-cgroup.c:2026
Inline: True
Direct callers:
  - mm/page_io.c:bio_associate_blkg_from_page
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:bio_associate_blkg
```
**Symbols:**

```
ffffffff817a1590-ffffffff817a18c2: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e50e0)
Location: block/blk-cgroup.c:2039
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/iomap/buffered-io.c:iomap_add_to_ioend
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - block/blk-cgroup.c:bio_clone_blkg_association
```
**Symbols:**

```
ffffffff817e50e0-ffffffff817e540c: bio_associate_blkg_from_css (STB_GLOBAL)
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
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105db990)
Location: block/bio.c:2098
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffff8000105db990-ffff8000105db9f8: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0788538)
Location: block/bio.c:2098
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
c0788538-c078858c: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076b8f0)
Location: block/bio.c:2098
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
c00000000076b8f0-c00000000076b980: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041e5ce)
Location: block/bio.c:2098
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffe00041e5ce-ffffffe00041e620: bio_associate_blkg_from_css (STB_GLOBAL)
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
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6b30)
Location: block/bio.c:2098
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff814d6b30-ffffffff814d6b81: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c74f0)
Location: block/bio.c:2098
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff814c74f0-ffffffff814c7541: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2bc0)
Location: block/bio.c:2098
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff814d2bc0-ffffffff814d2c11: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_associate_blkg_from_css(struct bio *bio, struct cgroup_subsys_state *css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb740)
Location: block/bio.c:2098
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
```
**Symbols:**

```
ffffffff814eb740-ffffffff814eb7a0: bio_associate_blkg_from_css (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
