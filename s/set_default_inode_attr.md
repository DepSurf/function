# Function: <code>set_default_inode_attr</code>

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
In fs/kernfs/inode.c (ffffffff812890d9)
Location: fs/kernfs/inode.c:238
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
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
In fs/kernfs/inode.c (ffffffff812b65d9)
Location: fs/kernfs/inode.c:240
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
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
In fs/kernfs/inode.c (ffffffff812cbdf3)
Location: fs/kernfs/inode.c:167
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
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
In fs/kernfs/inode.c (ffffffff812d9247)
Location: fs/kernfs/inode.c:167
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff812de111)
Location: fs/configfs/inode.c:112
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff812fdaa7)
Location: fs/kernfs/inode.c:167
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff81302a51)
Location: fs/configfs/inode.c:112
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff8132b727)
Location: fs/kernfs/inode.c:167
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff813309ad)
Location: fs/configfs/inode.c:112
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff81342a87)
Location: fs/kernfs/inode.c:167
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff81347d9d)
Location: fs/configfs/inode.c:112
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff8136abf8)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff8137022a)
Location: fs/configfs/inode.c:98
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff81382db8)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff8138875a)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff813cd2a8)
Location: fs/kernfs/inode.c:153
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_init_inode
```
```
In fs/configfs/inode.c (ffffffff813d349a)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff813deed8)
Location: fs/kernfs/inode.c:153
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_init_inode
```
```
In fs/configfs/inode.c (ffffffff813e51da)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff813e603a)
Location: fs/kernfs/inode.c:154
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff813ebdea)
Location: fs/configfs/inode.c:94
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff81437c3d)
Location: fs/kernfs/inode.c:148
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff8143db81)
Location: fs/configfs/inode.c:88
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff814b29a4)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff814b9449)
Location: fs/configfs/inode.c:88
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff81549584)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff81550b99)
Location: fs/configfs/inode.c:88
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff81581161)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff81588886)
Location: fs/configfs/inode.c:88
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff815b9c11)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff815c1478)
Location: fs/configfs/inode.c:88
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffff8000104512b4)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffff8000104589e4)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (c06142ac)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (c061a770)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (c00000000056992c)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (c000000000573460)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffe0002e415c)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffe0002e9a28)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff8137b398)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff81380d3a)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff8136be68)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff813717ca)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff81378e68)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff8137e80a)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
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
In fs/kernfs/inode.c (ffffffff8138c918)
Location: fs/kernfs/inode.c:151
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_get_inode
```
```
In fs/configfs/inode.c (ffffffff8139231a)
Location: fs/configfs/inode.c:95
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
```
</details>
</li>
</ul>

## Differences
