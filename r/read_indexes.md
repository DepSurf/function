# Function: <code>read_indexes</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81322270)
Location: fs/squashfs/file.c:173
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff81322270-ffffffff81322370: read_indexes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81338100)
Location: fs/squashfs/file.c:173
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff81338100-ffffffff81338200: read_indexes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff8134ce10)
Location: fs/squashfs/file.c:173
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8134ce10-ffffffff8134cf07: read_indexes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81371490)
Location: fs/squashfs/file.c:173
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff81371490-ffffffff81371587: read_indexes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:173
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8139fd50-ffffffff8139fe3e: read_indexes (STB_LOCAL)
ffffffff813a08cb-ffffffff813a0906: read_indexes.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:173
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813b8ae0-ffffffff813b8bce: read_indexes (STB_LOCAL)
ffffffff813b964d-ffffffff813b9688: read_indexes.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813e3300-ffffffff813e33d5: read_indexes (STB_LOCAL)
ffffffff813e3ef2-ffffffff813e3f2d: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813fd330-ffffffff813fd405: read_indexes (STB_LOCAL)
ffffffff813fdf43-ffffffff813fdf7e: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
```
**Symbols:**

```
ffffffff8144ade0-ffffffff8144aeb5: read_indexes (STB_LOCAL)
ffffffff8144b900-ffffffff8144b93b: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
```
**Symbols:**

```
ffffffff814674c0-ffffffff81467595: read_indexes (STB_LOCAL)
ffffffff81bed452-ffffffff81bed48d: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8146caa0-ffffffff8146cb70: read_indexes (STB_LOCAL)
ffffffff81bdf536-ffffffff81bdf571: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff814c3340-ffffffff814c3410: read_indexes (STB_LOCAL)
ffffffff81ccef83-ffffffff81ccefbe: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_read_folio
```
**Symbols:**

```
ffffffff8154def0-ffffffff8154dfcf: read_indexes (STB_LOCAL)
ffffffff81e81fd3-ffffffff81e8200e: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff815ee1e0)
Location: fs/squashfs/file.c:161
Inline: False
Direct callers:
  - fs/squashfs/file.c:read_blocklist
  - fs/squashfs/file.c:fill_meta_index
```
**Symbols:**

```
ffffffff815ee1e0-ffffffff815ee2e8: read_indexes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81626160)
Location: fs/squashfs/file.c:161
Inline: False
Direct callers:
  - fs/squashfs/file.c:read_blocklist
  - fs/squashfs/file.c:fill_meta_index
```
**Symbols:**

```
ffffffff81626160-ffffffff81626268: read_indexes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff8165f2a0)
Location: fs/squashfs/file.c:161
Inline: False
Direct callers:
  - fs/squashfs/file.c:read_blocklist
  - fs/squashfs/file.c:fill_meta_index
```
**Symbols:**

```
ffffffff8165f2a0-ffffffff8165f3d7: read_indexes (STB_LOCAL)
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
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffff8000104db380)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffff8000104db380-ffff8000104db48c: read_indexes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (c069ca34)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
c069ca34-c069cb7c: read_indexes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (c000000000616270)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
c000000000616270-c000000000616448: read_indexes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffe000350110)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffe000350110-ffffffe000350210: read_indexes (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813f5910-ffffffff813f59e5: read_indexes (STB_LOCAL)
ffffffff813f6523-ffffffff813f655e: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813e6390-ffffffff813e6465: read_indexes (STB_LOCAL)
ffffffff813e6fa3-ffffffff813e6fde: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813f2c90-ffffffff813f2d65: read_indexes (STB_LOCAL)
ffffffff813f38a3-ffffffff813f38de: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long long int read_indexes(struct super_block *sb, int n, u64 *start_block, int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:160
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff81408880-ffffffff81408955: read_indexes (STB_LOCAL)
ffffffff814094d1-ffffffff8140950c: read_indexes.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
