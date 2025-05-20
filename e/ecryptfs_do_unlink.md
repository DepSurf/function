# Function: <code>ecryptfs_do_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff813019f0)
Location: fs/ecryptfs/inode.c:143
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff813019f0-ffffffff81301b0c: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81335a60)
Location: fs/ecryptfs/inode.c:142
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81335a60-ffffffff81335b7c: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8134b720)
Location: fs/ecryptfs/inode.c:142
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff8134b720-ffffffff8134b83c: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff813602a0)
Location: fs/ecryptfs/inode.c:142
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff813602a0-ffffffff813603be: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81384f70)
Location: fs/ecryptfs/inode.c:141
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81384f70-ffffffff8138508e: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:141
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff813b3d70-ffffffff813b3e7c: ecryptfs_do_unlink (STB_LOCAL)
ffffffff813b52ce-ffffffff813b52e3: ecryptfs_do_unlink.cold.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:141
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff813cd290-ffffffff813cd39c: ecryptfs_do_unlink (STB_LOCAL)
ffffffff813ce7ee-ffffffff813ce803: ecryptfs_do_unlink.cold.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff813f7e30-ffffffff813f7f3c: ecryptfs_do_unlink (STB_LOCAL)
ffffffff813f933e-ffffffff813f9353: ecryptfs_do_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81411c70-ffffffff81411d94: ecryptfs_do_unlink (STB_LOCAL)
ffffffff8141319e-ffffffff8141321f: ecryptfs_do_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff8145fb20-ffffffff8145fc44: ecryptfs_do_unlink (STB_LOCAL)
ffffffff8146136b-ffffffff814613ec: ecryptfs_do_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff8147b740-ffffffff8147b864: ecryptfs_do_unlink (STB_LOCAL)
ffffffff81bedfd8-ffffffff81bee059: ecryptfs_do_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81481920-ffffffff81481a8f: ecryptfs_do_unlink (STB_LOCAL)
ffffffff81be0140-ffffffff81be016e: ecryptfs_do_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff814d96e0-ffffffff814d984f: ecryptfs_do_unlink (STB_LOCAL)
ffffffff81cd08d1-ffffffff81cd08ff: ecryptfs_do_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81566f20)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81566f20-ffffffff8156708e: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8160a520)
Location: fs/ecryptfs/inode.c:129
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff8160a520-ffffffff8160a690: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81642400)
Location: fs/ecryptfs/inode.c:129
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81642400-ffffffff81642570: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8167ba20)
Location: fs/ecryptfs/inode.c:137
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff8167ba20-ffffffff8167bb99: ecryptfs_do_unlink (STB_LOCAL)
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
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffff8000104f3010)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffff8000104f3010-ffff8000104f3130: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (c06b077c)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
c06b077c-c06b08b4: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (c000000000632fa0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
c000000000632fa0-c000000000633140: ecryptfs_do_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffe0003625da)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffe0003625da-ffffffe00036271c: ecryptfs_do_unlink (STB_LOCAL)
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
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff8140a250-ffffffff8140a374: ecryptfs_do_unlink (STB_LOCAL)
ffffffff8140b77e-ffffffff8140b7ff: ecryptfs_do_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff813facd0-ffffffff813fadf4: ecryptfs_do_unlink (STB_LOCAL)
ffffffff813fc1fe-ffffffff813fc27f: ecryptfs_do_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff814075d0-ffffffff814076f4: ecryptfs_do_unlink (STB_LOCAL)
ffffffff81408afe-ffffffff81408b7f: ecryptfs_do_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_do_unlink(struct inode *dir, struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:127
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff8141d290-ffffffff8141d3b4: ecryptfs_do_unlink (STB_LOCAL)
ffffffff8141e7be-ffffffff8141e83f: ecryptfs_do_unlink.cold (STB_LOCAL)
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
