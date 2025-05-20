# Function: <code>PageChecked</code>

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
In mm/migrate.c (ffffffff811f1c5d)
Location: include/linux/page-flags.h:218
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/ext4/inode.c (ffffffff81295dc4)
Location: include/linux/page-flags.h:218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff812ac9b1)
Location: include/linux/page-flags.h:218
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff81210662)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/ext4/inode.c (ffffffff812c3394)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff812e1071)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff812227a7)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/ext4/inode.c (ffffffff812d8984)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff812f6ba1)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff8122e23d)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In fs/ext4/inode.c (ffffffff812fcc64)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff8132b495)
Location: include/linux/page-flags.h:277
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff81249311)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/ext4/inode.c (ffffffff813214c4)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff8134f8f5)
Location: include/linux/page-flags.h:278
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff8126cd92)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/ext4/inode.c (ffffffff8134f4d4)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff8137dd65)
Location: include/linux/page-flags.h:285
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff812815be)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/ext4/inode.c (ffffffff813676b4)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff81396615)
Location: include/linux/page-flags.h:296
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff8129d850)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/ext4/inode.c (ffffffff81390aa4)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff813c061d)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff812ad16e)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffffffff813512ec)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff813a9504)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff813d98d5)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff812e2cae)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffffffff81397d43)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff813f6644)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff81425c85)
Location: include/linux/page-flags.h:335
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff812ee0de)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffffffff813a95c3)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff81408e9e)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff8143d375)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff812f3bce)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffffffff813b0b03)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff8140effe)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff814431b5)
Location: include/linux/page-flags.h:344
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff8133e56e)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffffffff8140070d)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff81461ffb)
Location: include/linux/page-flags.h:358
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
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
In fs/verity/verify.c (ffffffff8147472d)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff814e89c9)
Location: include/linux/page-flags.h:508
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/verity/verify.c (ffffffff8150685d)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff81581720)
Location: include/linux/page-flags.h:487
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff8153d9dc)
Location: include/linux/page-flags.h:480
Inline: True
Inline callers:
  - fs/verity/verify.c:is_hash_block_verified
  - fs/verity/verify.c:is_hash_block_verified
  - fs/verity/verify.c:is_hash_block_verified
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/verity/verify.c (ffffffff81572e3c)
Location: include/linux/page-flags.h:482
Inline: True
Inline callers:
  - fs/verity/verify.c:is_hash_block_verified
  - fs/verity/verify.c:is_hash_block_verified
  - fs/verity/verify.c:is_hash_block_verified
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
In mm/migrate.c (ffff80001034f46c)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffff800010413378)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffff80001047e5a8)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffff8000104ad0b8)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (c05513fc)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (c05df5e8)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (c063eaf4)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (c06757a0)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (c0000000004318a0)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (c0000000005211b8)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (c0000000005a0c54)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (c0000000005e5510)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffe00023e490)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffffffe0002bae32)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffe000306cec)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffe0003303f2)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff812a574e)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffffffff813498cc)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff813a1ae4)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff813d1eb5)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff8129721e)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffffffff8133a5ac)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff81392574)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff813c2935)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff812a355e)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffffffff8134739c)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff8139f344)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff813cf345)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
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
In mm/migrate.c (ffffffff812b3d6e)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In fs/verity/verify.c (ffffffff8135a69c)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/verity/verify.c:verify_page
```
```
In fs/ext4/inode.c (ffffffff813b39d4)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_releasepage
  - fs/ext4/inode.c:ext4_writepage
```
```
In fs/ext4/super.c (ffffffff813e4685)
Location: include/linux/page-flags.h:327
Inline: True
Inline callers:
  - fs/ext4/super.c:bdev_try_to_free_page
```
</details>
</li>
</ul>

## Differences
