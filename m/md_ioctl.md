# Function: <code>md_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81699af0)
Location: drivers/md/md.c:6688
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff81699af0-ffffffff8169b7c2: md_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816faba0)
Location: drivers/md/md.c:6728
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff816faba0-ffffffff816fc8fa: md_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8172c530)
Location: drivers/md/md.c:6783
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff8172c530-ffffffff8172e4c6: md_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81744e50)
Location: drivers/md/md.c:6999
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff81744e50-ffffffff81746d2a: md_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b7020)
Location: drivers/md/md.c:7054
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff817b7020-ffffffff817b8f9b: md_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7123
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff817fe520-ffffffff817ffd92: md_ioctl (STB_LOCAL)
ffffffff81801101-ffffffff818018f7: md_ioctl.cold.93 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7110
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff8182a6c0-ffffffff8182bf36: md_ioctl (STB_LOCAL)
ffffffff8182d2f5-ffffffff8182db08: md_ioctl.cold.92 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7172
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff8186cba0-ffffffff8186e459: md_ioctl (STB_LOCAL)
ffffffff8186fc79-ffffffff8187015a: md_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7276
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff8189e990-ffffffff818a0259: md_ioctl (STB_LOCAL)
ffffffff818a1a7e-ffffffff818a1f5d: md_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7474
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff8196ed20-ffffffff8196fb1f: md_ioctl (STB_LOCAL)
ffffffff81971a1f-ffffffff81971b55: md_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7508
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff81975cd0-ffffffff81976736: md_ioctl (STB_LOCAL)
ffffffff81c27612-ffffffff81c276b7: md_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7463
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff81959d10-ffffffff8195a93d: md_ioctl (STB_LOCAL)
ffffffff81c197c5-ffffffff81c19892: md_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7476
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff819ff4e0-ffffffff81a0010c: md_ioctl (STB_LOCAL)
ffffffff81d28e05-ffffffff81d28ed2: md_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7473
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff81b669c0-ffffffff81b67640: md_ioctl (STB_LOCAL)
ffffffff81ef4ec6-ffffffff81ef4fc5: md_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d02340)
Location: drivers/md/md.c:7493
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff81d02340-ffffffff81d02d03: md_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d6b470)
Location: drivers/md/md.c:7496
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff81d6b470-ffffffff81d6bd64: md_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, blk_mode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e21490)
Location: drivers/md/md.c:7621
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff81e21490-ffffffff81e21ecd: md_ioctl (STB_LOCAL)
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
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010af33a8)
Location: drivers/md/md.c:7276
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffff800010af33a8-ffff800010af5080: md_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bd4974)
Location: drivers/md/md.c:7276
Inline: False
```
**Symbols:**

```
c0bd4974-c0bd695c: md_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000be02d0)
Location: drivers/md/md.c:7276
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
c000000000be02d0-c000000000be281c: md_ioctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e6da2)
Location: drivers/md/md.c:7276
Inline: False
```
**Symbols:**

```
ffffffe0006e6da2-ffffffe0006e87f4: md_ioctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7276
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff81844810-ffffffff818460d9: md_ioctl (STB_LOCAL)
ffffffff818478fe-ffffffff81847ddd: md_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7276
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff8180be70-ffffffff8180d739: md_ioctl (STB_LOCAL)
ffffffff8180ef5e-ffffffff8180f43d: md_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7276
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff81893e40-ffffffff81895709: md_ioctl (STB_LOCAL)
ffffffff81896f2e-ffffffff8189740d: md_ioctl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int md_ioctl(struct block_device *bdev, fmode_t mode, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7276
Inline: False
Direct callers:
  - drivers/md/md.c:md_compat_ioctl
  - drivers/md/md.c:md_compat_ioctl
```
**Symbols:**

```
ffffffff818afa30-ffffffff818b171f: md_ioctl (STB_LOCAL)
ffffffff818b2f0e-ffffffff818b34e6: md_ioctl.cold (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>fmode_t mode</code> ➡️ <code>blk_mode_t mode</code>
</li>
</ul>
</details>
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
