# Function: <code>jbd2_journal_invalidate_folio</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_invalidate_folio(journal_t *journal, struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:2450
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
```
**Symbols:**

```
ffffffff81e81670-ffffffff81e816bc: jbd2_journal_invalidate_folio.cold (STB_LOCAL)
ffffffff8153fd20-ffffffff8153ff46: jbd2_journal_invalidate_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_invalidate_folio(journal_t *journal, struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:2458
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
```
**Symbols:**

```
ffffffff8207134a-ffffffff82071396: jbd2_journal_invalidate_folio.cold (STB_LOCAL)
ffffffff815de8a0-ffffffff815dea29: jbd2_journal_invalidate_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_invalidate_folio(journal_t *journal, struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:2437
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
```
**Symbols:**

```
ffffffff820f100f-ffffffff820f105b: jbd2_journal_invalidate_folio.cold (STB_LOCAL)
ffffffff81616300-ffffffff81616489: jbd2_journal_invalidate_folio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int jbd2_journal_invalidate_folio(journal_t *journal, struct folio *folio, size_t offset, size_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:2447
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_journalled_invalidate_folio
```
**Symbols:**

```
ffffffff821ce1de-ffffffff821ce228: jbd2_journal_invalidate_folio.cold (STB_LOCAL)
ffffffff8164f120-ffffffff8164f2ad: jbd2_journal_invalidate_folio (STB_GLOBAL)
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
