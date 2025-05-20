# Function: <code>add_page_for_migration</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81271b84)
Location: mm/migrate.c:1494
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812861a4)
Location: mm/migrate.c:1527
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a0686)
Location: mm/migrate.c:1522
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b1a33)
Location: mm/migrate.c:1525
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_page_for_migration(struct mm_struct *mm, long unsigned int addr, int node, struct list_head *pagelist, bool migrate_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e30f0)
Location: mm/migrate.c:1539
Inline: False
Direct callers:
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff812e30f0-ffffffff812e331c: add_page_for_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_page_for_migration(struct mm_struct *mm, long unsigned int addr, int node, struct list_head *pagelist, bool migrate_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ee530)
Location: mm/migrate.c:1660
Inline: False
Direct callers:
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff812ee530-ffffffff812ee796: add_page_for_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_page_for_migration(struct mm_struct *mm, long unsigned int addr, int node, struct list_head *pagelist, bool migrate_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f46d0)
Location: mm/migrate.c:1642
Inline: False
Direct callers:
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff812f46d0-ffffffff812f4928: add_page_for_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_page_for_migration(struct mm_struct *mm, long unsigned int addr, int node, struct list_head *pagelist, bool migrate_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133ee70)
Location: mm/migrate.c:1686
Inline: False
Direct callers:
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff8133ee70-ffffffff8133f0c2: add_page_for_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_page_for_migration(struct mm_struct *mm, long unsigned int addr, int node, struct list_head *pagelist, bool migrate_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b24a0)
Location: mm/migrate.c:1617
Inline: False
Direct callers:
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff813b24a0-ffffffff813b284b: add_page_for_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_page_for_migration(struct mm_struct *mm, long unsigned int addr, int node, struct list_head *pagelist, bool migrate_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81432be0)
Location: mm/migrate.c:1724
Inline: False
Direct callers:
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81432be0-ffffffff81432ff4: add_page_for_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_page_for_migration(struct mm_struct *mm, const void *p, int node, struct list_head *pagelist, bool migrate_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81468d00)
Location: mm/migrate.c:2055
Inline: False
Direct callers:
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81468d00-ffffffff81469104: add_page_for_migration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_page_for_migration(struct mm_struct *mm, const void *p, int node, struct list_head *pagelist, bool migrate_all);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81497350)
Location: mm/migrate.c:2078
Inline: False
Direct callers:
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81497350-ffffffff8149760f: add_page_for_migration (STB_LOCAL)
```
</details>
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
In mm/migrate.c (ffff80001035217c)
Location: mm/migrate.c:1525
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0000000004389b4)
Location: mm/migrate.c:1525
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812aa013)
Location: mm/migrate.c:1525
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129b973)
Location: mm/migrate.c:1525
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a7e23)
Location: mm/migrate.c:1525
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b8123)
Location: mm/migrate.c:1525
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *p</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
