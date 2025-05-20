# Function: <code>migrate_page_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f1ab0)
Location: mm/migrate.c:524
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
  - fs/hugetlbfs/inode.c:hugetlbfs_migrate_page
```
**Symbols:**

```
ffffffff811f1ab0-ffffffff811f1fd4: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81210480)
Location: mm/migrate.c:619
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:buffer_migrate_page
  - fs/aio.c:aio_migratepage
  - fs/hugetlbfs/inode.c:hugetlbfs_migrate_page
```
**Symbols:**

```
ffffffff81210480-ffffffff81210a46: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812225b0)
Location: mm/migrate.c:621
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:buffer_migrate_page
  - fs/aio.c:aio_migratepage
  - fs/hugetlbfs/inode.c:hugetlbfs_migrate_page
```
**Symbols:**

```
ffffffff812225b0-ffffffff81222b9f: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122e0d0)
Location: mm/migrate.c:607
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
  - fs/hugetlbfs/inode.c:hugetlbfs_migrate_page
```
**Symbols:**

```
ffffffff8122e0d0-ffffffff8122e5a6: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124a4e0)
Location: mm/migrate.c:717
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff8124a4e0-ffffffff8124a844: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126d830)
Location: mm/migrate.c:729
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff8126d830-ffffffff8126db70: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81281e30)
Location: mm/migrate.c:658
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff81281e30-ffffffff8128217a: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129df50)
Location: mm/migrate.c:654
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff8129df50-ffffffff8129e2fa: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ad800)
Location: mm/migrate.c:655
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812ad800-ffffffff812adbaa: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e2e60)
Location: mm/migrate.c:675
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812e2e60-ffffffff812e2f06: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ee2a0)
Location: mm/migrate.c:673
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812ee2a0-ffffffff812ee346: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f4240)
Location: mm/migrate.c:653
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812f4240-ffffffff812f44ee: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133e730)
Location: mm/migrate.c:616
Inline: False
Direct callers:
  - mm/migrate.c:migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff8133e730-ffffffff8133e7d6: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/folio-compat.c (ffffffff813010e0)
Location: mm/folio-compat.c:69
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff813010e0-ffffffff81301171: migrate_page_copy (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff80001034f7d0)
Location: mm/migrate.c:655
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:__buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffff80001034f7d0-ffff80001034fab4: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0551ba8)
Location: mm/migrate.c:655
Inline: True
Inline callers:
  - mm/migrate.c:__buffer_migrate_page
Direct callers:
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
c05515a8-c0551604: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000432120)
Location: mm/migrate.c:655
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
c000000000432120-c0000000004325d8: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023e658)
Location: mm/migrate.c:655
Inline: False
Direct callers:
  - mm/migrate.c:__buffer_migrate_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffe00023e658-ffffffe00023e976: migrate_page_copy (STB_GLOBAL)
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
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a5de0)
Location: mm/migrate.c:655
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812a5de0-ffffffff812a618a: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81297890)
Location: mm/migrate.c:655
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff81297890-ffffffff81297c3a: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a3bf0)
Location: mm/migrate.c:655
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812a3bf0-ffffffff812a3f9a: migrate_page_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void migrate_page_copy(struct page *newpage, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b4400)
Location: mm/migrate.c:655
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - fs/aio.c:aio_migratepage
```
**Symbols:**

```
ffffffff812b4400-ffffffff812b487d: migrate_page_copy (STB_GLOBAL)
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
