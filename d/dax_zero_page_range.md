# Function: <code>dax_zero_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dax_zero_page_range(struct inode *inode, loff_t from, unsigned int length, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8125eac0)
Location: fs/dax.c:736
Inline: False
Direct callers:
  - fs/dax.c:dax_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff8125eac0-ffffffff8125ec16: dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dax_zero_page_range(struct inode *inode, loff_t from, unsigned int length, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81286a00)
Location: fs/dax.c:1204
Inline: False
Direct callers:
  - fs/dax.c:dax_truncate_page
  - fs/ext4/inode.c:ext4_block_zero_page_range
```
**Symbols:**

```
ffffffff81286a00-ffffffff81286ae4: dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dax_zero_page_range(struct dax_device *dax_dev, long unsigned int pgoff, size_t nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81822ab0)
Location: drivers/dax/super.c:351
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_zero
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
```
**Symbols:**

```
ffffffff81822ab0-ffffffff81822ae8: dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dax_zero_page_range(struct dax_device *dax_dev, long unsigned int pgoff, size_t nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff818317c0)
Location: drivers/dax/super.c:359
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_zero
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
```
**Symbols:**

```
ffffffff818317c0-ffffffff818317f8: dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dax_zero_page_range(struct dax_device *dax_dev, long unsigned int pgoff, size_t nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff818149f0)
Location: drivers/dax/super.c:359
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_zero
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
```
**Symbols:**

```
ffffffff818149f0-ffffffff81814a28: dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dax_zero_page_range(struct dax_device *dax_dev, long unsigned int pgoff, size_t nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f1b0)
Location: drivers/dax/super.c:351
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_zero
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
```
**Symbols:**

```
ffffffff8189f1b0-ffffffff8189f1e8: dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dax_zero_page_range(struct dax_device *dax_dev, long unsigned int pgoff, size_t nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e8ce0)
Location: drivers/dax/super.c:181
Inline: False
Direct callers:
  - fs/dax.c:dax_zero_range
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
```
**Symbols:**

```
ffffffff819e8ce0-ffffffff819e8d36: dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dax_zero_page_range(struct dax_device *dax_dev, long unsigned int pgoff, size_t nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65520)
Location: drivers/dax/super.c:203
Inline: False
Direct callers:
  - fs/dax.c:dax_zero_range
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
```
**Symbols:**

```
ffffffff81b65520-ffffffff81b65576: dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dax_zero_page_range(struct dax_device *dax_dev, long unsigned int pgoff, size_t nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb8b20)
Location: drivers/dax/super.c:203
Inline: False
Direct callers:
  - fs/dax.c:dax_zero_range
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
```
**Symbols:**

```
ffffffff81bb8b20-ffffffff81bb8b93: dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dax_zero_page_range(struct dax_device *dax_dev, long unsigned int pgoff, size_t nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d180)
Location: drivers/dax/super.c:203
Inline: False
Direct callers:
  - fs/dax.c:dax_zero_range
  - drivers/md/dm-linear.c:linear_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
```
**Symbols:**

```
ffffffff81c0d180-ffffffff81c0d1f3: dax_zero_page_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
