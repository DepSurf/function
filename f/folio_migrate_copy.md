# Function: <code>folio_migrate_copy</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void folio_migrate_copy(struct folio *newfolio, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b23f4)
Location: mm/migrate.c:596
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page
Direct callers:
  - mm/folio-compat.c:migrate_page_copy
  - mm/folio-compat.c:migrate_page_copy
  - fs/iomap/buffered-io.c:iomap_migrate_page
```
**Symbols:**

```
ffffffff813b0a00-ffffffff813b0a2f: folio_migrate_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void folio_migrate_copy(struct folio *newfolio, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff814343df)
Location: mm/migrate.c:628
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
Direct callers:
  - fs/aio.c:aio_migrate_folio
```
**Symbols:**

```
ffffffff814315e0-ffffffff8143160f: folio_migrate_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void folio_migrate_copy(struct folio *newfolio, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81469d32)
Location: mm/migrate.c:638
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
Direct callers:
  - fs/aio.c:aio_migrate_folio
```
**Symbols:**

```
ffffffff81466f60-ffffffff81466f8f: folio_migrate_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void folio_migrate_copy(struct folio *newfolio, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81498cf4)
Location: mm/migrate.c:647
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_folio
Direct callers:
  - fs/aio.c:aio_migrate_folio
```
**Symbols:**

```
ffffffff814961a0-ffffffff814961cf: folio_migrate_copy (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
