# Function: <code>inode_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128e1cc)
Location: include/linux/fs.h:755
Inline: True
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
In fs/locks.c (ffffffff812a2188)
Location: include/linux/fs.h:708
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b0ece)
Location: include/linux/fs.h:727
Inline: True
```
```
In fs/ext4/file.c (ffffffff812f1bb5)
Location: include/linux/fs.h:727
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffff812d4983)
Location: include/linux/fs.h:731
Inline: True
```
```
In fs/ext4/file.c (ffffffff81316116)
Location: include/linux/fs.h:731
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffff812fefd8)
Location: include/linux/fs.h:733
Inline: True
```
```
In fs/ext4/file.c (ffffffff81343fa6)
Location: include/linux/fs.h:733
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffff813149fc)
Location: include/linux/fs.h:781
Inline: True
```
```
In fs/ext4/file.c (ffffffff8135c0e6)
Location: include/linux/fs.h:781
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffff8133c369)
Location: include/linux/fs.h:796
Inline: True
```
```
In fs/ext4/file.c (ffffffff813852a4)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffff813548a9)
Location: include/linux/fs.h:810
Inline: True
```
```
In fs/ext4/file.c (ffffffff8139df28)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffff8139b4d5)
Location: include/linux/fs.h:828
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
```
```
In fs/ext4/file.c (ffffffff813e9147)
Location: include/linux/fs.h:828
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
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
In fs/locks.c (ffffffff813acf18)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
```
```
In fs/ext4/file.c (ffffffff813fb547)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
```
In fs/fuse/dax.c (ffffffff8149dec4)
Location: include/linux/fs.h:791
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
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
In fs/locks.c (ffffffff813b428c)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
```
```
In fs/ext4/file.c (ffffffff81401a17)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
```
In fs/fuse/dax.c (ffffffff814a3e94)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
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
In fs/locks.c (ffffffff81403f8c)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
```
```
In fs/ext4/file.c (ffffffff81453fa7)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
```
In fs/fuse/dax.c (ffffffff814fbf14)
Location: include/linux/fs.h:804
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
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
In fs/locks.c (ffffffff81479b3f)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
```
```
In fs/ext4/file.c (ffffffff814d1527)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
```
In fs/fuse/dax.c (ffffffff8158c474)
Location: include/linux/fs.h:759
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
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
In fs/locks.c (ffffffff8150c4df)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
```
```
In fs/ext4/file.c (ffffffff8156a2f7)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
```
In fs/fuse/dax.c (ffffffff81632ce4)
Location: include/linux/fs.h:774
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
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
In fs/locks.c (ffffffff81543c54)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
```
```
In fs/ext4/file.c (ffffffff815a225a)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
```
In fs/fuse/dax.c (ffffffff8166af97)
Location: include/linux/fs.h:789
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
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
In fs/locks.c (ffffffff81579137)
Location: include/linux/fs.h:822
Inline: True
Inline callers:
  - fs/locks.c:generic_add_lease
```
```
In fs/ext4/file.c (ffffffff815daf8a)
Location: include/linux/fs.h:822
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
```
In fs/fuse/dax.c (ffffffff816a52d7)
Location: include/linux/fs.h:822
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_write_iter
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
In fs/locks.c (ffff80001041777c)
Location: include/linux/fs.h:810
Inline: True
```
```
In fs/ext4/file.c (ffff8000104712a4)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (c05e44f8)
Location: include/linux/fs.h:810
Inline: True
```
```
In fs/ext4/file.c (c0632034)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (c000000000527350)
Location: include/linux/fs.h:810
Inline: True
```
```
In fs/ext4/file.c (c000000000591cc0)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffe0002bdf5c)
Location: include/linux/fs.h:810
Inline: True
```
```
In fs/ext4/file.c (ffffffe0002fd532)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffff8134ce89)
Location: include/linux/fs.h:810
Inline: True
```
```
In fs/ext4/file.c (ffffffff81396508)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffff8133db69)
Location: include/linux/fs.h:810
Inline: True
```
```
In fs/ext4/file.c (ffffffff81386f98)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffff8134a959)
Location: include/linux/fs.h:810
Inline: True
```
```
In fs/ext4/file.c (ffffffff81393e68)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
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
In fs/locks.c (ffffffff8135f237)
Location: include/linux/fs.h:810
Inline: True
```
```
In fs/ext4/file.c (ffffffff813a7ef8)
Location: include/linux/fs.h:810
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_file_write_iter
```
</details>
</li>
</ul>

## Differences
