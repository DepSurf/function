# Function: <code>squashfs_read_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff81324e77)
Location: fs/squashfs/file_direct.c:140
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff8133acd1)
Location: fs/squashfs/file_direct.c:140
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff8134f90c)
Location: fs/squashfs/file_direct.c:140
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff81373fba)
Location: fs/squashfs/file_direct.c:140
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff813a2a65)
Location: fs/squashfs/file_direct.c:146
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff813bb84d)
Location: fs/squashfs/file_direct.c:146
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff813e60ed)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff81400150)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int squashfs_read_cache(struct page *target_page, u64 block, int bsize, int pages, struct page **page, int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:144
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff8144d9b0-ffffffff8144dadd: squashfs_read_cache (STB_LOCAL)
ffffffff8144df6d-ffffffff8144df81: squashfs_read_cache.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int squashfs_read_cache(struct page *target_page, u64 block, int bsize, int pages, struct page **page, int bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:144
Inline: False
Direct callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
**Symbols:**

```
ffffffff81469f70-ffffffff8146a09a: squashfs_read_cache (STB_LOCAL)
ffffffff81bed5f5-ffffffff81bed609: squashfs_read_cache.cold (STB_LOCAL)
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
In fs/squashfs/file_direct.c (ffffffff8146f807)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
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
In fs/squashfs/file_direct.c (ffffffff814c6271)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
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
In fs/squashfs/file_direct.c (ffffffff8155122f)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffff8000104de178)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (c069fdac)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (c000000000619e70)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffe000352b56)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff813f8730)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff813e91b0)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff813f5ab0)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff8140b700)
Location: fs/squashfs/file_direct.c:144
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:squashfs_readpage_block
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
