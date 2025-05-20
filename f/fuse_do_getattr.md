# Function: <code>fuse_do_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81313110)
Location: fs/fuse/dir.c:864
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_update_attributes
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
```
**Symbols:**

```
ffffffff81313110-ffffffff8131342c: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81347680)
Location: fs/fuse/dir.c:868
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff81347680-ffffffff813479a3: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8135cfa0)
Location: fs/fuse/dir.c:881
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff8135cfa0-ffffffff8135d2c8: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81371990)
Location: fs/fuse/dir.c:881
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff81371990-ffffffff81371ca9: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81396690)
Location: fs/fuse/dir.c:881
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff81396690-ffffffff813969a9: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813c5240)
Location: fs/fuse/dir.c:882
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff813c5240-ffffffff813c5574: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813de3e0)
Location: fs/fuse/dir.c:879
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff813de3e0-ffffffff813de714: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81409940)
Location: fs/fuse/dir.c:866
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff81409940-ffffffff81409c34: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81424050)
Location: fs/fuse/dir.c:923
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff81424050-ffffffff81424342: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81473590)
Location: fs/fuse/dir.c:923
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff81473590-ffffffff81473773: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148dfb0)
Location: fs/fuse/dir.c:1023
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff8148dfb0-ffffffff8148e1ba: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814938b0)
Location: fs/fuse/dir.c:1040
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff814938b0-ffffffff81493c07: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:988
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff814ead10-ffffffff814eb070: fuse_do_getattr (STB_LOCAL)
ffffffff81cd204a-ffffffff81cd206e: fuse_do_getattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:1068
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff81579830-ffffffff81579b56: fuse_do_getattr (STB_LOCAL)
ffffffff81e8516e-ffffffff81e85192: fuse_do_getattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:1091
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff8161eed0-ffffffff8161f1f6: fuse_do_getattr (STB_LOCAL)
ffffffff82072661-ffffffff82072685: fuse_do_getattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:1157
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff816572f0-ffffffff8165761b: fuse_do_getattr (STB_LOCAL)
ffffffff820f22e1-ffffffff820f2305: fuse_do_getattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81690f40)
Location: fs/fuse/dir.c:1235
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_permission
  - fs/fuse/dir.c:fuse_update_get_attr
```
**Symbols:**

```
ffffffff81690f40-ffffffff8169116e: fuse_do_getattr (STB_LOCAL)
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
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffff800010507818)
Location: fs/fuse/dir.c:923
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffff800010507818-ffff800010507a98: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c36d4)
Location: fs/fuse/dir.c:923
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
```
**Symbols:**

```
c06c36d4-c06c39b8: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c00000000064ce50)
Location: fs/fuse/dir.c:923
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
c00000000064ce50-c00000000064d168: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffe00037367e)
Location: fs/fuse/dir.c:923
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffe00037367e-ffffffe000373932: fuse_do_getattr (STB_LOCAL)
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
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8141c630)
Location: fs/fuse/dir.c:923
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff8141c630-ffffffff8141c922: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8140d0b0)
Location: fs/fuse/dir.c:923
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff8140d0b0-ffffffff8140d3a2: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814187d0)
Location: fs/fuse/dir.c:923
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff814187d0-ffffffff81418ac2: fuse_do_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_do_getattr(struct inode *inode, struct kstat *stat, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8142f540)
Location: fs/fuse/dir.c:923
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_setattr
  - fs/fuse/dir.c:fuse_perm_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff8142f540-ffffffff8142f832: fuse_do_getattr (STB_LOCAL)
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
