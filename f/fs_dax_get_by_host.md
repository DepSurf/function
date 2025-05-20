# Function: <code>fs_dax_get_by_host</code>

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
In fs/ext4/inode.c (ffffffff81300e17)
Location: include/linux/dax.h:50
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iomap_begin
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
In drivers/dax/super.c (ffffffff816a5b89)
Location: include/linux/dax.h:49
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
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
In drivers/dax/super.c (ffffffff816e1fab)
Location: include/linux/dax.h:76
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
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
In drivers/dax/super.c (ffffffff817053c8)
Location: include/linux/dax.h:78
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
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
In drivers/dax/super.c (ffffffff8173f268)
Location: include/linux/dax.h:132
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
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
In drivers/dax/super.c (ffffffff81763448)
Location: include/linux/dax.h:132
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
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
In drivers/dax/super.c (ffff800010963198)
Location: include/linux/dax.h:132
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a19820)
Location: include/linux/dax.h:132
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
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
In drivers/dax/super.c (ffffffe0005d0856)
Location: include/linux/dax.h:132
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
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
In drivers/dax/super.c (ffffffff81717b38)
Location: include/linux/dax.h:132
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
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
In drivers/dax/super.c (ffffffff816f0068)
Location: include/linux/dax.h:132
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
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
In drivers/dax/super.c (ffffffff81756908)
Location: include/linux/dax.h:132
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
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
In drivers/dax/super.c (ffffffff81771d68)
Location: include/linux/dax.h:132
Inline: True
Inline callers:
  - drivers/dax/super.c:fs_dax_get_by_bdev
```
</details>
</li>
</ul>

## Differences
