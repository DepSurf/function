# Function: <code>ext4_get_branch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812d8460)
Location: fs/ext4/indirect.c:143
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff812d8460-ffffffff812d858a: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813081d0)
Location: fs/ext4/indirect.c:143
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813081d0-ffffffff813082fa: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131e1c0)
Location: fs/ext4/indirect.c:143
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8131e1c0-ffffffff8131e2ea: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812f6da0)
Location: fs/ext4/indirect.c:143
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff812f6da0-ffffffff812f6ece: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131b3e0)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8131b3e0-ffffffff8131b50e: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81349310)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81349310-ffffffff8134943e: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813614d0)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813614d0-ffffffff813615fe: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138a560)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8138a560-ffffffff8138a693: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813a2fb0)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813a2fb0-ffffffff813a30e3: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ef180)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813ef180-ffffffff813ef2b3: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814018d0)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff814018d0-ffffffff81401a07: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81407e10)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81407e10-ffffffff81407f49: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8145a720)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8145a720-ffffffff8145a859: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814d8470)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff814d8470-ffffffff814d85b7: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81571210)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81571210-ffffffff81571389: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815a8f80)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff815a8f80-ffffffff815a90fc: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815e21d0)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff815e21d0-ffffffff815e235b: ext4_get_branch (STB_LOCAL)
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
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffff800010477538)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffff800010477538-ffff8000104776a8: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c0638210)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
c0638210-c0638368: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c000000000598910)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
c000000000598910-c000000000598af8: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffe00030205c)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffe00030205c-ffffffe000302172: ext4_get_branch (STB_LOCAL)
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
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8139b590)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8139b590-ffffffff8139b6c3: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138c020)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff8138c020-ffffffff8138c153: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81398df0)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff81398df0-ffffffff81398f23: ext4_get_branch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
Indirect *ext4_get_branch(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, int *err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ad210)
Location: fs/ext4/indirect.c:144
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_find_shared
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff813ad210-ffffffff813ad343: ext4_get_branch (STB_LOCAL)
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
