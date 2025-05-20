# Function: <code>dax_read_lock</code>

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
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163cdf9)
Location: drivers/dax/super.c:36
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8163cad0-ffffffff8163cae7: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5ac9)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:__dax_zero_page_range
  - fs/dax.c:dax_iomap_pfn
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff816a5760-ffffffff816a5777: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1ef3)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff816e19b0-ffffffff816e19c7: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81705313)
Location: drivers/dax/super.c:37
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff81704dd0-ffffffff81704de7: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f1a3)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff8173ec50-ffffffff8173ec67: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81763383)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff81762e30-ffffffff81762e47: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81823223)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff81822bf0-ffffffff81822c07: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831f63)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-table.c:device_not_dax_capable
```
**Symbols:**

```
ffffffff81831900-ffffffff81831917: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81815693)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
Direct callers:
  - fs/dax.c:dax_iomap_pte_fault
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_pfn
  - drivers/md/dm-table.c:device_not_dax_capable
```
**Symbols:**

```
ffffffff81814b30-ffffffff81814b47: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f99d)
Location: drivers/dax/super.c:49
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:dax_get_by_host
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_iomap_zero
  - fs/dax.c:dax_iomap_zero
```
**Symbols:**

```
ffffffff8189f2f0-ffffffff8189f307: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e9427)
Location: drivers/dax/super.c:41
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
Direct callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
```
**Symbols:**

```
ffffffff819e8f20-ffffffff819e8f3d: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65ae5)
Location: drivers/dax/super.c:45
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
Direct callers:
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_file_unshare
  - fs/dax.c:dax_iomap_direct_access
```
**Symbols:**

```
ffffffff81b65320-ffffffff81b6533d: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb9105)
Location: drivers/dax/super.c:45
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
Direct callers:
  - fs/dax.c:dax_range_compare_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_iomap_direct_access
```
**Symbols:**

```
ffffffff81bb8920-ffffffff81bb893d: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d765)
Location: drivers/dax/super.c:45
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_holder_notify_failure
  - drivers/dax/super.c:fs_dax_get_by_bdev
Direct callers:
  - fs/dax.c:dax_range_compare_iter
  - fs/dax.c:dax_fault_cow_page
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_iomap_direct_access
```
**Symbols:**

```
ffffffff81c0cf80-ffffffff81c0cf9d: dax_read_lock (STB_GLOBAL)
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
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010963070)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
```
**Symbols:**

```
ffff800010962b90-ffff800010962bb4: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a3a398)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
c0a39a04-c0a39a28: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a19530)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
c000000000a18c10-c000000000a18c4c: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d074e)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
```
**Symbols:**

```
ffffffe0005d01d0-ffffffe0005d01fa: dax_read_lock (STB_GLOBAL)
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
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717a73)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff81717520-ffffffff81717537: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816effa3)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
  - drivers/dax/device.c:dev_dax_huge_fault
  - drivers/dax/device.c:dev_dax_huge_fault
```
**Symbols:**

```
ffffffff816efa50-ffffffff816efa67: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756843)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff817562f0-ffffffff81756307: dax_read_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dax_read_lock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771ca3)
Location: drivers/dax/super.c:31
Inline: True
Inline callers:
  - drivers/dax/super.c:dax_get_by_host
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - fs/dax.c:dax_iomap_pfn
```
**Symbols:**

```
ffffffff81771760-ffffffff81771777: dax_read_lock (STB_GLOBAL)
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
