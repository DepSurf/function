# Function: <code>aa_mount_change_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8138f340)
Location: security/apparmor/mount.c:429
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8138f340-ffffffff8138f522: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813ca980)
Location: security/apparmor/mount.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813ca980-ffffffff813caa92: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813e2000)
Location: security/apparmor/mount.c:447
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813e2000-ffffffff813e2112: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813f0940)
Location: security/apparmor/mount.c:448
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813f0940-ffffffff813f09e7: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81418950)
Location: security/apparmor/mount.c:453
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81418950-ffffffff814189fa: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8144adc0)
Location: security/apparmor/mount.c:453
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8144adc0-ffffffff8144ae65: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81467d30)
Location: security/apparmor/mount.c:454
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81467d30-ffffffff81467dd5: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81494d60)
Location: security/apparmor/mount.c:450
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81494d60-ffffffff81494e02: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814aec90)
Location: security/apparmor/mount.c:450
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814aec90-ffffffff814aed32: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150def0)
Location: security/apparmor/mount.c:459
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8150def0-ffffffff8150dfb0: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152ad60)
Location: security/apparmor/mount.c:459
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8152ad60-ffffffff8152ae20: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81530f70)
Location: security/apparmor/mount.c:459
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81530f70-ffffffff81531030: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158f3b0)
Location: security/apparmor/mount.c:459
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8158f3b0-ffffffff8158f470: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81630420)
Location: security/apparmor/mount.c:446
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81630420-ffffffff816304f6: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_mount_change_type(const struct cred *subj_cred, struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e50f0)
Location: security/apparmor/mount.c:458
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff816e50f0-ffffffff816e51ce: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_mount_change_type(const struct cred *subj_cred, struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171e760)
Location: security/apparmor/mount.c:458
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8171e760-ffffffff8171e842: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_mount_change_type(const struct cred *subj_cred, struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175d180)
Location: security/apparmor/mount.c:458
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8175d180-ffffffff8175d262: aa_mount_change_type (STB_GLOBAL)
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
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a6390)
Location: security/apparmor/mount.c:450
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffff8000105a6390-ffff8000105a6458: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c075633c)
Location: security/apparmor/mount.c:450
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
c075633c-c0756400: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c0000000007226e0)
Location: security/apparmor/mount.c:450
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
c0000000007226e0-c000000000722830: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003efe70)
Location: security/apparmor/mount.c:450
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffe0003efe70-ffffffe0003eff2a: aa_mount_change_type (STB_GLOBAL)
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
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a7270)
Location: security/apparmor/mount.c:450
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814a7270-ffffffff814a7312: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81497c90)
Location: security/apparmor/mount.c:450
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81497c90-ffffffff81497d32: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a3310)
Location: security/apparmor/mount.c:450
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814a3310-ffffffff814a33b2: aa_mount_change_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_mount_change_type(struct aa_label *label, const struct path *path, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814bbb10)
Location: security/apparmor/mount.c:450
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814bbb10-ffffffff814bbbc9: aa_mount_change_type (STB_GLOBAL)
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
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>label, path, flags</code> ➡️ <code>subj_cred, label, path, flags</code>
</li>
</ul>
</details>
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
