# Function: <code>__ext4_expand_extra_isize</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fd210)
Location: fs/ext4/inode.c:5707
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff812fd210-ffffffff812fd298: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81321af0)
Location: fs/ext4/inode.c:5760
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff81321af0-ffffffff81321b78: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8134fb40)
Location: fs/ext4/inode.c:5856
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff8134fb40-ffffffff8134fbcf: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81367d30)
Location: fs/ext4/inode.c:5909
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff81367d30-ffffffff81367dbf: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81391010)
Location: fs/ext4/inode.c:5931
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff81391010-ffffffff81391095: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a99d0)
Location: fs/ext4/inode.c:5945
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff813a99d0-ffffffff813a9ac5: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f5b10)
Location: fs/ext4/inode.c:5666
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff813f5b10-ffffffff813f5c10: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814082e0)
Location: fs/ext4/inode.c:5759
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff814082e0-ffffffff814083e0: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140e5f0)
Location: fs/ext4/inode.c:5756
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff8140e5f0-ffffffff8140e6f0: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81461340)
Location: fs/ext4/inode.c:5696
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff81461340-ffffffff81461440: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814dfe00)
Location: fs/ext4/inode.c:5774
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff814dfe00-ffffffff814dff36: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815790e0)
Location: fs/ext4/inode.c:5910
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff815790e0-ffffffff81579232: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b0530)
Location: fs/ext4/inode.c:5722
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff815b0530-ffffffff815b0681: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815e9320)
Location: fs/ext4/inode.c:5742
Inline: False
Direct callers:
  - fs/ext4/inode.c:__ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff815e9320-ffffffff815e9471: __ext4_expand_extra_isize (STB_LOCAL)
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
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff80001047d610)
Location: fs/ext4/inode.c:5945
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffff80001047d610-ffff80001047d738: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c063f234)
Location: fs/ext4/inode.c:5945
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
c063f234-c063f35c: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a1d50)
Location: fs/ext4/inode.c:5945
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
c0000000005a1d50-c0000000005a1eec: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe0003072f6)
Location: fs/ext4/inode.c:5945
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffe0003072f6-ffffffe0003073ee: __ext4_expand_extra_isize (STB_LOCAL)
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
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a1fb0)
Location: fs/ext4/inode.c:5945
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff813a1fb0-ffffffff813a20a5: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81392a40)
Location: fs/ext4/inode.c:5945
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff81392a40-ffffffff81392b35: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139f810)
Location: fs/ext4/inode.c:5945
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff8139f810-ffffffff8139f905: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ext4_expand_extra_isize(struct inode *inode, unsigned int new_extra_isize, struct ext4_iloc *iloc, handle_t *handle, int *no_expand);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b3ed0)
Location: fs/ext4/inode.c:5945
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_mark_inode_dirty
  - fs/ext4/inode.c:ext4_expand_extra_isize
```
**Symbols:**

```
ffffffff813b3ed0-ffffffff813b3fc5: __ext4_expand_extra_isize (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
