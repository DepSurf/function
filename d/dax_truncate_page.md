# Function: <code>dax_truncate_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dax_truncate_page(struct inode *inode, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8125ec20)
Location: fs/dax.c:782
Inline: False
```
**Symbols:**

```
ffffffff8125ec20-ffffffff8125ec42: dax_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dax_truncate_page(struct inode *inode, loff_t from, get_block_t *get_block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81286af0)
Location: fs/dax.c:1238
Inline: False
```
**Symbols:**

```
ffffffff81286af0-ffffffff81286b12: dax_truncate_page (STB_GLOBAL)
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dax_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1115
Inline: False
```
**Symbols:**

```
ffffffff81e781f2-ffffffff81e7821c: dax_truncate_page.cold (STB_LOCAL)
ffffffff81467d90-ffffffff81467df8: dax_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dax_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1387
Inline: False
```
**Symbols:**

```
ffffffff8206a183-ffffffff8206a1ad: dax_truncate_page.cold (STB_LOCAL)
ffffffff814f8df0-ffffffff814f8e58: dax_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dax_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1420
Inline: False
```
**Symbols:**

```
ffffffff820ea168-ffffffff820ea192: dax_truncate_page.cold (STB_LOCAL)
ffffffff81530150-ffffffff815301b8: dax_truncate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dax_truncate_page(struct inode *inode, loff_t pos, bool *did_zero, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:1406
Inline: False
```
**Symbols:**

```
ffffffff821c6c0d-ffffffff821c6c37: dax_truncate_page.cold (STB_LOCAL)
ffffffff81565030-ffffffff81565098: dax_truncate_page (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
