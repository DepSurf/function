# Function: <code>prepare_warning</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812706b0)
Location: fs/quota/dquot.c:1230
Inline: True
Inline callers:
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff812706b0-ffffffff812706fd: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8129d5c3)
Location: fs/quota/dquot.c:1239
Inline: True
Inline callers:
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff8129ca40-ffffffff8129ca8d: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b2f03)
Location: fs/quota/dquot.c:1236
Inline: True
Inline callers:
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff812b2400-ffffffff812b244d: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c0554)
Location: fs/quota/dquot.c:1242
Inline: True
Inline callers:
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_bdq
  - fs/quota/dquot.c:check_idq
  - fs/quota/dquot.c:check_idq
  - fs/quota/dquot.c:check_idq
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff812bf950-ffffffff812bf99d: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e3e5e)
Location: fs/quota/dquot.c:1219
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff812e3370-ffffffff812e33b7: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813109f7)
Location: fs/quota/dquot.c:1216
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff8130fea0-ffffffff8130fee5: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81327c17)
Location: fs/quota/dquot.c:1216
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff81326e30-ffffffff81326e75: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8134f769)
Location: fs/quota/dquot.c:1226
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff8134e9d0-ffffffff8134ea15: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81367a79)
Location: fs/quota/dquot.c:1228
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff81366cc0-ffffffff81366d05: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b1ddb)
Location: fs/quota/dquot.c:1226
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
**Symbols:**

```
ffffffff813ae770-ffffffff813ae7b7: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c33bd)
Location: fs/quota/dquot.c:1227
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
**Symbols:**

```
ffffffff813bfd60-ffffffff813bfda7: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c99a3)
Location: fs/quota/dquot.c:1225
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
**Symbols:**

```
ffffffff813c6c00-ffffffff813c6c47: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8141a248)
Location: fs/quota/dquot.c:1230
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
**Symbols:**

```
ffffffff81416f80-ffffffff81416fc7: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81493261)
Location: fs/quota/dquot.c:1240
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
**Symbols:**

```
ffffffff8148f350-ffffffff8148f3b3: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81526f21)
Location: fs/quota/dquot.c:1240
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
**Symbols:**

```
ffffffff81522df0-ffffffff81522e53: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8155f3e9)
Location: fs/quota/dquot.c:1298
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
**Symbols:**

```
ffffffff8155af70-ffffffff8155afd3: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81595ad9)
Location: fs/quota/dquot.c:1252
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
**Symbols:**

```
ffffffff81591730-ffffffff81591793: prepare_warning (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff8000104328f0)
Location: fs/quota/dquot.c:1228
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffff80001042ebb8-ffff80001042ec94: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c05f80f8)
Location: fs/quota/dquot.c:1228
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
c05f7b7c-c05f7bec: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c0000000005404e0)
Location: fs/quota/dquot.c:1228
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
c00000000053f9e0-c00000000053fa7c: prepare_warning (STB_LOCAL)
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
In fs/quota/dquot.c (ffffffe0002ce942)
Location: fs/quota/dquot.c:1228
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81360059)
Location: fs/quota/dquot.c:1228
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff8135f2a0-ffffffff8135f2e5: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81350cf9)
Location: fs/quota/dquot.c:1228
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff8134ff40-ffffffff8134ff85: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135db29)
Location: fs/quota/dquot.c:1228
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff8135cd70-ffffffff8135cdb5: prepare_warning (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void prepare_warning(struct dquot_warn *warn, struct dquot *dquot, int warntype);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813713b7)
Location: fs/quota/dquot.c:1228
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_space
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
  - fs/quota/dquot.c:dquot_add_inodes
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_free_inode
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff813705e0-ffffffff81370625: prepare_warning (STB_LOCAL)
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
