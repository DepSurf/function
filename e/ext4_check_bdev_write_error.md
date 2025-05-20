# Function: <code>ext4_check_bdev_write_error</code>

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
void ext4_check_bdev_write_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813dc270)
Location: fs/ext4/ext4_jbd2.c:198
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
**Symbols:**

```
ffffffff813dc270-ffffffff813dc30f: ext4_check_bdev_write_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_check_bdev_write_error(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813edd00)
Location: fs/ext4/ext4_jbd2.c:198
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
**Symbols:**

```
ffffffff813edd00-ffffffff813eddab: ext4_check_bdev_write_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813f47b5)
Location: fs/ext4/ext4_jbd2.c:198
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8144691c)
Location: fs/ext4/ext4_jbd2.c:200
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff814c2b9b)
Location: fs/ext4/ext4_jbd2.c:200
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8155aefb)
Location: fs/ext4/ext4_jbd2.c:206
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81592d1b)
Location: fs/ext4/ext4_jbd2.c:206
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff815cbaad)
Location: fs/ext4/ext4_jbd2.c:207
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_get_write_access
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
</ul>
