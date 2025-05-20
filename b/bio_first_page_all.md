# Function: <code>bio_first_page_all</code>

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
Location: include/linux/bio.h:324
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81246aa5)
Location: include/linux/bio.h:324
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
Location: include/linux/bio.h:278
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8125aec5)
Location: include/linux/bio.h:278
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
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81275ec5)
Location: include/linux/bio.h:285
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
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81285995)
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff81351745)
Location: include/linux/bio.h:285
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
Location: include/linux/bio.h:293
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812b7d35)
Location: include/linux/bio.h:293
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff813981f5)
Location: include/linux/bio.h:293
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
Location: include/linux/bio.h:304
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812c33e5)
Location: include/linux/bio.h:304
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff813a9a75)
Location: include/linux/bio.h:304
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
Location: include/linux/bio.h:306
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff812ca1f5)
Location: include/linux/bio.h:306
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff813b0fb5)
Location: include/linux/bio.h:306
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
Location: include/linux/bio.h:305
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8130f215)
Location: include/linux/bio.h:305
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff81400c95)
Location: include/linux/bio.h:305
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
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81379475)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff81474d15)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
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
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff813f6e95)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff815070f5)
Location: include/linux/bio.h:249
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
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
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8142a025)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
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
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff81463445)
Location: include/linux/bio.h:251
Inline: True
Inline callers:
  - mm/page_io.c:__end_swap_bio_read
  - mm/page_io.c:__end_swap_bio_write
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
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffff800010413894)
Location: include/linux/bio.h:285
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
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (c05388d4)
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (c05dfb38)
Location: include/linux/bio.h:285
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
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (c00000000052185c)
Location: include/linux/bio.h:285
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
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffe0002bb28a)
Location: include/linux/bio.h:285
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
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff81349d25)
Location: include/linux/bio.h:285
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
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8126fe15)
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff8133aa05)
Location: include/linux/bio.h:285
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
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8127bd85)
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff813477f5)
Location: include/linux/bio.h:285
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
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - kernel/power/swap.c:hib_end_io
```
```
In mm/page_io.c (ffffffff8128b965)
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - mm/page_io.c:end_swap_bio_read
  - mm/page_io.c:end_swap_bio_write
```
```
In fs/verity/verify.c (ffffffff8135aaf5)
Location: include/linux/bio.h:285
Inline: True
Inline callers:
  - fs/verity/verify.c:fsverity_verify_bio
```
</details>
</li>
</ul>

## Differences
