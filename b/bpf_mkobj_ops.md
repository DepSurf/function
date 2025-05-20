# Function: <code>bpf_mkobj_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct inode *dir, struct dentry *dentry, umode_t mode, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81176d00)
Location: kernel/bpf/inode.c:150
Inline: False
```
**Symbols:**

```
ffffffff81176d00-ffffffff81176db4: bpf_mkobj_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct inode *dir, struct dentry *dentry, umode_t mode, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811857c0)
Location: kernel/bpf/inode.c:142
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkobj
```
**Symbols:**

```
ffffffff811857c0-ffffffff8118582d: bpf_mkobj_ops (STB_LOCAL)
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
In kernel/bpf/inode.c (ffffffff81192dfd)
Location: kernel/bpf/inode.c:152
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkobj
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
In kernel/bpf/inode.c (ffffffff81199c8b)
Location: kernel/bpf/inode.c:153
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkobj
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
In kernel/bpf/inode.c (ffffffff811a901b)
Location: kernel/bpf/inode.c:153
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkobj
  - kernel/bpf/inode.c:bpf_mkobj
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
In kernel/bpf/inode.c (ffffffff811c0040)
Location: kernel/bpf/inode.c:309
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (ffffffff811d149a)
Location: kernel/bpf/inode.c:309
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (ffffffff811e57ca)
Location: kernel/bpf/inode.c:306
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (ffffffff811f1f2a)
Location: kernel/bpf/inode.c:306
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (ffffffff8121445b)
Location: kernel/bpf/inode.c:329
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry *dentry, umode_t mode, void *raw, const struct inode_operations *iops, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81215a60)
Location: kernel/bpf/inode.c:330
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_iter_link_pin_kernel
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
```
**Symbols:**

```
ffffffff81215a60-ffffffff81215af0: bpf_mkobj_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry *dentry, umode_t mode, void *raw, const struct inode_operations *iops, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81218650)
Location: kernel/bpf/inode.c:331
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
```
**Symbols:**

```
ffffffff81218650-ffffffff812186e0: bpf_mkobj_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry *dentry, umode_t mode, void *raw, const struct inode_operations *iops, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8124ec80)
Location: kernel/bpf/inode.c:331
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
```
**Symbols:**

```
ffffffff8124ec80-ffffffff8124ed10: bpf_mkobj_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry *dentry, umode_t mode, void *raw, const struct inode_operations *iops, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81295d80)
Location: kernel/bpf/inode.c:331
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
```
**Symbols:**

```
ffffffff81295d80-ffffffff81295e1f: bpf_mkobj_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry *dentry, umode_t mode, void *raw, const struct inode_operations *iops, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812f0bd0)
Location: kernel/bpf/inode.c:331
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
```
**Symbols:**

```
ffffffff812f0bd0-ffffffff812f0c6f: bpf_mkobj_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry *dentry, umode_t mode, void *raw, const struct inode_operations *iops, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8131d840)
Location: kernel/bpf/inode.c:331
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
```
**Symbols:**

```
ffffffff8131d840-ffffffff8131d91d: bpf_mkobj_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_mkobj_ops(struct dentry *dentry, umode_t mode, void *raw, const struct inode_operations *iops, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff8133fc00)
Location: kernel/bpf/inode.c:328
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_mklink
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
```
**Symbols:**

```
ffffffff8133fc00-ffffffff8133fd2e: bpf_mkobj_ops (STB_LOCAL)
```
</details>
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
In kernel/bpf/inode.c (ffff800010275a90)
Location: kernel/bpf/inode.c:306
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (c04a81c4)
Location: kernel/bpf/inode.c:306
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (c00000000031dbe4)
Location: kernel/bpf/inode.c:306
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (ffffffe0001ae0f6)
Location: kernel/bpf/inode.c:306
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (ffffffff811ea54a)
Location: kernel/bpf/inode.c:306
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (ffffffff811dd30a)
Location: kernel/bpf/inode.c:306
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (ffffffff811e831a)
Location: kernel/bpf/inode.c:306
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
In kernel/bpf/inode.c (ffffffff811f66ca)
Location: kernel/bpf/inode.c:306
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_mkmap
  - kernel/bpf/inode.c:bpf_mkprog
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
