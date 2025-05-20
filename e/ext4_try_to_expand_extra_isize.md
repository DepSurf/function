# Function: <code>ext4_try_to_expand_extra_isize</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813031a5)
Location: fs/ext4/inode.c:5747
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff81327b98)
Location: fs/ext4/inode.c:5800
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff813557f3)
Location: fs/ext4/inode.c:5896
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff8136db23)
Location: fs/ext4/inode.c:5949
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff81397145)
Location: fs/ext4/inode.c:5971
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff813afb75)
Location: fs/ext4/inode.c:6000
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f6400)
Location: fs/ext4/inode.c:5721
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
```
**Symbols:**

```
ffffffff813f6400-ffffffff813f650f: ext4_try_to_expand_extra_isize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81408d60)
Location: fs/ext4/inode.c:5814
Inline: True
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
```
**Symbols:**

```
ffffffff81408d60-ffffffff81408e6b: ext4_try_to_expand_extra_isize.isra.0 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff814144d2)
Location: fs/ext4/inode.c:5811
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff81467852)
Location: fs/ext4/inode.c:5751
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff814e74f6)
Location: fs/ext4/inode.c:5829
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff81580eb6)
Location: fs/ext4/inode.c:5973
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff815b8466)
Location: fs/ext4/inode.c:5785
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff815f1206)
Location: fs/ext4/inode.c:5805
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffff80001048464c)
Location: fs/ext4/inode.c:6000
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (c0645c20)
Location: fs/ext4/inode.c:6000
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (c0000000005a9930)
Location: fs/ext4/inode.c:6000
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffe00030ca34)
Location: fs/ext4/inode.c:6000
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff813a8155)
Location: fs/ext4/inode.c:6000
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff81398be5)
Location: fs/ext4/inode.c:6000
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff813a59b5)
Location: fs/ext4/inode.c:6000
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
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
In fs/ext4/inode.c (ffffffff813ba0f0)
Location: fs/ext4/inode.c:6000
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
```
</details>
</li>
</ul>

## Differences
