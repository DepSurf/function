# Function: <code>fat_search_long</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff812f7bf0)
Location: fs/fat/dir.c:462
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff812f7bf0-ffffffff812f811b: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8132b2b0)
Location: fs/fat/dir.c:462
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff8132b2b0-ffffffff8132b7ee: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81340ff0)
Location: fs/fat/dir.c:462
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff81340ff0-ffffffff8134152e: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81355c40)
Location: fs/fat/dir.c:462
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff81355c40-ffffffff81356183: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8137a860)
Location: fs/fat/dir.c:461
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff8137a860-ffffffff8137adae: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:462
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff813aa992-ffffffff813aa99e: fat_search_long.cold.32 (STB_LOCAL)
ffffffff813a9280-ffffffff813a97bb: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:464
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff813c3772-ffffffff813c377e: fat_search_long.cold.33 (STB_LOCAL)
ffffffff813c2060-ffffffff813c2596: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:465
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff813edfcf-ffffffff813edfdb: fat_search_long.cold (STB_LOCAL)
ffffffff813ec8b0-ffffffff813ecdf3: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff814080ef-ffffffff814080fb: fat_search_long.cold (STB_LOCAL)
ffffffff814069d0-ffffffff81406f13: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
**Symbols:**

```
ffffffff81455baf-ffffffff81455bbb: fat_search_long.cold (STB_LOCAL)
ffffffff814547d0-ffffffff81454b9b: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
**Symbols:**

```
ffffffff81bed822-ffffffff81bed82e: fat_search_long.cold (STB_LOCAL)
ffffffff81470c80-ffffffff8147104b: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
**Symbols:**

```
ffffffff81bdf922-ffffffff81bdf92e: fat_search_long.cold (STB_LOCAL)
ffffffff81476210-ffffffff81476789: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
**Symbols:**

```
ffffffff81ccf9ac-ffffffff81ccf9cf: fat_search_long.cold (STB_LOCAL)
ffffffff814ccd90-ffffffff814cd31c: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
**Symbols:**

```
ffffffff81e82cb6-ffffffff81e82ce7: fat_search_long.cold (STB_LOCAL)
ffffffff8155a000-ffffffff8155a672: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
**Symbols:**

```
ffffffff82071df1-ffffffff82071e16: fat_search_long.cold (STB_LOCAL)
ffffffff815fad80-ffffffff815fb3b8: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
**Symbols:**

```
ffffffff820f1a6f-ffffffff820f1a94: fat_search_long.cold (STB_LOCAL)
ffffffff81632cd0-ffffffff81633343: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
**Symbols:**

```
ffffffff821ced51-ffffffff821ced76: fat_search_long.cold (STB_LOCAL)
ffffffff8166c1a0-ffffffff8166c813: fat_search_long (STB_GLOBAL)
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
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffff8000104e57b8)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffff8000104e57b8-ffff8000104e5c20: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (c06a50b0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
c06a50b0-c06a55a0: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (c000000000623760)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
c000000000623760-c000000000623d10: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffe00035915e)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffe00035915e-ffffffe0003594ec: fat_search_long (STB_GLOBAL)
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
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff814006cf-ffffffff814006db: fat_search_long.cold (STB_LOCAL)
ffffffff813fefb0-ffffffff813ff4f3: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff813f114f-ffffffff813f115b: fat_search_long.cold (STB_LOCAL)
ffffffff813efa30-ffffffff813eff73: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff813fda4f-ffffffff813fda5b: fat_search_long.cold (STB_LOCAL)
ffffffff813fc330-ffffffff813fc873: fat_search_long (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fat_search_long(struct inode *inode, const unsigned char *name, int name_len, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:463
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_find
```
**Symbols:**

```
ffffffff8141367f-ffffffff8141368b: fat_search_long.cold (STB_LOCAL)
ffffffff81411f50-ffffffff81412493: fat_search_long (STB_GLOBAL)
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
