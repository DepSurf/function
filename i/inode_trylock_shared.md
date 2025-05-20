# Function: <code>inode_trylock_shared</code>

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
In fs/dcache.c (ffffffff8124d0e3)
Location: include/linux/fs.h:760
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
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
In fs/dcache.c (ffffffff812601a3)
Location: include/linux/fs.h:713
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
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
In fs/dcache.c (ffffffff8126dacf)
Location: include/linux/fs.h:732
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff812f13a3)
Location: include/linux/fs.h:732
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
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
In fs/dcache.c (ffffffff8129056f)
Location: include/linux/fs.h:736
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff81315f63)
Location: include/linux/fs.h:736
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
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
In fs/dcache.c (ffffffff812b6da3)
Location: include/linux/fs.h:738
Inline: True
```
```
In fs/ext4/file.c (ffffffff81343be1)
Location: include/linux/fs.h:738
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
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
In fs/dcache.c (ffffffff812cbf2f)
Location: include/linux/fs.h:786
Inline: True
```
```
In fs/ext4/file.c (ffffffff8135bd21)
Location: include/linux/fs.h:786
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
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
In fs/dcache.c (ffffffff812e8562)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff81384ddc)
Location: include/linux/fs.h:801
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
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
In fs/dcache.c (ffffffff812fa0f2)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff8139d864)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813b33be)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/dcache.c (ffffffff813331b2)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff813e9c78)
Location: include/linux/fs.h:833
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
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
In fs/dcache.c (ffffffff8133eb12)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff813fbd96)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fuse/dax.c (ffffffff8149de3c)
Location: include/linux/fs.h:796
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/dcache.c (ffffffff81344f02)
Location: include/linux/fs.h:797
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff81402071)
Location: include/linux/fs.h:797
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fuse/dax.c (ffffffff814a3e0c)
Location: include/linux/fs.h:797
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/dcache.c (ffffffff813929f2)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff8145479a)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fuse/dax.c (ffffffff814fbe8c)
Location: include/linux/fs.h:809
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/dcache.c (ffffffff814142a2)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff814d213b)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fuse/dax.c (ffffffff8158c3db)
Location: include/linux/fs.h:764
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/dcache.c (ffffffff8149f722)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff8156a9dd)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fuse/dax.c (ffffffff81632c3b)
Location: include/linux/fs.h:779
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/dcache.c (ffffffff814d4a42)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff815a2b16)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fuse/dax.c (ffffffff8166aeee)
Location: include/linux/fs.h:794
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/dcache.c (ffffffff81506d82)
Location: include/linux/fs.h:827
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff815db830)
Location: include/linux/fs.h:827
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/fuse/dax.c (ffffffff816a522e)
Location: include/linux/fs.h:827
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_read_iter
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
In fs/dcache.c (ffff8000103a8d44)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffff800010470dfc)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffff800010487bfc)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/dcache.c (c058a360)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/inode.c (c0649db4)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/dcache.c (c0000000004a38f8)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (c000000000591570)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (c0000000005ae2dc)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/dcache.c (ffffffe00026f03c)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffe0002fd0fc)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffe00030f51c)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/dcache.c (ffffffff812f26d2)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff81395e44)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813ab99e)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/dcache.c (ffffffff812e3302)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff813868d4)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff8139c42e)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/dcache.c (ffffffff812f04e2)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff813937a4)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813a91fe)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/dcache.c (ffffffff81301658)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
```
```
In fs/ext4/file.c (ffffffff813a7834)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_file_read_iter
```
```
In fs/ext4/inode.c (ffffffff813bdaae)
Location: include/linux/fs.h:815
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
</details>
</li>
</ul>

## Differences
