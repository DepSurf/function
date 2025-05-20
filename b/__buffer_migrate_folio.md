# Function: <code>__buffer_migrate_folio</code>

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
int __buffer_migrate_folio(struct address_space *mapping, struct folio *dst, struct folio *src, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff814341e0)
Location: mm/migrate.c:716
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_folio_norefs
  - mm/migrate.c:buffer_migrate_folio
```
**Symbols:**

```
ffffffff814341e0-ffffffff81434453: __buffer_migrate_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __buffer_migrate_folio(struct address_space *mapping, struct folio *dst, struct folio *src, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81469b20)
Location: mm/migrate.c:721
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_folio_norefs
  - mm/migrate.c:buffer_migrate_folio
```
**Symbols:**

```
ffffffff81469b20-ffffffff81469daa: __buffer_migrate_folio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __buffer_migrate_folio(struct address_space *mapping, struct folio *dst, struct folio *src, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:730
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_folio_norefs
  - mm/migrate.c:buffer_migrate_folio
```
**Symbols:**

```
ffffffff81498ab0-ffffffff81498d6c: __buffer_migrate_folio (STB_LOCAL)
ffffffff821c3f5e-ffffffff821c3f84: __buffer_migrate_folio.cold (STB_LOCAL)
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
