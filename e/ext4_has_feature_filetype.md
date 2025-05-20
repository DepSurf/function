# Function: <code>ext4_has_feature_filetype</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81290b2a)
Location: fs/ext4/ext4.h:1707
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/namei.c (ffffffff812a2d2e)
Location: fs/ext4/ext4.h:1707
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_insert_dentry
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
```
```
In fs/ext4/inline.c (ffffffff812e19c7)
Location: fs/ext4/ext4.h:1707
Inline: True
Inline callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_read_inline_dir
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812be03a)
Location: fs/ext4/ext4.h:1775
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/namei.c (ffffffff812d5a53)
Location: fs/ext4/ext4.h:1775
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
```
In fs/ext4/inline.c (ffffffff81311cfc)
Location: fs/ext4/ext4.h:1775
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812d352a)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/namei.c (ffffffff812eb753)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
```
In fs/ext4/inline.c (ffffffff81327c3c)
Location: fs/ext4/ext4.h:1760
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812e4fc8)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff812fbb01)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8131b43c)
Location: fs/ext4/ext4.h:1765
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813099fa)
Location: fs/ext4/ext4.h:1725
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8132025b)
Location: fs/ext4/ext4.h:1725
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8133faf3)
Location: fs/ext4/ext4.h:1725
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81337966)
Location: fs/ext4/ext4.h:1728
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8134e445)
Location: fs/ext4/ext4.h:1728
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8136daa3)
Location: fs/ext4/ext4.h:1728
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8134ebb6)
Location: fs/ext4/ext4.h:1741
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813665e1)
Location: fs/ext4/ext4.h:1741
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81385f23)
Location: fs/ext4/ext4.h:1741
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81377886)
Location: fs/ext4/ext4.h:1761
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8138f8f4)
Location: fs/ext4/ext4.h:1761
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813aff03)
Location: fs/ext4/ext4.h:1761
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8138fc06)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a8354)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813c8ec3)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813db2ae)
Location: fs/ext4/ext4.h:1915
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813f43f4)
Location: fs/ext4/ext4.h:1915
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff81414a63)
Location: fs/ext4/ext4.h:1915
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813eccde)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81406b84)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff814280b3)
Location: fs/ext4/ext4.h:2040
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813f320e)
Location: fs/ext4/ext4.h:2049
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8140d076)
Location: fs/ext4/ext4.h:2049
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8142ebc9)
Location: fs/ext4/ext4.h:2049
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8144522b)
Location: fs/ext4/ext4.h:2116
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8145feb6)
Location: fs/ext4/ext4.h:2116
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8148336d)
Location: fs/ext4/ext4.h:2116
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff814c124b)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff814de626)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815064cd)
Location: fs/ext4/ext4.h:2118
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff815594cb)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81577693)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815a0f8d)
Location: fs/ext4/ext4.h:2128
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff815912ce)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815aeb86)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff815d790d)
Location: fs/ext4/ext4.h:2122
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff815ca00e)
Location: fs/ext4/ext4.h:2140
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815e7946)
Location: fs/ext4/ext4.h:2140
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff8160ff7d)
Location: fs/ext4/ext4.h:2140
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffff800010462324)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffff80001047bbb0)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffff8000104a09b0)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c06228ac)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c063d530)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (c0662afc)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c00000000057ed64)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c00000000059f204)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (c0000000005cceb8)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffe0002f1134)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffe000305ed4)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffe000322c04)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813881e6)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a0934)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813c14a3)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81378c76)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813913c4)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813b1f33)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81385b46)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139e194)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813be953)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81399836)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/dir.c:call_filldir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813b2704)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
```
```
In fs/ext4/namei.c (ffffffff813d3a33)
Location: fs/ext4/ext4.h:1818
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_init_dot_dotdot
  - fs/ext4/namei.c:ext4_insert_dentry
```
</details>
</li>
</ul>

## Differences
