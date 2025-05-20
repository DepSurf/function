# Function: <code>bdi_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811aee30)
Location: mm/backing-dev.c:772
Inline: False
Direct callers:
  - mm/backing-dev.c:default_bdi_init
  - fs/fuse/inode.c:fuse_fill_super
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff811aee30-ffffffff811aef2a: bdi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c8280)
Location: mm/backing-dev.c:772
Inline: False
Direct callers:
  - mm/backing-dev.c:default_bdi_init
  - fs/fuse/inode.c:fuse_fill_super
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff811c8280-ffffffff811c836d: bdi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d83b0)
Location: mm/backing-dev.c:778
Inline: False
Direct callers:
  - mm/backing-dev.c:default_bdi_init
  - fs/fuse/inode.c:fuse_fill_super
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff811d83b0-ffffffff811d849d: bdi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e17a6)
Location: mm/backing-dev.c:823
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f77c6)
Location: mm/backing-dev.c:838
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81218bc6)
Location: mm/backing-dev.c:836
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122b959)
Location: mm/backing-dev.c:839
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123b5cd)
Location: mm/backing-dev.c:826
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81249aed)
Location: mm/backing-dev.c:849
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81277d4b)
Location: mm/backing-dev.c:848
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
Direct callers:
  - mm/backing-dev.c:default_bdi_init
```
**Symbols:**

```
ffffffff812784a7-ffffffff8127851c: bdi_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8128235f)
Location: mm/backing-dev.c:715
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
Direct callers:
  - mm/backing-dev.c:default_bdi_init
```
**Symbols:**

```
ffffffff81be6fcc-ffffffff81be7041: bdi_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8128746f)
Location: mm/backing-dev.c:714
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
Direct callers:
  - mm/backing-dev.c:default_bdi_init
```
**Symbols:**

```
ffffffff81bd8d74-ffffffff81bd8de9: bdi_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c6def)
Location: mm/backing-dev.c:787
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
Direct callers:
  - mm/backing-dev.c:default_bdi_init
```
**Symbols:**

```
ffffffff81cbabef-ffffffff81cbac64: bdi_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813241b0)
Location: mm/backing-dev.c:777
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_alloc
  - drivers/base/init.c:driver_init
```
**Symbols:**

```
ffffffff813241b0-ffffffff813242aa: bdi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81398ab0)
Location: mm/backing-dev.c:904
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_alloc
  - drivers/base/init.c:driver_init
```
**Symbols:**

```
ffffffff81398ab0-ffffffff81398baa: bdi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813cba10)
Location: mm/backing-dev.c:917
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_alloc
  - drivers/base/init.c:driver_init
```
**Symbols:**

```
ffffffff813cba10-ffffffff813cbb0a: bdi_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bdi_init(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f6350)
Location: mm/backing-dev.c:912
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_alloc
  - drivers/base/init.c:driver_init
```
**Symbols:**

```
ffffffff813f6350-ffffffff813f6455: bdi_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102df2f8)
Location: mm/backing-dev.c:849
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c0504154)
Location: mm/backing-dev.c:849
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039ed58)
Location: mm/backing-dev.c:849
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f70be)
Location: mm/backing-dev.c:849
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124213d)
Location: mm/backing-dev.c:849
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123510d)
Location: mm/backing-dev.c:849
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123fedd)
Location: mm/backing-dev.c:849
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124f63d)
Location: mm/backing-dev.c:849
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc_node
  - mm/backing-dev.c:default_bdi_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
