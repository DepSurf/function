# Function: <code>dax_lock_mapping_entry</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool dax_lock_mapping_entry(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff812f9df0)
Location: fs/dax.c:409
Inline: False
```
**Symbols:**

```
ffffffff812f9df0-ffffffff812f9f0d: dax_lock_mapping_entry (STB_GLOBAL)
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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
dax_entry_t dax_lock_mapping_entry(struct address_space *mapping, long unsigned int index, struct page **page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814fb380)
Location: fs/dax.c:504
Inline: False
Direct callers:
  - mm/memory-failure.c:mf_dax_kill_procs
```
**Symbols:**

```
ffffffff814fb380-ffffffff814fb4b5: dax_lock_mapping_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
dax_entry_t dax_lock_mapping_entry(struct address_space *mapping, long unsigned int index, struct page **page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff815327d0)
Location: fs/dax.c:504
Inline: False
Direct callers:
  - mm/memory-failure.c:mf_dax_kill_procs
```
**Symbols:**

```
ffffffff815327d0-ffffffff81532905: dax_lock_mapping_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
dax_entry_t dax_lock_mapping_entry(struct address_space *mapping, long unsigned int index, struct page **page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff815676c0)
Location: fs/dax.c:490
Inline: False
Direct callers:
  - mm/memory-failure.c:mf_dax_kill_procs
```
**Symbols:**

```
ffffffff815676c0-ffffffff815677f5: dax_lock_mapping_entry (STB_GLOBAL)
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
