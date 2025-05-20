# Function: <code>find_next_bit_le</code>

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
In fs/ext4/mballoc.c (ffffffff812ce272)
Location: include/asm-generic/bitops/le.h:17
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In drivers/nvdimm/label.c (ffffffff8159f98f)
Location: include/asm-generic/bitops/le.h:17
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff813056a3)
Location: include/asm-generic/bitops/le.h:17
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff815f59a2)
Location: include/asm-generic/bitops/le.h:17
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff8131b661)
Location: include/asm-generic/bitops/le.h:17
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81623662)
Location: include/asm-generic/bitops/le.h:17
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff813131dd)
Location: include/asm-generic/bitops/le.h:17
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8163838b)
Location: include/asm-generic/bitops/le.h:17
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff8133799d)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff816a0a8b)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff81365ee6)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff816dcd85)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff8137e346)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff816ff0d5)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff813a77ac)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81738e66)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff813c064c)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8175cbb2)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff8140c77c)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8181c4b2)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff8141fbec)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8182b502)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff814264ff)
Location: include/asm-generic/bitops/le.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8180e823)
Location: include/asm-generic/bitops/le.h:20
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff8147a195)
Location: include/asm-generic/bitops/le.h:20
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81898e03)
Location: include/asm-generic/bitops/le.h:20
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff814fc421)
Location: include/linux/find.h:221
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff819e2d23)
Location: include/linux/find.h:221
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff81596b74)
Location: include/linux/find.h:423
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81b5e983)
Location: include/linux/find.h:423
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff815cd592)
Location: include/linux/find.h:488
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81bb1f33)
Location: include/linux/find.h:488
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff81605e12)
Location: include/linux/find.h:488
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81c06423)
Location: include/linux/find.h:488
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffff8000104971ec)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffff80001095e364)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (c0659580)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_release_inode_pa
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
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
In fs/ext4/mballoc.c (c0000000005c1810)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (c000000000a1026c)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffe00031bc6e)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffe0005cc316)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff813b8c2c)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff817112a2)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff813a96bc)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff816e4d22)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff813b648c)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff81750072)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
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
In fs/ext4/mballoc.c (ffffffff813cb1ac)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mballoc_query_range
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_mb_generate_buddy
```
```
In drivers/nvdimm/label.c (ffffffff8176b4f2)
Location: include/asm-generic/bitops/le.h:18
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_alloc_slot
```
</details>
</li>
</ul>

## Differences
