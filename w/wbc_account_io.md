# Function: <code>wbc_account_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wbc_account_io(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81235c20)
Location: fs/fs-writeback.c:674
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81235c20-ffffffff81235c91: wbc_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wbc_account_io(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8125f580)
Location: fs/fs-writeback.c:676
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff8125f580-ffffffff8125f5f1: wbc_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wbc_account_io(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81272aa0)
Location: fs/fs-writeback.c:676
Inline: False
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff81272aa0-ffffffff81272b11: wbc_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_io(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812803f0)
Location: fs/fs-writeback.c:690
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812803f0-ffffffff81280461: wbc_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_io(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a2f20)
Location: fs/fs-writeback.c:690
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812a2f20-ffffffff812a2f91: wbc_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_io(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812c9970)
Location: fs/fs-writeback.c:690
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812c9970-ffffffff812c99e7: wbc_account_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wbc_account_io(struct writeback_control *wbc, struct page *page, size_t bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812deba0)
Location: fs/fs-writeback.c:713
Inline: True
Direct callers:
  - fs/buffer.c:submit_bh_wbc
  - fs/mpage.c:__mpage_writepage
  - fs/ext4/page-io.c:ext4_bio_write_page
```
**Symbols:**

```
ffffffff812deba0-ffffffff812dec17: wbc_account_io (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
