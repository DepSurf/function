# Function: <code>bad_inode_link</code>

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
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:40
Inline: False
```
**Symbols:**

```
ffffffff81252220-ffffffff81252230: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (0)
Location: fs/bad_inode.c:40
Inline: False
```
**Symbols:**

```
ffffffff812654c0-ffffffff812654d0: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81272ad0)
Location: fs/bad_inode.c:40
Inline: True
```
**Symbols:**

```
ffffffff81272ad0-ffffffff81272ae0: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81295400)
Location: fs/bad_inode.c:41
Inline: True
```
**Symbols:**

```
ffffffff81295400-ffffffff81295410: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812bb610)
Location: fs/bad_inode.c:41
Inline: True
```
**Symbols:**

```
ffffffff812bb610-ffffffff812bb620: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812d0800)
Location: fs/bad_inode.c:41
Inline: True
```
**Symbols:**

```
ffffffff812d0800-ffffffff812d0810: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ed830)
Location: fs/bad_inode.c:41
Inline: False
```
**Symbols:**

```
ffffffff812ed830-ffffffff812ed840: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812ff2f0)
Location: fs/bad_inode.c:41
Inline: False
```
**Symbols:**

```
ffffffff812ff2f0-ffffffff812ff300: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff813383e0)
Location: fs/bad_inode.c:42
Inline: True
```
**Symbols:**

```
ffffffff813383e0-ffffffff813383f0: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81343d70)
Location: fs/bad_inode.c:42
Inline: True
```
**Symbols:**

```
ffffffff81343d70-ffffffff81343d80: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8134a110)
Location: fs/bad_inode.c:43
Inline: True
```
**Symbols:**

```
ffffffff8134a110-ffffffff8134a120: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81397e70)
Location: fs/bad_inode.c:43
Inline: True
```
**Symbols:**

```
ffffffff81397e70-ffffffff81397e80: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8141a370)
Location: fs/bad_inode.c:43
Inline: True
```
**Symbols:**

```
ffffffff8141a370-ffffffff8141a384: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff814a6100)
Location: fs/bad_inode.c:43
Inline: True
```
**Symbols:**

```
ffffffff814a6100-ffffffff814a6114: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff814db0c0)
Location: fs/bad_inode.c:43
Inline: True
```
**Symbols:**

```
ffffffff814db0c0-ffffffff814db0d4: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff8150d680)
Location: fs/bad_inode.c:43
Inline: True
```
**Symbols:**

```
ffffffff8150d680-ffffffff8150d694: bad_inode_link (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffff8000103b0730)
Location: fs/bad_inode.c:41
Inline: True
```
**Symbols:**

```
ffff8000103b0730-ffff8000103b074c: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (c0590050)
Location: fs/bad_inode.c:41
Inline: True
```
**Symbols:**

```
c0590050-c059006c: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (c0000000004ac120)
Location: fs/bad_inode.c:41
Inline: False
```
**Symbols:**

```
c0000000004ac120-c0000000004ac130: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffe000274ac2)
Location: fs/bad_inode.c:41
Inline: True
```
**Symbols:**

```
ffffffe000274ac2-ffffffe000274ade: bad_inode_link (STB_LOCAL)
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
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f78d0)
Location: fs/bad_inode.c:41
Inline: False
```
**Symbols:**

```
ffffffff812f78d0-ffffffff812f78e0: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812e84f0)
Location: fs/bad_inode.c:41
Inline: False
```
**Symbols:**

```
ffffffff812e84f0-ffffffff812e8500: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff812f56e0)
Location: fs/bad_inode.c:41
Inline: False
```
**Symbols:**

```
ffffffff812f56e0-ffffffff812f56f0: bad_inode_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bad_inode_link(struct dentry *old_dentry, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/bad_inode.c (ffffffff81306870)
Location: fs/bad_inode.c:41
Inline: False
```
**Symbols:**

```
ffffffff81306870-ffffffff81306880: bad_inode_link (STB_LOCAL)
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
