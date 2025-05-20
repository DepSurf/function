# Function: <code>ext4_free_data_revoke_credits</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e00cb)
Location: fs/ext4/ext4_jbd2.h:480
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/indirect.c (ffffffff813efadf)
Location: fs/ext4/ext4_jbd2.h:480
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f197f)
Location: fs/ext4/ext4_jbd2.h:472
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/indirect.c (ffffffff8140223f)
Location: fs/ext4/ext4_jbd2.h:472
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f7dff)
Location: fs/ext4/ext4_jbd2.h:472
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/indirect.c (ffffffff8140863f)
Location: fs/ext4/ext4_jbd2.h:472
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8144a2d7)
Location: fs/ext4/ext4_jbd2.h:478
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/indirect.c (ffffffff8145b09f)
Location: fs/ext4/ext4_jbd2.h:478
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c6a1e)
Location: fs/ext4/ext4_jbd2.h:478
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/indirect.c (ffffffff814d8e45)
Location: fs/ext4/ext4_jbd2.h:478
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155f01e)
Location: fs/ext4/ext4_jbd2.h:478
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/indirect.c (ffffffff81571c65)
Location: fs/ext4/ext4_jbd2.h:478
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81596de1)
Location: fs/ext4/ext4_jbd2.h:478
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/indirect.c (ffffffff815a99f5)
Location: fs/ext4/ext4_jbd2.h:478
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cfa91)
Location: fs/ext4/ext4_jbd2.h:478
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_rm_leaf
```
```
In fs/ext4/indirect.c (ffffffff815e2795)
Location: fs/ext4/ext4_jbd2.h:478
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
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
