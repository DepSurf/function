# Function: <code>ext4_check_blockref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff812d6520)
Location: fs/ext4/block_validity.c:222
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/indirect.c:ext4_get_branch
```
**Symbols:**

```
ffffffff812d6520-ffffffff812d65ce: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813061b0)
Location: fs/ext4/block_validity.c:222
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/indirect.c:ext4_get_branch
```
**Symbols:**

```
ffffffff813061b0-ffffffff8130625e: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff8131c170)
Location: fs/ext4/block_validity.c:222
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/indirect.c:ext4_get_branch
```
**Symbols:**

```
ffffffff8131c170-ffffffff8131c21e: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff812e4d40)
Location: fs/ext4/block_validity.c:222
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff812e4d40-ffffffff812e4dee: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81309770)
Location: fs/ext4/block_validity.c:223
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff81309770-ffffffff8130981e: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81337650)
Location: fs/ext4/block_validity.c:223
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:ext4_iget
```
**Symbols:**

```
ffffffff81337650-ffffffff813376fe: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff8134e8d0)
Location: fs/ext4/block_validity.c:223
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff8134e8d0-ffffffff8134e97e: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81377410)
Location: fs/ext4/block_validity.c:273
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81377410-ffffffff813774d8: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff8138f760)
Location: fs/ext4/block_validity.c:361
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff8138f760-ffffffff8138f833: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813dacb0)
Location: fs/ext4/block_validity.c:347
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813dacb0-ffffffff813dad69: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813ec9a0)
Location: fs/ext4/block_validity.c:341
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813ec9a0-ffffffff813eca59: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813f2ee0)
Location: fs/ext4/block_validity.c:341
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813f2ee0-ffffffff813f2f99: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81444ed0)
Location: fs/ext4/block_validity.c:341
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81444ed0-ffffffff81444f89: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff814c0f20)
Location: fs/ext4/block_validity.c:349
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff814c0f20-ffffffff814c1001: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff815590d0)
Location: fs/ext4/block_validity.c:349
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff815590d0-ffffffff815591b1: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81590f20)
Location: fs/ext4/block_validity.c:349
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81590f20-ffffffff81591001: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff815c9c60)
Location: fs/ext4/block_validity.c:349
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff815c9c60-ffffffff815c9d41: ext4_check_blockref (STB_GLOBAL)
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
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffff800010462060)
Location: fs/ext4/block_validity.c:361
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffff800010462060-ffff800010462154: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (c0622610)
Location: fs/ext4/block_validity.c:361
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
c0622610-c06226f4: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (c00000000057e9c0)
Location: fs/ext4/block_validity.c:361
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
c00000000057e9c0-c00000000057eb30: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffe0002f0f14)
Location: fs/ext4/block_validity.c:361
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffe0002f0f14-ffffffe0002f0fd0: ext4_check_blockref (STB_GLOBAL)
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
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81387d40)
Location: fs/ext4/block_validity.c:361
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81387d40-ffffffff81387e13: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813787d0)
Location: fs/ext4/block_validity.c:361
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813787d0-ffffffff813788a3: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff81385810)
Location: fs/ext4/block_validity.c:361
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff81385810-ffffffff813858e3: ext4_check_blockref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_check_blockref(const char *function, unsigned int line, struct inode *inode, __le32 *p, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/block_validity.c (ffffffff813993a0)
Location: fs/ext4/block_validity.c:361
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_get_branch
  - fs/ext4/inode.c:__ext4_iget
```
**Symbols:**

```
ffffffff813993a0-ffffffff81399468: ext4_check_blockref (STB_GLOBAL)
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
