# Function: <code>config_group_put</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812defe3)
Location: include/linux/configfs.h:116
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffff812e1cca)
Location: include/linux/configfs.h:116
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81303953)
Location: include/linux/configfs.h:116
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffff813066a7)
Location: include/linux/configfs.h:116
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813316d3)
Location: include/linux/configfs.h:116
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffff813346a7)
Location: include/linux/configfs.h:116
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81348ac3)
Location: include/linux/configfs.h:116
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffff8134b9c7)
Location: include/linux/configfs.h:116
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/dir.c (ffffffff81371024)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffff81374382)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/dir.c (ffffffff813894a4)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffff8138c602)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/dir.c (ffffffff813d5846)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/item.c (ffffffff813d79f2)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/dir.c (ffffffff813e7566)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/item.c (ffffffff813e9692)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/dir.c (ffffffff813edf36)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/item.c (ffffffff813f01f2)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/dir.c (ffffffff81440150)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/item.c (ffffffff814420df)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/dir.c (ffffffff814bbc68)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/item.c (ffffffff814bde0d)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/dir.c (ffffffff81553738)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/item.c (ffffffff81555b8d)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/dir.c (ffffffff8158b4c3)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/item.c (ffffffff8158d92d)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/dir.c (ffffffff815c41e2)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
```
```
In fs/configfs/item.c (ffffffff815c666d)
Location: include/linux/configfs.h:100
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/dir.c (ffff800010459af4)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffff80001045e14c)
Location: include/linux/configfs.h:102
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
In fs/configfs/dir.c (c061b97c)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (c061ec00)
Location: include/linux/configfs.h:102
Inline: True
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
In fs/configfs/dir.c (c000000000574e7c)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (c000000000579d48)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_put
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
In fs/configfs/dir.c (ffffffe0002ea7a0)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffe0002ede5e)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/dir.c (ffffffff81381a84)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffff81384be2)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/dir.c (ffffffff81372514)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffff81375672)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/dir.c (ffffffff8137f554)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffff813826b2)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/dir.c (ffffffff81393244)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/dir.c:unlink_obj
```
```
In fs/configfs/item.c (ffffffff813961d2)
Location: include/linux/configfs.h:102
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
```
</details>
</li>
</ul>

## Differences
