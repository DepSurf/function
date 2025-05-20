# Function: <code>mext_check_arguments</code>

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
In fs/ext4/move_extent.c (ffffffff812d746a)
Location: fs/ext4/move_extent.c:456
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff813071b8)
Location: fs/ext4/move_extent.c:457
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff8131d192)
Location: fs/ext4/move_extent.c:457
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff81315c48)
Location: fs/ext4/move_extent.c:457
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff8133a4ae)
Location: fs/ext4/move_extent.c:457
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff81368a52)
Location: fs/ext4/move_extent.c:449
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff81380ee3)
Location: fs/ext4/move_extent.c:447
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff813aa202)
Location: fs/ext4/move_extent.c:448
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff813c3132)
Location: fs/ext4/move_extent.c:448
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mext_check_arguments(struct inode *orig_inode, struct inode *donor_inode, __u64 orig_start, __u64 donor_start, __u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff8140e6b0)
Location: fs/ext4/move_extent.c:448
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff8140e6b0-ffffffff8140e856: mext_check_arguments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mext_check_arguments(struct inode *orig_inode, struct inode *donor_inode, __u64 orig_start, __u64 donor_start, __u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff81421b60)
Location: fs/ext4/move_extent.c:448
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff81421b60-ffffffff81421d06: mext_check_arguments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mext_check_arguments(struct inode *orig_inode, struct inode *donor_inode, __u64 orig_start, __u64 donor_start, __u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/move_extent.c (ffffffff81428360)
Location: fs/ext4/move_extent.c:448
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff81428360-ffffffff81428509: mext_check_arguments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mext_check_arguments(struct inode *orig_inode, struct inode *donor_inode, __u64 orig_start, __u64 donor_start, __u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/move_extent.c:448
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff8147c010-ffffffff8147c1fa: mext_check_arguments (STB_LOCAL)
ffffffff81ccc865-ffffffff81ccc974: mext_check_arguments.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mext_check_arguments(struct inode *orig_inode, struct inode *donor_inode, __u64 orig_start, __u64 donor_start, __u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/move_extent.c:453
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff814fe550-ffffffff814fe75a: mext_check_arguments (STB_LOCAL)
ffffffff81e7f74c-ffffffff81e7f863: mext_check_arguments.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mext_check_arguments(struct inode *orig_inode, struct inode *donor_inode, __u64 orig_start, __u64 donor_start, __u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/move_extent.c:460
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff81598d90-ffffffff81598f9a: mext_check_arguments (STB_LOCAL)
ffffffff8206fc3e-ffffffff8206fd55: mext_check_arguments.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mext_check_arguments(struct inode *orig_inode, struct inode *donor_inode, __u64 orig_start, __u64 donor_start, __u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/move_extent.c:461
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff815cf870-ffffffff815cfa74: mext_check_arguments (STB_LOCAL)
ffffffff820ef7fe-ffffffff820ef8f3: mext_check_arguments.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mext_check_arguments(struct inode *orig_inode, struct inode *donor_inode, __u64 orig_start, __u64 donor_start, __u64 *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/move_extent.c (0)
Location: fs/ext4/move_extent.c:453
Inline: False
Direct callers:
  - fs/ext4/move_extent.c:ext4_move_extents
```
**Symbols:**

```
ffffffff81608100-ffffffff81608304: mext_check_arguments (STB_LOCAL)
ffffffff821cc8e5-ffffffff821cc9da: mext_check_arguments.cold (STB_LOCAL)
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
In fs/ext4/move_extent.c (ffff80001049a9e0)
Location: fs/ext4/move_extent.c:448
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (c065c370)
Location: fs/ext4/move_extent.c:448
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (c0000000005c52b4)
Location: fs/ext4/move_extent.c:448
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffe00031e12c)
Location: fs/ext4/move_extent.c:448
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff813bb712)
Location: fs/ext4/move_extent.c:448
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff813ac1a2)
Location: fs/ext4/move_extent.c:448
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff813b8f72)
Location: fs/ext4/move_extent.c:448
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
In fs/ext4/move_extent.c (ffffffff813cdc92)
Location: fs/ext4/move_extent.c:448
Inline: True
Inline callers:
  - fs/ext4/move_extent.c:ext4_move_extents
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
