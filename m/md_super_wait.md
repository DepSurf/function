# Function: <code>md_super_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff816939a0)
Location: drivers/md/md.c:754
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff816939a0-ffffffff81693a2d: md_super_wait.part.50 (STB_LOCAL)
ffffffff81697a80-ffffffff81697aa7: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff816f8408)
Location: drivers/md/md.c:752
Inline: True
Inline callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff816f44b0-ffffffff816f453d: md_super_wait.part.50 (STB_LOCAL)
ffffffff816f8560-ffffffff816f8587: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81727ff0)
Location: drivers/md/md.c:779
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff81727ff0-ffffffff81728091: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81740830)
Location: drivers/md/md.c:791
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/bitmap.c:write_page
```
**Symbols:**

```
ffffffff81740830-ffffffff817408d1: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b2900)
Location: drivers/md/md.c:826
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff817b2900-ffffffff817b29a1: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f9ad0)
Location: drivers/md/md.c:841
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff817f9ad0-ffffffff817f9b72: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81825b40)
Location: drivers/md/md.c:834
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81825b40-ffffffff81825be2: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81867f60)
Location: drivers/md/md.c:895
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81867f60-ffffffff81868002: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81899cf0)
Location: drivers/md/md.c:907
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81899cf0-ffffffff81899d92: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81969980)
Location: drivers/md/md.c:1033
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81969980-ffffffff81969a22: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81970500)
Location: drivers/md/md.c:1022
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81970500-ffffffff819705a2: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81954450)
Location: drivers/md/md.c:981
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81954450-ffffffff819544f2: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f9a50)
Location: drivers/md/md.c:982
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff819f9a50-ffffffff819f9af2: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b60fb0)
Location: drivers/md/md.c:986
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81b60fb0-ffffffff81b6108b: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfb570)
Location: drivers/md/md.c:977
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81cfb570-ffffffff81cfb64b: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d62720)
Location: drivers/md/md.c:953
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff81d62720-ffffffff81d627fb: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e19670)
Location: drivers/md/md.c:1065
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:md_bitmap_flush
  - drivers/md/md-bitmap.c:write_sb_page
```
**Symbols:**

```
ffffffff81e19670-ffffffff81e1974b: md_super_wait (STB_GLOBAL)
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
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aedfc0)
Location: drivers/md/md.c:907
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffff800010aedfc0-ffff800010aee0a4: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bcf1f4)
Location: drivers/md/md.c:907
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
c0bcf1f4-c0bcf2b0: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd9270)
Location: drivers/md/md.c:907
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:md_bitmap_wait_writes
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
c000000000bd9270-c000000000bd93a4: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e273c)
Location: drivers/md/md.c:907
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffe0006e273c-ffffffe0006e27c8: md_super_wait (STB_GLOBAL)
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
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8183fb70)
Location: drivers/md/md.c:907
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff8183fb70-ffffffff8183fc12: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818071d0)
Location: drivers/md/md.c:907
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff818071d0-ffffffff81807272: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8188f1a0)
Location: drivers/md/md.c:907
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff8188f1a0-ffffffff8188f242: md_super_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int md_super_wait(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818aada0)
Location: drivers/md/md.c:907
Inline: False
Direct callers:
  - drivers/md/md.c:super_1_rdev_size_change
  - drivers/md/md.c:super_90_rdev_size_change
  - drivers/md/md-bitmap.c:write_page
```
**Symbols:**

```
ffffffff818aada0-ffffffff818aae3d: md_super_wait (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
