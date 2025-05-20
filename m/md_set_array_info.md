# Function: <code>md_set_array_info</code>

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
int md_set_array_info(struct mddev *mddev, struct mdu_array_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7142
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81c27014-ffffffff81c2702b: md_set_array_info.cold (STB_LOCAL)
ffffffff819729b0-ffffffff81972b85: md_set_array_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int md_set_array_info(struct mddev *mddev, struct mdu_array_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7097
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81c191c5-ffffffff81c191dc: md_set_array_info.cold (STB_LOCAL)
ffffffff81956ab0-ffffffff81956c76: md_set_array_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int md_set_array_info(struct mddev *mddev, struct mdu_array_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7110
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81d287eb-ffffffff81d28805: md_set_array_info.cold (STB_LOCAL)
ffffffff819fc150-ffffffff819fc343: md_set_array_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int md_set_array_info(struct mddev *mddev, struct mdu_array_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:7107
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81ef4850-ffffffff81ef4869: md_set_array_info.cold (STB_LOCAL)
ffffffff81b637d0-ffffffff81b639c0: md_set_array_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int md_set_array_info(struct mddev *mddev, struct mdu_array_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfe490)
Location: drivers/md/md.c:7093
Inline: False
Direct callers:
  - drivers/md/md.c:__md_set_array_info
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81cfe490-ffffffff81cfe699: md_set_array_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int md_set_array_info(struct mddev *mddev, struct mdu_array_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d65730)
Location: drivers/md/md.c:7096
Inline: False
Direct callers:
  - drivers/md/md.c:__md_set_array_info
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81d65730-ffffffff81d65939: md_set_array_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int md_set_array_info(struct mddev *mddev, struct mdu_array_info_s *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1c4b0)
Location: drivers/md/md.c:7211
Inline: False
Direct callers:
  - drivers/md/md.c:__md_set_array_info
  - drivers/md/md-autodetect.c:md_setup_drive
```
**Symbols:**

```
ffffffff81e1c4b0-ffffffff81e1c6b9: md_set_array_info (STB_GLOBAL)
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
