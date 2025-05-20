# Function: <code>migrate_device_unmap</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int migrate_device_unmap(long unsigned int *src_pfns, long unsigned int npages, struct page *fault_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff81437fe0)
Location: mm/migrate_device.c:363
Inline: False
Direct callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff81437fe0-ffffffff81438544: migrate_device_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int migrate_device_unmap(long unsigned int *src_pfns, long unsigned int npages, struct page *fault_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff8146dcb0)
Location: mm/migrate_device.c:357
Inline: False
Direct callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff8146dcb0-ffffffff8146e226: migrate_device_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int migrate_device_unmap(long unsigned int *src_pfns, long unsigned int npages, struct page *fault_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff8149e680)
Location: mm/migrate_device.c:360
Inline: False
Direct callers:
  - mm/migrate_device.c:migrate_device_coherent_page
  - mm/migrate_device.c:migrate_device_range
  - mm/migrate_device.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff8149e680-ffffffff8149ebcf: migrate_device_unmap (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
