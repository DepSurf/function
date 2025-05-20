# Function: <code>simple_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81234a60)
Location: fs/libfs.c:61
Inline: True
```
**Symbols:**

```
ffffffff81234a60-ffffffff81234ab4: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125cc90)
Location: fs/libfs.c:61
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff8125cc90-ffffffff8125ccdc: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812701d0)
Location: fs/libfs.c:61
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff812701d0-ffffffff8127021c: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127d8f0)
Location: fs/libfs.c:62
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff8127d8f0-ffffffff8127d93c: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812a0390)
Location: fs/libfs.c:62
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff812a0390-ffffffff812a03dc: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c6b30)
Location: fs/libfs.c:62
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff812c6b30-ffffffff812c6b7c: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dbd30)
Location: fs/libfs.c:62
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff812dbd30-ffffffff812dbd7c: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fa3d0)
Location: fs/libfs.c:65
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff812fa3d0-ffffffff812fa420: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130c1d0)
Location: fs/libfs.c:66
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff8130c1d0-ffffffff8130c220: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813456b0)
Location: fs/libfs.c:66
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff813456b0-ffffffff81345700: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81351bc0)
Location: fs/libfs.c:68
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff81351bc0-ffffffff81351c10: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813588e0)
Location: fs/libfs.c:69
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff813588e0-ffffffff81358930: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a6f50)
Location: fs/libfs.c:69
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff813a6f50-ffffffff813a6fa0: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142bcd0)
Location: fs/libfs.c:69
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff8142bcd0-ffffffff8142bd30: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8e90)
Location: fs/libfs.c:70
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff814b8e90-ffffffff814b8ef0: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ee170)
Location: fs/libfs.c:70
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff814ee170-ffffffff814ee1d0: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81521ee0)
Location: fs/libfs.c:73
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff81521ee0-ffffffff81521f40: simple_lookup (STB_GLOBAL)
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
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c0858)
Location: fs/libfs.c:66
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffff8000103c0858-ffff8000103c08cc: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059de48)
Location: fs/libfs.c:66
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
c059de48-c059deb8: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004c0140)
Location: fs/libfs.c:66
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
c0000000004c0140-c0000000004c01d8: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000280f42)
Location: fs/libfs.c:66
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffe000280f42-ffffffe000280fa4: simple_lookup (STB_GLOBAL)
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
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813047b0)
Location: fs/libfs.c:66
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff813047b0-ffffffff81304800: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f53d0)
Location: fs/libfs.c:66
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff812f53d0-ffffffff812f5420: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813025a0)
Location: fs/libfs.c:66
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff813025a0-ffffffff813025f0: simple_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *simple_lookup(struct inode *dir, struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81313bc0)
Location: fs/libfs.c:66
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_lookup
```
**Symbols:**

```
ffffffff81313bc0-ffffffff81313c10: simple_lookup (STB_GLOBAL)
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
