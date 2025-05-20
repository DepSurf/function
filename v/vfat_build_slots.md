# Function: <code>vfat_build_slots</code>

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
In fs/fat/namei_vfat.c (ffffffff812ff50c)
Location: fs/fat/namei_vfat.c:578
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
In fs/fat/namei_vfat.c (ffffffff813334ff)
Location: fs/fat/namei_vfat.c:578
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
In fs/fat/namei_vfat.c (ffffffff8134928f)
Location: fs/fat/namei_vfat.c:589
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
In fs/fat/namei_vfat.c (ffffffff8135de37)
Location: fs/fat/namei_vfat.c:589
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
In fs/fat/namei_vfat.c (ffffffff81382b30)
Location: fs/fat/namei_vfat.c:578
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
In fs/fat/namei_vfat.c (ffffffff813b152d)
Location: fs/fat/namei_vfat.c:578
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff813cb310)
Location: fs/fat/namei_vfat.c:578
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff813f5fa0)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813f5fa0-ffffffff813f6475: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8140fe70)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8140fe70-ffffffff81410345: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8145df50)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8145df50-ffffffff8145e288: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81479c20)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81479c20-ffffffff81479f58: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8147f680)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8147f680-ffffffff8147f999: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff814d6f20)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff814d6f20-ffffffff814d7239: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81564480)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81564480-ffffffff815647c3: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff816070f0)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff816070f0-ffffffff81607433: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8163ef80)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8163ef80-ffffffff8163f2c3: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81678500)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81678500-ffffffff81678843: vfat_build_slots (STB_LOCAL)
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
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffff8000104f0c48)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffff8000104f0c48-ffff8000104f11a0: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (c06ae5ec)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
c06ae5ec-c06aeb4c: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (c000000000630230)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
c000000000630230-c000000000630988: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffe000360ab8)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffe000360ab8-ffffffe00036102a: vfat_build_slots (STB_LOCAL)
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
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff81408450)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff81408450-ffffffff81408925: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff813f8ed0)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff813f8ed0-ffffffff813f93a5: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff814057d0)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff814057d0-ffffffff81405ca5: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfat_build_slots(struct inode *dir, const unsigned char *name, int len, int is_dir, int cluster, struct timespec64 *ts, struct msdos_dir_slot *slots, int *nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/namei_vfat.c (ffffffff8141b490)
Location: fs/fat/namei_vfat.c:579
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
```
**Symbols:**

```
ffffffff8141b490-ffffffff8141b965: vfat_build_slots (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
