# Function: <code>ext4_inode_attach_jinode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81296d60)
Location: fs/ext4/inode.c:3727
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/inode.c:ext4_truncate
```
**Symbols:**

```
ffffffff81296d60-ffffffff81296e05: ext4_inode_attach_jinode.part.60 (STB_LOCAL)
ffffffff81299b60-ffffffff81299b92: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff812ca768)
Location: fs/ext4/inode.c:4035
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff812c4380-ffffffff812c4425: ext4_inode_attach_jinode.part.68 (STB_LOCAL)
ffffffff812c7240-ffffffff812c7273: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff812e03fc)
Location: fs/ext4/inode.c:4161
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
```
**Symbols:**

```
ffffffff812d9a30-ffffffff812d9ad5: ext4_inode_attach_jinode.part.68 (STB_LOCAL)
ffffffff812dcd40-ffffffff812dcd73: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff8130482d)
Location: fs/ext4/inode.c:4283
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff812fd950-ffffffff812fd9f5: ext4_inode_attach_jinode.part.70 (STB_LOCAL)
ffffffff813015d0-ffffffff81301603: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff8132923d)
Location: fs/ext4/inode.c:4332
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
**Symbols:**

```
ffffffff81322130-ffffffff813221d5: ext4_inode_attach_jinode.part.67 (STB_LOCAL)
ffffffff81325f70-ffffffff81325fa3: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813575dd)
Location: fs/ext4/inode.c:4380
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81352380-ffffffff81352422: ext4_inode_attach_jinode.part.72 (STB_LOCAL)
ffffffff81354320-ffffffff81354352: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136f90d)
Location: fs/ext4/inode.c:4410
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81368e50-ffffffff81368ef2: ext4_inode_attach_jinode.part.76 (STB_LOCAL)
ffffffff8136c590-ffffffff8136c5c2: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff81398f81)
Location: fs/ext4/inode.c:4422
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
**Symbols:**

```
ffffffff81392260-ffffffff81392302: ext4_inode_attach_jinode.part.0 (STB_LOCAL)
ffffffff81395b50-ffffffff81395b82: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b1a01)
Location: fs/ext4/inode.c:4408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813aabf0-ffffffff813aac92: ext4_inode_attach_jinode.part.0 (STB_LOCAL)
ffffffff813ae520-ffffffff813ae552: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fa4c0)
Location: fs/ext4/inode.c:4105
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813fa4c0-ffffffff813fa579: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140ca90)
Location: fs/ext4/inode.c:4141
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff8140ca90-ffffffff8140cb49: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412c10)
Location: fs/ext4/inode.c:4140
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81412c10-ffffffff81412cc9: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81465f40)
Location: fs/ext4/inode.c:4063
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81465f40-ffffffff81465ff9: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e59e0)
Location: fs/ext4/inode.c:4133
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff814e59e0-ffffffff814e5aa5: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157f110)
Location: fs/ext4/inode.c:4219
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff8157f110-ffffffff8157f1d5: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b65c0)
Location: fs/ext4/inode.c:4004
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_open
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff815b65c0-ffffffff815b6685: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ef360)
Location: fs/ext4/inode.c:4023
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff815ef360-ffffffff815ef425: ext4_inode_attach_jinode (STB_GLOBAL)
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
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffff800010486398)
Location: fs/ext4/inode.c:4408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffff80001047de30-ffff80001047df44: ext4_inode_attach_jinode.part.0 (STB_LOCAL)
ffff800010483080-ffff8000104830d4: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (c0648230)
Location: fs/ext4/inode.c:4408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
c063f80c-c063f8c8: ext4_inode_attach_jinode.part.0 (STB_LOCAL)
c064446c-c06444b0: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (c0000000005abde8)
Location: fs/ext4/inode.c:4408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
c0000000005a2210-c0000000005a236c: ext4_inode_attach_jinode.part.0 (STB_LOCAL)
c0000000005a7e60-c0000000005a7ea8: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030e28e)
Location: fs/ext4/inode.c:4408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffe0003082b0-ffffffe00030838a: ext4_inode_attach_jinode.part.0 (STB_LOCAL)
ffffffe00030b7a6-ffffffe00030b7f0: ext4_inode_attach_jinode (STB_GLOBAL)
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
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a9fe1)
Location: fs/ext4/inode.c:4408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813a31d0-ffffffff813a3272: ext4_inode_attach_jinode.part.0 (STB_LOCAL)
ffffffff813a6b00-ffffffff813a6b32: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139aa71)
Location: fs/ext4/inode.c:4408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81393c60-ffffffff81393d02: ext4_inode_attach_jinode.part.0 (STB_LOCAL)
ffffffff81397590-ffffffff813975c2: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a7841)
Location: fs/ext4/inode.c:4408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813a0a30-ffffffff813a0ad2: ext4_inode_attach_jinode.part.0 (STB_LOCAL)
ffffffff813a4360-ffffffff813a4392: ext4_inode_attach_jinode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_inode_attach_jinode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (ffffffff813bc087)
Location: fs/ext4/inode.c:4408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
Direct callers:
  - fs/ext4/inode.c:ext4_truncate
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813b4830-ffffffff813b48e2: ext4_inode_attach_jinode.part.0 (STB_LOCAL)
ffffffff813b8a60-ffffffff813b8a92: ext4_inode_attach_jinode (STB_GLOBAL)
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
