# Function: <code>ext4_fc_cleanup</code>

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
void ext4_fc_cleanup(journal_t *journal, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81455bb0)
Location: fs/ext4/fast_commit.c:1230
Inline: False
```
**Symbols:**

```
ffffffff81455bb0-ffffffff81455dec: ext4_fc_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_fc_cleanup(journal_t *journal, int full);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8145b7b0)
Location: fs/ext4/fast_commit.c:1226
Inline: False
```
**Symbols:**

```
ffffffff8145b7b0-ffffffff8145ba1e: ext4_fc_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_fc_cleanup(journal_t *journal, int full, tid_t tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814af070)
Location: fs/ext4/fast_commit.c:1198
Inline: False
```
**Symbols:**

```
ffffffff814af070-ffffffff814af2fd: ext4_fc_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fc_cleanup(journal_t *journal, int full, tid_t tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81536110)
Location: fs/ext4/fast_commit.c:1276
Inline: False
```
**Symbols:**

```
ffffffff81536110-ffffffff8153643a: ext4_fc_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fc_cleanup(journal_t *journal, int full, tid_t tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d4610)
Location: fs/ext4/fast_commit.c:1266
Inline: False
```
**Symbols:**

```
ffffffff815d4610-ffffffff815d493a: ext4_fc_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fc_cleanup(journal_t *journal, int full, tid_t tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160c200)
Location: fs/ext4/fast_commit.c:1266
Inline: False
```
**Symbols:**

```
ffffffff8160c200-ffffffff8160c52a: ext4_fc_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_fc_cleanup(journal_t *journal, int full, tid_t tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81644fc0)
Location: fs/ext4/fast_commit.c:1266
Inline: False
```
**Symbols:**

```
ffffffff81644fc0-ffffffff816452ea: ext4_fc_cleanup (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>tid_t tid</code>
</li>
</ul>
</details>
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
