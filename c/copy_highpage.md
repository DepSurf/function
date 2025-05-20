# Function: <code>copy_highpage</code>

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
In kernel/kexec_core.c (ffffffff8110c837)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff8118754f)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811a8d7b)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/migrate.c (ffffffff811f1e16)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In fs/fuse/file.c (ffffffff81319b4b)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
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
In kernel/kexec_core.c (ffffffff811140a7)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff81199aef)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811c030d)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/migrate.c (ffffffff81210886)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8121b017)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fuse/file.c (ffffffff8134ebb2)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff8111b7bb)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff811a923f)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811d08bd)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/migrate.c (ffffffff812229ea)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8122c72b)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fuse/file.c (ffffffff813644c2)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff8111d51c)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff811b07e0)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811d8edd)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/migrate.c (ffffffff8122e457)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff81238f94)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fuse/file.c (ffffffff81378cd2)
Location: include/linux/highmem.h:239
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff81128c6c)
Location: include/linux/highmem.h:240
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff811c43ad)
Location: include/linux/highmem.h:240
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811ee15d)
Location: include/linux/highmem.h:240
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/migrate.c (ffffffff8124a6b8)
Location: include/linux/highmem.h:240
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff812576b1)
Location: include/linux/highmem.h:240
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fuse/file.c (ffffffff8139db72)
Location: include/linux/highmem.h:240
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff81136cfd)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff811e48bc)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8120ea8b)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/migrate.c (ffffffff8126d9f3)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8127b809)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fuse/file.c (ffffffff813ccf42)
Location: include/linux/highmem.h:242
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff8114235d)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff811f5717)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff81221e1c)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/migrate.c (ffffffff81281ff9)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8128fc13)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fuse/file.c (ffffffff813e62ca)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff8114d773)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff8120d493)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff81233338)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/migrate.c (ffffffff8129e122)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff812aacb5)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_shmem
```
```
In fs/fuse/file.c (ffffffff81412227)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff81159483)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff8121a91d)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8124153a)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/migrate.c (ffffffff812ad9d2)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff812bc286)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff8142bf6b)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff8116a558)
Location: include/linux/highmem.h:335
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff81247314)
Location: include/linux/highmem.h:335
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8126d325)
Location: include/linux/highmem.h:335
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/migrate.c (ffffffff812e2ea8)
Location: include/linux/highmem.h:335
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/khugepaged.c (ffffffff812f17be)
Location: include/linux/highmem.h:335
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff8147bcc9)
Location: include/linux/highmem.h:335
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff81166c98)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff81251990)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff81277b15)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/migrate.c (ffffffff812ee2e8)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:copy_huge_page
  - mm/migrate.c:__copy_gigantic_page
```
```
In mm/khugepaged.c (ffffffff812fdd13)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff81496b2e)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff81167a32)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff812557c2)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8127c875)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/migrate.c (ffffffff812f4411)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff81304e82)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff8149bc22)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff8118d2c6)
Location: include/linux/highmem.h:252
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff81291472)
Location: include/linux/highmem.h:252
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff812ba9d5)
Location: include/linux/highmem.h:252
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/util.c (ffffffff812c10a0)
Location: include/linux/highmem.h:252
Inline: True
Inline callers:
  - mm/util.c:copy_huge_page
```
```
In mm/migrate.c (ffffffff8133e778)
Location: include/linux/highmem.h:252
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff8134ec15)
Location: include/linux/highmem.h:252
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff814f3619)
Location: include/linux/highmem.h:252
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff811bc7f8)
Location: include/linux/highmem.h:323
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff812e6a5c)
Location: include/linux/highmem.h:323
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff813180ab)
Location: include/linux/highmem.h:323
Inline: True
Inline callers:
  - mm/shmem.c:shmem_replace_page
```
```
In mm/util.c (ffffffff8131e016)
Location: include/linux/highmem.h:323
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/khugepaged.c (ffffffff813c586e)
Location: include/linux/highmem.h:323
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff815830b4)
Location: include/linux/highmem.h:323
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff811fe774)
Location: include/linux/highmem.h:350
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff81350549)
Location: include/linux/highmem.h:350
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/util.c (ffffffff81391a74)
Location: include/linux/highmem.h:350
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/migrate_device.c (ffffffff8143a582)
Location: include/linux/highmem.h:350
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In mm/khugepaged.c (ffffffff8144a1cd)
Location: include/linux/highmem.h:350
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff81629044)
Location: include/linux/highmem.h:350
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff81213b74)
Location: include/linux/highmem.h:320
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff8138177a)
Location: include/linux/highmem.h:320
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/util.c (ffffffff813c447c)
Location: include/linux/highmem.h:320
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/migrate_device.c (ffffffff8146fec6)
Location: include/linux/highmem.h:320
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In fs/fuse/file.c (ffffffff81661266)
Location: include/linux/highmem.h:320
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff8122bacb)
Location: include/linux/highmem.h:320
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff813aab0c)
Location: include/linux/highmem.h:320
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/util.c (ffffffff813ee2b9)
Location: include/linux/highmem.h:320
Inline: True
Inline callers:
  - mm/util.c:folio_copy
```
```
In mm/migrate_device.c (ffffffff8149f140)
Location: include/linux/highmem.h:320
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_device_coherent_page
```
```
In fs/fuse/file.c (ffffffff8169b126)
Location: include/linux/highmem.h:320
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffff8000101c89c0)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffff8000102a5ce8)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffff8000102d38a4)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/migrate.c (ffff80001034f9dc)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffff80001035d408)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffff80001050fe50)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (c040fa04)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (c04d50b0)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (c04fbc10)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/migrate.c (c0551ba8)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
```
```
In fs/fuse/file.c (c06cb66c)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (c0000000002312d8)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (c000000000358d38)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (c000000000392af4)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/migrate.c (c0000000004323e8)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (c000000000448f10)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (c000000000657658)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In mm/shmem.c (ffffffe0001ef980)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/migrate.c (ffffffe00023e808)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In fs/fuse/file.c (ffffffe00037a6aa)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff81151aa3)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff81212f6d)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff81239b8a)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/migrate.c (ffffffff812a5fb2)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff812b4866)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff8142454b)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff81144d83)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff81205cdd)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8122cba6)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/migrate.c (ffffffff81297a62)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff812a58ce)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff81414fcb)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff8114f953)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff81210d0d)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8123792a)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/migrate.c (ffffffff812a3dc2)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff812b2676)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff814206eb)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
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
In kernel/kexec_core.c (ffffffff8115c78b)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_alloc_page
```
```
In kernel/events/uprobes.c (ffffffff8121fc2c)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff81246e88)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
```
```
In mm/migrate.c (ffffffff812b4655)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
  - mm/migrate.c:migrate_page_copy
```
```
In mm/khugepaged.c (ffffffff812c2d28)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/fuse/file.c (ffffffff814374ac)
Location: include/linux/highmem.h:266
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
</details>
</li>
</ul>

## Differences
