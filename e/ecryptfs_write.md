# Function: <code>ecryptfs_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff813049b0)
Location: fs/ecryptfs/read_write.c:105
Inline: False
```
**Symbols:**

```
ffffffff813049b0-ffffffff81304d24: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81338ad0)
Location: fs/ecryptfs/read_write.c:105
Inline: False
```
**Symbols:**

```
ffffffff81338ad0-ffffffff81338e8b: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff8134e870)
Location: fs/ecryptfs/read_write.c:105
Inline: False
```
**Symbols:**

```
ffffffff8134e870-ffffffff8134ec22: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81363390)
Location: fs/ecryptfs/read_write.c:107
Inline: False
```
**Symbols:**

```
ffffffff81363390-ffffffff813636f7: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81388070)
Location: fs/ecryptfs/read_write.c:107
Inline: False
```
**Symbols:**

```
ffffffff81388070-ffffffff81388420: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:107
Inline: False
```
**Symbols:**

```
ffffffff813b7309-ffffffff813b7362: ecryptfs_write.cold.7 (STB_LOCAL)
ffffffff813b6ed0-ffffffff813b721d: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:107
Inline: False
```
**Symbols:**

```
ffffffff813d0859-ffffffff813d08b2: ecryptfs_write.cold.7 (STB_LOCAL)
ffffffff813d0420-ffffffff813d076d: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
```
**Symbols:**

```
ffffffff813fb479-ffffffff813fb4e0: ecryptfs_write.cold (STB_LOCAL)
ffffffff813fb020-ffffffff813fb383: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
```
**Symbols:**

```
ffffffff81415349-ffffffff814153b0: ecryptfs_write.cold (STB_LOCAL)
ffffffff81414ef0-ffffffff81415253: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:truncate_upper
```
**Symbols:**

```
ffffffff81463609-ffffffff81463670: ecryptfs_write.cold (STB_LOCAL)
ffffffff814631b0-ffffffff81463512: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:truncate_upper
```
**Symbols:**

```
ffffffff81bee571-ffffffff81bee5d8: ecryptfs_write.cold (STB_LOCAL)
ffffffff8147ea00-ffffffff8147ed5f: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:truncate_upper
```
**Symbols:**

```
ffffffff81be05f8-ffffffff81be066a: ecryptfs_write.cold (STB_LOCAL)
ffffffff81484590-ffffffff814848eb: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:truncate_upper
```
**Symbols:**

```
ffffffff81cd0d95-ffffffff81cd0e07: ecryptfs_write.cold (STB_LOCAL)
ffffffff814dbc10-ffffffff814dbf6b: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:truncate_upper
```
**Symbols:**

```
ffffffff81e83ff4-ffffffff81e8404f: ecryptfs_write.cold (STB_LOCAL)
ffffffff81569880-ffffffff81569c5f: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff8160d4b0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:truncate_upper
```
**Symbols:**

```
ffffffff8160d4b0-ffffffff8160d8e1: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff81645370)
Location: fs/ecryptfs/read_write.c:93
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:truncate_upper
```
**Symbols:**

```
ffffffff81645370-ffffffff8164579a: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffff8167e890)
Location: fs/ecryptfs/read_write.c:93
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:truncate_upper
```
**Symbols:**

```
ffffffff8167e890-ffffffff8167ec7c: ecryptfs_write (STB_GLOBAL)
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
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffff8000104f6588)
Location: fs/ecryptfs/read_write.c:93
Inline: False
```
**Symbols:**

```
ffff8000104f6588-ffff8000104f6834: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (c06b3f34)
Location: fs/ecryptfs/read_write.c:93
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:truncate_upper
```
**Symbols:**

```
c06b3f34-c06b42f8: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (c000000000637480)
Location: fs/ecryptfs/read_write.c:93
Inline: False
```
**Symbols:**

```
c000000000637480-c0000000006378a8: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/read_write.c (ffffffe000365276)
Location: fs/ecryptfs/read_write.c:93
Inline: False
```
**Symbols:**

```
ffffffe000365276-ffffffe0003654de: ecryptfs_write (STB_GLOBAL)
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
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
```
**Symbols:**

```
ffffffff8140d929-ffffffff8140d990: ecryptfs_write.cold (STB_LOCAL)
ffffffff8140d4d0-ffffffff8140d833: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
```
**Symbols:**

```
ffffffff813fe3a9-ffffffff813fe410: ecryptfs_write.cold (STB_LOCAL)
ffffffff813fdf50-ffffffff813fe2b3: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
```
**Symbols:**

```
ffffffff8140aca9-ffffffff8140ad10: ecryptfs_write.cold (STB_LOCAL)
ffffffff8140a850-ffffffff8140abb3: ecryptfs_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write(struct inode *ecryptfs_inode, char *data, loff_t offset, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/read_write.c (0)
Location: fs/ecryptfs/read_write.c:93
Inline: False
```
**Symbols:**

```
ffffffff81420942-ffffffff814209a9: ecryptfs_write.cold (STB_LOCAL)
ffffffff81420510-ffffffff8142087e: ecryptfs_write (STB_GLOBAL)
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
