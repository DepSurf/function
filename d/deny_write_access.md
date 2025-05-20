# Function: <code>deny_write_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c7403)
Location: include/linux/fs.h:2511
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff8121214f)
Location: include/linux/fs.h:2511
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e39b3)
Location: include/linux/fs.h:2626
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff81238c21)
Location: include/linux/fs.h:2626
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f3993)
Location: include/linux/fs.h:2595
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff8124b8d1)
Location: include/linux/fs.h:2595
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
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
In mm/mmap.c (ffffffff811fe9b4)
Location: include/linux/fs.h:2720
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812579f9)
Location: include/linux/fs.h:2720
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
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
In mm/mmap.c (ffffffff81216f66)
Location: include/linux/fs.h:2781
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff81279cc9)
Location: include/linux/fs.h:2781
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
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
In mm/mmap.c (ffffffff81237eb1)
Location: include/linux/fs.h:2803
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (0)
Location: include/linux/fs.h:2803
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
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
In mm/mmap.c (ffffffff8124b7d2)
Location: include/linux/fs.h:2874
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812b64ca)
Location: include/linux/fs.h:2874
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
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
In mm/mmap.c (ffffffff8125dcbb)
Location: include/linux/fs.h:2880
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812d3249)
Location: include/linux/fs.h:2880
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
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
In mm/mmap.c (ffffffff8126c48b)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812e4dd9)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff8134fe72)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (ffffffff8129c221)
Location: include/linux/fs.h:2984
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff8131c663)
Location: include/linux/fs.h:2984
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff813966e6)
Location: include/linux/fs.h:2984
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (ffffffff812a7544)
Location: include/linux/fs.h:2819
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff813281b8)
Location: include/linux/fs.h:2819
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff81365b62)
Location: include/linux/fs.h:2819
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff813a8406)
Location: include/linux/fs.h:2819
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (ffffffff812ad27b)
Location: include/linux/fs.h:3072
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff8132e0dc)
Location: include/linux/fs.h:3072
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff8136c5a2)
Location: include/linux/fs.h:3072
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff813af45f)
Location: include/linux/fs.h:3072
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/fork.c (ffffffff810b330f)
Location: include/linux/fs.h:3060
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In fs/exec.c (ffffffff8137b8cc)
Location: include/linux/fs.h:3060
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff813bb272)
Location: include/linux/fs.h:3060
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff813ff00f)
Location: include/linux/fs.h:3060
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/fork.c (ffffffff810c952f)
Location: include/linux/fs.h:2826
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In fs/exec.c (ffffffff813fc164)
Location: include/linux/fs.h:2826
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff814411dd)
Location: include/linux/fs.h:2826
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff81472baf)
Location: include/linux/fs.h:2826
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/fork.c (ffffffff810e6a8b)
Location: include/linux/fs.h:2980
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In fs/exec.c (ffffffff81485bd4)
Location: include/linux/fs.h:2980
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff814d011e)
Location: include/linux/fs.h:2980
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff81504906)
Location: include/linux/fs.h:2980
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/fork.c (ffffffff810f2445)
Location: include/linux/fs.h:2594
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In fs/exec.c (ffffffff814b98c8)
Location: include/linux/fs.h:2594
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff815063c1)
Location: include/linux/fs.h:2594
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff8153c008)
Location: include/linux/fs.h:2594
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In kernel/fork.c (ffffffff810fc015)
Location: include/linux/fs.h:2878
Inline: True
Inline callers:
  - kernel/fork.c:replace_mm_exe_file
  - kernel/fork.c:dup_mmap
```
```
In fs/exec.c (ffffffff814ebdb8)
Location: include/linux/fs.h:2878
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/kernel_read_file.c (ffffffff8153b0e1)
Location: include/linux/fs.h:2878
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file
```
```
In fs/verity/enable.c (ffffffff815712e8)
Location: include/linux/fs.h:2878
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (ffff8000103037d8)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffff80001038c83c)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffff800010411a2c)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (c0521e90)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (c05743f0)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (c05de0fc)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (c0000000003d0360)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (c000000000484788)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (c00000000051f5e0)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (ffffffe0002102bc)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffe00025d0d2)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffe0002b9c22)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (ffffffff81264adb)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812dd3b9)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff81348452)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (ffffffff81256efb)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812ce039)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff81339132)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (ffffffff8126287b)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812db1c9)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff81345f22)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
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
In mm/mmap.c (ffffffff8127223b)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - mm/mmap.c:mmap_region
```
```
In fs/exec.c (ffffffff812ec149)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file
  - fs/exec.c:do_open_execat
```
```
In fs/verity/enable.c (ffffffff81359202)
Location: include/linux/fs.h:2942
Inline: True
Inline callers:
  - fs/verity/enable.c:fsverity_ioctl_enable
```
</details>
</li>
</ul>

## Differences
