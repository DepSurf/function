# Function: <code>init_inodecache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81f96251)
Location: fs/ext4/super.c:969
Inline: True
```
```
In net/socket.c (ffffffff81fbac53)
Location: net/socket.c:290
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81fc0d23)
Location: fs/ext4/super.c:995
Inline: True
```
```
In fs/squashfs/super.c (ffffffff81fc1da6)
Location: fs/squashfs/super.c:418
Inline: True
```
```
In net/socket.c (ffffffff81fe8817)
Location: net/socket.c:290
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81ffd73d)
Location: fs/ext4/super.c:1000
Inline: True
```
```
In fs/squashfs/super.c (ffffffff81ffe7c0)
Location: fs/squashfs/super.c:418
Inline: True
```
```
In net/socket.c (ffffffff8202703d)
Location: net/socket.c:290
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff820e0aa5)
Location: fs/ext4/super.c:1042
Inline: True
```
```
In fs/squashfs/super.c (ffffffff820e1a20)
Location: fs/squashfs/super.c:418
Inline: True
```
```
In net/socket.c (ffffffff8210a590)
Location: net/socket.c:290
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff826e9728)
Location: fs/ext4/super.c:1043
Inline: True
```
```
In fs/squashfs/super.c (ffffffff826ea6a3)
Location: fs/squashfs/super.c:418
Inline: True
```
```
In net/socket.c (ffffffff82713f32)
Location: net/socket.c:290
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82713d5d)
Location: fs/ext4/super.c:1082
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82714b26)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff8273e157)
Location: net/socket.c:284
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff828cb1b1)
Location: fs/ext4/super.c:1136
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff828cbf7f)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff828f817d)
Location: net/socket.c:282
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff828e4ace)
Location: fs/ext4/super.c:1149
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff828e590d)
Location: fs/squashfs/super.c:406
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff82913bf4)
Location: net/socket.c:270
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff828ed529)
Location: fs/ext4/super.c:1157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff828ee36d)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff8291d977)
Location: net/socket.c:270
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82d03342)
Location: fs/ext4/super.c:1192
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82d0373b)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff82d2cad5)
Location: net/socket.c:284
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff82ff0645)
Location: fs/ext4/super.c:1357
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff82ff0a87)
Location: fs/squashfs/super.c:418
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff8301b54e)
Location: net/socket.c:284
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff831faeec)
Location: fs/ext4/super.c:1366
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff831fb32e)
Location: fs/squashfs/super.c:418
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff8322668e)
Location: net/socket.c:284
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff832e1e4d)
Location: fs/ext4/super.c:1372
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff832e228b)
Location: fs/squashfs/super.c:502
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff833109de)
Location: net/socket.c:334
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8349803e)
Location: fs/ext4/super.c:1412
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff834984bd)
Location: fs/squashfs/super.c:536
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff834ca6ed)
Location: net/socket.c:335
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff83ecd84c)
Location: fs/ext4/super.c:1407
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff83ecdde5)
Location: fs/squashfs/super.c:597
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff83f0c491)
Location: net/socket.c:335
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff836f28ec)
Location: fs/ext4/super.c:1473
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff836f2e85)
Location: fs/squashfs/super.c:614
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff83732811)
Location: net/socket.c:337
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff83925a8c)
Location: fs/ext4/super.c:1499
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff83926055)
Location: fs/squashfs/super.c:614
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff83966ce1)
Location: net/socket.c:339
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff800011466f7c)
Location: fs/ext4/super.c:1157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffff800011467e30)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffff8000114ae2b8)
Location: net/socket.c:270
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c153f920)
Location: fs/ext4/super.c:1157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (c1540974)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (c15b2eec)
Location: net/socket.c:270
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000013944fc)
Location: fs/ext4/super.c:1157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (c0000000013957b4)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (c0000000013be08c)
Location: net/socket.c:270
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe0000222fe)
Location: fs/ext4/super.c:1157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffe00002303e)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffe00003d574)
Location: net/socket.c:270
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff828d63dd)
Location: fs/ext4/super.c:1157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff828d7221)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff8290267b)
Location: net/socket.c:270
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff828ceaf9)
Location: fs/ext4/super.c:1157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff828cf93d)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff828fa9c9)
Location: net/socket.c:270
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff828e915d)
Location: fs/ext4/super.c:1157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff828e9fa1)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff82917c82)
Location: net/socket.c:270
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff828ee573)
Location: fs/ext4/super.c:1157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
```
```
In fs/squashfs/super.c (ffffffff828ef3b7)
Location: fs/squashfs/super.c:419
Inline: True
Inline callers:
  - fs/squashfs/super.c:init_squashfs_fs
```
```
In net/socket.c (ffffffff8291e9d9)
Location: net/socket.c:270
Inline: True
Inline callers:
  - net/socket.c:sock_init
```
</details>
</li>
</ul>

## Differences
