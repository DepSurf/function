# Function: <code>ext4_ext_remove_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c66f0)
Location: fs/ext4/extents.c:2799
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff812c66f0-ffffffff812c785f: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f5f50)
Location: fs/ext4/extents.c:2821
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
```
**Symbols:**

```
ffffffff812f5f50-ffffffff812f707c: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130bf00)
Location: fs/ext4/extents.c:2821
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
```
**Symbols:**

```
ffffffff8130bf00-ffffffff8130d08d: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812ea630)
Location: fs/ext4/extents.c:2822
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff812ea630-ffffffff812eb818: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130f0d0)
Location: fs/ext4/extents.c:2822
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8130f0d0-ffffffff813102c3: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133d890)
Location: fs/ext4/extents.c:2816
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8133d890-ffffffff8133e157: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81355b20)
Location: fs/ext4/extents.c:2871
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81355b20-ffffffff81356485: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2888
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8138268c-ffffffff813826b3: ext4_ext_remove_space.cold (STB_LOCAL)
ffffffff8137f4f0-ffffffff8137fe37: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81397c10)
Location: fs/ext4/extents.c:2934
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81397c10-ffffffff81398534: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e38d0)
Location: fs/ext4/extents.c:2768
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813e38d0-ffffffff813e41aa: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f5120)
Location: fs/ext4/extents.c:2767
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813f5120-ffffffff813f5999: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813fb460)
Location: fs/ext4/extents.c:2770
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813fb460-ffffffff813fbccc: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2808
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81cc9504-ffffffff81cc95bb: ext4_ext_remove_space.cold (STB_LOCAL)
ffffffff8144d820-ffffffff8144e0ba: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2807
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81e7c212-ffffffff81e7c2b9: ext4_ext_remove_space.cold (STB_LOCAL)
ffffffff814ca380-ffffffff814cacbb: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2813
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8206c863-ffffffff8206c90a: ext4_ext_remove_space.cold (STB_LOCAL)
ffffffff81562a20-ffffffff81563336: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2813
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff820ec640-ffffffff820ec6a1: ext4_ext_remove_space.cold (STB_LOCAL)
ffffffff8159a750-ffffffff8159b038: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents.c (0)
Location: fs/ext4/extents.c:2789
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff821c988a-ffffffff821c98eb: ext4_ext_remove_space.cold (STB_LOCAL)
ffffffff815d3590-ffffffff815d3e78: ext4_ext_remove_space (STB_GLOBAL)
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
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff80001046a818)
Location: fs/ext4/extents.c:2934
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffff80001046a818-ffff80001046b0f8: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c062b674)
Location: fs/ext4/extents.c:2934
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
c062b674-c062c080: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000589940)
Location: fs/ext4/extents.c:2934
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
c000000000589940-c00000000058a42c: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f80aa)
Location: fs/ext4/extents.c:2934
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffe0002f80aa-ffffffe0002f8822: ext4_ext_remove_space (STB_GLOBAL)
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
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813901f0)
Location: fs/ext4/extents.c:2934
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813901f0-ffffffff81390b14: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81380c80)
Location: fs/ext4/extents.c:2934
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff81380c80-ffffffff813815a4: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138db50)
Location: fs/ext4/extents.c:2934
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff8138db50-ffffffff8138e474: ext4_ext_remove_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_remove_space(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813a18f0)
Location: fs/ext4/extents.c:2934
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff813a18f0-ffffffff813a223d: ext4_ext_remove_space (STB_GLOBAL)
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
