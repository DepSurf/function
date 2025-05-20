# Function: <code>fat_add_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff812f6f60)
Location: fs/fat/dir.c:1275
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff812f6f60-ffffffff812f74f7: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff8132a610)
Location: fs/fat/dir.c:1275
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8132a610-ffffffff8132abbc: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81340350)
Location: fs/fat/dir.c:1275
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81340350-ffffffff813408fc: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81354f20)
Location: fs/fat/dir.c:1275
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81354f20-ffffffff8135551c: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffff81379b40)
Location: fs/fat/dir.c:1274
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81379b40-ffffffff8137a13c: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1275
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813aa92f-ffffffff813aa992: fat_add_entries.cold.31 (STB_LOCAL)
ffffffff813a8380-ffffffff813a8907: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1277
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813c370f-ffffffff813c3772: fat_add_entries.cold.32 (STB_LOCAL)
ffffffff813c13c0-ffffffff813c1947: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1278
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813edf6f-ffffffff813edfcf: fat_add_entries.cold (STB_LOCAL)
ffffffff813ebc20-ffffffff813ec185: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1285
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8140808f-ffffffff814080ef: fat_add_entries.cold (STB_LOCAL)
ffffffff81405d40-ffffffff814062a5: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1281
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81455b4f-ffffffff81455baf: fat_add_entries.cold (STB_LOCAL)
ffffffff81453e10-ffffffff8145436b: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1281
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81bed7c2-ffffffff81bed822: fat_add_entries.cold (STB_LOCAL)
ffffffff814702c0-ffffffff8147081b: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1281
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81bdf8c5-ffffffff81bdf922: fat_add_entries.cold (STB_LOCAL)
ffffffff81475740-ffffffff81475cad: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1281
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81ccfa11-ffffffff81ccfacd: fat_add_entries.cold (STB_LOCAL)
ffffffff814cd7e0-ffffffff814cdeaa: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1281
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81e82bf5-ffffffff81e82cb6: fat_add_entries.cold (STB_LOCAL)
ffffffff81559730-ffffffff81559ff2: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1281
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff82071edd-ffffffff82071f30: fat_add_entries.cold (STB_LOCAL)
ffffffff815fc840-ffffffff815fd1ab: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1281
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff820f1b40-ffffffff820f1b93: fat_add_entries.cold (STB_LOCAL)
ffffffff816347d0-ffffffff81635145: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1281
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff821cee22-ffffffff821cee75: fat_add_entries.cold (STB_LOCAL)
ffffffff8166dcb0-ffffffff8166e625: fat_add_entries (STB_GLOBAL)
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
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffff8000104e4bd8)
Location: fs/fat/dir.c:1285
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffff8000104e4bd8-ffff8000104e514c: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (c06a3fa8)
Location: fs/fat/dir.c:1285
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
c06a3fa8-c06a45b4: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (c000000000622730)
Location: fs/fat/dir.c:1285
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
c000000000622730-c000000000622de4: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/dir.c (ffffffe000357f92)
Location: fs/fat/dir.c:1285
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffe000357f92-ffffffe0003583f0: fat_add_entries (STB_GLOBAL)
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
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1285
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8140066f-ffffffff814006cf: fat_add_entries.cold (STB_LOCAL)
ffffffff813fe320-ffffffff813fe885: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1285
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813f10ef-ffffffff813f114f: fat_add_entries.cold (STB_LOCAL)
ffffffff813eeda0-ffffffff813ef305: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1285
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813fd9ef-ffffffff813fda4f: fat_add_entries.cold (STB_LOCAL)
ffffffff813fb6a0-ffffffff813fbc05: fat_add_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fat_add_entries(struct inode *dir, void *slots, int nr_slots, struct fat_slot_info *sinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/dir.c (0)
Location: fs/fat/dir.c:1285
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8141361f-ffffffff8141367f: fat_add_entries.cold (STB_LOCAL)
ffffffff814112c0-ffffffff81411825: fat_add_entries (STB_GLOBAL)
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
