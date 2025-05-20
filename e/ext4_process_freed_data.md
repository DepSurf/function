# Function: <code>ext4_process_freed_data</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813101d0)
Location: fs/ext4/mballoc.c:2861
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff813101d0-ffffffff81310643: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813350b0)
Location: fs/ext4/mballoc.c:2861
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff813350b0-ffffffff8133557a: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81363360)
Location: fs/ext4/mballoc.c:2830
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff81363360-ffffffff81363797: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137b570)
Location: fs/ext4/mballoc.c:2830
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff8137b570-ffffffff8137ba39: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a5690)
Location: fs/ext4/mballoc.c:2832
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff813a5690-ffffffff813a5b2b: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813be510)
Location: fs/ext4/mballoc.c:2850
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff813be510-ffffffff813be9ab: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8140a520)
Location: fs/ext4/mballoc.c:2974
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff8140a520-ffffffff8140a7c7: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141d4c0)
Location: fs/ext4/mballoc.c:3078
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff8141d4c0-ffffffff8141d73a: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81423c30)
Location: fs/ext4/mballoc.c:3610
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff81423c30-ffffffff81423eaa: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81477640)
Location: fs/ext4/mballoc.c:3691
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff81477640-ffffffff81477ae0: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814f9990)
Location: fs/ext4/mballoc.c:3688
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff814f9990-ffffffff814f9f4a: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815941b0)
Location: fs/ext4/mballoc.c:3658
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff815941b0-ffffffff81594754: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815cb180)
Location: fs/ext4/mballoc.c:3879
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff815cb180-ffffffff815cb73a: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81603fa0)
Location: fs/ext4/mballoc.c:3903
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff81603fa0-ffffffff816044b7: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff8000104950a0)
Location: fs/ext4/mballoc.c:2850
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffff8000104950a0-ffff800010495670: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0656bac)
Location: fs/ext4/mballoc.c:2850
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
c0656bac-c0657158: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005be8d0)
Location: fs/ext4/mballoc.c:2850
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
c0000000005be8d0-c0000000005bef80: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe000319d4c)
Location: fs/ext4/mballoc.c:2850
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffe000319d4c-ffffffe00031a18a: ext4_process_freed_data (STB_GLOBAL)
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
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b6af0)
Location: fs/ext4/mballoc.c:2850
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff813b6af0-ffffffff813b6f8b: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a7580)
Location: fs/ext4/mballoc.c:2850
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff813a7580-ffffffff813a7a1b: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b4350)
Location: fs/ext4/mballoc.c:2850
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff813b4350-ffffffff813b47eb: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_process_freed_data(struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c8f60)
Location: fs/ext4/mballoc.c:2850
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_journal_commit_callback
```
**Symbols:**

```
ffffffff813c8f60-ffffffff813c940d: ext4_process_freed_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
