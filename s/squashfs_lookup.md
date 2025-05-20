# Function: <code>squashfs_lookup</code>

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
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff813239b0)
Location: fs/squashfs/namei.c:139
Inline: False
```
**Symbols:**

```
ffffffff813239b0-ffffffff81323dff: squashfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff81339840)
Location: fs/squashfs/namei.c:139
Inline: False
```
**Symbols:**

```
ffffffff81339840-ffffffff81339c8f: squashfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff8134e520)
Location: fs/squashfs/namei.c:139
Inline: False
```
**Symbols:**

```
ffffffff8134e520-ffffffff8134e95c: squashfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff81372bd0)
Location: fs/squashfs/namei.c:139
Inline: False
```
**Symbols:**

```
ffffffff81372bd0-ffffffff8137300c: squashfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:139
Inline: False
```
**Symbols:**

```
ffffffff813a14f0-ffffffff813a18f3: squashfs_lookup (STB_LOCAL)
ffffffff813a18f3-ffffffff813a1955: squashfs_lookup.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:139
Inline: False
```
**Symbols:**

```
ffffffff813ba2d0-ffffffff813ba6d3: squashfs_lookup (STB_LOCAL)
ffffffff813ba6d3-ffffffff813ba735: squashfs_lookup.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff813e4ba0-ffffffff813e4fb5: squashfs_lookup (STB_LOCAL)
ffffffff813e4fb5-ffffffff813e501c: squashfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff813febf0-ffffffff813ff005: squashfs_lookup (STB_LOCAL)
ffffffff813ff005-ffffffff813ff06c: squashfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff8144c6d0-ffffffff8144c96d: squashfs_lookup (STB_LOCAL)
ffffffff8144c984-ffffffff8144c9cb: squashfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff81468d80-ffffffff8146901d: squashfs_lookup (STB_LOCAL)
ffffffff81bed51a-ffffffff81bed561: squashfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff8146e480-ffffffff8146e71d: squashfs_lookup (STB_LOCAL)
ffffffff81bdf5fc-ffffffff81bdf643: squashfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff814c4d10-ffffffff814c4fa7: squashfs_lookup (STB_LOCAL)
ffffffff81ccf0db-ffffffff81ccf122: squashfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff8154fb20-ffffffff8154fde0: squashfs_lookup (STB_LOCAL)
ffffffff81e82161-ffffffff81e821a9: squashfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff815f0600)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff815f0600-ffffffff815f08ef: squashfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff81628640)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff81628640-ffffffff8162892f: squashfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff816617f0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff816617f0-ffffffff81661b11: squashfs_lookup (STB_LOCAL)
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
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffff8000104dccb0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffff8000104dccb0-ffff8000104dd0f8: squashfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (c069e6c8)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
c069e6c8-c069ebbc: squashfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (c0000000006182e0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
c0000000006182e0-c0000000006189c0: squashfs_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffe0003517a2)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffe0003517a2-ffffffe000351ba6: squashfs_lookup (STB_LOCAL)
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
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff813f71d0-ffffffff813f75e5: squashfs_lookup (STB_LOCAL)
ffffffff813f75e5-ffffffff813f764c: squashfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff813e7c50-ffffffff813e8065: squashfs_lookup (STB_LOCAL)
ffffffff813e8065-ffffffff813e80cc: squashfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff813f4550-ffffffff813f4965: squashfs_lookup (STB_LOCAL)
ffffffff813f4965-ffffffff813f49cc: squashfs_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *squashfs_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:126
Inline: False
```
**Symbols:**

```
ffffffff8140a180-ffffffff8140a595: squashfs_lookup (STB_LOCAL)
ffffffff8140a595-ffffffff8140a5fc: squashfs_lookup.cold (STB_LOCAL)
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
