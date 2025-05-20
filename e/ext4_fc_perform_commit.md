# Function: <code>ext4_fc_perform_commit</code>

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
int ext4_fc_perform_commit(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81456470)
Location: fs/ext4/fast_commit.c:1059
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81456470-ffffffff814566db: ext4_fc_perform_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fc_perform_commit(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145bbf0)
Location: fs/ext4/fast_commit.c:1055
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff8145bbf0-ffffffff8145c081: ext4_fc_perform_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fc_perform_commit(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814af300)
Location: fs/ext4/fast_commit.c:1019
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff814af300-ffffffff814af901: ext4_fc_perform_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_fc_perform_commit(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81536c90)
Location: fs/ext4/fast_commit.c:1094
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81536c90-ffffffff815372c3: ext4_fc_perform_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_fc_perform_commit(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d5130)
Location: fs/ext4/fast_commit.c:1084
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff815d5130-ffffffff815d5666: ext4_fc_perform_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_fc_perform_commit(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160ccf0)
Location: fs/ext4/fast_commit.c:1084
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff8160ccf0-ffffffff8160d226: ext4_fc_perform_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_fc_perform_commit(journal_t *journal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81645ab0)
Location: fs/ext4/fast_commit.c:1084
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81645ab0-ffffffff81645fe6: ext4_fc_perform_commit (STB_LOCAL)
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
