# Function: <code>ext4_fc_replay</code>

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
int ext4_fc_replay(journal_t *journal, struct buffer_head *bh, enum passtype pass, int off, tid_t expected_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81455df0)
Location: fs/ext4/fast_commit.c:2039
Inline: False
```
**Symbols:**

```
ffffffff81455df0-ffffffff81456176: ext4_fc_replay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fc_replay(journal_t *journal, struct buffer_head *bh, enum passtype pass, int off, tid_t expected_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145b160)
Location: fs/ext4/fast_commit.c:2041
Inline: False
```
**Symbols:**

```
ffffffff8145b160-ffffffff8145b64c: ext4_fc_replay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fc_replay(journal_t *journal, struct buffer_head *bh, enum passtype pass, int off, tid_t expected_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814b0940)
Location: fs/ext4/fast_commit.c:2024
Inline: False
```
**Symbols:**

```
ffffffff814b0940-ffffffff814b0e2c: ext4_fc_replay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_fc_replay(journal_t *journal, struct buffer_head *bh, enum passtype pass, int off, tid_t expected_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81539280)
Location: fs/ext4/fast_commit.c:2108
Inline: False
```
**Symbols:**

```
ffffffff81539280-ffffffff815398b0: ext4_fc_replay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_fc_replay(journal_t *journal, struct buffer_head *bh, enum passtype pass, int off, tid_t expected_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d7610)
Location: fs/ext4/fast_commit.c:2150
Inline: False
```
**Symbols:**

```
ffffffff815d7610-ffffffff815d7d75: ext4_fc_replay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_fc_replay(journal_t *journal, struct buffer_head *bh, enum passtype pass, int off, tid_t expected_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160f220)
Location: fs/ext4/fast_commit.c:2150
Inline: False
```
**Symbols:**

```
ffffffff8160f220-ffffffff8160f908: ext4_fc_replay (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_fc_replay(journal_t *journal, struct buffer_head *bh, enum passtype pass, int off, tid_t expected_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81647fe0)
Location: fs/ext4/fast_commit.c:2150
Inline: False
```
**Symbols:**

```
ffffffff81647fe0-ffffffff816486c8: ext4_fc_replay (STB_LOCAL)
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
