# Function: <code>kobject_get_unless_zero</code>

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
In lib/kobject.c (ffffffff813ebf83)
Location: lib/kobject.c:604
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In lib/kobject.c (ffffffff81431b63)
Location: lib/kobject.c:604
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
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
In lib/kobject.c (ffffffff8144ddd3)
Location: lib/kobject.c:604
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818ee053)
Location: lib/kobject.c:604
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - block/genhd.c:get_disk
```
**Symbols:**

```
ffffffff818ee310-ffffffff818ee346: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8197426b)
Location: lib/kobject.c:604
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - block/genhd.c:get_disk
```
**Symbols:**

```
ffffffff819745a0-ffffffff8197460a: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0b73)
Location: lib/kobject.c:619
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
ffffffff819d0740-ffffffff819d07aa: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a09e13)
Location: lib/kobject.c:619
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
ffffffff81a09ca0-ffffffff81a09d0a: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79685)
Location: lib/kobject.c:650
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
ffffffff81a79540-ffffffff81a79574: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab09e5)
Location: lib/kobject.c:650
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - fs/char_dev.c:cdev_get
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
ffffffff81ab08a0-ffffffff81ab08d4: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eaac0)
Location: lib/kobject.c:668
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - block/genhd.c:exact_lock
  - lib/kobject.c:kset_find_obj
```
**Symbols:**

```
ffffffff815eaac0-ffffffff815eab0c: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f3e0)
Location: lib/kobject.c:665
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/block_dev.c:blkdev_get_no_open
  - lib/kobject.c:kset_find_obj
```
**Symbols:**

```
ffffffff8160f3e0-ffffffff8160f42c: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2b20)
Location: lib/kobject.c:665
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - fs/block_dev.c:blkdev_get_no_open
  - block/genhd.c:disk_uevent
  - lib/kobject.c:kset_find_obj
```
**Symbols:**

```
ffffffff815f2b20-ffffffff815f2b68: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8165fd00)
Location: lib/kobject.c:665
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - block/bdev.c:blkdev_get_no_open
  - block/genhd.c:disk_uevent
  - lib/kobject.c:kset_find_obj
```
**Symbols:**

```
ffffffff8165fd00-ffffffff8165fd48: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779840)
Location: lib/kobject.c:633
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - block/bdev.c:blkdev_get_no_open
  - block/genhd.c:disk_uevent
  - lib/kobject.c:kset_find_obj
```
**Symbols:**

```
ffffffff81779840-ffffffff817798b0: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820227e0)
Location: lib/kobject.c:641
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - block/bdev.c:blkdev_get_no_open
  - block/genhd.c:disk_uevent
  - lib/kobject.c:kset_find_obj
```
**Symbols:**

```
ffffffff820227e0-ffffffff82022850: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2850)
Location: lib/kobject.c:642
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - block/bdev.c:blkdev_get_no_open
  - block/genhd.c:blk_mark_disk_dead
  - block/genhd.c:disk_uevent
  - lib/kobject.c:kset_find_obj
```
**Symbols:**

```
ffffffff820a2850-ffffffff820a28bc: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217a8d0)
Location: lib/kobject.c:649
Inline: False
Direct callers:
  - fs/char_dev.c:exact_lock
  - fs/char_dev.c:chrdev_open
  - fs/char_dev.c:chrdev_open
  - block/bdev.c:blkdev_get_no_open
  - block/genhd.c:blk_report_disk_dead
  - block/genhd.c:disk_uevent
  - lib/kobject.c:kset_find_obj
```
**Symbols:**

```
ffffffff8217a8d0-ffffffff8217a93c: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8aa14)
Location: lib/kobject.c:650
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - fs/char_dev.c:cdev_get
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
ffff800010d8a670-ffff800010d8a6b8: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e85374)
Location: lib/kobject.c:650
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - fs/char_dev.c:cdev_get
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
c0e84fd8-c0e85010: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecbe54)
Location: lib/kobject.c:650
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - fs/char_dev.c:cdev_get
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
c000000000ecb450-c000000000ecb498: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b3f50)
Location: lib/kobject.c:650
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - fs/char_dev.c:cdev_get
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
ffffffe0008b3a8a-ffffffe0008b3ac2: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4f835)
Location: lib/kobject.c:650
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - fs/char_dev.c:cdev_get
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
ffffffff81a4f6f0-ffffffff81a4f724: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0c935)
Location: lib/kobject.c:650
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - fs/char_dev.c:cdev_get
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
ffffffff81a0c7f0-ffffffff81a0c824: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abbc25)
Location: lib/kobject.c:650
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - fs/char_dev.c:cdev_get
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
ffffffff81abbae0-ffffffff81abbb14: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct kobject *kobject_get_unless_zero(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac8063)
Location: lib/kobject.c:650
Inline: True
Inline callers:
  - lib/kobject.c:kset_find_obj
Direct callers:
  - fs/char_dev.c:cdev_get
  - block/genhd.c:get_disk_and_module
```
**Symbols:**

```
ffffffff81ac8360-ffffffff81ac8394: kobject_get_unless_zero (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
