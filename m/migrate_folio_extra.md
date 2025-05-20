# Function: <code>migrate_folio_extra</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int migrate_folio_extra(struct address_space *mapping, struct folio *dst, struct folio *src, enum migrate_mode mode, int extra_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81431f45)
Location: mm/migrate.c:639
Inline: True
Direct callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate_device.c:__migrate_device_pages
```
**Symbols:**

```
ffffffff81434140-ffffffff814341c9: migrate_folio_extra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int migrate_folio_extra(struct address_space *mapping, struct folio *dst, struct folio *src, enum migrate_mode mode, int extra_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81468085)
Location: mm/migrate.c:649
Inline: True
Direct callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate_device.c:__migrate_device_pages
```
**Symbols:**

```
ffffffff81469a80-ffffffff81469b09: migrate_folio_extra (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int migrate_folio_extra(struct address_space *mapping, struct folio *dst, struct folio *src, enum migrate_mode mode, int extra_count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff814970f5)
Location: mm/migrate.c:658
Inline: True
Direct callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
  - mm/migrate_device.c:__migrate_device_pages
```
**Symbols:**

```
ffffffff81498a10-ffffffff81498a98: migrate_folio_extra (STB_GLOBAL)
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
