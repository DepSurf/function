# Function: <code>kernfs_fill_super</code>

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
In fs/kernfs/mount.c (ffffffff812887cd)
Location: fs/kernfs/mount.c:134
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
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
In fs/kernfs/mount.c (ffffffff812b5c84)
Location: fs/kernfs/mount.c:148
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
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
In fs/kernfs/mount.c (ffffffff812cb514)
Location: fs/kernfs/mount.c:148
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
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
In fs/kernfs/mount.c (ffffffff812d895d)
Location: fs/kernfs/mount.c:148
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
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
In fs/kernfs/mount.c (ffffffff812fd1dd)
Location: fs/kernfs/mount.c:221
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
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
In fs/kernfs/mount.c (ffffffff8132ae15)
Location: fs/kernfs/mount.c:221
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
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
In fs/kernfs/mount.c (ffffffff81342175)
Location: fs/kernfs/mount.c:225
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
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
In fs/kernfs/mount.c (ffffffff8136a527)
Location: fs/kernfs/mount.c:213
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff81382707)
Location: fs/kernfs/mount.c:213
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff813ccc00)
Location: fs/kernfs/mount.c:236
Inline: True
Direct callers:
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffffffff813ccc00-ffffffff813ccd0e: kernfs_fill_super.constprop.0 (STB_LOCAL)
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
In fs/kernfs/mount.c (ffffffff813de850)
Location: fs/kernfs/mount.c:236
Inline: True
Direct callers:
  - fs/kernfs/mount.c:kernfs_get_tree
```
**Symbols:**

```
ffffffff813de850-ffffffff813de95e: kernfs_fill_super.constprop.0 (STB_LOCAL)
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
In fs/kernfs/mount.c (ffffffff813e579a)
Location: fs/kernfs/mount.c:236
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff8143736a)
Location: fs/kernfs/mount.c:236
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff814b1feb)
Location: fs/kernfs/mount.c:236
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff81548b3b)
Location: fs/kernfs/mount.c:239
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff815806f3)
Location: fs/kernfs/mount.c:239
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff815b9174)
Location: fs/kernfs/mount.c:246
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffff800010450bc4)
Location: fs/kernfs/mount.c:213
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (c0613b7c)
Location: fs/kernfs/mount.c:213
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (c000000000568f28)
Location: fs/kernfs/mount.c:213
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffe0002e3ae6)
Location: fs/kernfs/mount.c:213
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff8137ace7)
Location: fs/kernfs/mount.c:213
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff8136b7b7)
Location: fs/kernfs/mount.c:213
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff813787b7)
Location: fs/kernfs/mount.c:213
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
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
In fs/kernfs/mount.c (ffffffff8138c267)
Location: fs/kernfs/mount.c:213
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
```
</details>
</li>
</ul>

## Differences
