# Function: <code>aa_bind_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8138f0c0)
Location: security/apparmor/mount.c:377
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8138f0c0-ffffffff8138f33d: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813ca800)
Location: security/apparmor/mount.c:416
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813ca800-ffffffff813ca97e: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813e1e80)
Location: security/apparmor/mount.c:417
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813e1e80-ffffffff813e1ffe: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813f0810)
Location: security/apparmor/mount.c:418
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813f0810-ffffffff813f0932: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81418820)
Location: security/apparmor/mount.c:423
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81418820-ffffffff81418942: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8144aca0)
Location: security/apparmor/mount.c:423
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8144aca0-ffffffff8144adb7: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81467c10)
Location: security/apparmor/mount.c:424
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81467c10-ffffffff81467d27: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81494c40)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81494c40-ffffffff81494d5e: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814aeb70)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814aeb70-ffffffff814aec8e: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150ddb0)
Location: security/apparmor/mount.c:422
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8150ddb0-ffffffff8150def0: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152ac20)
Location: security/apparmor/mount.c:422
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8152ac20-ffffffff8152ad60: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81530e30)
Location: security/apparmor/mount.c:422
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81530e30-ffffffff81530f70: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158f270)
Location: security/apparmor/mount.c:422
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8158f270-ffffffff8158f3b0: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816302c0)
Location: security/apparmor/mount.c:409
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff816302c0-ffffffff81630420: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_bind_mount(const struct cred *subj_cred, struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e4f70)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff816e4f70-ffffffff816e50d7: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_bind_mount(const struct cred *subj_cred, struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171e5e0)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8171e5e0-ffffffff8171e747: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_bind_mount(const struct cred *subj_cred, struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175d000)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8175d000-ffffffff8175d167: aa_bind_mount (STB_GLOBAL)
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
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a6250)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffff8000105a6250-ffff8000105a638c: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c07561f8)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
c07561f8-c075633c: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c000000000722500)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
c000000000722500-c0000000007226d4: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003efd80)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffe0003efd80-ffffffe0003efe70: aa_bind_mount (STB_GLOBAL)
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
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a7150)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814a7150-ffffffff814a726e: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81497b70)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81497b70-ffffffff81497c8e: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a31f0)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814a31f0-ffffffff814a330e: aa_bind_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_bind_mount(struct aa_label *label, const struct path *path, const char *dev_name, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814bb9d0)
Location: security/apparmor/mount.c:420
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814bb9d0-ffffffff814bbb05: aa_bind_mount (STB_GLOBAL)
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
<code>label, path, dev_name, flags</code> ➡️ <code>subj_cred, label, path, dev_name, flags</code>
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
