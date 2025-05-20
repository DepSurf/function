# Function: <code>bpf_symlink</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81192ae0)
Location: kernel/bpf/inode.c:196
Inline: False
```
**Symbols:**

```
ffffffff81192ae0-ffffffff81192b69: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81199950)
Location: kernel/bpf/inode.c:197
Inline: False
```
**Symbols:**

```
ffffffff81199950-ffffffff811999d9: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811a8bf0)
Location: kernel/bpf/inode.c:197
Inline: False
```
**Symbols:**

```
ffffffff811a8bf0-ffffffff811a8c79: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811c0100)
Location: kernel/bpf/inode.c:352
Inline: False
```
**Symbols:**

```
ffffffff811c0100-ffffffff811c018a: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811d1560)
Location: kernel/bpf/inode.c:353
Inline: False
```
**Symbols:**

```
ffffffff811d1560-ffffffff811d15ea: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e5890)
Location: kernel/bpf/inode.c:350
Inline: False
```
**Symbols:**

```
ffffffff811e5890-ffffffff811e591e: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f1ff0)
Location: kernel/bpf/inode.c:350
Inline: False
```
**Symbols:**

```
ffffffff811f1ff0-ffffffff811f207e: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81213ac0)
Location: kernel/bpf/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff81213ac0-ffffffff81213b76: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81215360)
Location: kernel/bpf/inode.c:384
Inline: False
```
**Symbols:**

```
ffffffff81215360-ffffffff81215416: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_symlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81218070)
Location: kernel/bpf/inode.c:385
Inline: False
```
**Symbols:**

```
ffffffff81218070-ffffffff81218126: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_symlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8124e650)
Location: kernel/bpf/inode.c:385
Inline: False
```
**Symbols:**

```
ffffffff8124e650-ffffffff8124e706: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_symlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812956c0)
Location: kernel/bpf/inode.c:385
Inline: False
```
**Symbols:**

```
ffffffff812956c0-ffffffff81295782: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_symlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812f0450)
Location: kernel/bpf/inode.c:385
Inline: False
```
**Symbols:**

```
ffffffff812f0450-ffffffff812f0512: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_symlink(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8131d760)
Location: kernel/bpf/inode.c:385
Inline: False
```
**Symbols:**

```
ffffffff8131d760-ffffffff8131d822: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_symlink(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8133faf0)
Location: kernel/bpf/inode.c:382
Inline: False
```
**Symbols:**

```
ffffffff8133faf0-ffffffff8133fbe1: bpf_symlink (STB_LOCAL)
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
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffff800010275b90)
Location: kernel/bpf/inode.c:350
Inline: False
```
**Symbols:**

```
ffff800010275b90-ffff800010275c38: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (c04a828c)
Location: kernel/bpf/inode.c:350
Inline: False
```
**Symbols:**

```
c04a828c-c04a831c: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (c00000000031dd20)
Location: kernel/bpf/inode.c:350
Inline: False
```
**Symbols:**

```
c00000000031dd20-c00000000031ddf4: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffe0001ae1d6)
Location: kernel/bpf/inode.c:350
Inline: False
```
**Symbols:**

```
ffffffe0001ae1d6-ffffffe0001ae26a: bpf_symlink (STB_LOCAL)
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
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811ea610)
Location: kernel/bpf/inode.c:350
Inline: False
```
**Symbols:**

```
ffffffff811ea610-ffffffff811ea69e: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811dd3d0)
Location: kernel/bpf/inode.c:350
Inline: False
```
**Symbols:**

```
ffffffff811dd3d0-ffffffff811dd45e: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e83e0)
Location: kernel/bpf/inode.c:350
Inline: False
```
**Symbols:**

```
ffffffff811e83e0-ffffffff811e846e: bpf_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_symlink(struct inode *dir, struct dentry *dentry, const char *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f6790)
Location: kernel/bpf/inode.c:350
Inline: False
```
**Symbols:**

```
ffffffff811f6790-ffffffff811f681e: bpf_symlink (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dir, dentry, target</code> ➡️ <code>mnt_userns, dir, dentry, target</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
