# Function: <code>fsnotify_inode_watches_children</code>

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
In fs/dcache.c (ffffffff81224421)
Location: include/linux/fsnotify_backend.h:256
Inline: True
Inline callers:
  - fs/dcache.c:__d_instantiate
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
```
```
In fs/notify/fsnotify.c (ffffffff8124f74f)
Location: include/linux/fsnotify_backend.h:256
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff8124cff3)
Location: include/linux/fsnotify_backend.h:256
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff81277fee)
Location: include/linux/fsnotify_backend.h:256
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff812600b3)
Location: include/linux/fsnotify_backend.h:255
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff8128bcce)
Location: include/linux/fsnotify_backend.h:255
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff8126d9c4)
Location: include/linux/fsnotify_backend.h:280
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff81298b29)
Location: include/linux/fsnotify_backend.h:280
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff81290464)
Location: include/linux/fsnotify_backend.h:281
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff812bbeb9)
Location: include/linux/fsnotify_backend.h:281
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff812b57ee)
Location: include/linux/fsnotify_backend.h:324
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff812e4ac9)
Location: include/linux/fsnotify_backend.h:324
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff812cab0c)
Location: include/linux/fsnotify_backend.h:354
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff812f9539)
Location: include/linux/fsnotify_backend.h:354
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff812e83e9)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff81319b8f)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff812f9f79)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff8132c9bf)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff81332040)
Location: include/linux/fsnotify_backend.h:389
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff813667a5)
Location: include/linux/fsnotify_backend.h:389
Inline: True
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
In fs/dcache.c (ffffffff8133da60)
Location: include/linux/fsnotify_backend.h:438
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff81373b69)
Location: include/linux/fsnotify_backend.h:438
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff81343d5f)
Location: include/linux/fsnotify_backend.h:435
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff8137a54e)
Location: include/linux/fsnotify_backend.h:435
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff8139168f)
Location: include/linux/fsnotify_backend.h:435
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff813c71ce)
Location: include/linux/fsnotify_backend.h:435
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff8141363b)
Location: include/linux/fsnotify_backend.h:563
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff8144e55f)
Location: include/linux/fsnotify_backend.h:563
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff8149ea23)
Location: include/linux/fsnotify_backend.h:564
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff814dcc6f)
Location: include/linux/fsnotify_backend.h:564
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff814d3d43)
Location: include/linux/fsnotify_backend.h:564
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff815134be)
Location: include/linux/fsnotify_backend.h:564
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff81506408)
Location: include/linux/fsnotify_backend.h:564
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff8154794e)
Location: include/linux/fsnotify_backend.h:564
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffff8000103a8b24)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffff8000103e835c)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (c058a160)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (c05bfd3c)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (c0000000004a3644)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (c0000000004eed04)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffe00026ee56)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffe00029d06a)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff812f2559)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff81324f9f)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff812e3189)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff81315b3f)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff812f0369)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff81322a6f)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
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
In fs/dcache.c (ffffffff81301470)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/dcache.c:d_splice_alias
  - fs/dcache.c:__d_move
  - fs/dcache.c:__d_move
  - fs/dcache.c:d_add
  - fs/dcache.c:__d_instantiate
```
```
In fs/notify/fsnotify.c (ffffffff813347bf)
Location: include/linux/fsnotify_backend.h:362
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:__fsnotify_parent
```
</details>
</li>
</ul>

## Differences
