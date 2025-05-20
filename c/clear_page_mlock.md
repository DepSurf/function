# Function: <code>clear_page_mlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811c3050)
Location: mm/mlock.c:57
Inline: False
```
**Symbols:**

```
ffffffff811c3050-ffffffff811c30e5: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811ded70)
Location: mm/mlock.c:57
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff811ded70-ffffffff811dee1f: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811eeb90)
Location: mm/mlock.c:57
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff811eeb90-ffffffff811eec3f: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811f9b40)
Location: mm/mlock.c:58
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff811f9b40-ffffffff811f9bf2: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81211fa0)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff81211fa0-ffffffff8121204c: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81232ce0)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff81232ce0-ffffffff81232d8d: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812464b0)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812464b0-ffffffff8124655d: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812586f0)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812586f0-ffffffff812587a3: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81266bc0)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff81266bc0-ffffffff81266c73: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81296e10)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff81296e10-ffffffff81296ec2: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a1e40)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812a1e40-ffffffff812a1f04: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a76d0)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812a76d0-ffffffff812a7794: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812e8c30)
Location: mm/mlock.c:60
Inline: False
Direct callers:
  - mm/rmap.c:page_remove_rmap
  - mm/rmap.c:page_remove_anon_compound_rmap
  - mm/rmap.c:page_remove_file_rmap
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff812e8c30-ffffffff812e8d32: clear_page_mlock (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffff8000102fdc98)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffff8000102fdc98-ffff8000102fddf0: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c051cfc0)
Location: mm/mlock.c:59
Inline: False
```
**Symbols:**

```
c051cfc0-c051d098: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c0000000003c9290)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
c0000000003c9290-c0000000003c9428: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffe00020c412)
Location: mm/mlock.c:59
Inline: False
```
**Symbols:**

```
ffffffe00020c412-ffffffe00020c512: clear_page_mlock (STB_GLOBAL)
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
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125f210)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff8125f210-ffffffff8125f2c3: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81251630)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff81251630-ffffffff812516e3: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125cfb0)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff8125cfb0-ffffffff8125d063: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void clear_page_mlock(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8126c9b0)
Location: mm/mlock.c:59
Inline: False
Direct callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff8126c9b0-ffffffff8126ca63: clear_page_mlock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
