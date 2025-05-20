# Function: <code>mmu_notifier_range_init_owner</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812dedd2)
Location: include/linux/mmu_notifier.h:530
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/rmap.c (ffffffff812f8b28)
Location: include/linux/mmu_notifier.h:530
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
```
```
In mm/migrate.c (ffffffff8134150d)
Location: include/linux/mmu_notifier.h:530
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:migrate_vma_setup
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
In mm/memory.c (ffffffff8133ed66)
Location: include/linux/mmu_notifier.h:530
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/rmap.c (ffffffff8135f107)
Location: include/linux/mmu_notifier.h:530
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
```
```
In mm/migrate_device.c (ffffffff813b8461)
Location: include/linux/mmu_notifier.h:530
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_pages
  - mm/migrate_device.c:migrate_vma_setup
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
In mm/memory.c (ffffffff813b604b)
Location: include/linux/mmu_notifier.h:530
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/rmap.c (ffffffff813d9fbf)
Location: include/linux/mmu_notifier.h:530
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
```
```
In mm/migrate_device.c (ffffffff8143a22f)
Location: include/linux/mmu_notifier.h:530
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
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
In mm/memory.c (ffffffff813ea916)
Location: include/linux/mmu_notifier.h:527
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/rmap.c (ffffffff8140e6e4)
Location: include/linux/mmu_notifier.h:527
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
```
```
In mm/migrate_device.c (ffffffff8146ee9a)
Location: include/linux/mmu_notifier.h:527
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
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
In mm/memory.c (ffffffff81417039)
Location: include/linux/mmu_notifier.h:526
Inline: True
Inline callers:
  - mm/memory.c:remove_device_exclusive_entry
```
```
In mm/rmap.c (ffffffff8143aec9)
Location: include/linux/mmu_notifier.h:526
Inline: True
Inline callers:
  - mm/rmap.c:page_make_device_exclusive_one
```
```
In mm/migrate_device.c (ffffffff8149d941)
Location: include/linux/mmu_notifier.h:526
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
  - mm/migrate_device.c:migrate_vma_setup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
