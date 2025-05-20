# Function: <code>SetPageMappedToDisk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f1c77)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff81244de4)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/buffer.c:block_read_full_page
  - fs/buffer.c:nobh_write_begin
```
```
In fs/mpage.c (ffffffff8124e572)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff812e3470)
Location: include/linux/page-flags.h:243
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8121068a)
Location: include/linux/page-flags.h:298
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff8126f2f7)
Location: include/linux/page-flags.h:298
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff81276c8c)
Location: include/linux/page-flags.h:298
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81313314)
Location: include/linux/page-flags.h:298
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812227d1)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff812824fc)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff8128a977)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813292b2)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122e265)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/buffer.c (ffffffff8128fbd8)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff81297834)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff8131ee55)
Location: include/linux/page-flags.h:308
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81249339)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff812b2902)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff812baabb)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813434ef)
Location: include/linux/page-flags.h:309
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126cdba)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff812da817)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff812e360d)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813712f1)
Location: include/linux/page-flags.h:316
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff812815e6)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff812efcf7)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff812f8339)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813897ad)
Location: include/linux/page-flags.h:328
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff8129d879)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff81311590)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff81318966)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813b3983)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff812ad197)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff81324570)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff8132b7ad)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813ccbb8)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff812e2cd5)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8135e57e)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff8136542e)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81418de0)
Location: include/linux/page-flags.h:369
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff812ee105)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8136c001)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff8137232f)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff8142ca4f)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff812f3bf5)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff81372931)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff8137841a)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81433685)
Location: include/linux/page-flags.h:377
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff8133e595)
Location: include/linux/page-flags.h:391
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff813c198f)
Location: include/linux/page-flags.h:391
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff813c4ba6)
Location: include/linux/page-flags.h:391
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff81486f32)
Location: include/linux/page-flags.h:391
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/buffer.c (ffffffff814489a9)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
```
```
In fs/mpage.c (ffffffff8144b99b)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff8150a9ad)
Location: include/linux/page-flags.h:541
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In fs/ext4/readpage.c (ffffffff815a551e)
Location: include/linux/page-flags.h:520
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff80001034f494)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffff8000103dd8cc)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffff8000103e6c10)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffff8000104a4f40)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (c0551424)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (c05b6dfc)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (c05be9a0)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (c0666dbc)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (c0000000004318dc)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (c0000000004e3378)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (c0000000004ecf64)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (c0000000005d2184)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffe00023e4b6)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffe0002958bc)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffe00029bd58)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffe000325fec)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff812a5777)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8131cb50)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff81323d8d)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813c5198)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff81297247)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8130d6f0)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff8131492d)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813b5c18)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff812a3587)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8131a620)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff8132185d)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813c2628)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
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
In mm/migrate.c (ffffffff812b3d97)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/buffer.c (ffffffff8132c333)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:block_read_full_page
```
```
In fs/mpage.c (ffffffff813335b1)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/ext4/readpage.c (ffffffff813d780d)
Location: include/linux/page-flags.h:361
Inline: True
Inline callers:
  - fs/ext4/readpage.c:ext4_mpage_readpages
```
</details>
</li>
</ul>

## Differences
