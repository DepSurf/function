# Function: <code>strict_blocks_to_sectors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168cba0)
Location: drivers/md/md.c:2930
Inline: False
Direct callers:
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:rdev_size_store
  - drivers/md/md.c:size_store
```
**Symbols:**

```
ffffffff8168cba0-ffffffff8168cc05: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816ee270)
Location: drivers/md/md.c:2938
Inline: False
Direct callers:
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff816ee270-ffffffff816ee2d5: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8171f9f0)
Location: drivers/md/md.c:2983
Inline: False
Direct callers:
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff8171f9f0-ffffffff8171fa55: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817375f0)
Location: drivers/md/md.c:3045
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff817375f0-ffffffff81737655: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817a9630)
Location: drivers/md/md.c:3100
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff817a9630-ffffffff817a9695: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f12e0)
Location: drivers/md/md.c:3116
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff817f12e0-ffffffff817f1345: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8181d1e0)
Location: drivers/md/md.c:3107
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff8181d1e0-ffffffff8181d245: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8185f420)
Location: drivers/md/md.c:3174
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff8185f420-ffffffff8185f485: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81891000)
Location: drivers/md/md.c:3228
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff81891000-ffffffff81891065: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196b003)
Location: drivers/md/md.c:3353
Inline: True
Inline callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81971b83)
Location: drivers/md/md.c:3374
Inline: True
Inline callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81955c73)
Location: drivers/md/md.c:3338
Inline: True
Inline callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819fb2a3)
Location: drivers/md/md.c:3357
Inline: True
Inline callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b58c2c)
Location: drivers/md/md.c:3348
Inline: True
Inline callers:
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf19cc)
Location: drivers/md/md.c:3327
Inline: True
Inline callers:
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
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
In drivers/md/md.c (ffffffff81d66a0c)
Location: drivers/md/md.c:3304
Inline: True
Inline callers:
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1e8cc)
Location: drivers/md/md.c:3426
Inline: True
Inline callers:
  - drivers/md/md.c:array_size_store
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
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
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae3510)
Location: drivers/md/md.c:3228
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffff800010ae3510-ffff800010ae3598: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc4b3c)
Location: drivers/md/md.c:3228
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
c0bc4b3c-c0bc4bcc: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bcb910)
Location: drivers/md/md.c:3228
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
c000000000bcb910-c000000000bcb9b0: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006d9d74)
Location: drivers/md/md.c:3228
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffe0006d9d74-ffffffe0006d9dc2: strict_blocks_to_sectors (STB_LOCAL)
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
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81836e80)
Location: drivers/md/md.c:3228
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff81836e80-ffffffff81836ee5: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817fe4f0)
Location: drivers/md/md.c:3228
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff817fe4f0-ffffffff817fe555: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818864b0)
Location: drivers/md/md.c:3228
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff818864b0-ffffffff81886515: strict_blocks_to_sectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int strict_blocks_to_sectors(const char *buf, sector_t *sectors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a2410)
Location: drivers/md/md.c:3228
Inline: False
Direct callers:
  - drivers/md/md.c:size_store
  - drivers/md/md.c:rdev_size_store
```
**Symbols:**

```
ffffffff818a2410-ffffffff818a2475: strict_blocks_to_sectors (STB_LOCAL)
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
