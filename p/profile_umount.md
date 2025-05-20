# Function: <code>profile_umount</code>

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
In security/apparmor/mount.c (ffffffff8138fc73)
Location: security/apparmor/mount.c:588
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
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
In security/apparmor/mount.c (ffffffff813caf4a)
Location: security/apparmor/mount.c:548
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
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
In security/apparmor/mount.c (ffffffff813e25ca)
Location: security/apparmor/mount.c:549
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
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
In security/apparmor/mount.c (ffffffff813f0dc6)
Location: security/apparmor/mount.c:551
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
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
In security/apparmor/mount.c (ffffffff81418dd6)
Location: security/apparmor/mount.c:556
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
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
In security/apparmor/mount.c (ffffffff8144b218)
Location: security/apparmor/mount.c:556
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
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
In security/apparmor/mount.c (ffffffff81468188)
Location: security/apparmor/mount.c:557
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814951c8)
Location: security/apparmor/mount.c:553
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814af0f8)
Location: security/apparmor/mount.c:553
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int profile_umount(struct aa_profile *profile, struct path *path, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150d580)
Location: security/apparmor/mount.c:582
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_umount
```
**Symbols:**

```
ffffffff8150d580-ffffffff8150d706: profile_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int profile_umount(struct aa_profile *profile, struct path *path, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152a3f0)
Location: security/apparmor/mount.c:582
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_umount
```
**Symbols:**

```
ffffffff8152a3f0-ffffffff8152a576: profile_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81531457)
Location: security/apparmor/mount.c:582
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158f897)
Location: security/apparmor/mount.c:582
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int profile_umount(struct aa_profile *profile, const struct path *path, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8162fcd0)
Location: security/apparmor/mount.c:569
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_umount
```
**Symbols:**

```
ffffffff8162fcd0-ffffffff8162fe62: profile_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int profile_umount(const struct cred *subj_cred, struct aa_profile *profile, const struct path *path, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e4930)
Location: security/apparmor/mount.c:587
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_umount
```
**Symbols:**

```
ffffffff816e4930-ffffffff816e4aca: profile_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int profile_umount(const struct cred *subj_cred, struct aa_profile *profile, const struct path *path, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171df80)
Location: security/apparmor/mount.c:597
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_umount
```
**Symbols:**

```
ffffffff8171df80-ffffffff8171e124: profile_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int profile_umount(const struct cred *subj_cred, struct aa_profile *profile, const struct path *path, char *buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175c9d0)
Location: security/apparmor/mount.c:601
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_umount
```
**Symbols:**

```
ffffffff8175c9d0-ffffffff8175cb74: profile_umount (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a6820)
Location: security/apparmor/mount.c:553
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c07567ec)
Location: security/apparmor/mount.c:553
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c000000000722d60)
Location: security/apparmor/mount.c:553
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003f0220)
Location: security/apparmor/mount.c:553
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a76d8)
Location: security/apparmor/mount.c:553
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814980f8)
Location: security/apparmor/mount.c:553
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a3778)
Location: security/apparmor/mount.c:553
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814bbfdf)
Location: security/apparmor/mount.c:553
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_umount
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
<code>profile, path, buffer</code> ➡️ <code>subj_cred, profile, path, buffer</code>
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
