# Function: <code>ext4_update_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812c0ae1)
Location: fs/ext4/resize.c:1305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812f03be)
Location: fs/ext4/resize.c:1305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8130638e)
Location: fs/ext4/resize.c:1305
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81320d2a)
Location: fs/ext4/resize.c:1306
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8134545a)
Location: fs/ext4/resize.c:1332
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8137350e)
Location: fs/ext4/resize.c:1335
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8138b902)
Location: fs/ext4/resize.c:1335
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b6543)
Location: fs/ext4/resize.c:1343
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813cf473)
Location: fs/ext4/resize.c:1375
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ext4_update_super(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1353
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81419130-ffffffff8141934c: ext4_update_super (STB_LOCAL)
ffffffff8141d09c-ffffffff8141d0ba: ext4_update_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
void ext4_update_super(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1358
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff81444780)
Location: fs/ext4/super.c:5484
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff8142d0f0-ffffffff8142d3e5: ext4_update_super (STB_LOCAL)
ffffffff81bec54d-ffffffff81bec56c: ext4_update_super.cold (STB_LOCAL)
ffffffff81444780-ffffffff81444b8f: ext4_update_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
void ext4_update_super(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1358
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (ffffffff8144a010)
Location: fs/ext4/super.c:5530
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff81433dc0-ffffffff814340aa: ext4_update_super (STB_LOCAL)
ffffffff81bde5ff-ffffffff81bde61e: ext4_update_super.cold (STB_LOCAL)
ffffffff8144a010-ffffffff8144a418: ext4_update_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
void ext4_update_super(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1368
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:5385
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff81487770-ffffffff81487ae8: ext4_update_super (STB_LOCAL)
ffffffff81cccfad-ffffffff81ccd097: ext4_update_super.cold (STB_LOCAL)
ffffffff8149e4c0-ffffffff8149e915: ext4_update_super (STB_LOCAL)
ffffffff81ccd6f2-ffffffff81ccd710: ext4_update_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
void ext4_update_super(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1390
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:5831
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff8150b030-ffffffff8150b3dc: ext4_update_super (STB_LOCAL)
ffffffff81e7feae-ffffffff81e7ffb1: ext4_update_super.cold (STB_LOCAL)
ffffffff81524bb0-ffffffff81525014: ext4_update_super (STB_LOCAL)
ffffffff81e80521-ffffffff81e8053f: ext4_update_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
void ext4_update_super(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1417
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:5983
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff815a5c20-ffffffff815a6067: ext4_update_super (STB_LOCAL)
ffffffff8207033b-ffffffff8207045f: ext4_update_super.cold (STB_LOCAL)
ffffffff815c2080-ffffffff815c24fe: ext4_update_super (STB_LOCAL)
ffffffff82070949-ffffffff82070967: ext4_update_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
void ext4_update_super(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1416
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:6070
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff815dc490-ffffffff815dc8d7: ext4_update_super (STB_LOCAL)
ffffffff820f0011-ffffffff820f0135: ext4_update_super.cold (STB_LOCAL)
ffffffff815f9800-ffffffff815f9c7e: ext4_update_super (STB_LOCAL)
ffffffff820f05d2-ffffffff820f05f0: ext4_update_super.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
void ext4_update_super(struct super_block *sb, struct ext4_new_flex_group_data *flex_gd);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1418
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:6098
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_commit_super
  - fs/ext4/super.c:update_super_work
```
**Symbols:**

```
ffffffff81614d70-ffffffff816151b7: ext4_update_super (STB_LOCAL)
ffffffff821cd1ce-ffffffff821cd2f2: ext4_update_super.cold (STB_LOCAL)
ffffffff81632400-ffffffff8163287e: ext4_update_super (STB_LOCAL)
ffffffff821cd7a5-ffffffff821cd7c3: ext4_update_super.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffff8000104a7da0)
Location: fs/ext4/resize.c:1375
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0669f5c)
Location: fs/ext4/resize.c:1375
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (c0000000005d56dc)
Location: fs/ext4/resize.c:1375
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffe000328356)
Location: fs/ext4/resize.c:1375
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c7a53)
Location: fs/ext4/resize.c:1375
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813b84d3)
Location: fs/ext4/resize.c:1375
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813c4ee3)
Location: fs/ext4/resize.c:1375
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff813da0d0)
Location: fs/ext4/resize.c:1375
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
