# Function: <code>get_unlocked_mapping_entry</code>

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
void *get_unlocked_mapping_entry(struct address_space *mapping, long unsigned int index, void ***slotp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81287160)
Location: fs/dax.c:370
Inline: False
Direct callers:
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:dax_fault
  - fs/dax.c:dax_delete_mapping_entry
```
**Symbols:**

```
ffffffff81287160-ffffffff8128727a: get_unlocked_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *get_unlocked_mapping_entry(struct address_space *mapping, long unsigned int index, void ***slotp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8129adb0)
Location: fs/dax.c:214
Inline: False
Direct callers:
  - fs/dax.c:dax_pfn_mkwrite
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff8129adb0-ffffffff8129aef5: get_unlocked_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *get_unlocked_mapping_entry(struct address_space *mapping, long unsigned int index, void ***slotp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812a9e90)
Location: fs/dax.c:230
Inline: False
Direct callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff812a9e90-ffffffff812a9fd0: get_unlocked_mapping_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *get_unlocked_mapping_entry(struct address_space *mapping, long unsigned int index, void ***slotp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812cd440)
Location: fs/dax.c:233
Inline: False
Direct callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
```
**Symbols:**

```
ffffffff812cd440-ffffffff812cd580: get_unlocked_mapping_entry (STB_LOCAL)
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
In fs/dax.c (ffffffff812f80d5)
Location: fs/dax.c:274
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:__dax_invalidate_mapping_entry
  - fs/dax.c:grab_mapping_entry
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
