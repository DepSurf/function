# Function: <code>add_new_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f57f7)
Location: drivers/md/md.c:5950
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff816f57f7-ffffffff816f5cf7: add_new_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8175a4c5)
Location: drivers/md/md.c:5965
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8175a4c5-ffffffff8175a9df: add_new_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817869c2)
Location: drivers/md/md.c:6013
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff817869c2-ffffffff81786f39: add_new_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81746f56)
Location: drivers/md/md.c:6227
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81746f56-ffffffff817474bf: add_new_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b91bc)
Location: drivers/md/md.c:6278
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff817b91bc-ffffffff817b974d: add_new_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6344
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff817fdf50-ffffffff817fe51d: add_new_disk (STB_LOCAL)
ffffffff8180103e-ffffffff81801101: add_new_disk.cold.92 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6331
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8182a0f0-ffffffff8182a6bd: add_new_disk (STB_LOCAL)
ffffffff8182d232-ffffffff8182d2f5: add_new_disk.cold.91 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6393
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8186c5c0-ffffffff8186cb99: add_new_disk (STB_LOCAL)
ffffffff8186fba6-ffffffff8186fc79: add_new_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6494
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8189e3b0-ffffffff8189e989: add_new_disk (STB_LOCAL)
ffffffff818a19ab-ffffffff818a1a7e: add_new_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6692
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8196e560-ffffffff8196eb49: add_new_disk (STB_LOCAL)
ffffffff819718d8-ffffffff819719ab: add_new_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010af2d68)
Location: drivers/md/md.c:6494
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffff800010af2d68-ffff800010af33a4: add_new_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bd425c)
Location: drivers/md/md.c:6494
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
c0bd425c-c0bd4974: add_new_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bdfa50)
Location: drivers/md/md.c:6494
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
c000000000bdfa50-c000000000be02c4: add_new_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e68b2)
Location: drivers/md/md.c:6494
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffe0006e68b2-ffffffe0006e6da2: add_new_disk (STB_LOCAL)
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
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6494
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81844230-ffffffff81844809: add_new_disk (STB_LOCAL)
ffffffff8184782b-ffffffff818478fe: add_new_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6494
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff8180b890-ffffffff8180be69: add_new_disk (STB_LOCAL)
ffffffff8180ee8b-ffffffff8180ef5e: add_new_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6494
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff81893860-ffffffff81893e39: add_new_disk (STB_LOCAL)
ffffffff81896e5b-ffffffff81896f2e: add_new_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int add_new_disk(struct mddev *mddev, mdu_disk_info_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:6494
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
```
**Symbols:**

```
ffffffff818af450-ffffffff818afa29: add_new_disk (STB_LOCAL)
ffffffff818b2e3b-ffffffff818b2f0e: add_new_disk.cold (STB_LOCAL)
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
