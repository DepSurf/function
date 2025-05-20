# Function: <code>ima_must_appraise</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8139a370)
Location: security/integrity/ima/ima_appraise.c:40
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff8139a370-ffffffff8139a396: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff813d7781)
Location: security/integrity/ima/ima_appraise.c:39
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
```
**Symbols:**

```
ffffffff813d71c0-ffffffff813d71e9: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff813ef45a)
Location: security/integrity/ima/ima_appraise.c:39
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
```
**Symbols:**

```
ffffffff813eee60-ffffffff813eee89: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff813fba29)
Location: security/integrity/ima/ima_appraise.c:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
```
**Symbols:**

```
ffffffff813fb3d0-ffffffff813fb3fa: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81423ef9)
Location: security/integrity/ima/ima_appraise.c:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
```
**Symbols:**

```
ffffffff81423870-ffffffff8142389a: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8145664b)
Location: security/integrity/ima/ima_appraise.c:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff81455e70-ffffffff81455ef2: ima_must_appraise.part.7 (STB_LOCAL)
ffffffff81455f20-ffffffff81455f3b: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81473abb)
Location: security/integrity/ima/ima_appraise.c:51
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff81473270-ffffffff814732f2: ima_must_appraise.part.7 (STB_LOCAL)
ffffffff81473320-ffffffff8147333b: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814a17b4)
Location: security/integrity/ima/ima_appraise.c:48
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff814a0f70-ffffffff814a0ff3: ima_must_appraise.part.0 (STB_LOCAL)
ffffffff814a1020-ffffffff814a103b: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814bc254)
Location: security/integrity/ima/ima_appraise.c:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff814bb730-ffffffff814bb7b3: ima_must_appraise.part.0 (STB_LOCAL)
ffffffff814bb7e0-ffffffff814bb7fb: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8151c705)
Location: security/integrity/ima/ima_appraise.c:55
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
```
**Symbols:**

```
ffffffff8151bd90-ffffffff8151be22: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81539575)
Location: security/integrity/ima/ima_appraise.c:71
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
```
**Symbols:**

```
ffffffff81538c00-ffffffff81538c92: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct user_namespace *mnt_userns, struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81541c87)
Location: security/integrity/ima/ima_appraise.c:71
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
```
**Symbols:**

```
ffffffff81541320-ffffffff815413d0: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct user_namespace *mnt_userns, struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff815a1a47)
Location: security/integrity/ima/ima_appraise.c:71
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
```
**Symbols:**

```
ffffffff815a10a0-ffffffff815a1152: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct user_namespace *mnt_userns, struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81647e2f)
Location: security/integrity/ima/ima_appraise.c:73
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
```
**Symbols:**

```
ffffffff81647330-ffffffff81647402: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct user_namespace *mnt_userns, struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8170067f)
Location: security/integrity/ima/ima_appraise.c:73
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
```
**Symbols:**

```
ffffffff816ffb10-ffffffff816ffbe2: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct mnt_idmap *idmap, struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8173a71f)
Location: security/integrity/ima/ima_appraise.c:73
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
```
**Symbols:**

```
ffffffff81739b80-ffffffff81739c52: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ima_must_appraise(struct mnt_idmap *idmap, struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8177b247)
Location: security/integrity/ima/ima_appraise.c:73
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
```
**Symbols:**

```
ffffffff8177a6a0-ffffffff8177a76a: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffff8000105b4b20)
Location: security/integrity/ima/ima_appraise.c:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffff8000105b3e60-ffff8000105b3ef4: ima_must_appraise.part.0 (STB_LOCAL)
ffff8000105b3fe8-ffff8000105b4038: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (c0763ef8)
Location: security/integrity/ima/ima_appraise.c:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
c0763210-c07632bc: ima_must_appraise.part.0 (STB_LOCAL)
c07632e4-c076331c: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (c000000000737868)
Location: security/integrity/ima/ima_appraise.c:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
c0000000007367f0-c0000000007368a0: ima_must_appraise.part.0 (STB_LOCAL)
c0000000007368d0-c000000000736904: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffe0003fbcb4)
Location: security/integrity/ima/ima_appraise.c:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffe0003fb2f2-ffffffe0003fb34a: ima_must_appraise.part.0 (STB_LOCAL)
ffffffe0003fb36e-ffffffe0003fb3b2: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814b4834)
Location: security/integrity/ima/ima_appraise.c:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff814b3d10-ffffffff814b3d93: ima_must_appraise.part.0 (STB_LOCAL)
ffffffff814b3dc0-ffffffff814b3ddb: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814a5254)
Location: security/integrity/ima/ima_appraise.c:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff814a4730-ffffffff814a47b3: ima_must_appraise.part.0 (STB_LOCAL)
ffffffff814a47e0-ffffffff814a47fb: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814b08c4)
Location: security/integrity/ima/ima_appraise.c:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff814afda0-ffffffff814afe23: ima_must_appraise.part.0 (STB_LOCAL)
ffffffff814afe50-ffffffff814afe6b: ima_must_appraise (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ima_must_appraise(struct inode *inode, int mask, enum ima_hooks func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814c9344)
Location: security/integrity/ima/ima_appraise.c:49
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
Direct callers:
  - security/integrity/ima/ima_main.c:ima_post_path_mknod
  - security/integrity/ima/ima_main.c:ima_post_create_tmpfile
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
```
**Symbols:**

```
ffffffff814c8820-ffffffff814c88a3: ima_must_appraise.part.0 (STB_LOCAL)
ffffffff814c88d0-ffffffff814c88eb: ima_must_appraise (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, mask, func</code> ➡️ <code>mnt_userns, inode, mask, func</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
