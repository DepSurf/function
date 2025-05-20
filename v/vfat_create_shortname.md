# Function: <code>vfat_create_shortname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff812ff6b3)
Location: fs/fat/namei_vfat.c:313
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8133367f)
Location: fs/fat/namei_vfat.c:313
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8134940f)
Location: fs/fat/namei_vfat.c:324
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8135e17f)
Location: fs/fat/namei_vfat.c:324
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81382e54)
Location: fs/fat/namei_vfat.c:326
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff813b1819)
Location: fs/fat/namei_vfat.c:326
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:326
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813caaa0-ffffffff813cb234: vfat_create_shortname (STB_LOCAL)
ffffffff813cc36c-ffffffff813cc378: vfat_create_shortname.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff813f5800-ffffffff813f5f92: vfat_create_shortname (STB_LOCAL)
ffffffff813f6edb-ffffffff813f6ee7: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8140f6d0-ffffffff8140fe62: vfat_create_shortname (STB_LOCAL)
ffffffff81410dab-ffffffff81410db7: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8145d6e0-ffffffff8145df50: vfat_create_shortname (STB_LOCAL)
ffffffff8145ecf7-ffffffff8145ed03: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff814793b0-ffffffff81479c20: vfat_create_shortname (STB_LOCAL)
ffffffff81bedf3d-ffffffff81bedf49: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8147ee20-ffffffff8147f676: vfat_create_shortname (STB_LOCAL)
ffffffff81be0047-ffffffff81be0053: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff814d65d0-ffffffff814d6f1a: vfat_create_shortname (STB_LOCAL)
ffffffff81cd076f-ffffffff81cd077b: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81563920-ffffffff8156447f: vfat_create_shortname (STB_LOCAL)
ffffffff81e839f3-ffffffff81e839ff: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81606550)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81606550-ffffffff816070d8: vfat_create_shortname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8163e3e0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8163e3e0-ffffffff8163ef6f: vfat_create_shortname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81677960)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81677960-ffffffff816784ef: vfat_create_shortname (STB_LOCAL)
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
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffff8000104f0508)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffff8000104f0508-ffff8000104f0c48: vfat_create_shortname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (c06addc0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
c06addc0-c06ae5ec: vfat_create_shortname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (c00000000062f960)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
c00000000062f960-c000000000630230: vfat_create_shortname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffe000360436)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffe000360436-ffffffe000360ab8: vfat_create_shortname (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81407cb0-ffffffff81408442: vfat_create_shortname (STB_LOCAL)
ffffffff8140938b-ffffffff81409397: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff813f8730-ffffffff813f8ec2: vfat_create_shortname (STB_LOCAL)
ffffffff813f9e0b-ffffffff813f9e17: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff81405030-ffffffff814057c2: vfat_create_shortname (STB_LOCAL)
ffffffff8140670b-ffffffff81406717: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfat_create_shortname(struct inode *dir, struct nls_table *nls, wchar_t *uname, int ulen, unsigned char *name_res, unsigned char *lcase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:327
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_build_slots
```
**Symbols:**

```
ffffffff8141acf0-ffffffff8141b482: vfat_create_shortname (STB_LOCAL)
ffffffff8141c3cb-ffffffff8141c3d7: vfat_create_shortname.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
