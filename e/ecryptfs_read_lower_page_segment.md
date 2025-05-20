# Function: <code>ecryptfs_read_lower_page_segment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81304d60)
Location: fs/ecryptfs/read_write.c:256
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
```
**Symbols:**

```
ffffffff81304d60-ffffffff81304dde: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81338ec0)
Location: fs/ecryptfs/read_write.c:256
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81338ec0-ffffffff81338f3b: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff8134ec60)
Location: fs/ecryptfs/read_write.c:256
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8134ec60-ffffffff8134ecd5: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81363730)
Location: fs/ecryptfs/read_write.c:258
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81363730-ffffffff813637a0: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81388460)
Location: fs/ecryptfs/read_write.c:258
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81388460-ffffffff81388509: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff813b7260)
Location: fs/ecryptfs/read_write.c:258
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813b7260-ffffffff813b7309: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff813d07b0)
Location: fs/ecryptfs/read_write.c:258
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813d07b0-ffffffff813d0859: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff813fb3d0)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813fb3d0-ffffffff813fb479: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff814152a0)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff814152a0-ffffffff81415349: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81463560)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81463560-ffffffff81463609: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff8147eda0)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8147eda0-ffffffff8147ee49: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81484930)
Location: fs/ecryptfs/read_write.c:246
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81484930-ffffffff814849d6: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff814dbfb0)
Location: fs/ecryptfs/read_write.c:246
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff814dbfb0-ffffffff814dc056: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81569cb0)
Location: fs/ecryptfs/read_write.c:246
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81569cb0-ffffffff81569d65: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff8160d960)
Location: fs/ecryptfs/read_write.c:246
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8160d960-ffffffff8160da15: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81645810)
Location: fs/ecryptfs/read_write.c:246
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff81645810-ffffffff816458c5: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff8167ecf0)
Location: fs/ecryptfs/read_write.c:246
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_read_folio
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8167ecf0-ffffffff8167ed84: ecryptfs_read_lower_page_segment (STB_GLOBAL)
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
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffff8000104f6890)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffff8000104f6890-ffff8000104f694c: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (c06b4344)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
c06b4344-c06b43f0: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (c000000000637910)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
c000000000637910-c000000000637a10: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffe00036552a)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffe00036552a-ffffffe0003655c8: ecryptfs_read_lower_page_segment (STB_GLOBAL)
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
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff8140d880)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8140d880-ffffffff8140d929: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff813fe300)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff813fe300-ffffffff813fe3a9: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff8140ac00)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff8140ac00-ffffffff8140aca9: ecryptfs_read_lower_page_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ecryptfs_read_lower_page_segment(struct page *page_for_ecryptfs, long unsigned int page_index, size_t offset_in_page, size_t size, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff814208c0)
Location: fs/ecryptfs/read_write.c:244
Inline: False
Direct callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_write_begin
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_readpage
  - fs/ecryptfs/mmap.c:ecryptfs_copy_up_encrypted_with_header
```
**Symbols:**

```
ffffffff814208c0-ffffffff81420942: ecryptfs_read_lower_page_segment (STB_GLOBAL)
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
