# Function: <code>mnt_free_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8122c3d0)
Location: fs/namespace.c:117
Inline: True
Direct callers:
  - fs/namespace.c:alloc_vfsmnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:cleanup_mnt
```
**Symbols:**

```
ffffffff8122c3d0-ffffffff8122c415: mnt_free_id.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81254b60)
Location: fs/namespace.c:117
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:alloc_vfsmnt
```
**Symbols:**

```
ffffffff81254b60-ffffffff81254ba5: mnt_free_id.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812680c0)
Location: fs/namespace.c:116
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:alloc_vfsmnt
```
**Symbols:**

```
ffffffff812680c0-ffffffff81268105: mnt_free_id.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81275570)
Location: fs/namespace.c:119
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
```
**Symbols:**

```
ffffffff81275570-ffffffff812755b5: mnt_free_id.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff81297e30)
Location: fs/namespace.c:119
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
```
**Symbols:**

```
ffffffff81297e30-ffffffff81297e75: mnt_free_id.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812bdcf0)
Location: fs/namespace.c:119
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
```
**Symbols:**

```
ffffffff812bdcf0-ffffffff812bdd35: mnt_free_id.isra.34 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812d306f)
Location: fs/namespace.c:110
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff812f1369)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff81302f09)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff8133c965)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff81348825)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff8134ebf9)
Location: fs/namespace.c:135
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff8139cc70)
Location: fs/namespace.c:135
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff8141fb4d)
Location: fs/namespace.c:136
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff814ac046)
Location: fs/namespace.c:153
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff814e0e03)
Location: fs/namespace.c:137
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff81514ed3)
Location: fs/namespace.c:142
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffff8000103b6278)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (c05945f0)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (c0000000004b285c)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffe000278f9e)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff812fb4e9)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff812ec109)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff812f92d9)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
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
In fs/namespace.c (ffffffff8130a5f9)
Location: fs/namespace.c:115
Inline: True
Inline callers:
  - fs/namespace.c:cleanup_mnt
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:alloc_vfsmnt
```
</details>
</li>
</ul>

## Differences
