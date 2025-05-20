# Function: <code>ext4_truncate_restart_trans</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812987f0)
Location: fs/ext4/inode.c:158
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff812987f0-ffffffff81298861: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c59a0)
Location: fs/ext4/inode.c:164
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff812c59a0-ffffffff812c5a11: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812db1d0)
Location: fs/ext4/inode.c:164
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff812db1d0-ffffffff812db241: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812ffa90)
Location: fs/ext4/inode.c:160
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff812ffa90-ffffffff812ffb06: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813242a0)
Location: fs/ext4/inode.c:170
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff813242a0-ffffffff81324316: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813524e0)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff813524e0-ffffffff81352556: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136a600)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff8136a600-ffffffff8136a676: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81393b00)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff81393b00-ffffffff81393b76: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ac4a0)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff813ac4a0-ffffffff813ac516: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010480bb0)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffff800010480bb0-ffff800010480c3c: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0641c9c)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
c0641c9c-c0641d14: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a4f10)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
c0000000005a4f10-c0000000005a5010: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000309980)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffe000309980-ffffffe0003099fc: ext4_truncate_restart_trans (STB_GLOBAL)
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
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4a80)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff813a4a80-ffffffff813a4af6: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395510)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff81395510-ffffffff81395586: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a22e0)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff813a22e0-ffffffff813a2356: ext4_truncate_restart_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_truncate_restart_trans(handle_t *handle, struct inode *inode, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b69b0)
Location: fs/ext4/inode.c:171
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff813b69b0-ffffffff813b6a26: ext4_truncate_restart_trans (STB_GLOBAL)
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
