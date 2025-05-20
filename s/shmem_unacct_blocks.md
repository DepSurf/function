# Function: <code>shmem_unacct_blocks</code>

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
In mm/shmem.c (ffffffff811a829f)
Location: mm/shmem.c:186
Inline: True
Inline callers:
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_getpage_gfp
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
In mm/shmem.c (ffffffff811c0986)
Location: mm/shmem.c:182
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff811d0f65)
Location: mm/shmem.c:178
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff811dcca0)
Location: mm/shmem.c:189
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff811eed35)
Location: mm/shmem.c:190
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff8120f849)
Location: mm/shmem.c:190
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff812229ae)
Location: mm/shmem.c:192
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff81231faf)
Location: mm/shmem.c:197
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff8124006f)
Location: mm/shmem.c:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff8126e72d)
Location: mm/shmem.c:211
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
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
In mm/shmem.c (ffffffff81279128)
Location: mm/shmem.c:210
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff8127e0d6)
Location: mm/shmem.c:210
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff812c008d)
Location: mm/shmem.c:206
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff8131c8f3)
Location: mm/shmem.c:204
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
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
In mm/shmem.c (ffffffff813905a5)
Location: mm/shmem.c:195
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
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
In mm/shmem.c (ffffffff813c2ec5)
Location: mm/shmem.c:196
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_get_folio_gfp
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_alloc_and_acct_folio
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
In mm/shmem.c (ffffffff813e80bf)
Location: mm/shmem.c:204
Inline: True
Inline callers:
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
In mm/shmem.c (ffff8000102d332c)
Location: mm/shmem.c:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (c04fb344)
Location: mm/shmem.c:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (c000000000391edc)
Location: mm/shmem.c:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffe0001ee58a)
Location: mm/shmem.c:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff812386bf)
Location: mm/shmem.c:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff8122b6d3)
Location: mm/shmem.c:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff8123645f)
Location: mm/shmem.c:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
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
In mm/shmem.c (ffffffff8124674a)
Location: mm/shmem.c:212
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_uncharge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_charge
  - mm/shmem.c:shmem_recalc_inode
  - mm/shmem.c:shmem_recalc_inode
```
</details>
</li>
</ul>

## Differences
