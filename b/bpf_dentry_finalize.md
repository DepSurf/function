# Function: <code>bpf_dentry_finalize</code>

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
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81192a20)
Location: kernel/bpf/inode.c:124
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff81192a20-ffffffff81192a69: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81199890)
Location: kernel/bpf/inode.c:125
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff81199890-ffffffff811998dd: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811a8b30)
Location: kernel/bpf/inode.c:125
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811a8b30-ffffffff811a8b7d: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811bffc0)
Location: kernel/bpf/inode.c:125
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811bffc0-ffffffff811c0009: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811d1410)
Location: kernel/bpf/inode.c:125
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811d1410-ffffffff811d1459: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e5740)
Location: kernel/bpf/inode.c:122
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811e5740-ffffffff811e5789: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f1ea0)
Location: kernel/bpf/inode.c:123
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811f1ea0-ffffffff811f1ee9: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81213b1f)
Location: kernel/bpf/inode.c:144
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812153bf)
Location: kernel/bpf/inode.c:145
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
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
In kernel/bpf/inode.c (ffffffff812180cf)
Location: kernel/bpf/inode.c:145
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
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
In kernel/bpf/inode.c (ffffffff8124e6af)
Location: kernel/bpf/inode.c:145
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
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
In kernel/bpf/inode.c (ffffffff8129571f)
Location: kernel/bpf/inode.c:145
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812f04af)
Location: kernel/bpf/inode.c:145
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8131d7bf)
Location: kernel/bpf/inode.c:145
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8133fb83)
Location: kernel/bpf/inode.c:143
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkobj_ops
  - kernel/bpf/inode.c:bpf_mkdir
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
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffff800010275478)
Location: kernel/bpf/inode.c:123
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffff800010275478-ffff8000102754dc: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (c04a7c24)
Location: kernel/bpf/inode.c:123
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
c04a7c24-c04a7cb4: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (c00000000031d470)
Location: kernel/bpf/inode.c:123
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
c00000000031d470-c00000000031d4ec: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffe0001adbf2)
Location: kernel/bpf/inode.c:123
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffe0001adbf2-ffffffe0001adc4c: bpf_dentry_finalize (STB_LOCAL)
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
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811ea4c0)
Location: kernel/bpf/inode.c:123
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811ea4c0-ffffffff811ea509: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811dd280)
Location: kernel/bpf/inode.c:123
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811dd280-ffffffff811dd2c9: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e8290)
Location: kernel/bpf/inode.c:123
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811e8290-ffffffff811e82d9: bpf_dentry_finalize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_dentry_finalize(struct dentry *dentry, struct inode *inode, struct inode *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f6640)
Location: kernel/bpf/inode.c:123
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_symlink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
  - kernel/bpf/inode.c:bpf_mkdir
```
**Symbols:**

```
ffffffff811f6640-ffffffff811f6689: bpf_dentry_finalize (STB_LOCAL)
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
