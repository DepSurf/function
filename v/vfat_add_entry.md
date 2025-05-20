# Function: <code>vfat_add_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, struct qstr *qname, int is_dir, int cluster, struct timespec *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff812ff440)
Location: fs/fat/namei_vfat.c:655
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff812ff440-ffffffff813003f8: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81333430)
Location: fs/fat/namei_vfat.c:655
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff81333430-ffffffff81334330: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff813491c0)
Location: fs/fat/namei_vfat.c:666
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff813491c0-ffffffff8134a0c0: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8135dd60)
Location: fs/fat/namei_vfat.c:666
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff8135dd60-ffffffff8135ebd9: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81382a60)
Location: fs/fat/namei_vfat.c:655
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff81382a60-ffffffff81383897: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/namei_vfat.c (0)
Location: fs/fat/namei_vfat.c:655
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff813b1450-ffffffff813b22fe: vfat_add_entry (STB_LOCAL)
ffffffff813b2e82-ffffffff813b2e8e: vfat_add_entry.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff813cb240)
Location: fs/fat/namei_vfat.c:655
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff813cb240-ffffffff813cb85e: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff813f6480)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff813f6480-ffffffff813f65d4: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81410350)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff81410350-ffffffff814104a4: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8145e290)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff8145e290-ffffffff8145e3e4: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81479f60)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff81479f60-ffffffff8147a0b4: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8147f9a0)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff8147f9a0-ffffffff8147faf4: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff814d7240)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff814d7240-ffffffff814d7394: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff815647d0)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff815647d0-ffffffff8156491e: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81607450)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff81607450-ffffffff8160759e: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8163f2e0)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff8163f2e0-ffffffff8163f42e: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81678860)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff81678860-ffffffff816789dd: vfat_add_entry (STB_LOCAL)
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
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffff8000104f11a0)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffff8000104f11a0-ffff8000104f1314: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (c06aeb4c)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
c06aeb4c-c06aecb4: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (c000000000630990)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
c000000000630990-c000000000630b64: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffe00036102a)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffe00036102a-ffffffe00036114a: vfat_add_entry (STB_LOCAL)
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
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81408930)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff81408930-ffffffff81408a84: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff813f93b0)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff813f93b0-ffffffff813f9504: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81405cb0)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff81405cb0-ffffffff81405e04: vfat_add_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfat_add_entry(struct inode *dir, const struct qstr *qname, int is_dir, int cluster, struct timespec64 *ts, struct fat_slot_info *sinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8141b970)
Location: fs/fat/namei_vfat.c:656
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_rename
  - fs/fat/namei_vfat.c:vfat_mkdir
  - fs/fat/namei_vfat.c:vfat_create
```
**Symbols:**

```
ffffffff8141b970-ffffffff8141bac4: vfat_add_entry (STB_LOCAL)
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
<code>struct qstr *qname</code> ➡️ <code>const struct qstr *qname</code>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *ts</code> ➡️ <code>struct timespec64 *ts</code>
</li>
</ul>
</details>
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
