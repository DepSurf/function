# Function: <code>ext4_xattr_shift_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_shift_entries(struct ext4_xattr_entry *entry, int value_offs_shift, void *to, void *from, size_t n, int blocksize);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812dcc90)
Location: fs/ext4/xattr.c:1230
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff812dcc90-ffffffff812dcced: ext4_xattr_shift_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_xattr_shift_entries(struct ext4_xattr_entry *entry, int value_offs_shift, void *to, void *from, size_t n, int blocksize);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130c6f0)
Location: fs/ext4/xattr.c:1319
Inline: True
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff8130c6f0-ffffffff8130c74d: ext4_xattr_shift_entries (STB_LOCAL)
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
In fs/ext4/xattr.c (ffffffff81324985)
Location: fs/ext4/xattr.c:1320
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff8133e62c)
Location: fs/ext4/xattr.c:2469
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff81362c0c)
Location: fs/ext4/xattr.c:2505
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff81391430)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff813aa026)
Location: fs/ext4/xattr.c:2520
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff813d435a)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff813eda3a)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8143ab6a)
Location: fs/ext4/xattr.c:2508
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814536da)
Location: fs/ext4/xattr.c:2515
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81458e17)
Location: fs/ext4/xattr.c:2515
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814acf27)
Location: fs/ext4/xattr.c:2498
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81534f4c)
Location: fs/ext4/xattr.c:2513
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_xattr_shift_entries(struct ext4_xattr_entry *entry, int value_offs_shift, void *to, void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815ce290)
Location: fs/ext4/xattr.c:2533
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff815ce290-ffffffff815ce303: ext4_xattr_shift_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_xattr_shift_entries(struct ext4_xattr_entry *entry, int value_offs_shift, void *to, void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81605b60)
Location: fs/ext4/xattr.c:2576
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff81605b60-ffffffff81605bd3: ext4_xattr_shift_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_xattr_shift_entries(struct ext4_xattr_entry *entry, int value_offs_shift, void *to, void *from, size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8163e870)
Location: fs/ext4/xattr.c:2576
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
```
**Symbols:**

```
ffffffff8163e870-ffffffff8163e8e3: ext4_xattr_shift_entries (STB_LOCAL)
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
In fs/ext4/xattr.c (ffff8000104c68c8)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (c068a8f4)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (c0000000005fed8c)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffe000340d16)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff813e601a)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff813d6a9a)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff813e339a)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
In fs/ext4/xattr.c (ffffffff813f87aa)
Location: fs/ext4/xattr.c:2521
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_extra_isize_ea
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
