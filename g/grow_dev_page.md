# Function: <code>grow_dev_page</code>

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
In fs/buffer.c (ffffffff81243c64)
Location: fs/buffer.c:992
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
In fs/buffer.c (ffffffff8126ca19)
Location: fs/buffer.c:985
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
In fs/buffer.c (ffffffff8127fce5)
Location: fs/buffer.c:986
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff8128d28e)
Location: fs/buffer.c:983
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff812afdce)
Location: fs/buffer.c:949
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff812d8073)
Location: fs/buffer.c:920
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff812ed0e3)
Location: fs/buffer.c:928
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff8130e89c)
Location: fs/buffer.c:929
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff813218b8)
Location: fs/buffer.c:929
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int grow_dev_page(struct block_device *bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135bc50)
Location: fs/buffer.c:955
Inline: False
Direct callers:
  - fs/buffer.c:__getblk_slow
```
**Symbols:**

```
ffffffff8135bc50-ffffffff8135be20: grow_dev_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int grow_dev_page(struct block_device *bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136a1f0)
Location: fs/buffer.c:954
Inline: False
Direct callers:
  - fs/buffer.c:__getblk_slow
```
**Symbols:**

```
ffffffff8136a1f0-ffffffff8136a3bd: grow_dev_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int grow_dev_page(struct block_device *bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81370e10)
Location: fs/buffer.c:954
Inline: False
Direct callers:
  - fs/buffer.c:__getblk_gfp
```
**Symbols:**

```
ffffffff81370e10-ffffffff81370fd7: grow_dev_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int grow_dev_page(struct block_device *bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:929
Inline: False
Direct callers:
  - fs/buffer.c:__getblk_gfp
```
**Symbols:**

```
ffffffff813bfd70-ffffffff813bff71: grow_dev_page (STB_LOCAL)
ffffffff81cc4701-ffffffff81cc4731: grow_dev_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int grow_dev_page(struct block_device *bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:926
Inline: False
Direct callers:
  - fs/buffer.c:__getblk_gfp
```
**Symbols:**

```
ffffffff81445680-ffffffff81445972: grow_dev_page (STB_LOCAL)
ffffffff81e76f81-ffffffff81e76fb1: grow_dev_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int grow_dev_page(struct block_device *bdev, sector_t block, long unsigned int index, int size, int sizebits, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:926
Inline: False
Direct callers:
  - fs/buffer.c:__getblk_gfp
```
**Symbols:**

```
ffffffff814d46f0-ffffffff814d49e2: grow_dev_page (STB_LOCAL)
ffffffff820690a5-ffffffff820690d5: grow_dev_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150c59e)
Location: fs/buffer.c:1043
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/buffer.c (ffff8000103da23c)
Location: fs/buffer.c:929
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (c05b37a0)
Location: fs/buffer.c:929
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_slow
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
In fs/buffer.c (c0000000004df25c)
Location: fs/buffer.c:929
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffe000292ffa)
Location: fs/buffer.c:929
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff81319e98)
Location: fs/buffer.c:929
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff8130aa38)
Location: fs/buffer.c:929
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff81317968)
Location: fs/buffer.c:929
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
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
In fs/buffer.c (ffffffff81329563)
Location: fs/buffer.c:929
Inline: True
Inline callers:
  - fs/buffer.c:__getblk_gfp
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
