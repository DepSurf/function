# Function: <code>ext4_es_is_delonly</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135b62c)
Location: fs/ext4/extents_status.h:186
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
```
In fs/ext4/inode.c (ffffffff81367610)
Location: fs/ext4/extents_status.h:186
Inline: False
```
**Symbols:**

```
ffffffff81359690-ffffffff813596aa: ext4_es_is_delonly (STB_LOCAL)
ffffffff81367610-ffffffff8136762a: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81384646)
Location: fs/ext4/extents_status.h:186
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
```
In fs/ext4/inode.c (ffffffff81390a00)
Location: fs/ext4/extents_status.h:186
Inline: False
```
**Symbols:**

```
ffffffff813826c0-ffffffff813826de: ext4_es_is_delonly (STB_LOCAL)
ffffffff81390a00-ffffffff81390a1e: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139d2c6)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff813a9460)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff8139abc0-ffffffff8139abde: ext4_es_is_delonly (STB_LOCAL)
ffffffff813a9460-ffffffff813a947e: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e6e82)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
```
```
In fs/ext4/inode.c (ffffffff813f53b0)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff813e60d0-ffffffff813e60ee: ext4_es_is_delonly (STB_LOCAL)
ffffffff813f53b0-ffffffff813f53ce: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f9142)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
```
```
In fs/ext4/inode.c (ffffffff81407b50)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff813f8430-ffffffff813f844e: ext4_es_is_delonly (STB_LOCAL)
ffffffff81407b50-ffffffff81407b6e: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8140108e)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
```
```
In fs/ext4/inode.c (ffffffff8140dfd0)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff813fe8b0-ffffffff813fe8ce: ext4_es_is_delonly (STB_LOCAL)
ffffffff8140dfd0-ffffffff8140dfee: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814513ce)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
```
```
In fs/ext4/inode.c (ffffffff81460e90)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff81450c30-ffffffff81450c54: ext4_es_is_delonly (STB_LOCAL)
ffffffff81460e90-ffffffff81460eb4: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814ceb37)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
```
```
In fs/ext4/inode.c (ffffffff814df8d0)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff814cdc60-ffffffff814cdc8b: ext4_es_is_delonly (STB_LOCAL)
ffffffff814df8d0-ffffffff814df8fb: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815673a7)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
```
```
In fs/ext4/inode.c (ffffffff81578a50)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff815663d0-ffffffff815663fb: ext4_es_is_delonly (STB_LOCAL)
ffffffff81578a50-ffffffff81578a7b: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8159f577)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
```
```
In fs/ext4/inode.c (ffffffff815afff0)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff8159e060-ffffffff8159e08b: ext4_es_is_delonly (STB_LOCAL)
ffffffff815afff0-ffffffff815b001b: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d80c7)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:get_rsvd
  - fs/ext4/extents_status.c:get_rsvd
```
```
In fs/ext4/inode.c (ffffffff815e8da0)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff815d6cb0-ffffffff815d6cdb: ext4_es_is_delonly (STB_LOCAL)
ffffffff815e8da0-ffffffff815e8dcb: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff8000104704e8)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffff80001047d328)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffff80001046d678-ffff80001046d698: ext4_es_is_delonly (STB_LOCAL)
ffff80001047d328-ffff80001047d348: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c0631904)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
```
```
In fs/ext4/inode.c (c063e810)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
c062eba0-c062ebc4: ext4_es_is_delonly (STB_LOCAL)
c063e810-c063e834: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c000000000590b7c)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
```
```
In fs/ext4/inode.c (c0000000005a0960)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
c00000000058d420-c00000000058d448: ext4_es_is_delonly (STB_LOCAL)
c0000000005a0960-c0000000005a0988: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fcc04)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:count_rsvd
```
```
In fs/ext4/inode.c (ffffffe000306bc2)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffe0002fa8c0-ffffffe0002fa8e4: ext4_es_is_delonly (STB_LOCAL)
ffffffe000306bc2-ffffffe000306be6: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813958a6)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff813a1a40)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff813931a0-ffffffff813931be: ext4_es_is_delonly (STB_LOCAL)
ffffffff813a1a40-ffffffff813a1a5e: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81386336)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff813924d0)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff81383c30-ffffffff81383c4e: ext4_es_is_delonly (STB_LOCAL)
ffffffff813924d0-ffffffff813924ee: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81393206)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff8139f2a0)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff81390b00-ffffffff81390b1e: ext4_es_is_delonly (STB_LOCAL)
ffffffff8139f2a0-ffffffff8139f2be: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ext4_es_is_delonly(struct extent_status *es);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a7299)
Location: fs/ext4/extents_status.h:187
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:__es_remove_extent
```
```
In fs/ext4/inode.c (ffffffff813b3800)
Location: fs/ext4/extents_status.h:187
Inline: False
```
**Symbols:**

```
ffffffff813a4990-ffffffff813a49ae: ext4_es_is_delonly (STB_LOCAL)
ffffffff813b3800-ffffffff813b381e: ext4_es_is_delonly (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
