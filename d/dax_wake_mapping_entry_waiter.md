# Function: <code>dax_wake_mapping_entry_waiter</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space *mapping, long unsigned int index, bool wake_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81287750)
Location: fs/dax.c:463
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_tree_insert
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:dax_delete_mapping_entry
  - fs/dax.c:dax_unlock_mapping_entry
```
**Symbols:**

```
ffffffff81287750-ffffffff812877d8: dax_wake_mapping_entry_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space *mapping, long unsigned int index, void *entry, bool wake_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129b310)
Location: fs/dax.c:436
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_tree_insert
  - fs/dax.c:dax_invalidate_mapping_entry
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_mapping_entry
```
**Symbols:**

```
ffffffff8129b310-ffffffff8129b3a2: dax_wake_mapping_entry_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space *mapping, long unsigned int index, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812a9390)
Location: fs/dax.c:164
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_mapping_entry
```
**Symbols:**

```
ffffffff812a9390-ffffffff812a9422: dax_wake_mapping_entry_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space *mapping, long unsigned int index, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812cc860)
Location: fs/dax.c:167
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_unlock_mapping_entry
```
**Symbols:**

```
ffffffff812cc860-ffffffff812cc8f2: dax_wake_mapping_entry_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dax_wake_mapping_entry_waiter(struct address_space *mapping, long unsigned int index, void *entry, bool wake_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f6c20)
Location: fs/dax.c:165
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:unlock_mapping_entry
```
**Symbols:**

```
ffffffff812f6c20-ffffffff812f6cb2: dax_wake_mapping_entry_waiter (STB_LOCAL)
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
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *entry</code>
</li>
<li>
<b>Param reordered. </b>
<code>mapping, index, wake_all</code> ➡️ <code>mapping, index, entry, wake_all</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
