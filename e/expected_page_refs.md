# Function: <code>expected_page_refs</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int expected_page_refs(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81281470)
Location: mm/migrate.c:375
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff81281470-ffffffff812814f6: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129d9c0)
Location: mm/migrate.c:373
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff8129d9c0-ffffffff8129da22: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ad020)
Location: mm/migrate.c:374
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812ad020-ffffffff812ad082: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e2150)
Location: mm/migrate.c:379
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812e2150-ffffffff812e21b5: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ed2f0)
Location: mm/migrate.c:375
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812ed2f0-ffffffff812ed351: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f3690)
Location: mm/migrate.c:349
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812f3690-ffffffff812f36f1: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133dbe0)
Location: mm/migrate.c:357
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff8133dbe0-ffffffff8133dc41: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b2882)
Location: mm/migrate.c:355
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:folio_migrate_mapping
  - mm/migrate.c:folio_migrate_mapping
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff8000103501bc)
Location: mm/migrate.c:374
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c05518d8)
Location: mm/migrate.c:374
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000431220)
Location: mm/migrate.c:374
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
c000000000431220-c0000000004312b8: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023ee94)
Location: mm/migrate.c:374
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate.c:migrate_page_move_mapping
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5600)
Location: mm/migrate.c:374
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812a5600-ffffffff812a5662: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812970d0)
Location: mm/migrate.c:374
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812970d0-ffffffff81297132: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a3410)
Location: mm/migrate.c:374
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812a3410-ffffffff812a3472: expected_page_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int expected_page_refs(struct address_space *mapping, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b36a0)
Location: mm/migrate.c:374
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page_move_mapping
```
**Symbols:**

```
ffffffff812b36a0-ffffffff812b3702: expected_page_refs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct address_space *mapping</code>
</li>
<li>
<b>Param reordered. </b>
<code>page</code> ➡️ <code>mapping, page</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
