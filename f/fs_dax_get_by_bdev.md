# Function: <code>fs_dax_get_by_bdev</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5b60)
Location: drivers/dax/super.c:66
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff816a5b60-ffffffff816a5b93: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1f90)
Location: drivers/dax/super.c:66
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff816e1f90-ffffffff816e1fc4: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817053b0)
Location: drivers/dax/super.c:66
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff817053b0-ffffffff817053e1: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f250)
Location: drivers/dax/super.c:60
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8173f250-ffffffff8173f281: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81763430)
Location: drivers/dax/super.c:60
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81763430-ffffffff81763461: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff818232d0)
Location: drivers/dax/super.c:60
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff818232d0-ffffffff81823301: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81832010)
Location: drivers/dax/super.c:61
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81832010-ffffffff8183203e: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81815740)
Location: drivers/dax/super.c:61
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81815740-ffffffff8181576e: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189fee0)
Location: drivers/dax/super.c:115
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8189fee0-ffffffff8189ff0e: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev, u64 *start_off);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (0)
Location: drivers/dax/super.c:75
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81ed471e-ffffffff81ed4734: fs_dax_get_by_bdev.cold (STB_LOCAL)
ffffffff819e93e0-ffffffff819e9498: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev, u64 *start_off, void *holder, const struct dax_holder_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65c20)
Location: drivers/dax/super.c:81
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81b65c20-ffffffff81b65d43: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev, u64 *start_off, void *holder, const struct dax_holder_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb9240)
Location: drivers/dax/super.c:81
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81bb9240-ffffffff81bb9360: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev, u64 *start_off, void *holder, const struct dax_holder_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d8a0)
Location: drivers/dax/super.c:81
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81c0d8a0-ffffffff81c0d9bd: fs_dax_get_by_bdev (STB_GLOBAL)
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
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010963170)
Location: drivers/dax/super.c:60
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffff800010963170-ffff8000109631c0: fs_dax_get_by_bdev (STB_GLOBAL)
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
In fs/ext4/super.c (0)
Location: include/linux/dax.h:172
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a19800)
Location: drivers/dax/super.c:60
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c000000000a19800-c000000000a19838: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d0832)
Location: drivers/dax/super.c:60
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe0005d0832-ffffffe0005d086c: fs_dax_get_by_bdev (STB_GLOBAL)
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
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717b20)
Location: drivers/dax/super.c:60
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81717b20-ffffffff81717b51: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816f0050)
Location: drivers/dax/super.c:60
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff816f0050-ffffffff816f0081: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817568f0)
Location: drivers/dax/super.c:60
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff817568f0-ffffffff81756921: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dax_device *fs_dax_get_by_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771d50)
Location: drivers/dax/super.c:60
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81771d50-ffffffff81771d81: fs_dax_get_by_bdev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 *start_off</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *holder</code>
</li>
<li>
<b>Param added. </b>
<code>const struct dax_holder_operations *ops</code>
</li>
</ul>
</details>
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
