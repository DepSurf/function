# Function: <code>skip_hole</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void skip_hole(struct inode *inode, ext4_lblk_t *cur);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f7ed0)
Location: fs/ext4/extents.c:5904
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
```
**Symbols:**

```
ffffffff813eea30-ffffffff813eea9c: skip_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void skip_hole(struct inode *inode, ext4_lblk_t *cur);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fe34f)
Location: fs/ext4/extents.c:5910
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
```
**Symbols:**

```
ffffffff813f5000-ffffffff813f506c: skip_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int skip_hole(struct inode *inode, ext4_lblk_t *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:5941
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
```
**Symbols:**

```
ffffffff81447270-ffffffff814472f7: skip_hole (STB_LOCAL)
ffffffff81cc8ed2-ffffffff81cc8ef4: skip_hole.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int skip_hole(struct inode *inode, ext4_lblk_t *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:5954
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
```
**Symbols:**

```
ffffffff814c3770-ffffffff814c381b: skip_hole (STB_LOCAL)
ffffffff81e7bbf5-ffffffff81e7bc17: skip_hole.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int skip_hole(struct inode *inode, ext4_lblk_t *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:5964
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
```
**Symbols:**

```
ffffffff8155ba90-ffffffff8155bb3b: skip_hole (STB_LOCAL)
ffffffff8206c27a-ffffffff8206c29c: skip_hole.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int skip_hole(struct inode *inode, ext4_lblk_t *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:5935
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
```
**Symbols:**

```
ffffffff815938b0-ffffffff8159395b: skip_hole (STB_LOCAL)
ffffffff820ec10c-ffffffff820ec12e: skip_hole.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int skip_hole(struct inode *inode, ext4_lblk_t *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:5970
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
  - fs/ext4/extents.c:ext4_ext_replay_set_iblocks
```
**Symbols:**

```
ffffffff815cc5a0-ffffffff815cc64b: skip_hole (STB_LOCAL)
ffffffff821c9344-ffffffff821c9366: skip_hole.cold (STB_LOCAL)
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
