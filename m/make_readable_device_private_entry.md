# Function: <code>make_readable_device_private_entry</code>

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
In mm/memory.c (0)
Location: include/linux/swapops.h:110
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:110
Inline: True
```
```
In mm/migrate.c (ffffffff8133ebb2)
Location: include/linux/swapops.h:110
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
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
In mm/memory.c (0)
Location: include/linux/swapops.h:122
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:122
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (0)
Location: include/linux/swapops.h:122
Inline: True
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
In mm/memory.c (0)
Location: include/linux/swapops.h:168
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:168
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/swapops.h:168
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (0)
Location: include/linux/swapops.h:168
Inline: True
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
In mm/memory.c (0)
Location: include/linux/swapops.h:168
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:168
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/swapops.h:168
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (0)
Location: include/linux/swapops.h:168
Inline: True
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
In mm/memory.c (ffffffff81416ec8)
Location: include/linux/swapops.h:168
Inline: True
Inline callers:
  - mm/memory.c:copy_nonpresent_pte
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:168
Inline: True
```
```
In mm/migrate.c (ffffffff81497ce5)
Location: include/linux/swapops.h:168
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8149d5fb)
Location: include/linux/swapops.h:168
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
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
