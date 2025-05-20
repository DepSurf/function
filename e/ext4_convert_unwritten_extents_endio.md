# Function: <code>ext4_convert_unwritten_extents_endio</code>

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
In fs/ext4/extents.c (ffffffff812c7c79)
Location: fs/ext4/extents.c:3703
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff812f7889)
Location: fs/ext4/extents.c:3717
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/extents.c (ffffffff8130d8a7)
Location: fs/ext4/extents.c:3717
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
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
In fs/ext4/extents.c (ffffffff812eba74)
Location: fs/ext4/extents.c:3712
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff81310534)
Location: fs/ext4/extents.c:3712
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff8133e3d4)
Location: fs/ext4/extents.c:3706
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff81354f34)
Location: fs/ext4/extents.c:3768
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff8137f086)
Location: fs/ext4/extents.c:3788
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff813977a6)
Location: fs/ext4/extents.c:3834
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents_endio(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e2740)
Location: fs/ext4/extents.c:3669
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff813e2740-ffffffff813e2885: ext4_convert_unwritten_extents_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_convert_unwritten_extents_endio(handle_t *handle, struct inode *inode, struct ext4_map_blocks *map, struct ext4_ext_path **ppath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f3fa0)
Location: fs/ext4/extents.c:3668
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff813f3fa0-ffffffff813f40e5: ext4_convert_unwritten_extents_endio (STB_LOCAL)
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
In fs/ext4/extents.c (ffffffff813faba3)
Location: fs/ext4/extents.c:3674
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff8144cf93)
Location: fs/ext4/extents.c:3713
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff814c99fa)
Location: fs/ext4/extents.c:3711
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8156207a)
Location: fs/ext4/extents.c:3716
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81599dea)
Location: fs/ext4/extents.c:3715
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d2c3a)
Location: fs/ext4/extents.c:3691
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffff80001046a3a0)
Location: fs/ext4/extents.c:3834
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (c062b1f8)
Location: fs/ext4/extents.c:3834
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (c000000000589350)
Location: fs/ext4/extents.c:3834
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffe0002f7c88)
Location: fs/ext4/extents.c:3834
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff8138fd86)
Location: fs/ext4/extents.c:3834
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff81380816)
Location: fs/ext4/extents.c:3834
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff8138d6e6)
Location: fs/ext4/extents.c:3834
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
In fs/ext4/extents.c (ffffffff813a1476)
Location: fs/ext4/extents.c:3834
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
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
</ul>
