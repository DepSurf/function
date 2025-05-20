# Function: <code>cap_convert_nscap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8139b3c0)
Location: security/commoncap.c:490
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff8139b3c0-ffffffff8139b535: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813c09d0)
Location: security/commoncap.c:481
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff813c09d0-ffffffff813c0b4d: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813f1940)
Location: security/commoncap.c:483
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff813f1940-ffffffff813f1ab0: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8140cc10)
Location: security/commoncap.c:481
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff8140cc10-ffffffff8140cd80: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81439db0)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff81439db0-ffffffff81439f1e: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81453c20)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff81453c20-ffffffff81453d8e: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814a6530)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff814a6530-ffffffff814a669e: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, const void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814c3ae0)
Location: security/commoncap.c:495
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
```
**Symbols:**

```
ffffffff814c3ae0-ffffffff814c3c43: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cap_convert_nscap(struct user_namespace *mnt_userns, struct dentry *dentry, const void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814c9f40)
Location: security/commoncap.c:537
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
```
**Symbols:**

```
ffffffff814c9f40-ffffffff814ca0ea: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cap_convert_nscap(struct user_namespace *mnt_userns, struct dentry *dentry, const void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81522be0)
Location: security/commoncap.c:537
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
```
**Symbols:**

```
ffffffff81522be0-ffffffff81522d8a: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cap_convert_nscap(struct user_namespace *mnt_userns, struct dentry *dentry, const void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff815b68d0)
Location: security/commoncap.c:540
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
```
**Symbols:**

```
ffffffff815b68d0-ffffffff815b6abb: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cap_convert_nscap(struct user_namespace *mnt_userns, struct dentry *dentry, const void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81661a70)
Location: security/commoncap.c:530
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
```
**Symbols:**

```
ffffffff81661a70-ffffffff81661c62: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cap_convert_nscap(struct mnt_idmap *idmap, struct dentry *dentry, const void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8169a0f0)
Location: security/commoncap.c:530
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
```
**Symbols:**

```
ffffffff8169a0f0-ffffffff8169a2af: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cap_convert_nscap(struct mnt_idmap *idmap, struct dentry *dentry, const void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff816d6800)
Location: security/commoncap.c:530
Inline: False
Direct callers:
  - fs/xattr.c:vfs_setxattr
```
**Symbols:**

```
ffffffff816d6800-ffffffff816d69ee: cap_convert_nscap (STB_GLOBAL)
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
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffff80001053ed28)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffff80001053ed28-ffff80001053eeb4: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c06f4d18)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
c06f4d18-c06f4e88: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c00000000068f550)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
c00000000068f550-c00000000068f774: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffe00039c38e)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffe00039c38e-ffffffe00039c4ce: cap_convert_nscap (STB_GLOBAL)
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
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8144c200)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff8144c200-ffffffff8144c36e: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8143cc50)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff8143cc50-ffffffff8143cdbe: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814482a0)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff814482a0-ffffffff8144840e: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cap_convert_nscap(struct dentry *dentry, void **ivalue, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8145f670)
Location: security/commoncap.c:476
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
```
**Symbols:**

```
ffffffff8145f670-ffffffff8145f7de: cap_convert_nscap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void **ivalue</code> ➡️ <code>const void **ivalue</code>
</li>
</ul>
</details>
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
<code>dentry, ivalue, size</code> ➡️ <code>mnt_userns, dentry, ivalue, size</code>
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
