# Function: <code>selinux_inode_getsecurity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_inode_getsecurity(const struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81347240)
Location: security/selinux/hooks.c:3136
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff81347240-ffffffff81347339: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137cb00)
Location: security/selinux/hooks.c:3217
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff8137cb00-ffffffff8137cc2d: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813935b0)
Location: security/selinux/hooks.c:3252
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff813935b0-ffffffff813936dd: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a9a00)
Location: security/selinux/hooks.c:3239
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff813a9a00-ffffffff813a9ac9: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cf990)
Location: security/selinux/hooks.c:3254
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff813cf990-ffffffff813cfa59: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81401250)
Location: security/selinux/hooks.c:3412
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff81401250-ffffffff8140131b: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8141d6e0)
Location: security/selinux/hooks.c:3160
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff8141d6e0-ffffffff8141d7bf: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144b0f0)
Location: security/selinux/hooks.c:3283
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff8144b0f0-ffffffff8144b1d0: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81464d70)
Location: security/selinux/hooks.c:3341
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff81464d70-ffffffff81464e50: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b7800)
Location: security/selinux/hooks.c:3328
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff814b7800-ffffffff814b78c4: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d54e0)
Location: security/selinux/hooks.c:3339
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff814d54e0-ffffffff814d55b3: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814dc300)
Location: security/selinux/hooks.c:3495
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff814dc300-ffffffff814dc3d6: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3480
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff815357a0-ffffffff81535887: selinux_inode_getsecurity (STB_LOCAL)
ffffffff81cd3da4-ffffffff81cd3dc1: selinux_inode_getsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3370
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff815cbba0-ffffffff815cbc94: selinux_inode_getsecurity (STB_LOCAL)
ffffffff81e86d9c-ffffffff81e86db9: selinux_inode_getsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int selinux_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3388
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff81678d60-ffffffff81678e54: selinux_inode_getsecurity (STB_LOCAL)
ffffffff82073762-ffffffff8207377f: selinux_inode_getsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int selinux_inode_getsecurity(struct mnt_idmap *idmap, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3381
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff816b0f90-ffffffff816b107f: selinux_inode_getsecurity (STB_LOCAL)
ffffffff820f335c-ffffffff820f3379: selinux_inode_getsecurity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_inode_getsecurity(struct mnt_idmap *idmap, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3438
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff816edf40-ffffffff816ee02f: selinux_inode_getsecurity (STB_LOCAL)
ffffffff821d04be-ffffffff821d04db: selinux_inode_getsecurity.cold (STB_LOCAL)
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
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010552eb0)
Location: security/selinux/hooks.c:3341
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffff800010552eb0-ffff800010552fb8: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0706ab0)
Location: security/selinux/hooks.c:3341
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
c0706ab0-c0706bb4: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006ac9b0)
Location: security/selinux/hooks.c:3341
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
c0000000006ac9b0-c0000000006acc30: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003abbd2)
Location: security/selinux/hooks.c:3341
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffe0003abbd2-ffffffe0003abc98: selinux_inode_getsecurity (STB_LOCAL)
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
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145d350)
Location: security/selinux/hooks.c:3341
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff8145d350-ffffffff8145d430: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144dd80)
Location: security/selinux/hooks.c:3341
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff8144dd80-ffffffff8144de60: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814593f0)
Location: security/selinux/hooks.c:3341
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff814593f0-ffffffff814594d0: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146f750)
Location: security/selinux/hooks.c:3341
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecctx
```
**Symbols:**

```
ffffffff8146f750-ffffffff8146f830: selinux_inode_getsecurity (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct inode *inode</code> ➡️ <code>struct inode *inode</code>
</li>
</ul>
</details>
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
<code>inode, name, buffer, alloc</code> ➡️ <code>mnt_userns, inode, name, buffer, alloc</code>
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
