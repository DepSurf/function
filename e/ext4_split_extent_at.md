# Function: <code>ext4_split_extent_at</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c6000)
Location: fs/ext4/extents.c:3158
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
```
**Symbols:**

```
ffffffff812c6000-ffffffff812c63f3: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f5840)
Location: fs/ext4/extents.c:3172
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff812f5840-ffffffff812f5c44: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130b7f0)
Location: fs/ext4/extents.c:3172
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8130b7f0-ffffffff8130bbf4: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e9ee0)
Location: fs/ext4/extents.c:3173
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff812e9ee0-ffffffff812ea321: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130e980)
Location: fs/ext4/extents.c:3173
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8130e980-ffffffff8130edc1: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133d150)
Location: fs/ext4/extents.c:3167
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8133d150-ffffffff8133d582: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81354800)
Location: fs/ext4/extents.c:3229
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81354800-ffffffff81354c32: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137e020)
Location: fs/ext4/extents.c:3249
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8137e020-ffffffff8137e519: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81396740)
Location: fs/ext4/extents.c:3295
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81396740-ffffffff81396c39: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e1d80)
Location: fs/ext4/extents.c:3132
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813e1d80-ffffffff813e22b2: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f35e0)
Location: fs/ext4/extents.c:3131
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813f35e0-ffffffff813f3b12: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f99d0)
Location: fs/ext4/extents.c:3134
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813f99d0-ffffffff813f9e97: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8144be60)
Location: fs/ext4/extents.c:3172
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8144be60-ffffffff8144c2db: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c8750)
Location: fs/ext4/extents.c:3171
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff814c8750-ffffffff814c8c43: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81560d90)
Location: fs/ext4/extents.c:3176
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81560d90-ffffffff8156127a: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81598b60)
Location: fs/ext4/extents.c:3176
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff81598b60-ffffffff81599004: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d19a0)
Location: fs/ext4/extents.c:3152
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_ext_replay_update_ex
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff815d19a0-ffffffff815d1e44: ext4_split_extent_at (STB_LOCAL)
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
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010469558)
Location: fs/ext4/extents.c:3295
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffff800010469558-ffff800010469934: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062a2ac)
Location: fs/ext4/extents.c:3295
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_split_extent
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
c062a2ac-c062a6d0: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0000000005881e0)
Location: fs/ext4/extents.c:3295
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
c0000000005881e0-c000000000588724: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f6ea2)
Location: fs/ext4/extents.c:3295
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffe0002f6ea2-ffffffe0002f7294: ext4_split_extent_at (STB_LOCAL)
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
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138ed20)
Location: fs/ext4/extents.c:3295
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8138ed20-ffffffff8138f219: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137f7b0)
Location: fs/ext4/extents.c:3295
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8137f7b0-ffffffff8137fca9: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138c680)
Location: fs/ext4/extents.c:3295
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff8138c680-ffffffff8138cb79: ext4_split_extent_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_split_extent_at(handle_t *handle, struct inode *inode, struct ext4_ext_path **ppath, ext4_lblk_t split, int split_flag, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a03d0)
Location: fs/ext4/extents.c:3295
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_swap_extents
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_ext_remove_space
```
**Symbols:**

```
ffffffff813a03d0-ffffffff813a08c9: ext4_split_extent_at (STB_LOCAL)
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
