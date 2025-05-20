# Function: <code>ext4_mb_prefetch_fini</code>

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
void ext4_mb_prefetch_fini(struct super_block *sb, ext4_group_t group, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141c120)
Location: fs/ext4/mballoc.c:2252
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff8141c120-ffffffff8141c24c: ext4_mb_prefetch_fini (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_mb_prefetch_fini(struct super_block *sb, ext4_group_t group, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814223a0)
Location: fs/ext4/mballoc.c:2591
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff814223a0-ffffffff814224cc: ext4_mb_prefetch_fini (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_mb_prefetch_fini(struct super_block *sb, ext4_group_t group, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2609
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff81ccc134-ffffffff81ccc172: ext4_mb_prefetch_fini.cold (STB_LOCAL)
ffffffff81475ae0-ffffffff81475c25: ext4_mb_prefetch_fini (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_mb_prefetch_fini(struct super_block *sb, ext4_group_t group, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2606
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff81e7f11f-ffffffff81e7f162: ext4_mb_prefetch_fini.cold (STB_LOCAL)
ffffffff814f7dc0-ffffffff814f7f2f: ext4_mb_prefetch_fini (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ext4_mb_prefetch_fini(struct super_block *sb, ext4_group_t group, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2569
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff8206f636-ffffffff8206f679: ext4_mb_prefetch_fini.cold (STB_LOCAL)
ffffffff815923a0-ffffffff8159250f: ext4_mb_prefetch_fini (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_mb_prefetch_fini(struct super_block *sb, ext4_group_t group, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c9420)
Location: fs/ext4/mballoc.c:2739
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff815c9420-ffffffff815c94c8: ext4_mb_prefetch_fini (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_mb_prefetch_fini(struct super_block *sb, ext4_group_t group, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81602200)
Location: fs/ext4/mballoc.c:2763
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
  - fs/ext4/super.c:ext4_run_li_request
```
**Symbols:**

```
ffffffff81602200-ffffffff816022a8: ext4_mb_prefetch_fini (STB_GLOBAL)
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
