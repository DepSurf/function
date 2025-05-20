# Function: <code>mnt_warn_timestamp_expiry</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:2478
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff81301aa0-ffffffff81301b6a: mnt_warn_timestamp_expiry (STB_LOCAL)
ffffffff81307b61-ffffffff81307bb9: mnt_warn_timestamp_expiry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:2536
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_reconfigure_mnt
```
**Symbols:**

```
ffffffff8133a970-ffffffff8133aa3a: mnt_warn_timestamp_expiry (STB_LOCAL)
ffffffff81341041-ffffffff81341099: mnt_warn_timestamp_expiry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:2542
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_reconfigure_mnt
```
**Symbols:**

```
ffffffff81346510-ffffffff813465da: mnt_warn_timestamp_expiry (STB_LOCAL)
ffffffff81bea77a-ffffffff81bea7d2: mnt_warn_timestamp_expiry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:2566
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8134c930-ffffffff8134c9fa: mnt_warn_timestamp_expiry (STB_LOCAL)
ffffffff81bdc7af-ffffffff81bdc807: mnt_warn_timestamp_expiry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:2568
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8139a7b0-ffffffff8139a87a: mnt_warn_timestamp_expiry (STB_LOCAL)
ffffffff81cc3e8f-ffffffff81cc3ee7: mnt_warn_timestamp_expiry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:2609
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8141d4b0-ffffffff8141d5a5: mnt_warn_timestamp_expiry (STB_LOCAL)
ffffffff81e76790-ffffffff81e767f0: mnt_warn_timestamp_expiry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814a9810)
Location: fs/namespace.c:2714
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff814a9810-ffffffff814a997f: mnt_warn_timestamp_expiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814de760)
Location: fs/namespace.c:2792
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff814de760-ffffffff814de854: mnt_warn_timestamp_expiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81511270)
Location: fs/namespace.c:2797
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff81511270-ffffffff81511364: mnt_warn_timestamp_expiry (STB_LOCAL)
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
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b4138)
Location: fs/namespace.c:2478
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffff8000103b4138-ffff8000103b4264: mnt_warn_timestamp_expiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0593204)
Location: fs/namespace.c:2478
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
c0593204-c0593354: mnt_warn_timestamp_expiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b0110)
Location: fs/namespace.c:2478
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
c0000000004b0110-c0000000004b02b4: mnt_warn_timestamp_expiry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002779b4)
Location: fs/namespace.c:2478
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffe0002779b4-ffffffe000277a9c: mnt_warn_timestamp_expiry (STB_LOCAL)
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
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:2478
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812fa080-ffffffff812fa14a: mnt_warn_timestamp_expiry (STB_LOCAL)
ffffffff81300141-ffffffff81300199: mnt_warn_timestamp_expiry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:2478
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812eaca0-ffffffff812ead6a: mnt_warn_timestamp_expiry (STB_LOCAL)
ffffffff812f0d61-ffffffff812f0db9: mnt_warn_timestamp_expiry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:2478
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812f7e70-ffffffff812f7f3a: mnt_warn_timestamp_expiry (STB_LOCAL)
ffffffff812fdf31-ffffffff812fdf89: mnt_warn_timestamp_expiry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mnt_warn_timestamp_expiry(struct path *mountpoint, struct vfsmount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namespace.c (0)
Location: fs/namespace.c:2478
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff813097b0-ffffffff8130987a: mnt_warn_timestamp_expiry (STB_LOCAL)
ffffffff8130f271-ffffffff8130f2c9: mnt_warn_timestamp_expiry.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
