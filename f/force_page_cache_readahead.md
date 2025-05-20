# Function: <code>force_page_cache_readahead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8119c2c0)
Location: mm/readahead.c:210
Inline: False
Direct callers:
  - mm/readahead.c:SyS_readahead
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff8119c2c0-ffffffff8119c3b6: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811b14c0)
Location: mm/readahead.c:209
Inline: False
Direct callers:
  - mm/readahead.c:SyS_readahead
  - mm/fadvise.c:SyS_fadvise64
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811b14c0-ffffffff811b15b6: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811c1af0)
Location: mm/readahead.c:209
Inline: False
Direct callers:
  - mm/readahead.c:SyS_readahead
  - mm/fadvise.c:SyS_fadvise64
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811c1af0-ffffffff811c1bf4: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811c9d90)
Location: mm/readahead.c:209
Inline: False
Direct callers:
  - mm/readahead.c:SyS_readahead
  - mm/fadvise.c:SyS_fadvise64
  - mm/madvise.c:madvise_willneed
```
**Symbols:**

```
ffffffff811c9d90-ffffffff811c9e9a: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff811dec60)
Location: mm/readahead.c:209
Inline: False
Direct callers:
  - mm/readahead.c:SyS_readahead
  - mm/fadvise.c:SyS_fadvise64
  - mm/madvise.c:madvise_willneed
```
**Symbols:**

```
ffffffff811dec60-ffffffff811ded6a: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812003e0)
Location: mm/readahead.c:219
Inline: False
Direct callers:
  - mm/readahead.c:ksys_readahead
  - mm/fadvise.c:ksys_fadvise64_64
  - mm/madvise.c:madvise_willneed
```
**Symbols:**

```
ffffffff812003e0-ffffffff812004d0: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81212d10)
Location: mm/readahead.c:219
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
  - mm/madvise.c:madvise_willneed
```
**Symbols:**

```
ffffffff81212d10-ffffffff81212e00: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81222700)
Location: mm/readahead.c:222
Inline: False
Direct callers:
  - mm/fadvise.c:vfs_fadvise
  - mm/madvise.c:madvise_willneed
```
**Symbols:**

```
ffffffff81222700-ffffffff81222806: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812301b0)
Location: mm/readahead.c:222
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffffffff812301b0-ffffffff812302b6: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int index, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8125d430)
Location: mm/readahead.c:281
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffffffff8125d430-ffffffff8125d569: force_page_cache_readahead (STB_GLOBAL)
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
In mm/fadvise.c (ffffffff81262525)
Location: mm/internal.h:56
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
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
In mm/fadvise.c (ffffffff81266fae)
Location: mm/internal.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
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
In mm/fadvise.c (ffffffff812a39f5)
Location: mm/internal.h:55
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
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
In mm/fadvise.c (ffffffff812fb9e1)
Location: mm/internal.h:100
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
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
In mm/fadvise.c (ffffffff81365a12)
Location: mm/internal.h:102
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
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
In mm/fadvise.c (ffffffff81397eb9)
Location: mm/internal.h:120
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
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
In mm/fadvise.c (ffffffff813c1ce9)
Location: mm/internal.h:126
Inline: True
Inline callers:
  - mm/fadvise.c:generic_fadvise
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
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffff8000102bfa18)
Location: mm/readahead.c:222
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffff8000102bfa18-ffff8000102bfb1c: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c04eb4d8)
Location: mm/readahead.c:222
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
c04eb4d8-c04eb5f0: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c000000000378980)
Location: mm/readahead.c:222
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
c000000000378980-c000000000378b34: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffe0001e1a4c)
Location: mm/readahead.c:222
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffffffe0001e1a4c-ffffffe0001e1b1a: force_page_cache_readahead (STB_GLOBAL)
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
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81228800)
Location: mm/readahead.c:222
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffffffff81228800-ffffffff81228906: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8121b940)
Location: mm/readahead.c:222
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffffffff8121b940-ffffffff8121ba46: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812265a0)
Location: mm/readahead.c:222
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffffffff812265a0-ffffffff812266a6: force_page_cache_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int force_page_cache_readahead(struct address_space *mapping, struct file *filp, long unsigned int offset, long unsigned int nr_to_read);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812358d0)
Location: mm/readahead.c:222
Inline: False
Direct callers:
  - mm/fadvise.c:generic_fadvise
```
**Symbols:**

```
ffffffff812358d0-ffffffff812359d6: force_page_cache_readahead (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int index</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int offset</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
