# Function: <code>jbd2_fc_get_buf</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_fc_get_buf(journal_t *journal, struct buffer_head **bh_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81464b00)
Location: fs/jbd2/journal.c:871
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff81464b00-ffffffff81464bcf: jbd2_fc_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_fc_get_buf(journal_t *journal, struct buffer_head **bh_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8146a290)
Location: fs/jbd2/journal.c:871
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff8146a290-ffffffff8146a35f: jbd2_fc_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_fc_get_buf(journal_t *journal, struct buffer_head **bh_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c0620)
Location: fs/jbd2/journal.c:871
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff814c0620-ffffffff814c06ef: jbd2_fc_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_fc_get_buf(journal_t *journal, struct buffer_head **bh_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154ae60)
Location: fs/jbd2/journal.c:873
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff8154ae60-ffffffff8154af43: jbd2_fc_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_fc_get_buf(journal_t *journal, struct buffer_head **bh_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815eaaa0)
Location: fs/jbd2/journal.c:870
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff815eaaa0-ffffffff815eab83: jbd2_fc_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_fc_get_buf(journal_t *journal, struct buffer_head **bh_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81622510)
Location: fs/jbd2/journal.c:869
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff81622510-ffffffff816225f3: jbd2_fc_get_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_fc_get_buf(journal_t *journal, struct buffer_head **bh_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165b560)
Location: fs/jbd2/journal.c:858
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
**Symbols:**

```
ffffffff8165b560-ffffffff8165b652: jbd2_fc_get_buf (STB_GLOBAL)
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
