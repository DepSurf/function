# Function: <code>truncate_upper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81302060)
Location: fs/ecryptfs/inode.c:734
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff81302060-ffffffff8130230f: truncate_upper.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81336030)
Location: fs/ecryptfs/inode.c:719
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff81336030-ffffffff813362bc: truncate_upper.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8134bcf0)
Location: fs/ecryptfs/inode.c:718
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff8134bcf0-ffffffff8134bf7c: truncate_upper.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81360880)
Location: fs/ecryptfs/inode.c:718
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff81360880-ffffffff81360ad8: truncate_upper.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81385550)
Location: fs/ecryptfs/inode.c:714
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff81385550-ffffffff813857a8: truncate_upper.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:712
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff813b42c0-ffffffff813b4514: truncate_upper.isra.19 (STB_LOCAL)
ffffffff813b5343-ffffffff813b536a: truncate_upper.isra.19.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:717
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff813cd7e0-ffffffff813cda34: truncate_upper.isra.20 (STB_LOCAL)
ffffffff813ce863-ffffffff813ce88a: truncate_upper.isra.20.cold.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:703
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff813f8390-ffffffff813f85e8: truncate_upper.isra.0 (STB_LOCAL)
ffffffff813f93b1-ffffffff813f93d8: truncate_upper.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:725
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff814121f0-ffffffff81412448: truncate_upper.isra.0 (STB_LOCAL)
ffffffff8141327d-ffffffff814132a4: truncate_upper.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int truncate_upper(struct dentry *dentry, struct iattr *ia, struct iattr *lower_ia);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:725
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff81460820-ffffffff81460a7a: truncate_upper (STB_LOCAL)
ffffffff81461465-ffffffff8146148c: truncate_upper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int truncate_upper(struct dentry *dentry, struct iattr *ia, struct iattr *lower_ia);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:725
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff8147c440-ffffffff8147c689: truncate_upper (STB_LOCAL)
ffffffff81bee0d2-ffffffff81bee0f9: truncate_upper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int truncate_upper(struct dentry *dentry, struct iattr *ia, struct iattr *lower_ia);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:724
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff81481ef0-ffffffff81482136: truncate_upper (STB_LOCAL)
ffffffff81be016e-ffffffff81be0195: truncate_upper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int truncate_upper(struct dentry *dentry, struct iattr *ia, struct iattr *lower_ia);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:724
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff814d8e70-ffffffff814d9024: truncate_upper (STB_LOCAL)
ffffffff81cd088c-ffffffff81cd08b3: truncate_upper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int truncate_upper(struct dentry *dentry, struct iattr *ia, struct iattr *lower_ia);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:724
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff81566650-ffffffff81566814: truncate_upper (STB_LOCAL)
ffffffff81e83b1a-ffffffff81e83b49: truncate_upper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int truncate_upper(struct dentry *dentry, struct iattr *ia, struct iattr *lower_ia);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81609bc0)
Location: fs/ecryptfs/inode.c:726
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff81609bc0-ffffffff81609da0: truncate_upper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int truncate_upper(struct dentry *dentry, struct iattr *ia, struct iattr *lower_ia);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff81641a80)
Location: fs/ecryptfs/inode.c:726
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff81641a80-ffffffff81641c5a: truncate_upper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int truncate_upper(struct dentry *dentry, struct iattr *ia, struct iattr *lower_ia);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffff8167b0a0)
Location: fs/ecryptfs/inode.c:736
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff8167b0a0-ffffffff8167b27a: truncate_upper (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (ffff8000104f35f0)
Location: fs/ecryptfs/inode.c:725
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffff8000104f35f0-ffff8000104f3860: truncate_upper.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int truncate_upper(struct dentry *dentry, struct iattr *ia, struct iattr *lower_ia);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/inode.c (c06b0d64)
Location: fs/ecryptfs/inode.c:725
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
c06b0d64-c06b1104: truncate_upper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (c000000000633790)
Location: fs/ecryptfs/inode.c:725
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
c000000000633790-c000000000633ae0: truncate_upper.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (ffffffe000362af2)
Location: fs/ecryptfs/inode.c:725
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffe000362af2-ffffffe000362d06: truncate_upper.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:725
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff8140a7d0-ffffffff8140aa28: truncate_upper.isra.0 (STB_LOCAL)
ffffffff8140b85d-ffffffff8140b884: truncate_upper.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:725
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff813fb250-ffffffff813fb4a8: truncate_upper.isra.0 (STB_LOCAL)
ffffffff813fc2dd-ffffffff813fc304: truncate_upper.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:725
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff81407b50-ffffffff81407da8: truncate_upper.isra.0 (STB_LOCAL)
ffffffff81408bdd-ffffffff81408c04: truncate_upper.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/inode.c (0)
Location: fs/ecryptfs/inode.c:725
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
```
**Symbols:**

```
ffffffff8141d810-ffffffff8141da68: truncate_upper.isra.0 (STB_LOCAL)
ffffffff8141e89d-ffffffff8141e8c4: truncate_upper.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
