# Function: <code>ext4_alloc_file_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c3340)
Location: fs/ext4/extents.c:4664
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff812c3340-ffffffff812c3649: ext4_alloc_file_blocks.isra.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f2d30)
Location: fs/ext4/extents.c:4668
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff812f2d30-ffffffff812f302b: ext4_alloc_file_blocks.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff81308d00)
Location: fs/ext4/extents.c:4658
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81308d00-ffffffff81308fde: ext4_alloc_file_blocks.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e7480)
Location: fs/ext4/extents.c:4653
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff812e7480-ffffffff812e7720: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130bee0)
Location: fs/ext4/extents.c:4653
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff8130bee0-ffffffff8130c1b5: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81339e90)
Location: fs/ext4/extents.c:4647
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81339e90-ffffffff8133a179: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81351200)
Location: fs/ext4/extents.c:4546
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81351200-ffffffff8135150a: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81379ee0)
Location: fs/ext4/extents.c:4556
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff81379ee0-ffffffff8137a1f6: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813923b0)
Location: fs/ext4/extents.c:4602
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff813923b0-ffffffff813926c6: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ddee0)
Location: fs/ext4/extents.c:4382
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff813ddee0-ffffffff813de217: ext4_alloc_file_blocks.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff813ef7d0)
Location: fs/ext4/extents.c:4379
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff813ef7d0-ffffffff813efb07: ext4_alloc_file_blocks.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f5ce0)
Location: fs/ext4/extents.c:4385
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff813f5ce0-ffffffff813f6003: ext4_alloc_file_blocks.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4424
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff81448560-ffffffff8144888c: ext4_alloc_file_blocks.isra.0 (STB_LOCAL)
ffffffff81cc8f9f-ffffffff81cc8fcc: ext4_alloc_file_blocks.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4420
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff814c4a50-ffffffff814c4da9: ext4_alloc_file_blocks.isra.0 (STB_LOCAL)
ffffffff81e7bcc2-ffffffff81e7bcef: ext4_alloc_file_blocks.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4424
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff8155d050-ffffffff8155d390: ext4_alloc_file_blocks.isra.0 (STB_LOCAL)
ffffffff8206c347-ffffffff8206c370: ext4_alloc_file_blocks.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4416
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff81594e70-ffffffff81595198: ext4_alloc_file_blocks.isra.0 (STB_LOCAL)
ffffffff820ec1c0-ffffffff820ec1e9: ext4_alloc_file_blocks.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:4448
Inline: True
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff815cdb20-ffffffff815cde36: ext4_alloc_file_blocks.isra.0 (STB_LOCAL)
ffffffff821c93f8-ffffffff821c9421: ext4_alloc_file_blocks.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010464bd0)
Location: fs/ext4/extents.c:4602
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffff800010464bd0-ffff800010464ecc: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0625758)
Location: fs/ext4/extents.c:4602
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
c0625758-c0625b0c: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000582aa0)
Location: fs/ext4/extents.c:4602
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
c000000000582aa0-c000000000582eac: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f350e)
Location: fs/ext4/extents.c:4602
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffe0002f350e-ffffffe0002f3792: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138a990)
Location: fs/ext4/extents.c:4602
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff8138a990-ffffffff8138aca6: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137b420)
Location: fs/ext4/extents.c:4602
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff8137b420-ffffffff8137b736: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813882f0)
Location: fs/ext4/extents.c:4602
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff813882f0-ffffffff81388606: ext4_alloc_file_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_alloc_file_blocks(struct file *file, ext4_lblk_t offset, ext4_lblk_t len, loff_t new_size, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139bff0)
Location: fs/ext4/extents.c:4602
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_zero_range
```
**Symbols:**

```
ffffffff8139bff0-ffffffff8139c306: ext4_alloc_file_blocks (STB_LOCAL)
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
