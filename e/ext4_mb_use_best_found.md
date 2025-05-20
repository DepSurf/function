# Function: <code>ext4_mb_use_best_found</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812d1bf0)
Location: fs/ext4/mballoc.c:1632
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_check_limits
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
```
**Symbols:**

```
ffffffff812d1bf0-ffffffff812d1cf8: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813012b0)
Location: fs/ext4/mballoc.c:1641
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813012b0-ffffffff813013ca: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81317330)
Location: fs/ext4/mballoc.c:1641
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81317330-ffffffff8131744a: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8130e350)
Location: fs/ext4/mballoc.c:1649
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff8130e350-ffffffff8130e43d: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81333460)
Location: fs/ext4/mballoc.c:1649
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81333460-ffffffff8133354d: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813615f0)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813615f0-ffffffff813616d8: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813798a0)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813798a0-ffffffff81379988: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a33f0)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813a33f0-ffffffff813a34d8: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813bc250)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813bc250-ffffffff813bc338: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81407e70)
Location: fs/ext4/mballoc.c:1697
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81407e70-ffffffff81407fa1: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141a8c0)
Location: fs/ext4/mballoc.c:1667
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff8141a8c0-ffffffff8141a9f1: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81420d70)
Location: fs/ext4/mballoc.c:2004
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81420d70-ffffffff81420ea2: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81474a30)
Location: fs/ext4/mballoc.c:2008
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81474a30-ffffffff81474b62: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814f6a80)
Location: fs/ext4/mballoc.c:2005
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff814f6a80-ffffffff814f6c1b: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81591050)
Location: fs/ext4/mballoc.c:1968
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff81591050-ffffffff815911e7: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c7fc0)
Location: fs/ext4/mballoc.c:2108
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
**Symbols:**

```
ffffffff815c7fc0-ffffffff815c815a: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815fdf60)
Location: fs/ext4/mballoc.c:2124
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
```
**Symbols:**

```
ffffffff815fdf60-ffffffff815fe0f1: ext4_mb_use_best_found (STB_LOCAL)
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
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff800010492f40)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffff800010492f40-ffff8000104930c4: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0654258)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
c0654258-c065438c: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005bb6b0)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
c0000000005bb6b0-c0000000005bb870: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe000317ab4)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffe000317ab4-ffffffe000317be4: ext4_mb_use_best_found (STB_LOCAL)
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
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b4830)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813b4830-ffffffff813b4918: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a52c0)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813a52c0-ffffffff813a53a8: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b2090)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813b2090-ffffffff813b2178: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_mb_use_best_found(struct ext4_allocation_context *ac, struct ext4_buddy *e4b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c6bd0)
Location: fs/ext4/mballoc.c:1634
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_scan_aligned
  - fs/ext4/mballoc.c:ext4_mb_complex_scan_group
  - fs/ext4/mballoc.c:ext4_mb_simple_scan_group
  - fs/ext4/mballoc.c:ext4_mb_find_by_goal
  - fs/ext4/mballoc.c:ext4_mb_try_best_found
  - fs/ext4/mballoc.c:ext4_mb_check_limits
```
**Symbols:**

```
ffffffff813c6bd0-ffffffff813c6cb6: ext4_mb_use_best_found (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
