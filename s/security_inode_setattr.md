# Function: <code>security_inode_setattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c560)
Location: security/security.c:610
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff8133c560-ffffffff8133c5c5: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81371b30)
Location: security/security.c:611
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff81371b30-ffffffff81371b95: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388460)
Location: security/security.c:620
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff81388460-ffffffff813884c5: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d4c0)
Location: security/security.c:1225
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff8139d4c0-ffffffff8139d525: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2da0)
Location: security/security.c:1174
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff813c2da0-ffffffff813c2e0b: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f39d0)
Location: security/security.c:716
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff813f39d0-ffffffff813f3a2a: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140ede0)
Location: security/security.c:1237
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffff8140ede0-ffffffff8140ee3a: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c140)
Location: security/security.c:1250
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff8143c140-ffffffff8143c1a3: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455df0)
Location: security/security.c:1290
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff81455df0-ffffffff81455e4a: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8c20)
Location: security/security.c:1438
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff814a8c20-ffffffff814a8c7a: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6190)
Location: security/security.c:1440
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff814c6190-ffffffff814c61ea: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc440)
Location: security/security.c:1486
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff814cc440-ffffffff814cc49a: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815252d0)
Location: security/security.c:1493
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff815252d0-ffffffff8152532a: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b9240)
Location: security/security.c:1499
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff815b9240-ffffffff815b92bb: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_inode_setattr(struct user_namespace *mnt_userns, struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816649b0)
Location: security/security.c:1497
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff816649b0-ffffffff81664a3d: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_inode_setattr(struct mnt_idmap *idmap, struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169ce90)
Location: security/security.c:2241
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff8169ce90-ffffffff8169cf1d: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_inode_setattr(struct mnt_idmap *idmap, struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9820)
Location: security/security.c:2314
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff816d9820-ffffffff816d98ad: security_inode_setattr (STB_GLOBAL)
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
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105414d0)
Location: security/security.c:1290
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffff8000105414d0-ffff800010541554: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f74d0)
Location: security/security.c:1290
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
c06f74d0-c06f754c: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693c60)
Location: security/security.c:1290
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
c000000000693c60-c000000000693d18: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e202)
Location: security/security.c:1290
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_generic_ioctl
```
**Symbols:**

```
ffffffe00039e202-ffffffe00039e26c: security_inode_setattr (STB_GLOBAL)
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
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e3d0)
Location: security/security.c:1290
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff8144e3d0-ffffffff8144e42a: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ee20)
Location: security/security.c:1290
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff8143ee20-ffffffff8143ee7a: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a470)
Location: security/security.c:1290
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff8144a470-ffffffff8144a4ca: security_inode_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_inode_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461840)
Location: security/security.c:1290
Inline: False
Direct callers:
  - fs/attr.c:notify_change
  - fs/fat/file.c:fat_ioctl_set_attributes
```
**Symbols:**

```
ffffffff81461840-ffffffff8146189a: security_inode_setattr (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, attr</code> ➡️ <code>mnt_userns, dentry, attr</code>
</li>
</ul>
</details>
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
