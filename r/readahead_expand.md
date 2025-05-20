# Function: <code>readahead_expand</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void readahead_expand(struct readahead_control *ractl, loff_t new_start, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126b920)
Location: mm/readahead.c:660
Inline: False
```
**Symbols:**

```
ffffffff8126b920-ffffffff8126bb29: readahead_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void readahead_expand(struct readahead_control *ractl, loff_t new_start, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812a85f0)
Location: mm/readahead.c:662
Inline: False
```
**Symbols:**

```
ffffffff812a85f0-ffffffff812a87f3: readahead_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void readahead_expand(struct readahead_control *ractl, loff_t new_start, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff813018c0)
Location: mm/readahead.c:781
Inline: False
```
**Symbols:**

```
ffffffff813018c0-ffffffff81301acb: readahead_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void readahead_expand(struct readahead_control *ractl, loff_t new_start, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/readahead.c (0)
Location: mm/readahead.c:791
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
```
**Symbols:**

```
ffffffff820624ed-ffffffff82062501: readahead_expand.cold (STB_LOCAL)
ffffffff8136bf90-ffffffff8136c213: readahead_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void readahead_expand(struct readahead_control *ractl, loff_t new_start, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/readahead.c (0)
Location: mm/readahead.c:790
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
```
**Symbols:**

```
ffffffff820e1cc8-ffffffff820e1cf0: readahead_expand.cold (STB_LOCAL)
ffffffff8139e210-ffffffff8139e42a: readahead_expand (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void readahead_expand(struct readahead_control *ractl, loff_t new_start, size_t new_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/readahead.c (0)
Location: mm/readahead.c:776
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readahead
```
**Symbols:**

```
ffffffff821be6ed-ffffffff821be715: readahead_expand.cold (STB_LOCAL)
ffffffff813c7eb0-ffffffff813c80cc: readahead_expand (STB_GLOBAL)
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
