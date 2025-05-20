# Function: <code>bio_first_folio</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff814884c4)
Location: include/linux/bio.h:277
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8151c344)
Location: include/linux/bio.h:277
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/mpage.c (ffffffff8150e365)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/crypto/bio.c (ffffffff8153a5a5)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8153e617)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff81554551)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff815d9b65)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815db015)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void bio_first_folio(struct folio_iter *fi, struct bio *bio, int i);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/mpage.c (0)
Location: include/linux/bio.h:284
Inline: False
Direct callers:
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/crypto/bio.c (0)
Location: include/linux/bio.h:284
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff81573c78)
Location: include/linux/bio.h:284
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
Direct callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8158a71e)
Location: include/linux/bio.h:284
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff816124f0)
Location: include/linux/bio.h:284
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
Direct callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81613aa4)
Location: include/linux/bio.h:284
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
Direct callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (0)
Location: include/linux/bio.h:284
Inline: False
Direct callers:
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:bio_set_pages_dirty
  - block/bio.c:__bio_release_pages
  - block/bio.c:__bio_release_pages
```
**Symbols:**

```
ffffffff81542e10-ffffffff81542f35: bio_first_folio (STB_LOCAL)
ffffffff821c5c7d-ffffffff821c5ca0: bio_first_folio.cold (STB_LOCAL)
ffffffff8156f050-ffffffff8156f175: bio_first_folio (STB_LOCAL)
ffffffff821c70cf-ffffffff821c70f2: bio_first_folio.cold (STB_LOCAL)
ffffffff81572f30-ffffffff81573055: bio_first_folio (STB_LOCAL)
ffffffff821c75b2-ffffffff821c75d5: bio_first_folio.cold (STB_LOCAL)
ffffffff81612110-ffffffff81612235: bio_first_folio (STB_LOCAL)
ffffffff821ccdb0-ffffffff821ccdd3: bio_first_folio.cold (STB_LOCAL)
ffffffff81613830-ffffffff81613955: bio_first_folio (STB_LOCAL)
ffffffff821ccffe-ffffffff821cd021: bio_first_folio.cold (STB_LOCAL)
ffffffff817aab70-ffffffff817aac95: bio_first_folio (STB_LOCAL)
ffffffff821d2cac-ffffffff821d2ccf: bio_first_folio.cold (STB_LOCAL)
```
</details>
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
</ul>
