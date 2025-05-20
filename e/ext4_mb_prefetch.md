# Function: <code>ext4_mb_prefetch</code>

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
ext4_group_t ext4_mb_prefetch(struct super_block *sb, ext4_group_t group, unsigned int nr, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141bf80)
Location: fs/ext4/mballoc.c:2201
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff8141bf80-ffffffff8141c117: ext4_mb_prefetch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ext4_group_t ext4_mb_prefetch(struct super_block *sb, ext4_group_t group, unsigned int nr, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814221f0)
Location: fs/ext4/mballoc.c:2540
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff814221f0-ffffffff81422397: ext4_mb_prefetch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ext4_group_t ext4_mb_prefetch(struct super_block *sb, ext4_group_t group, unsigned int nr, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2558
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff81ccc10e-ffffffff81ccc134: ext4_mb_prefetch.cold (STB_LOCAL)
ffffffff81475920-ffffffff81475ad8: ext4_mb_prefetch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ext4_group_t ext4_mb_prefetch(struct super_block *sb, ext4_group_t group, unsigned int nr, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2555
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff81e7f0f5-ffffffff81e7f11f: ext4_mb_prefetch.cold (STB_LOCAL)
ffffffff814f7bd0-ffffffff814f7dc0: ext4_mb_prefetch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ext4_group_t ext4_mb_prefetch(struct super_block *sb, ext4_group_t group, unsigned int nr, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2518
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff8206f60c-ffffffff8206f636: ext4_mb_prefetch.cold (STB_LOCAL)
ffffffff81592190-ffffffff81592383: ext4_mb_prefetch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ext4_group_t ext4_mb_prefetch(struct super_block *sb, ext4_group_t group, unsigned int nr, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c92d0)
Location: fs/ext4/mballoc.c:2690
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff815c92d0-ffffffff815c940f: ext4_mb_prefetch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ext4_group_t ext4_mb_prefetch(struct super_block *sb, ext4_group_t group, unsigned int nr, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff816020b0)
Location: fs/ext4/mballoc.c:2714
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff816020b0-ffffffff816021ef: ext4_mb_prefetch (STB_GLOBAL)
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
