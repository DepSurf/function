# Function: <code>fsverity_get_descriptor</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fsverity_get_descriptor(struct inode *inode, struct fsverity_descriptor **desc_ret, size_t *desc_size_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:266
Inline: False
Direct callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff81bdd6dc-ffffffff81bdd7f8: fsverity_get_descriptor.cold (STB_LOCAL)
ffffffff813b0290-ffffffff813b03a0: fsverity_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fsverity_get_descriptor(struct inode *inode, struct fsverity_descriptor **desc_ret, size_t *desc_size_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:266
Inline: False
Direct callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff81cc702c-ffffffff81cc7148: fsverity_get_descriptor.cold (STB_LOCAL)
ffffffff813ffe80-ffffffff813fff90: fsverity_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fsverity_get_descriptor(struct inode *inode, struct fsverity_descriptor **desc_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:265
Inline: False
Direct callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff81e79594-ffffffff81e796b0: fsverity_get_descriptor.cold (STB_LOCAL)
ffffffff81473c80-ffffffff81473d96: fsverity_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fsverity_get_descriptor(struct inode *inode, struct fsverity_descriptor **desc_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81505d50)
Location: fs/verity/open.c:265
Inline: False
Direct callers:
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff81505d50-ffffffff81505fb8: fsverity_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fsverity_get_descriptor(struct inode *inode, struct fsverity_descriptor **desc_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff8153d070)
Location: fs/verity/open.c:325
Inline: False
Direct callers:
  - fs/verity/open.c:__fsverity_file_open
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff8153d070-ffffffff8153d303: fsverity_get_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fsverity_get_descriptor(struct inode *inode, struct fsverity_descriptor **desc_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff815724d0)
Location: fs/verity/open.c:325
Inline: False
Direct callers:
  - fs/verity/open.c:__fsverity_file_open
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
  - fs/verity/read_metadata.c:fsverity_ioctl_read_metadata
```
**Symbols:**

```
ffffffff815724d0-ffffffff81572763: fsverity_get_descriptor (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t *desc_size_ret</code>
</li>
</ul>
</details>
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
