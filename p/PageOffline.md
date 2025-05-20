# Function: <code>PageOffline</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81100e16)
Location: include/linux/page-flags.h:749
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In fs/proc/page.c (ffffffff81369c2f)
Location: include/linux/page-flags.h:749
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff8110d276)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In fs/proc/page.c (ffffffff81381e4f)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff81118430)
Location: include/linux/page-flags.h:791
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff812b4577)
Location: include/linux/page-flags.h:791
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/memory_hotplug.c (ffffffff812e0e10)
Location: include/linux/page-flags.h:791
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/page_isolation.c (ffffffff81303fe2)
Location: include/linux/page-flags.h:791
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/proc/page.c (ffffffff813cc47f)
Location: include/linux/page-flags.h:791
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff81bdf8c7)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff812bffb6)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/memory_hotplug.c (ffffffff812ebc10)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/memory_hotplug.c:scan_movable_pages
```
```
In mm/page_isolation.c (ffffffff8130fead)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/proc/page.c (ffffffff813de0c6)
Location: include/linux/page-flags.h:767
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff81bd17ea)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff812c5726)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/memory_hotplug.c (ffffffff81c2d821)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/page_isolation.c (ffffffff81315f8e)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/proc/page.c (ffffffff813e4eb1)
Location: include/linux/page-flags.h:761
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff81caa442)
Location: include/linux/page-flags.h:775
Inline: True
```
```
In mm/page_alloc.c (ffffffff81309dad)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/memory_hotplug.c (ffffffff81d4c109)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/page_isolation.c (ffffffff81362094)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/proc/kcore.c (ffffffff814353d9)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff81436a81)
Location: include/linux/page-flags.h:775
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff81e5a85c)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff81372689)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory_hotplug.c (ffffffff81f1bafd)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/page_isolation.c (ffffffff813deb1d)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/proc/kcore.c (ffffffff814af471)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff814b120b)
Location: include/linux/page-flags.h:998
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff81185d06)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff813efde9)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory_hotplug.c (ffffffff820c3add)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/page_isolation.c (ffffffff814657dd)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/proc/kcore.c (ffffffff81545d2c)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/page.c (ffffffff81547bcb)
Location: include/linux/page-flags.h:977
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff81196ed6)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff81423969)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory_hotplug.c (ffffffff82147989)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/page_isolation.c (ffffffff8149b1d2)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/proc/kcore.c (ffffffff8157d884)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/page.c (ffffffff8157f7ea)
Location: include/linux/page-flags.h:966
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff811a5987)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In mm/page_alloc.c (ffffffff814508a9)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/page_alloc.c:__offline_isolated_pages
```
```
In mm/memory_hotplug.c (ffffffff8222a116)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
```
```
In mm/memory-failure.c (ffffffff814c6a10)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/memory-failure.c:unpoison_memory
  - mm/memory-failure.c:hwpoison_user_mappings
```
```
In mm/page_isolation.c (ffffffff814ca8b2)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/page_isolation.c:test_pages_isolated
```
```
In fs/proc/kcore.c (ffffffff815b6297)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/page.c (ffffffff815b8227)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In fs/proc/page.c (ffff800010450048)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (c03bfee8)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
  - kernel/power/snapshot.c:saveable_highmem_page
```
```
In fs/proc/page.c (c06132f0)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In fs/proc/page.c (c000000000568060)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In fs/proc/page.c (ffffffe0002e3240)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff81105496)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In fs/proc/page.c (ffffffff8137a42f)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff810f6736)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In fs/proc/page.c (ffffffff8136aeff)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff81103746)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In fs/proc/page.c (ffffffff81377eff)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In kernel/power/snapshot.c (ffffffff8110eb36)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - kernel/power/snapshot.c:saveable_page
```
```
In fs/proc/page.c (ffffffff8138b9af)
Location: include/linux/page-flags.h:765
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
</li>
</ul>

## Differences
