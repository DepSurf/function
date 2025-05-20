# Function: <code>configfs_get</code>

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
In fs/configfs/dir.c (ffffffff812e02a8)
Location: fs/configfs/configfs_internal.h:158
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
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
In fs/configfs/dir.c (ffffffff81304c28)
Location: fs/configfs/configfs_internal.h:158
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
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
In fs/configfs/dir.c (ffffffff81332db8)
Location: fs/configfs/configfs_internal.h:158
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
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
In fs/configfs/dir.c (ffffffff8134a1a8)
Location: fs/configfs/configfs_internal.h:158
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
  - fs/configfs/dir.c:configfs_make_dirent
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
In fs/configfs/dir.c (ffffffff8137293d)
Location: fs/configfs/configfs_internal.h:155
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
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
In fs/configfs/dir.c (ffffffff8138ad7c)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff8138ba1b)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff813d5cca)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff813d6e95)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff813e799a)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff813e8b35)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff813ee5ba)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff813ef6a5)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff814404ea)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff81441595)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff814bb2d7)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff814bd185)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff81552c17)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff81554de5)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff8158a997)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff8158cb85)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff815c366a)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff815c58c7)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffff80001045bd44)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffff80001045d064)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (c061d00c)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (c061de68)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (c000000000577214)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (c000000000578b5c)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffe0002ec214)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffe0002ed30c)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
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
In fs/configfs/dir.c (ffffffff8138335c)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff81383ffb)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff81373dec)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff81374a8b)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff81380e2c)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff81381acb)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
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
In fs/configfs/dir.c (ffffffff813948ec)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_make_dirent
```
```
In fs/configfs/symlink.c (ffffffff813955fb)
Location: fs/configfs/configfs_internal.h:144
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
</details>
</li>
</ul>

## Differences
