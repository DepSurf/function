# Function: <code>selinux_inode_removexattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81348a10)
Location: security/selinux/hooks.c:3121
Inline: False
```
**Symbols:**

```
ffffffff81348a10-ffffffff81348a42: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137dc20)
Location: security/selinux/hooks.c:3202
Inline: False
```
**Symbols:**

```
ffffffff8137dc20-ffffffff8137dc52: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813946b0)
Location: security/selinux/hooks.c:3237
Inline: False
```
**Symbols:**

```
ffffffff813946b0-ffffffff813946e2: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813aa590)
Location: security/selinux/hooks.c:3224
Inline: False
```
**Symbols:**

```
ffffffff813aa590-ffffffff813aa5c2: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813d07b0)
Location: security/selinux/hooks.c:3232
Inline: True
```
**Symbols:**

```
ffffffff813d07b0-ffffffff813d085c: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81402160)
Location: security/selinux/hooks.c:3390
Inline: True
```
**Symbols:**

```
ffffffff81402160-ffffffff8140221c: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8141e400)
Location: security/selinux/hooks.c:3138
Inline: True
```
**Symbols:**

```
ffffffff8141e400-ffffffff8141e4b5: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144bde0)
Location: security/selinux/hooks.c:3261
Inline: True
```
**Symbols:**

```
ffffffff8144bde0-ffffffff8144be98: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81465bc0)
Location: security/selinux/hooks.c:3275
Inline: True
```
**Symbols:**

```
ffffffff81465bc0-ffffffff81465c78: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b9100)
Location: security/selinux/hooks.c:3262
Inline: True
```
**Symbols:**

```
ffffffff814b9100-ffffffff814b91ec: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d7010)
Location: security/selinux/hooks.c:3270
Inline: True
```
**Symbols:**

```
ffffffff814d7010-ffffffff814d7102: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814de0c0)
Location: security/selinux/hooks.c:3425
Inline: True
```
**Symbols:**

```
ffffffff814de0c0-ffffffff814de1b4: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_inode_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81534c5b)
Location: security/selinux/hooks.c:3410
Inline: True
```
**Symbols:**

```
ffffffff81534bd0-ffffffff81534ca2: selinux_inode_removexattr (STB_LOCAL)
ffffffff81cd3d3a-ffffffff81cd3d55: selinux_inode_removexattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_inode_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff815cae96)
Location: security/selinux/hooks.c:3300
Inline: True
```
**Symbols:**

```
ffffffff815cae00-ffffffff815caef9: selinux_inode_removexattr (STB_LOCAL)
ffffffff81e86d31-ffffffff81e86d4b: selinux_inode_removexattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_inode_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff8167adee)
Location: security/selinux/hooks.c:3318
Inline: True
```
**Symbols:**

```
ffffffff8167ad50-ffffffff8167ae82: selinux_inode_removexattr (STB_LOCAL)
ffffffff820738ff-ffffffff8207392e: selinux_inode_removexattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_inode_removexattr(struct mnt_idmap *idmap, struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff816b2f1e)
Location: security/selinux/hooks.c:3311
Inline: True
```
**Symbols:**

```
ffffffff816b2e80-ffffffff816b2fb2: selinux_inode_removexattr (STB_LOCAL)
ffffffff820f34ed-ffffffff820f351c: selinux_inode_removexattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_inode_removexattr(struct mnt_idmap *idmap, struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff816eff5e)
Location: security/selinux/hooks.c:3368
Inline: True
```
**Symbols:**

```
ffffffff816efec0-ffffffff816efff2: selinux_inode_removexattr (STB_LOCAL)
ffffffff821d0670-ffffffff821d069f: selinux_inode_removexattr.cold (STB_LOCAL)
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
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010553dc0)
Location: security/selinux/hooks.c:3275
Inline: True
```
**Symbols:**

```
ffff800010553dc0-ffff800010553e84: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0707e40)
Location: security/selinux/hooks.c:3275
Inline: True
```
**Symbols:**

```
c0707e40-c0707f18: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006aee00)
Location: security/selinux/hooks.c:3275
Inline: True
```
**Symbols:**

```
c0000000006aee00-c0000000006af020: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003ac75a)
Location: security/selinux/hooks.c:3275
Inline: True
```
**Symbols:**

```
ffffffe0003ac75a-ffffffe0003ac7ec: selinux_inode_removexattr (STB_LOCAL)
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
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145e1a0)
Location: security/selinux/hooks.c:3275
Inline: True
```
**Symbols:**

```
ffffffff8145e1a0-ffffffff8145e258: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144ebd0)
Location: security/selinux/hooks.c:3275
Inline: True
```
**Symbols:**

```
ffffffff8144ebd0-ffffffff8144ec88: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145a240)
Location: security/selinux/hooks.c:3275
Inline: True
```
**Symbols:**

```
ffffffff8145a240-ffffffff8145a2f8: selinux_inode_removexattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int selinux_inode_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81470770)
Location: security/selinux/hooks.c:3275
Inline: True
```
**Symbols:**

```
ffffffff81470770-ffffffff81470828: selinux_inode_removexattr (STB_LOCAL)
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
<code>dentry, name</code> ➡️ <code>mnt_userns, dentry, name</code>
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
