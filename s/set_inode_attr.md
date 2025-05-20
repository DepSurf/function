# Function: <code>set_inode_attr</code>

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
In fs/kernfs/inode.c (ffffffff81288a72)
Location: fs/kernfs/inode.c:244
Inline: True
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
In fs/kernfs/inode.c (ffffffff812b5f36)
Location: fs/kernfs/inode.c:247
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
In fs/kernfs/inode.c (ffffffff812cb7c6)
Location: fs/kernfs/inode.c:174
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
In fs/kernfs/inode.c (ffffffff812d8c08)
Location: fs/kernfs/inode.c:174
Inline: True
```
```
In fs/configfs/inode.c (ffffffff812de0bf)
Location: fs/configfs/inode.c:119
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
In fs/kernfs/inode.c (ffffffff812fd468)
Location: fs/kernfs/inode.c:174
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813029ff)
Location: fs/configfs/inode.c:119
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
In fs/kernfs/inode.c (ffffffff8132b0c6)
Location: fs/kernfs/inode.c:174
Inline: True
```
```
In fs/configfs/inode.c (ffffffff8133095d)
Location: fs/configfs/inode.c:119
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
In fs/kernfs/inode.c (ffffffff81342736)
Location: fs/kernfs/inode.c:174
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81347d4d)
Location: fs/configfs/inode.c:119
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
In fs/kernfs/inode.c (ffffffff8136a896)
Location: fs/kernfs/inode.c:158
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813701ce)
Location: fs/configfs/inode.c:105
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
In fs/kernfs/inode.c (ffffffff81382a74)
Location: fs/kernfs/inode.c:158
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813886fe)
Location: fs/configfs/inode.c:102
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
In fs/kernfs/inode.c (ffffffff813cd19b)
Location: fs/kernfs/inode.c:160
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff813d343e)
Location: fs/configfs/inode.c:102
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
In fs/kernfs/inode.c (ffffffff813dedcb)
Location: fs/kernfs/inode.c:160
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff813e517e)
Location: fs/configfs/inode.c:102
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
In fs/kernfs/inode.c (ffffffff813e5aeb)
Location: fs/kernfs/inode.c:161
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff813ebd8e)
Location: fs/configfs/inode.c:101
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
In fs/kernfs/inode.c (ffffffff814376bb)
Location: fs/kernfs/inode.c:155
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff8143db25)
Location: fs/configfs/inode.c:95
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
In fs/kernfs/inode.c (ffffffff814b234b)
Location: fs/kernfs/inode.c:158
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff814b93ef)
Location: fs/configfs/inode.c:95
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
In fs/kernfs/inode.c (ffffffff81548edb)
Location: fs/kernfs/inode.c:158
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff81550b3f)
Location: fs/configfs/inode.c:95
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
In fs/kernfs/inode.c (ffffffff81580aab)
Location: fs/kernfs/inode.c:158
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff8158882c)
Location: fs/configfs/inode.c:95
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
In fs/kernfs/inode.c (ffffffff815b953b)
Location: fs/kernfs/inode.c:157
Inline: True
Inline callers:
  - fs/kernfs/inode.c:kernfs_refresh_inode
```
```
In fs/configfs/inode.c (ffffffff815c141c)
Location: fs/configfs/inode.c:94
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
In fs/kernfs/inode.c (ffff800010450f40)
Location: fs/kernfs/inode.c:158
Inline: True
```
```
In fs/configfs/inode.c (ffff8000104589a0)
Location: fs/configfs/inode.c:102
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
In fs/kernfs/inode.c (c0613f00)
Location: fs/kernfs/inode.c:158
Inline: True
```
```
In fs/configfs/inode.c (c061a704)
Location: fs/configfs/inode.c:102
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
In fs/kernfs/inode.c (c0000000005693fc)
Location: fs/kernfs/inode.c:158
Inline: True
```
```
In fs/configfs/inode.c (c0000000005733f8)
Location: fs/configfs/inode.c:102
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
In fs/kernfs/inode.c (ffffffe0002e3e10)
Location: fs/kernfs/inode.c:158
Inline: True
```
```
In fs/configfs/inode.c (ffffffe0002e99f0)
Location: fs/configfs/inode.c:102
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
In fs/kernfs/inode.c (ffffffff8137b054)
Location: fs/kernfs/inode.c:158
Inline: True
```
```
In fs/configfs/inode.c (ffffffff81380cde)
Location: fs/configfs/inode.c:102
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
In fs/kernfs/inode.c (ffffffff8136bb24)
Location: fs/kernfs/inode.c:158
Inline: True
```
```
In fs/configfs/inode.c (ffffffff8137176e)
Location: fs/configfs/inode.c:102
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
In fs/kernfs/inode.c (ffffffff81378b24)
Location: fs/kernfs/inode.c:158
Inline: True
```
```
In fs/configfs/inode.c (ffffffff8137e7ae)
Location: fs/configfs/inode.c:102
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
In fs/kernfs/inode.c (ffffffff8138c5d4)
Location: fs/kernfs/inode.c:158
Inline: True
```
```
In fs/configfs/inode.c (ffffffff813922be)
Location: fs/configfs/inode.c:102
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_new_inode
```
</details>
</li>
</ul>

## Differences
