# Function: <code>alloc_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81226ff0)
Location: fs/inode.c:193
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff81226ff0-ffffffff81227073: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124f730)
Location: fs/inode.c:200
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff8124f730-ffffffff8124f7af: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262760)
Location: fs/inode.c:202
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff81262760-ffffffff812627df: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126ffe0)
Location: fs/inode.c:203
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff8126ffe0-ffffffff8127005f: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81292910)
Location: fs/inode.c:203
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff81292910-ffffffff81292995: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8710)
Location: fs/inode.c:205
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff812b8710-ffffffff812b8795: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cd860)
Location: fs/inode.c:205
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff812cd860-ffffffff812cd8e5: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ea600)
Location: fs/inode.c:221
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff812ea600-ffffffff812ea69b: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc030)
Location: fs/inode.c:225
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff812fc030-ffffffff812fc0cb: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335820)
Location: fs/inode.c:226
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff81335820-ffffffff813358d5: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813411a0)
Location: fs/inode.c:227
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff813411a0-ffffffff81341255: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81347710)
Location: fs/inode.c:227
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff81347710-ffffffff813477c5: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81395000)
Location: fs/inode.c:231
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff81395000-ffffffff813950b5: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81417d70)
Location: fs/inode.c:255
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff81417d70-ffffffff81417e35: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a3530)
Location: fs/inode.c:253
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff814a3530-ffffffff814a35f5: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d86a0)
Location: fs/inode.c:253
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff814d86a0-ffffffff814d8765: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150af30)
Location: fs/inode.c:254
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode
```
**Symbols:**

```
ffffffff8150af30-ffffffff8150aff5: alloc_inode (STB_LOCAL)
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
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103aca78)
Location: fs/inode.c:225
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffff8000103aca78-ffff8000103acb38: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058ca98)
Location: fs/inode.c:225
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
c058ca98-c058cb44: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a6ae0)
Location: fs/inode.c:225
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
c0000000004a6ae0-c0000000004a6c04: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000270fb8)
Location: fs/inode.c:225
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffe000270fb8-ffffffe000271054: alloc_inode (STB_LOCAL)
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
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4610)
Location: fs/inode.c:225
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff812f4610-ffffffff812f46ab: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5230)
Location: fs/inode.c:225
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff812e5230-ffffffff812e52cb: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2420)
Location: fs/inode.c:225
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff812f2420-ffffffff812f24bb: alloc_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *alloc_inode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81303a50)
Location: fs/inode.c:225
Inline: False
Direct callers:
  - fs/inode.c:iget_locked
  - fs/inode.c:new_inode_pseudo
```
**Symbols:**

```
ffffffff81303a50-ffffffff81303aeb: alloc_inode (STB_LOCAL)
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
