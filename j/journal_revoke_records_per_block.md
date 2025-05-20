# Function: <code>journal_revoke_records_per_block</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int journal_revoke_records_per_block(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81446180)
Location: fs/jbd2/journal.c:1513
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff81446180-ffffffff814461e7: journal_revoke_records_per_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int journal_revoke_records_per_block(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81462490)
Location: fs/jbd2/journal.c:1713
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff81462490-ffffffff814624f7: journal_revoke_records_per_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int journal_revoke_records_per_block(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81467b40)
Location: fs/jbd2/journal.c:1713
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff81467b40-ffffffff81467ba7: journal_revoke_records_per_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int journal_revoke_records_per_block(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bdb80)
Location: fs/jbd2/journal.c:1869
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff814bdb80-ffffffff814bdbe7: journal_revoke_records_per_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int journal_revoke_records_per_block(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81549300)
Location: fs/jbd2/journal.c:1872
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff81549300-ffffffff81549396: journal_revoke_records_per_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int journal_revoke_records_per_block(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e8d20)
Location: fs/jbd2/journal.c:1878
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
```
**Symbols:**

```
ffffffff815e8d20-ffffffff815e8db6: journal_revoke_records_per_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int journal_revoke_records_per_block(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81620a10)
Location: fs/jbd2/journal.c:1892
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:jbd2_journal_set_features
```
**Symbols:**

```
ffffffff81620a10-ffffffff81620aa9: journal_revoke_records_per_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int journal_revoke_records_per_block(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81659650)
Location: fs/jbd2/journal.c:1439
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_clear_features
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_load_superblock
```
**Symbols:**

```
ffffffff81659650-ffffffff816596e9: journal_revoke_records_per_block (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
