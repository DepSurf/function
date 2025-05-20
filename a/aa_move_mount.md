# Function: <code>aa_move_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8138f530)
Location: security/apparmor/mount.c:467
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8138f530-ffffffff8138f7a4: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813caaa0)
Location: security/apparmor/mount.c:469
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813caaa0-ffffffff813cabfe: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813e2120)
Location: security/apparmor/mount.c:470
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813e2120-ffffffff813e227e: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813f09f0)
Location: security/apparmor/mount.c:471
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813f09f0-ffffffff813f0af1: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81418a00)
Location: security/apparmor/mount.c:476
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81418a00-ffffffff81418b01: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8144ae70)
Location: security/apparmor/mount.c:476
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8144ae70-ffffffff8144af66: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81467de0)
Location: security/apparmor/mount.c:477
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81467de0-ffffffff81467ed6: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81494e10)
Location: security/apparmor/mount.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81494e10-ffffffff81494f0a: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814aed40)
Location: security/apparmor/mount.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814aed40-ffffffff814aee3a: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150dfb0)
Location: security/apparmor/mount.c:484
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8150dfb0-ffffffff8150e0c5: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152ae20)
Location: security/apparmor/mount.c:484
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8152ae20-ffffffff8152af35: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81531030)
Location: security/apparmor/mount.c:484
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81531030-ffffffff81531145: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158f470)
Location: security/apparmor/mount.c:484
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8158f470-ffffffff8158f585: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81630500)
Location: security/apparmor/mount.c:471
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81630500-ffffffff81630634: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_move_mount(const struct cred *subj_cred, struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e51e0)
Location: security/apparmor/mount.c:485
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff816e51e0-ffffffff816e531b: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_move_mount(const struct cred *subj_cred, struct aa_label *label, const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171e860)
Location: security/apparmor/mount.c:485
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/mount.c:aa_move_mount_old
```
**Symbols:**

```
ffffffff8171e860-ffffffff8171e94a: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_move_mount(const struct cred *subj_cred, struct aa_label *label, const struct path *from_path, const struct path *to_path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175d280)
Location: security/apparmor/mount.c:485
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_move_mount
  - security/apparmor/mount.c:aa_move_mount_old
```
**Symbols:**

```
ffffffff8175d280-ffffffff8175d37f: aa_move_mount (STB_GLOBAL)
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
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a6458)
Location: security/apparmor/mount.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffff8000105a6458-ffff8000105a657c: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c0756400)
Location: security/apparmor/mount.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
c0756400-c075652c: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c000000000722830)
Location: security/apparmor/mount.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
c000000000722830-c0000000007229ec: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003eff2a)
Location: security/apparmor/mount.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffe0003eff2a-ffffffe0003f000e: aa_move_mount (STB_GLOBAL)
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
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a7320)
Location: security/apparmor/mount.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814a7320-ffffffff814a741a: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81497d40)
Location: security/apparmor/mount.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81497d40-ffffffff81497e3a: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a33c0)
Location: security/apparmor/mount.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814a33c0-ffffffff814a34ba: aa_move_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_move_mount(struct aa_label *label, const struct path *path, const char *orig_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814bbbd0)
Location: security/apparmor/mount.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814bbbd0-ffffffff814bbce1: aa_move_mount (STB_GLOBAL)
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
<code>label, path, orig_name</code> ➡️ <code>subj_cred, label, path, orig_name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path *from_path</code>
</li>
<li>
<b>Param added. </b>
<code>const struct path *to_path</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct path *path</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *orig_name</code>
</li>
</ul>
</details>
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
