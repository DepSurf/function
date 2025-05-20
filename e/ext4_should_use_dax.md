# Function: <code>ext4_should_use_dax</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8132602c)
Location: fs/ext4/inode.c:4636
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
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
In fs/ext4/inode.c (ffffffff813543dc)
Location: fs/ext4/inode.c:4685
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
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
In fs/ext4/inode.c (ffffffff8136c64c)
Location: fs/ext4/inode.c:4715
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
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
In fs/ext4/inode.c (ffffffff81395c03)
Location: fs/ext4/inode.c:4727
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
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
In fs/ext4/inode.c (ffffffff813ae5d3)
Location: fs/ext4/inode.c:4716
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/ext4/inode.c (ffff80001048317c)
Location: fs/ext4/inode.c:4716
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
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
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:4716
Inline: True
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
In fs/ext4/inode.c (c0000000005a7f48)
Location: fs/ext4/inode.c:4716
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
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
In fs/ext4/inode.c (ffffffe00030b87a)
Location: fs/ext4/inode.c:4716
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
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
In fs/ext4/inode.c (ffffffff813a6bb3)
Location: fs/ext4/inode.c:4716
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
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
In fs/ext4/inode.c (ffffffff81397643)
Location: fs/ext4/inode.c:4716
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
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
In fs/ext4/inode.c (ffffffff813a4413)
Location: fs/ext4/inode.c:4716
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
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
In fs/ext4/inode.c (ffffffff813b8b13)
Location: fs/ext4/inode.c:4716
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_set_inode_flags
```
</details>
</li>
</ul>

## Differences
