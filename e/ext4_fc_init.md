# Function: <code>ext4_fc_init</code>

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
void ext4_fc_init(struct super_block *sb, journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814574e0)
Location: fs/ext4/fast_commit.c:2128
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
**Symbols:**

```
ffffffff814574e0-ffffffff8145750e: ext4_fc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_fc_init(struct super_block *sb, journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145ce70)
Location: fs/ext4/fast_commit.c:2133
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
**Symbols:**

```
ffffffff8145ce70-ffffffff8145ce9e: ext4_fc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_fc_init(struct super_block *sb, journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814b0ee0)
Location: fs/ext4/fast_commit.c:2116
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
**Symbols:**

```
ffffffff814b0ee0-ffffffff814b0f0e: ext4_fc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fc_init(struct super_block *sb, journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81539970)
Location: fs/ext4/fast_commit.c:2200
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
**Symbols:**

```
ffffffff81539970-ffffffff815399a8: ext4_fc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fc_init(struct super_block *sb, journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d7e70)
Location: fs/ext4/fast_commit.c:2242
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
**Symbols:**

```
ffffffff815d7e70-ffffffff815d7ea8: ext4_fc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fc_init(struct super_block *sb, journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160fa00)
Location: fs/ext4/fast_commit.c:2242
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
**Symbols:**

```
ffffffff8160fa00-ffffffff8160fa38: ext4_fc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_fc_init(struct super_block *sb, journal_t *journal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff816487c0)
Location: fs/ext4/fast_commit.c:2242
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_journal_params
```
**Symbols:**

```
ffffffff816487c0-ffffffff816487f8: ext4_fc_init (STB_GLOBAL)
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
