# Function: <code>md_add_new_disk</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int md_add_new_disk(struct mddev *mddev, struct mdu_disk_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6724
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81c274cb-ffffffff81c2759e: md_add_new_disk.cold (STB_LOCAL)
ffffffff81975510-ffffffff81975af9: md_add_new_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int md_add_new_disk(struct mddev *mddev, struct mdu_disk_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6679
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81c1967b-ffffffff81c19751: md_add_new_disk.cold (STB_LOCAL)
ffffffff81959550-ffffffff81959b33: md_add_new_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int md_add_new_disk(struct mddev *mddev, struct mdu_disk_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6692
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81d28cbb-ffffffff81d28d91: md_add_new_disk.cold (STB_LOCAL)
ffffffff819fecf0-ffffffff819ff30c: md_add_new_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int md_add_new_disk(struct mddev *mddev, struct mdu_disk_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6683
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81ef4d19-ffffffff81ef4df5: md_add_new_disk.cold (STB_LOCAL)
ffffffff81b66280-ffffffff81b66817: md_add_new_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int md_add_new_disk(struct mddev *mddev, struct mdu_disk_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d01ab0)
Location: drivers/md/md.c:6669
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81d01ab0-ffffffff81d020e0: md_add_new_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int md_add_new_disk(struct mddev *mddev, struct mdu_disk_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d6abd0)
Location: drivers/md/md.c:6673
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81d6abd0-ffffffff81d6b202: md_add_new_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int md_add_new_disk(struct mddev *mddev, struct mdu_disk_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1ce60)
Location: drivers/md/md.c:6783
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81e1ce60-ffffffff81e1d486: md_add_new_disk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
