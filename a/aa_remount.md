# Function: <code>aa_remount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8138eef0)
Location: security/apparmor/mount.c:342
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8138eef0-ffffffff8138f0bc: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813ca6c0)
Location: security/apparmor/mount.c:394
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813ca6c0-ffffffff813ca7f5: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813e1d40)
Location: security/apparmor/mount.c:395
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813e1d40-ffffffff813e1e75: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813f0740)
Location: security/apparmor/mount.c:396
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813f0740-ffffffff813f0806: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81418750)
Location: security/apparmor/mount.c:401
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81418750-ffffffff81418819: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8144abd0)
Location: security/apparmor/mount.c:401
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8144abd0-ffffffff8144ac99: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81467b40)
Location: security/apparmor/mount.c:402
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81467b40-ffffffff81467c09: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81494b70)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81494b70-ffffffff81494c36: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814aeaa0)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814aeaa0-ffffffff814aeb66: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150dcc0)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8150dcc0-ffffffff8150dda4: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152ab30)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8152ab30-ffffffff8152ac14: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81530d40)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81530d40-ffffffff81530e25: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158f180)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8158f180-ffffffff8158f265: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816301c0)
Location: security/apparmor/mount.c:385
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff816301c0-ffffffff816302bf: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_remount(const struct cred *subj_cred, struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e4e50)
Location: security/apparmor/mount.c:394
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff816e4e50-ffffffff816e4f57: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_remount(const struct cred *subj_cred, struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171e4c0)
Location: security/apparmor/mount.c:394
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8171e4c0-ffffffff8171e5c1: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_remount(const struct cred *subj_cred, struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175cee0)
Location: security/apparmor/mount.c:394
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8175cee0-ffffffff8175cfe1: aa_remount (STB_GLOBAL)
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
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a6168)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffff8000105a6168-ffff8000105a624c: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c0756104)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
c0756104-c07561f8: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c000000000722380)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
c000000000722380-c0000000007224f8: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003efcb0)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffe0003efcb0-ffffffe0003efd80: aa_remount (STB_GLOBAL)
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
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a7080)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814a7080-ffffffff814a7146: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81497aa0)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81497aa0-ffffffff81497b66: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a3120)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814a3120-ffffffff814a31e6: aa_remount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_remount(struct aa_label *label, const struct path *path, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814bb8f0)
Location: security/apparmor/mount.c:398
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814bb8f0-ffffffff814bb9cd: aa_remount (STB_GLOBAL)
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
<code>label, path, flags, data</code> ➡️ <code>subj_cred, label, path, flags, data</code>
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
