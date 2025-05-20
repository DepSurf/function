# Function: <code>block_truncate_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81245ab0)
Location: fs/buffer.c:2809
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff81245ab0-ffffffff81245d70: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126e850)
Location: fs/buffer.c:2865
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff8126e850-ffffffff8126eb55: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81281a70)
Location: fs/buffer.c:2906
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff81281a70-ffffffff81281d6c: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128f230)
Location: fs/buffer.c:2900
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff8128f230-ffffffff8128f4c0: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b1e30)
Location: fs/buffer.c:2860
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff812b1e30-ffffffff812b20f6: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d9d80)
Location: fs/buffer.c:2831
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff812d9d80-ffffffff812da062: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ef270)
Location: fs/buffer.c:2843
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff812ef270-ffffffff812ef550: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff81311d9f-ffffffff81311dbe: block_truncate_page.cold (STB_LOCAL)
ffffffff81310ac0-ffffffff81310d99: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81323aa0)
Location: fs/buffer.c:2840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff81323aa0-ffffffff81323d80: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135d150)
Location: fs/buffer.c:2884
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff8135d150-ffffffff8135d428: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136a640)
Location: fs/buffer.c:2873
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff8136a640-ffffffff8136a8c5: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813711a0)
Location: fs/buffer.c:2894
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff813711a0-ffffffff8137143b: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2873
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff81cc469e-ffffffff81cc4701: block_truncate_page.cold (STB_LOCAL)
ffffffff813bfac0-ffffffff813bfd6c: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2861
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff81e77103-ffffffff81e77156: block_truncate_page.cold (STB_LOCAL)
ffffffff81446750-ffffffff81446a6b: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2525
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff820691df-ffffffff82069242: block_truncate_page.cold (STB_LOCAL)
ffffffff814d5870-ffffffff814d5b35: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2666
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff820e8bb6-ffffffff820e8c31: block_truncate_page.cold (STB_LOCAL)
ffffffff8150c0f0-ffffffff8150c2f7: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:2632
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff821c5852-ffffffff821c58eb: block_truncate_page.cold (STB_LOCAL)
ffffffff81540cf0-ffffffff81540f04: block_truncate_page (STB_GLOBAL)
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
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103dcdf0)
Location: fs/buffer.c:2840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffff8000103dcdf0-ffff8000103dd118: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b6300)
Location: fs/buffer.c:2840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
c05b6300-c05b661c: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004e2470)
Location: fs/buffer.c:2840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
c0000000004e2470-c0000000004e2888: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe00029500c)
Location: fs/buffer.c:2840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffe00029500c-ffffffe000295288: block_truncate_page (STB_GLOBAL)
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
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131c080)
Location: fs/buffer.c:2840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff8131c080-ffffffff8131c360: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130cc20)
Location: fs/buffer.c:2840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff8130cc20-ffffffff8130cf00: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81319b50)
Location: fs/buffer.c:2840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff81319b50-ffffffff81319e30: block_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int block_truncate_page(struct address_space *mapping, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8132b810)
Location: fs/buffer.c:2840
Inline: False
Direct callers:
  - fs/buffer.c:nobh_truncate_page
  - fs/fat/inode.c:fat_block_truncate_page
```
**Symbols:**

```
ffffffff8132b810-ffffffff8132bb08: block_truncate_page (STB_GLOBAL)
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
