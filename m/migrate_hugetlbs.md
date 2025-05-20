# Function: <code>migrate_hugetlbs</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int migrate_hugetlbs(struct list_head *from, new_folio_t *get_new_folio, free_folio_t *put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, struct migrate_pages_stats *stats, struct list_head *ret_folios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:1506
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff8146a370-ffffffff8146a560: migrate_hugetlbs (STB_LOCAL)
ffffffff820e736a-ffffffff820e738a: migrate_hugetlbs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int migrate_hugetlbs(struct list_head *from, new_folio_t *get_new_folio, free_folio_t *put_new_folio, long unsigned int private, enum migrate_mode mode, int reason, struct migrate_pages_stats *stats, struct list_head *ret_folios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:1520
Inline: False
Direct callers:
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffffffff81499330-ffffffff81499521: migrate_hugetlbs (STB_LOCAL)
ffffffff821c3f84-ffffffff821c3fa2: migrate_hugetlbs.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
