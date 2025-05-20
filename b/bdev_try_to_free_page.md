# Function: <code>bdev_try_to_free_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ac990)
Location: fs/ext4/super.c:1059
Inline: False
```
**Symbols:**

```
ffffffff812ac990-ffffffff812aca0c: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e1050)
Location: fs/ext4/super.c:1084
Inline: False
```
**Symbols:**

```
ffffffff812e1050-ffffffff812e10cc: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812f6b80)
Location: fs/ext4/super.c:1089
Inline: False
```
**Symbols:**

```
ffffffff812f6b80-ffffffff812f6bfc: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8132b490)
Location: fs/ext4/super.c:1131
Inline: False
```
**Symbols:**

```
ffffffff8132b490-ffffffff8132b4db: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8134f8f0)
Location: fs/ext4/super.c:1132
Inline: False
```
**Symbols:**

```
ffffffff8134f8f0-ffffffff8134f939: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8137dd60)
Location: fs/ext4/super.c:1171
Inline: False
```
**Symbols:**

```
ffffffff8137dd60-ffffffff8137dda9: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81396610)
Location: fs/ext4/super.c:1226
Inline: False
```
**Symbols:**

```
ffffffff81396610-ffffffff81396659: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:1239
Inline: False
```
**Symbols:**

```
ffffffff813c0600-ffffffff813c065b: bdev_try_to_free_page (STB_LOCAL)
ffffffff813ce5bc-ffffffff813ce5dd: bdev_try_to_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d98d0)
Location: fs/ext4/super.c:1248
Inline: False
```
**Symbols:**

```
ffffffff813d98d0-ffffffff813d9917: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81425c80)
Location: fs/ext4/super.c:1283
Inline: False
```
**Symbols:**

```
ffffffff81425c80-ffffffff81425cc7: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143d370)
Location: fs/ext4/super.c:1449
Inline: False
```
**Symbols:**

```
ffffffff8143d370-ffffffff8143d3b4: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814431b0)
Location: fs/ext4/super.c:1458
Inline: False
```
**Symbols:**

```
ffffffff814431b0-ffffffff814431f4: bdev_try_to_free_page (STB_LOCAL)
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
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104ad088)
Location: fs/ext4/super.c:1248
Inline: False
```
**Symbols:**

```
ffff8000104ad088-ffff8000104ad110: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0675774)
Location: fs/ext4/super.c:1248
Inline: False
```
**Symbols:**

```
c0675774-c06757f8: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005e5500)
Location: fs/ext4/super.c:1248
Inline: False
```
**Symbols:**

```
c0000000005e5500-c0000000005e558c: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe0003303d4)
Location: fs/ext4/super.c:1248
Inline: False
```
**Symbols:**

```
ffffffe0003303d4-ffffffe000330446: bdev_try_to_free_page (STB_LOCAL)
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
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d1eb0)
Location: fs/ext4/super.c:1248
Inline: False
```
**Symbols:**

```
ffffffff813d1eb0-ffffffff813d1ef7: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c2930)
Location: fs/ext4/super.c:1248
Inline: False
```
**Symbols:**

```
ffffffff813c2930-ffffffff813c2977: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cf340)
Location: fs/ext4/super.c:1248
Inline: False
```
**Symbols:**

```
ffffffff813cf340-ffffffff813cf387: bdev_try_to_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bdev_try_to_free_page(struct super_block *sb, struct page *page, gfp_t wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e4680)
Location: fs/ext4/super.c:1248
Inline: False
```
**Symbols:**

```
ffffffff813e4680-ffffffff813e46c7: bdev_try_to_free_page (STB_LOCAL)
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
