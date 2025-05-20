# Function: <code>ext4_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a8180)
Location: fs/ext4/namei.c:2980
Inline: True
```
**Symbols:**

```
ffffffff812a8180-ffffffff812a84f7: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d7270)
Location: fs/ext4/namei.c:3003
Inline: True
```
**Symbols:**

```
ffffffff812d7270-ffffffff812d75e3: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812ecec0)
Location: fs/ext4/namei.c:3005
Inline: True
```
**Symbols:**

```
ffffffff812ecec0-ffffffff812ed1de: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8131cbb0)
Location: fs/ext4/namei.c:2987
Inline: True
```
**Symbols:**

```
ffffffff8131cbb0-ffffffff8131cee4: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813411d0)
Location: fs/ext4/namei.c:2982
Inline: True
```
**Symbols:**

```
ffffffff813411d0-ffffffff8134150d: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136f1f0)
Location: fs/ext4/namei.c:2982
Inline: True
```
**Symbols:**

```
ffffffff8136f1f0-ffffffff8136f54e: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81387680)
Location: fs/ext4/namei.c:2985
Inline: True
```
**Symbols:**

```
ffffffff81387680-ffffffff813879de: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b16b0)
Location: fs/ext4/namei.c:3140
Inline: True
```
**Symbols:**

```
ffffffff813b16b0-ffffffff813b1a45: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ca710)
Location: fs/ext4/namei.c:3152
Inline: True
```
**Symbols:**

```
ffffffff813ca710-ffffffff813caa92: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff81416700)
Location: fs/ext4/namei.c:3190
Inline: True
```
**Symbols:**

```
ffffffff81416700-ffffffff814169e8: ext4_unlink.part.0 (STB_LOCAL)
ffffffff814169f0-ffffffff81416a82: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142a8f0)
Location: fs/ext4/namei.c:3246
Inline: False
```
**Symbols:**

```
ffffffff8142a8f0-ffffffff8142aaa5: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81431610)
Location: fs/ext4/namei.c:3376
Inline: False
```
**Symbols:**

```
ffffffff81431610-ffffffff814317c5: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81484e20)
Location: fs/ext4/namei.c:3204
Inline: False
```
**Symbols:**

```
ffffffff81484e20-ffffffff81484fd2: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81508110)
Location: fs/ext4/namei.c:3251
Inline: False
```
**Symbols:**

```
ffffffff81508110-ffffffff8150830d: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815a2c70)
Location: fs/ext4/namei.c:3280
Inline: False
```
**Symbols:**

```
ffffffff815a2c70-ffffffff815a2db6: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d9650)
Location: fs/ext4/namei.c:3301
Inline: False
```
**Symbols:**

```
ffffffff815d9650-ffffffff815d9796: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81611d00)
Location: fs/ext4/namei.c:3303
Inline: False
```
**Symbols:**

```
ffffffff81611d00-ffffffff81611e46: ext4_unlink (STB_LOCAL)
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
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff8000104a22c8)
Location: fs/ext4/namei.c:3152
Inline: True
```
**Symbols:**

```
ffff8000104a22c8-ffff8000104a26a0: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c066451c)
Location: fs/ext4/namei.c:3152
Inline: True
```
**Symbols:**

```
c066451c-c0664914: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005cf040)
Location: fs/ext4/namei.c:3152
Inline: True
```
**Symbols:**

```
c0000000005cf040-c0000000005cf504: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00032405c)
Location: fs/ext4/namei.c:3152
Inline: True
```
**Symbols:**

```
ffffffe00032405c-ffffffe000324364: ext4_unlink (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c2cf0)
Location: fs/ext4/namei.c:3152
Inline: True
```
**Symbols:**

```
ffffffff813c2cf0-ffffffff813c3072: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b3780)
Location: fs/ext4/namei.c:3152
Inline: True
```
**Symbols:**

```
ffffffff813b3780-ffffffff813b3b02: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c0190)
Location: fs/ext4/namei.c:3152
Inline: True
```
**Symbols:**

```
ffffffff813c0190-ffffffff813c0504: ext4_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d5280)
Location: fs/ext4/namei.c:3152
Inline: True
```
**Symbols:**

```
ffffffff813d5280-ffffffff813d5637: ext4_unlink (STB_LOCAL)
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
