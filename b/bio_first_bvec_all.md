# Function: <code>bio_first_bvec_all</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810ed975)
Location: include/linux/bio.h:318
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81246aa5)
Location: include/linux/bio.h:318
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810f8fe5)
Location: include/linux/bio.h:272
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8125aec5)
Location: include/linux/bio.h:272
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811016e5)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81275ec5)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110db15)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81285995)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff81351745)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81118b35)
Location: include/linux/bio.h:287
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812b7d35)
Location: include/linux/bio.h:287
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff813981f5)
Location: include/linux/bio.h:287
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81114605)
Location: include/linux/bio.h:298
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812c33e5)
Location: include/linux/bio.h:298
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff813a9a75)
Location: include/linux/bio.h:298
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81114dc5)
Location: include/linux/bio.h:300
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812ca1f5)
Location: include/linux/bio.h:300
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff813b0fb5)
Location: include/linux/bio.h:300
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81135445)
Location: include/linux/bio.h:299
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8130f215)
Location: include/linux/bio.h:299
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff81400c95)
Location: include/linux/bio.h:299
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81157935)
Location: include/linux/bio.h:243
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81379475)
Location: include/linux/bio.h:243
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff81474d15)
Location: include/linux/bio.h:243
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff814884c4)
Location: include/linux/bio.h:243
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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81188825)
Location: include/linux/bio.h:243
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff813f6e95)
Location: include/linux/bio.h:243
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff815070f5)
Location: include/linux/bio.h:243
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8151c344)
Location: include/linux/bio.h:243
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
In kernel/power/swap.c (ffffffff811999e5)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8142a025)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
```
```
In fs/mpage.c (ffffffff8150e365)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_write_end_io
  - fs/mpage.c:mpage_read_end_io
  - fs/mpage.c:mpage_read_end_io
```
```
In fs/crypto/bio.c (ffffffff8153a5a5)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/crypto/bio.c:fscrypt_decrypt_bio
```
```
In fs/verity/verify.c (ffffffff8153e617)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff81554551)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff815d9b65)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff815db015)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
  - fs/ext4/readpage.c:__read_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811a8a45)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81463445)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
```
```
In fs/mpage.c (ffffffff81542e10)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/mpage.c:bio_first_folio
```
```
In fs/crypto/bio.c (ffffffff8156f050)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/crypto/bio.c:bio_first_folio
```
```
In fs/verity/verify.c (ffffffff81573c78)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
```
In fs/iomap/buffered-io.c (ffffffff8158a71e)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_finish_ioend
  - fs/iomap/buffered-io.c:iomap_read_end_io
  - fs/iomap/buffered-io.c:iomap_read_end_io
```
```
In fs/ext4/page-io.c (ffffffff816124f0)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
```
In fs/ext4/readpage.c (ffffffff81613aa4)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - fs/ext4/readpage.c:__read_end_io
```
```
In block/bio.c (ffffffff817aab70)
Location: include/linux/bio.h:245
Inline: True
Inline callers:
  - block/bio.c:bio_first_folio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffff80001032008c)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffff800010413894)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (c03c0a28)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (c05388d4)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (c05dfb38)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c0000000003f4f18)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (c00000000052185c)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffe000221798)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffe0002bb28a)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8127dfe5)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff81349d25)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810f6fd5)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8126fe15)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff8133aa05)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81103fe5)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8127bd85)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff813477f5)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110f3d5)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8128b965)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff8135aaf5)
Location: include/linux/bio.h:279
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
</ul>

## Differences
