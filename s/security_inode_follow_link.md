# Function: <code>security_inode_follow_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133d840)
Location: security/security.c:594
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
**Symbols:**

```
ffffffff8133d840-ffffffff8133d8a5: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81372e70)
Location: security/security.c:595
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
**Symbols:**

```
ffffffff81372e70-ffffffff81372ed5: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813897a0)
Location: security/security.c:604
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
**Symbols:**

```
ffffffff813897a0-ffffffff81389805: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139eb80)
Location: security/security.c:1209
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
**Symbols:**

```
ffffffff8139eb80-ffffffff8139ebe5: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c4600)
Location: security/security.c:1158
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
**Symbols:**

```
ffffffff813c4600-ffffffff813c466b: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f4a30)
Location: security/security.c:700
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
```
**Symbols:**

```
ffffffff813f4a30-ffffffff813f4a88: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140fe00)
Location: security/security.c:1221
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff8140fe00-ffffffff8140fe58: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143d4a0)
Location: security/security.c:1234
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff8143d4a0-ffffffff8143d501: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456f30)
Location: security/security.c:1274
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff81456f30-ffffffff81456f86: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9d40)
Location: security/security.c:1422
Inline: False
Direct callers:
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff814a9d40-ffffffff814a9d96: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7350)
Location: security/security.c:1424
Inline: False
Direct callers:
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff814c7350-ffffffff814c73a6: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd790)
Location: security/security.c:1471
Inline: False
Direct callers:
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff814cd790-ffffffff814cd7e6: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815266e0)
Location: security/security.c:1477
Inline: False
Direct callers:
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff815266e0-ffffffff81526736: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bafc0)
Location: security/security.c:1484
Inline: False
Direct callers:
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff815bafc0-ffffffff815bb03f: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81666a90)
Location: security/security.c:1482
Inline: False
Direct callers:
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff81666a90-ffffffff81666b0f: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169f080)
Location: security/security.c:2199
Inline: False
Direct callers:
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff8169f080-ffffffff8169f0ff: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816db9d0)
Location: security/security.c:2272
Inline: False
Direct callers:
  - fs/namei.c:pick_link
```
**Symbols:**

```
ffffffff816db9d0-ffffffff816dba4f: security_inode_follow_link (STB_GLOBAL)
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
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105429c8)
Location: security/security.c:1274
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffff8000105429c8-ffff800010542a34: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f8988)
Location: security/security.c:1274
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
c06f8988-c06f89f8: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000696110)
Location: security/security.c:1274
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
c000000000696110-c0000000006961d8: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f1d8)
Location: security/security.c:1274
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffe00039f1d8-ffffffe00039f22e: security_inode_follow_link (STB_GLOBAL)
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
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f510)
Location: security/security.c:1274
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff8144f510-ffffffff8144f566: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ff60)
Location: security/security.c:1274
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff8143ff60-ffffffff8143ffb6: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144b5b0)
Location: security/security.c:1274
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff8144b5b0-ffffffff8144b606: security_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462980)
Location: security/security.c:1274
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
```
**Symbols:**

```
ffffffff81462980-ffffffff814629d6: security_inode_follow_link (STB_GLOBAL)
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
