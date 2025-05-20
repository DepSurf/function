# Function: <code>bio_associate_blkcg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bio_associate_blkcg(struct bio *bio, struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b10b0)
Location: block/bio.c:1960
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff813b10b0-ffffffff813b10e9: bio_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int bio_associate_blkcg(struct bio *bio, struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f4a80)
Location: block/bio.c:1955
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff813f4a80-ffffffff813f4ab9: bio_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bio_associate_blkcg(struct bio *bio, struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140e470)
Location: block/bio.c:2002
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8140e470-ffffffff8140e4a9: bio_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int bio_associate_blkcg(struct bio *bio, struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b1f0)
Location: block/bio.c:2021
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8141b1f0-ffffffff8141b227: bio_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bio_associate_blkcg(struct bio *bio, struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81445e20)
Location: block/bio.c:1982
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff81445e20-ffffffff81445e5f: bio_associate_blkcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bio_associate_blkcg(struct bio *bio, struct cgroup_subsys_state *blkcg_css);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479a9e)
Location: block/bio.c:2057
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
  - block/blk-core.c:generic_make_request_checks
```
**Symbols:**

```
ffffffff81479b60-ffffffff81479b9f: bio_associate_blkcg (STB_GLOBAL)
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
