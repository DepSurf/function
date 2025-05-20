# Function: <code>__bdev_dax_supported</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __bdev_dax_supported(struct super_block *sb, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163ce90)
Location: drivers/dax/super.c:72
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8163ce90-ffffffff8163cfe1: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __bdev_dax_supported(struct super_block *sb, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5ba0)
Location: drivers/dax/super.c:85
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff816a5ba0-ffffffff816a5d76: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1fd0)
Location: drivers/dax/super.c:85
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff816e1fd0-ffffffff816e22ce: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817053f0)
Location: drivers/dax/super.c:85
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff817053f0-ffffffff817056e6: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f3e0)
Location: drivers/dax/super.c:160
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8173f3e0-ffffffff8173f54d: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817635c0)
Location: drivers/dax/super.c:160
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff817635c0-ffffffff8176372d: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81823460)
Location: drivers/dax/super.c:160
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81823460-ffffffff818235cd: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81832190)
Location: drivers/dax/super.c:168
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81832190-ffffffff818322fa: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81815770)
Location: drivers/dax/super.c:168
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81815770-ffffffff818158da: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010963288)
Location: drivers/dax/super.c:160
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffff800010963288-ffff80001096340c: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a3a688)
Location: drivers/dax/super.c:160
Inline: False
```
**Symbols:**

```
c0a3a688-c0a3a8a8: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a19aa0)
Location: drivers/dax/super.c:160
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c000000000a19aa0-c000000000a19cd8: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d09d4)
Location: drivers/dax/super.c:160
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe0005d09d4-ffffffe0005d0b0c: __bdev_dax_supported (STB_GLOBAL)
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
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717cb0)
Location: drivers/dax/super.c:160
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81717cb0-ffffffff81717e1d: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816f01e0)
Location: drivers/dax/super.c:160
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff816f01e0-ffffffff816f034d: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756a80)
Location: drivers/dax/super.c:160
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81756a80-ffffffff81756bed: __bdev_dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __bdev_dax_supported(struct block_device *bdev, int blocksize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771ee0)
Location: drivers/dax/super.c:160
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81771ee0-ffffffff8177204d: __bdev_dax_supported (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct super_block *sb</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
