# Function: <code>generic_drop_inode</code>

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
In fs/inode.c (ffffffff81227fd8)
Location: include/linux/fs.h:2577
Inline: True
```
```
In fs/ext4/super.c (ffffffff812a8e7e)
Location: include/linux/fs.h:2577
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff81250706)
Location: include/linux/fs.h:2727
Inline: True
```
```
In fs/ext4/super.c (ffffffff812d7fae)
Location: include/linux/fs.h:2727
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812637a6)
Location: include/linux/fs.h:2696
Inline: True
```
```
In fs/ext4/super.c (ffffffff812edb8e)
Location: include/linux/fs.h:2696
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff8127120d)
Location: include/linux/fs.h:2821
Inline: True
```
```
In fs/ext4/super.c (ffffffff81322b9e)
Location: include/linux/fs.h:2821
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff81293b37)
Location: include/linux/fs.h:2883
Inline: True
```
```
In fs/ext4/super.c (ffffffff813472de)
Location: include/linux/fs.h:2883
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812b9e15)
Location: include/linux/fs.h:2905
Inline: True
```
```
In fs/ext4/super.c (ffffffff81375245)
Location: include/linux/fs.h:2905
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812ced85)
Location: include/linux/fs.h:2976
Inline: True
```
```
In fs/ext4/super.c (ffffffff8138d665)
Location: include/linux/fs.h:2976
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812ebc4a)
Location: include/linux/fs.h:2982
Inline: True
```
```
In fs/ext4/super.c (ffffffff813b7a55)
Location: include/linux/fs.h:2982
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812fd7d5)
Location: include/linux/fs.h:3044
Inline: True
```
```
In fs/ext4/super.c (ffffffff813d9b25)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff81336996)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/inode.c:iput_final
```
```
In fs/ext4/super.c (ffffffff81427335)
Location: include/linux/fs.h:3090
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff813422fc)
Location: include/linux/fs.h:2886
Inline: True
Inline callers:
  - fs/inode.c:iput_final
```
```
In fs/ext4/super.c (ffffffff8143e925)
Location: include/linux/fs.h:2886
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff813486fa)
Location: include/linux/fs.h:3139
Inline: True
Inline callers:
  - fs/inode.c:iput_final
```
```
In fs/ext4/super.c (ffffffff81444525)
Location: include/linux/fs.h:3139
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff81396401)
Location: include/linux/fs.h:3127
Inline: True
```
```
In fs/ext4/super.c (ffffffff81498325)
Location: include/linux/fs.h:3127
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff81417830)
Location: include/linux/fs.h:2893
Inline: True
```
```
In fs/ext4/super.c (ffffffff81522ff5)
Location: include/linux/fs.h:2893
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff814a2fb0)
Location: include/linux/fs.h:3047
Inline: True
```
```
In fs/ext4/super.c (ffffffff815c0175)
Location: include/linux/fs.h:3047
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff814d80ff)
Location: include/linux/fs.h:2661
Inline: True
```
```
In fs/ext4/super.c (ffffffff815f7915)
Location: include/linux/fs.h:2661
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff8150a8df)
Location: include/linux/fs.h:2944
Inline: True
```
```
In fs/ext4/super.c (ffffffff816304c5)
Location: include/linux/fs.h:2944
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffff8000103ae234)
Location: include/linux/fs.h:3044
Inline: True
```
```
In fs/ext4/super.c (ffff8000104b637c)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (c058e3d0)
Location: include/linux/fs.h:3044
Inline: True
```
```
In fs/ext4/super.c (c0675e2c)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (c0000000004a94e0)
Location: include/linux/fs.h:3044
Inline: True
```
```
In fs/ext4/super.c (c0000000005e5c1c)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffe000272ba2)
Location: include/linux/fs.h:3044
Inline: True
```
```
In fs/ext4/super.c (ffffffe0003305fc)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812f5db5)
Location: include/linux/fs.h:3044
Inline: True
```
```
In fs/ext4/super.c (ffffffff813d2105)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812e69d5)
Location: include/linux/fs.h:3044
Inline: True
```
```
In fs/ext4/super.c (ffffffff813c2b85)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff812f3bc5)
Location: include/linux/fs.h:3044
Inline: True
```
```
In fs/ext4/super.c (ffffffff813cf595)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
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
In fs/inode.c (ffffffff81304ffd)
Location: include/linux/fs.h:3044
Inline: True
```
```
In fs/ext4/super.c (ffffffff813e4b85)
Location: include/linux/fs.h:3044
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_drop_inode
```
</details>
</li>
</ul>

## Differences
