# Function: <code>is_mounted</code>

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
In fs/dcache.c (ffffffff8122516d)
Location: fs/mount.h:82
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
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
In fs/dcache.c (ffffffff8124b885)
Location: fs/mount.h:82
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
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
In fs/dcache.c (ffffffff8125e865)
Location: fs/mount.h:85
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
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
In fs/dcache.c (ffffffff8126c080)
Location: fs/mount.h:86
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
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
In fs/dcache.c (ffffffff8128f970)
Location: fs/mount.h:87
Inline: True
Inline callers:
  - fs/dcache.c:prepend_path
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
In fs/d_path.c (ffffffff812d3a42)
Location: fs/mount.h:87
Inline: True
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
In fs/d_path.c (ffffffff812e8c92)
Location: fs/mount.h:87
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f3cc0)
Location: fs/mount.h:89
Inline: True
```
```
In fs/d_path.c (ffffffff81307547)
Location: fs/mount.h:89
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301b3b)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff8131a5a7)
Location: fs/mount.h:89
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133f44e)
Location: fs/mount.h:95
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff813544b3)
Location: fs/mount.h:95
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
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
In fs/namespace.c (ffffffff8134b4ae)
Location: fs/mount.h:94
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
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
In fs/namespace.c (ffffffff8134cf05)
Location: fs/mount.h:94
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
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
In fs/namespace.c (ffffffff8139ae95)
Location: fs/mount.h:94
Inline: True
Inline callers:
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
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
In fs/namespace.c (ffffffff8142371c)
Location: fs/mount.h:94
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
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
In fs/namespace.c (ffffffff814afe7c)
Location: fs/mount.h:94
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
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
In fs/namespace.c (ffffffff814e4ec5)
Location: fs/mount.h:94
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_lock_mount
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
In fs/namespace.c (ffffffff81518cf5)
Location: fs/mount.h:92
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:do_set_group
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:do_lock_mount
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b41e8)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffff8000103d1834)
Location: fs/mount.h:89
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0596910)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (c05ac5b0)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/d_path.c:prepend_path
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b0228)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (c0000000004d42f0)
Location: fs/mount.h:89
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000277a3c)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffe00028cf56)
Location: fs/mount.h:89
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fa11b)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff81312b87)
Location: fs/mount.h:89
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ead3b)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff81303797)
Location: fs/mount.h:89
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7f0b)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff81310977)
Location: fs/mount.h:89
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130984b)
Location: fs/mount.h:89
Inline: True
Inline callers:
  - fs/namespace.c:mnt_warn_timestamp_expiry
```
```
In fs/d_path.c (ffffffff81322169)
Location: fs/mount.h:89
Inline: True
```
</details>
</li>
</ul>

## Differences
