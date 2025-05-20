# Function: <code>ext4_mb_good_group_nolock</code>

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
int ext4_mb_good_group_nolock(struct ext4_allocation_context *ac, ext4_group_t group, int cr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81405930)
Location: fs/ext4/mballoc.c:2175
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
**Symbols:**

```
ffffffff81405930-ffffffff81405bfc: ext4_mb_good_group_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context *ac, ext4_group_t group, int cr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81418ba0)
Location: fs/ext4/mballoc.c:2141
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
**Symbols:**

```
ffffffff81418ba0-ffffffff81418e77: ext4_mb_good_group_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context *ac, ext4_group_t group, int cr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141f460)
Location: fs/ext4/mballoc.c:2478
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
**Symbols:**

```
ffffffff8141f460-ffffffff8141f725: ext4_mb_good_group_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context *ac, ext4_group_t group, int cr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2488
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
**Symbols:**

```
ffffffff81472b80-ffffffff81472e2a: ext4_mb_good_group_nolock (STB_LOCAL)
ffffffff81ccbcc0-ffffffff81ccbd0f: ext4_mb_good_group_nolock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context *ac, ext4_group_t group, int cr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2485
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
**Symbols:**

```
ffffffff814f3c80-ffffffff814f404e: ext4_mb_good_group_nolock (STB_LOCAL)
ffffffff81e7ec8b-ffffffff81e7ecd2: ext4_mb_good_group_nolock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context *ac, ext4_group_t group, int cr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2448
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
**Symbols:**

```
ffffffff8158e260-ffffffff8158e55d: ext4_mb_good_group_nolock (STB_LOCAL)
ffffffff8206f135-ffffffff8206f184: ext4_mb_good_group_nolock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context *ac, ext4_group_t group, enum criteria cr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2617
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
**Symbols:**

```
ffffffff815c4bf0-ffffffff815c4f91: ext4_mb_good_group_nolock (STB_LOCAL)
ffffffff820eee65-ffffffff820eee8b: ext4_mb_good_group_nolock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_mb_good_group_nolock(struct ext4_allocation_context *ac, ext4_group_t group, enum criteria cr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2636
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_regular_allocator
```
**Symbols:**

```
ffffffff815fce70-ffffffff815fd211: ext4_mb_good_group_nolock (STB_LOCAL)
ffffffff821cbf1d-ffffffff821cbf43: ext4_mb_good_group_nolock.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int cr</code> ➡️ <code>enum criteria cr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
