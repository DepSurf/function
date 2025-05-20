# Function: <code>SHMEM_SB</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:131
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:127
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:139
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:139
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:141
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:146
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:161
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81272905)
Location: mm/shmem.c:160
Inline: True
Inline callers:
  - mm/shmem.c:shmem_huge_enabled
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_unused_huge_count
  - mm/shmem.c:shmem_unused_huge_scan
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127cda5)
Location: mm/shmem.c:159
Inline: True
Inline callers:
  - mm/shmem.c:shmem_huge_enabled
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_unused_huge_count
  - mm/shmem.c:shmem_unused_huge_scan
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_reserve_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81281f45)
Location: mm/shmem.c:159
Inline: True
Inline callers:
  - mm/shmem.c:shmem_huge_enabled
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_getattr
  - mm/shmem.c:shmem_unused_huge_count
  - mm/shmem.c:shmem_unused_huge_scan
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_reserve_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812b9608)
Location: mm/shmem.c:155
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_count
  - mm/shmem.c:shmem_unused_huge_scan
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_reserve_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813154f8)
Location: mm/shmem.c:153
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_count
  - mm/shmem.c:shmem_unused_huge_scan
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff813893f8)
Location: mm/shmem.c:144
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_count
  - mm/shmem.c:shmem_unused_huge_scan
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff813bb6a8)
Location: mm/shmem.c:145
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_fill_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_count
  - mm/shmem.c:shmem_unused_huge_scan
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff813e61c8)
Location: mm/shmem.c:153
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_xattr_handler_set
  - mm/shmem.c:shmem_initxattrs
  - mm/shmem.c:shmem_link
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:__shmem_get_inode
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_add_folio
  - mm/shmem.c:shmem_writepage
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_unused_huge_count
  - mm/shmem.c:shmem_unused_huge_scan
  - mm/shmem.c:shmem_inode_unacct_blocks
  - mm/shmem.c:shmem_inode_acct_blocks
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:161
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c152e004)
Location: mm/shmem.c:161
Inline: True
Inline callers:
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_free_inode
  - mm/shmem.c:shmem_reserve_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000397530)
Location: mm/shmem.c:161
Inline: True
Inline callers:
  - mm/shmem.c:shmem_huge_enabled
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_get_unmapped_area
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_unused_huge_count
  - mm/shmem.c:shmem_unused_huge_scan
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_free_inode
  - mm/shmem.c:shmem_reserve_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe00001262e)
Location: mm/shmem.c:161
Inline: True
Inline callers:
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_put_super
  - mm/shmem.c:shmem_show_options
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_statfs
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_inode
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_evict_inode
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_free_inode
  - mm/shmem.c:shmem_reserve_inode
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:161
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:161
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:161
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (0)
Location: mm/shmem.c:161
Inline: True
```
</details>
</li>
</ul>

## Differences
