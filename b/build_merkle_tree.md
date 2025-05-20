# Function: <code>build_merkle_tree</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree(struct inode *inode, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:113
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff8134f5b0-ffffffff8134f98f: build_merkle_tree (STB_LOCAL)
ffffffff8134ff1a-ffffffff8134ffab: build_merkle_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int build_merkle_tree(struct file *filp, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff813960e0)
Location: fs/verity/enable.c:151
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff813960e0-ffffffff813961e9: build_merkle_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int build_merkle_tree(struct file *filp, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff813a7e00)
Location: fs/verity/enable.c:151
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff813a7e00-ffffffff813a7f09: build_merkle_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int build_merkle_tree(struct file *filp, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff813aee60)
Location: fs/verity/enable.c:151
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff813aee60-ffffffff813aef69: build_merkle_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree(struct file *filp, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:151
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff813fea00-ffffffff813feb1b: build_merkle_tree (STB_LOCAL)
ffffffff81cc6cc4-ffffffff81cc6cfe: build_merkle_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree(struct file *filp, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:150
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81472580-ffffffff814726ab: build_merkle_tree (STB_LOCAL)
ffffffff81e7920b-ffffffff81e79245: build_merkle_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree(struct file *filp, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:150
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81504260-ffffffff8150438b: build_merkle_tree (STB_LOCAL)
ffffffff8206a9b2-ffffffff8206a9ec: build_merkle_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int build_merkle_tree(struct file *filp, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff8153b620)
Location: fs/verity/enable.c:72
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff8153b620-ffffffff8153bb17: build_merkle_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int build_merkle_tree(struct file *filp, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffff81570900)
Location: fs/verity/enable.c:72
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81570900-ffffffff81570df4: build_merkle_tree (STB_LOCAL)
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
int build_merkle_tree(struct inode *inode, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffff800010410fa8)
Location: fs/verity/enable.c:113
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffff800010410fa8-ffff8000104113f0: build_merkle_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int build_merkle_tree(struct inode *inode, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (c05dd574)
Location: fs/verity/enable.c:113
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
c05dd574-c05ddad8: build_merkle_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int build_merkle_tree(struct inode *inode, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (c00000000051ea60)
Location: fs/verity/enable.c:113
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
c00000000051ea60-c00000000051efe4: build_merkle_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int build_merkle_tree(struct inode *inode, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/enable.c (ffffffe0002b9428)
Location: fs/verity/enable.c:113
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffe0002b9428-ffffffe0002b9796: build_merkle_tree (STB_LOCAL)
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
int build_merkle_tree(struct inode *inode, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:113
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81347b90-ffffffff81347f6f: build_merkle_tree (STB_LOCAL)
ffffffff813484fa-ffffffff8134858b: build_merkle_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree(struct inode *inode, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:113
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81338870-ffffffff81338c4f: build_merkle_tree (STB_LOCAL)
ffffffff813391da-ffffffff8133926b: build_merkle_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree(struct inode *inode, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:113
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81345660-ffffffff81345a3f: build_merkle_tree (STB_LOCAL)
ffffffff81345fca-ffffffff8134605b: build_merkle_tree.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int build_merkle_tree(struct inode *inode, const struct merkle_tree_params *params, u8 *root_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/enable.c (0)
Location: fs/verity/enable.c:113
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81358940-ffffffff81358d1a: build_merkle_tree (STB_LOCAL)
ffffffff813592aa-ffffffff8135933b: build_merkle_tree.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *filp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
</ul>
</details>
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
