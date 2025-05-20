# Function: <code>reserve_backup_gdb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int reserve_backup_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff812bf480)
Location: fs/ext4/resize.c:932
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff812bf480-ffffffff812bf835: reserve_backup_gdb (STB_LOCAL)
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
In fs/ext4/resize.c (ffffffff812efa23)
Location: fs/ext4/resize.c:932
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
In fs/ext4/resize.c (ffffffff813059f3)
Location: fs/ext4/resize.c:932
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
In fs/ext4/resize.c (ffffffff8131fc26)
Location: fs/ext4/resize.c:933
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff813442c6)
Location: fs/ext4/resize.c:957
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff81372302)
Location: fs/ext4/resize.c:960
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff8138a9cf)
Location: fs/ext4/resize.c:956
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff813b5c76)
Location: fs/ext4/resize.c:964
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff813cee39)
Location: fs/ext4/resize.c:995
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int reserve_backup_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8141afc0)
Location: fs/ext4/resize.c:975
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff8141afc0-ffffffff8141b39b: reserve_backup_gdb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int reserve_backup_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff8142f460)
Location: fs/ext4/resize.c:980
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_add_new_descs
```
**Symbols:**

```
ffffffff8142f460-ffffffff8142f83b: reserve_backup_gdb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int reserve_backup_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/resize.c (ffffffff81434ea0)
Location: fs/ext4/resize.c:980
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81434ea0-ffffffff8143527b: reserve_backup_gdb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int reserve_backup_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:989
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81488940-ffffffff81488d2d: reserve_backup_gdb (STB_LOCAL)
ffffffff81ccd15a-ffffffff81ccd177: reserve_backup_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int reserve_backup_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1011
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff8150dfd0-ffffffff8150e404: reserve_backup_gdb (STB_LOCAL)
ffffffff81e8033d-ffffffff81e80362: reserve_backup_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int reserve_backup_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1014
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff815a8e30-ffffffff815a9263: reserve_backup_gdb (STB_LOCAL)
ffffffff82070781-ffffffff820707a6: reserve_backup_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int reserve_backup_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1014
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff815df690-ffffffff815dfac4: reserve_backup_gdb (STB_LOCAL)
ffffffff820f0440-ffffffff820f0465: reserve_backup_gdb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int reserve_backup_gdb(handle_t *handle, struct inode *inode, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/resize.c (0)
Location: fs/ext4/resize.c:1017
Inline: False
Direct callers:
  - fs/ext4/resize.c:ext4_flex_group_add
```
**Symbols:**

```
ffffffff81618170-ffffffff8161859e: reserve_backup_gdb (STB_LOCAL)
ffffffff821cd613-ffffffff821cd638: reserve_backup_gdb.cold (STB_LOCAL)
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
In fs/ext4/resize.c (ffff8000104a7758)
Location: fs/ext4/resize.c:995
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (c066990c)
Location: fs/ext4/resize.c:995
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (c0000000005d545c)
Location: fs/ext4/resize.c:995
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
In fs/ext4/resize.c (ffffffe00032803c)
Location: fs/ext4/resize.c:995
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
In fs/ext4/resize.c (ffffffff813c7419)
Location: fs/ext4/resize.c:995
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff813b7e99)
Location: fs/ext4/resize.c:995
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff813c48a9)
Location: fs/ext4/resize.c:995
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
In fs/ext4/resize.c (ffffffff813d9a9b)
Location: fs/ext4/resize.c:995
Inline: True
Inline callers:
  - fs/ext4/resize.c:ext4_add_new_descs
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
