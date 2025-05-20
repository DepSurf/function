# Function: <code>__generic_remap_file_range_prep</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags, const struct iomap_ops *dax_read_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (0)
Location: fs/remap_range.c:268
Inline: False
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/dax.c:dax_remap_file_range_prep
```
**Symbols:**

```
ffffffff82068e28-ffffffff82068e5e: __generic_remap_file_range_prep.cold (STB_LOCAL)
ffffffff814d13e0-ffffffff814d166d: __generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags, const struct iomap_ops *dax_read_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (0)
Location: fs/remap_range.c:271
Inline: False
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/dax.c:dax_remap_file_range_prep
```
**Symbols:**

```
ffffffff820e8748-ffffffff820e877e: __generic_remap_file_range_prep.cold (STB_LOCAL)
ffffffff81507b50-ffffffff81507de3: __generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags, const struct iomap_ops *dax_read_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (0)
Location: fs/remap_range.c:277
Inline: False
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
  - fs/dax.c:dax_remap_file_range_prep
```
**Symbols:**

```
ffffffff821c5527-ffffffff821c555d: __generic_remap_file_range_prep.cold (STB_LOCAL)
ffffffff8153c990-ffffffff8153cc23: __generic_remap_file_range_prep (STB_GLOBAL)
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
