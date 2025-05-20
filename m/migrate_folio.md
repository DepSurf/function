# Function: <code>migrate_folio</code>

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
int migrate_folio(struct address_space *mapping, struct folio *dst, struct folio *src, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81434588)
Location: mm/migrate.c:670
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
Direct callers:
  - mm/migrate_device.c:__migrate_device_pages
```
**Symbols:**

```
ffffffff81431f40-ffffffff81431fc2: migrate_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int migrate_folio(struct address_space *mapping, struct folio *dst, struct folio *src, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81469ed5)
Location: mm/migrate.c:680
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
Direct callers:
  - mm/migrate_device.c:__migrate_device_pages
```
**Symbols:**

```
ffffffff81468080-ffffffff81468102: migrate_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int migrate_folio(struct address_space *mapping, struct folio *dst, struct folio *src, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81498ea3)
Location: mm/migrate.c:689
Inline: True
Inline callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_folio
Direct callers:
  - mm/migrate_device.c:__migrate_device_pages
```
**Symbols:**

```
ffffffff814970f0-ffffffff81497171: migrate_folio (STB_GLOBAL)
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
