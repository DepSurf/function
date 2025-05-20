# Function: <code>ext4_find_shared</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812d8590)
Location: fs/ext4/indirect.c:874
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
```
**Symbols:**

```
ffffffff812d8590-ffffffff812d86d7: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81308300)
Location: fs/ext4/indirect.c:762
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff81308300-ffffffff81308461: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131e2f0)
Location: fs/ext4/indirect.c:762
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff8131e2f0-ffffffff8131e451: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812f6ed0)
Location: fs/ext4/indirect.c:762
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff812f6ed0-ffffffff812f701d: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131b510)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff8131b510-ffffffff8131b65d: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81349440)
Location: fs/ext4/indirect.c:769
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff81349440-ffffffff81349588: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81361600)
Location: fs/ext4/indirect.c:769
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff81361600-ffffffff8136174b: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138a9d0)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff8138a9d0-ffffffff8138aaf7: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813a3420)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff813a3420-ffffffff813a3547: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ef750)
Location: fs/ext4/indirect.c:785
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff813ef750-ffffffff813ef87c: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81401ea0)
Location: fs/ext4/indirect.c:786
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff81401ea0-ffffffff81401fcc: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814082a0)
Location: fs/ext4/indirect.c:786
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff814082a0-ffffffff814083c6: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8145acd0)
Location: fs/ext4/indirect.c:789
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff8145acd0-ffffffff8145adf6: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814d8a40)
Location: fs/ext4/indirect.c:789
Inline: True
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff814d8a40-ffffffff814d8b77: ext4_find_shared.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81571840)
Location: fs/ext4/indirect.c:796
Inline: True
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff81571840-ffffffff81571977: ext4_find_shared.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815a95c0)
Location: fs/ext4/indirect.c:804
Inline: True
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff815a95c0-ffffffff815a9702: ext4_find_shared.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815e2370)
Location: fs/ext4/indirect.c:804
Inline: True
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff815e2370-ffffffff815e24b2: ext4_find_shared.constprop.0 (STB_LOCAL)
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
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffff8000104776a8)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffff8000104776a8-ffff800010477808: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c0638368)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
c0638368-c06384bc: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c000000000598b00)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
c000000000598b00-c000000000598cbc: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffe000302172)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffe000302172-ffffffe000302264: ext4_find_shared (STB_LOCAL)
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
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8139ba00)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff8139ba00-ffffffff8139bb27: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138c490)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff8138c490-ffffffff8138c5b7: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81399260)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff81399260-ffffffff81399387: ext4_find_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
Indirect *ext4_find_shared(struct inode *inode, int depth, ext4_lblk_t *offsets, Indirect *chain, __le32 *top);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ad350)
Location: fs/ext4/indirect.c:763
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff813ad350-ffffffff813ad477: ext4_find_shared (STB_LOCAL)
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
