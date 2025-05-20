# Function: <code>dax_read_unlock</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163ce64)
Location: drivers/dax/super.c:42
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8163caf0-ffffffff8163cb09: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5b34)
Location: drivers/dax/super.c:43
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_iomap_pfn
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff816a5780-ffffffff816a5799: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1f54)
Location: drivers/dax/super.c:43
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff816e19d0-ffffffff816e19e9: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81705374)
Location: drivers/dax/super.c:43
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff81704df0-ffffffff81704e09: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f208)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff8173f140-ffffffff8173f16e: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817633e8)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff817632b0-ffffffff817632de: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81823288)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff81823150-ffffffff8182317e: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831fc8)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-table.c:device_not_dax_capable
```
**Symbols:**

```
ffffffff81831e90-ffffffff81831ebe: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff818156f8)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-table.c:device_not_dax_capable
```
**Symbols:**

```
ffffffff818150c0-ffffffff818150ee: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189fa62)
Location: drivers/dax/super.c:55
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:dax_get_by_host
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
```
**Symbols:**

```
ffffffff8189f830-ffffffff8189f85e: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e945e)
Location: drivers/dax/super.c:47
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
```
**Symbols:**

```
ffffffff819e8f40-ffffffff819e8f7e: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65b3a)
Location: drivers/dax/super.c:51
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
Direct callers:
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_file_unshare
  - fs/dax.c:dax_iomap_direct_access
```
**Symbols:**

```
ffffffff81b65350-ffffffff81b6538e: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb915a)
Location: drivers/dax/super.c:51
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
Direct callers:
  - fs/dax.c:dax_range_compare_iter
  - fs/dax.c:dax_range_compare_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_iomap_direct_access
```
**Symbols:**

```
ffffffff81bb8950-ffffffff81bb898e: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d7ba)
Location: drivers/dax/super.c:51
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
Direct callers:
  - fs/dax.c:dax_range_compare_iter
  - fs/dax.c:dax_range_compare_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_iomap_direct_access
```
**Symbols:**

```
ffffffff81c0cfb0-ffffffff81c0cfee: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff8000109630e8)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
**Symbols:**

```
ffff800010962ef8-ffff800010962f54: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a3a410)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
c0a39f9c-c0a3a004: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a19700)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
c000000000a19440-c000000000a194b4: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d07e4)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
```
**Symbols:**

```
ffffffe0005d063c-ffffffe0005d0678: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717ad8)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff817179a0-ffffffff817179ce: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816f0008)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/dax/device.c:dev_dax_huge_fault
```
**Symbols:**

```
ffffffff816efed0-ffffffff816efefe: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817568a8)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff81756770-ffffffff8175679e: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dax_read_unlock(int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771d06)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff81771c40-ffffffff81771c6e: dax_read_unlock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
