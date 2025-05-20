# Function: <code>remove_migration_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int remove_migration_pte(struct page *new, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f0b90)
Location: mm/migrate.c:106
Inline: False
```
**Symbols:**

```
ffffffff811f0b90-ffffffff811f0ece: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int remove_migration_pte(struct page *new, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8120fdd0)
Location: mm/migrate.c:196
Inline: False
```
**Symbols:**

```
ffffffff8120fdd0-ffffffff8121015d: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int remove_migration_pte(struct page *new, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81221f00)
Location: mm/migrate.c:196
Inline: False
```
**Symbols:**

```
ffffffff81221f00-ffffffff81222286: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122de50)
Location: mm/migrate.c:198
Inline: False
```
**Symbols:**

```
ffffffff8122de50-ffffffff8122e0ca: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81249b70)
Location: mm/migrate.c:202
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma
```
**Symbols:**

```
ffffffff81249b70-ffffffff81249eb4: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126d3c0)
Location: mm/migrate.c:203
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma
```
**Symbols:**

```
ffffffff8126d3c0-ffffffff8126d711: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81281ab0)
Location: mm/migrate.c:203
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma
```
**Symbols:**

```
ffffffff81281ab0-ffffffff81281e2b: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129dbc0)
Location: mm/migrate.c:203
Inline: False
```
**Symbols:**

```
ffffffff8129dbc0-ffffffff8129df48: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ad470)
Location: mm/migrate.c:204
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812ad470-ffffffff812ad7f8: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e27d0)
Location: mm/migrate.c:205
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_prepare
```
**Symbols:**

```
ffffffff812e27d0-ffffffff812e2bcd: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812edc00)
Location: mm/migrate.c:201
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_prepare
```
**Symbols:**

```
ffffffff812edc00-ffffffff812edffa: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f3d90)
Location: mm/migrate.c:174
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_prepare
```
**Symbols:**

```
ffffffff812f3d90-ffffffff812f4185: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133e7e0)
Location: mm/migrate.c:175
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_prepare
```
**Symbols:**

```
ffffffff8133e7e0-ffffffff8133ebdc: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool remove_migration_pte(struct folio *folio, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b18e0)
Location: mm/migrate.c:174
Inline: False
```
**Symbols:**

```
ffffffff813b18e0-ffffffff813b1dd1: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool remove_migration_pte(struct folio *folio, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:183
Inline: False
```
**Symbols:**

```
ffffffff81432340-ffffffff814328ad: remove_migration_pte (STB_LOCAL)
ffffffff820679af-ffffffff820679e9: remove_migration_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool remove_migration_pte(struct folio *folio, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:183
Inline: False
```
**Symbols:**

```
ffffffff81467aa0-ffffffff81467fbf: remove_migration_pte (STB_LOCAL)
ffffffff820e72f8-ffffffff820e734e: remove_migration_pte.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool remove_migration_pte(struct folio *folio, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate.c (0)
Location: mm/migrate.c:183
Inline: False
```
**Symbols:**

```
ffffffff81497760-ffffffff81497d0a: remove_migration_pte (STB_LOCAL)
ffffffff821c3ed0-ffffffff821c3f42: remove_migration_pte.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff80001034eeb0)
Location: mm/migrate.c:204
Inline: False
```
**Symbols:**

```
ffff80001034eeb0-ffff80001034f194: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0551604)
Location: mm/migrate.c:204
Inline: False
```
**Symbols:**

```
c0551604-c05517d4: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0000000004312c0)
Location: mm/migrate.c:204
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
c0000000004312c0-c000000000431720: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023e17c)
Location: mm/migrate.c:204
Inline: False
```
**Symbols:**

```
ffffffe00023e17c-ffffffe00023e3a6: remove_migration_pte (STB_LOCAL)
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
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5a50)
Location: mm/migrate.c:204
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812a5a50-ffffffff812a5dd8: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81297520)
Location: mm/migrate.c:204
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff81297520-ffffffff81297889: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a3860)
Location: mm/migrate.c:204
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812a3860-ffffffff812a3be8: remove_migration_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool remove_migration_pte(struct page *page, struct vm_area_struct *vma, long unsigned int addr, void *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b4070)
Location: mm/migrate.c:204
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812b4070-ffffffff812b43f8: remove_migration_pte (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *new</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
</li>
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
