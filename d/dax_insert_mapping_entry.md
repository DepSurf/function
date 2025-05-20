# Function: <code>dax_insert_mapping_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81287fdb)
Location: fs/dax.c:604
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *dax_insert_mapping_entry(struct address_space *mapping, struct vm_fault *vmf, void *entry, sector_t sector, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129af00)
Location: fs/dax.c:597
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_pmd_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff8129af00-ffffffff8129b1e5: dax_insert_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff812aa0c0)
Location: fs/dax.c:523
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff812aa0c0-ffffffff812aa236: dax_insert_mapping_entry.isra.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *dax_insert_mapping_entry(struct address_space *mapping, struct vm_fault *vmf, void *entry, sector_t sector, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812cd670)
Location: fs/dax.c:526
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
  - fs/dax.c:dax_iomap_fault
```
**Symbols:**

```
ffffffff812cd670-ffffffff812cd7e4: dax_insert_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *dax_insert_mapping_entry(struct address_space *mapping, struct vm_fault *vmf, void *entry, pfn_t pfn_t, long unsigned int flags, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f7c60)
Location: fs/dax.c:793
Inline: False
```
**Symbols:**

```
ffffffff812f7c60-ffffffff812f7f6c: dax_insert_mapping_entry (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pfn_t pfn_t</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t sector</code>
</li>
</ul>
</details>
</li>
</ul>
