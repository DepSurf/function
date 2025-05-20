# Function: <code>do_match_mnt</code>

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
In security/apparmor/mount.c (ffffffff8138ec3f)
Location: security/apparmor/mount.c:243
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt
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
In security/apparmor/mount.c (ffffffff813c9c45)
Location: security/apparmor/mount.c:243
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff813e12b5)
Location: security/apparmor/mount.c:243
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff813f0116)
Location: security/apparmor/mount.c:243
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff814180b0)
Location: security/apparmor/mount.c:242
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff8144a687)
Location: security/apparmor/mount.c:242
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff814675f7)
Location: security/apparmor/mount.c:243
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff814944e3)
Location: security/apparmor/mount.c:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff814ae413)
Location: security/apparmor/mount.c:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_match_mnt(struct aa_dfa *dfa, unsigned int start, const char *mntpnt, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, struct aa_perms *perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150d350)
Location: security/apparmor/mount.c:239
Inline: False
Direct callers:
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8150d350-ffffffff8150d572: do_match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_match_mnt(struct aa_dfa *dfa, unsigned int start, const char *mntpnt, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, struct aa_perms *perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152a1c0)
Location: security/apparmor/mount.c:239
Inline: False
Direct callers:
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8152a1c0-ffffffff8152a3e2: do_match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_match_mnt(struct aa_dfa *dfa, unsigned int start, const char *mntpnt, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, struct aa_perms *perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff815305b0)
Location: security/apparmor/mount.c:239
Inline: False
Direct callers:
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff815305b0-ffffffff815307e1: do_match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_match_mnt(struct aa_dfa *dfa, unsigned int start, const char *mntpnt, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, struct aa_perms *perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158e9d0)
Location: security/apparmor/mount.c:239
Inline: False
Direct callers:
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8158e9d0-ffffffff8158ec01: do_match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_match_mnt(struct aa_policydb *policy, unsigned int start, const char *mntpnt, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, struct aa_perms *perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8162f1b0)
Location: security/apparmor/mount.c:220
Inline: False
Direct callers:
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8162f1b0-ffffffff8162f41a: do_match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_match_mnt(struct aa_policydb *policy, unsigned int start, const char *mntpnt, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, struct aa_perms *perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e3dd0)
Location: security/apparmor/mount.c:224
Inline: False
Direct callers:
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff816e3dd0-ffffffff816e403a: do_match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_match_mnt(struct aa_policydb *policy, unsigned int start, const char *mntpnt, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, struct aa_perms *perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171d330)
Location: security/apparmor/mount.c:224
Inline: False
Direct callers:
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8171d330-ffffffff8171d5a5: do_match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_match_mnt(struct aa_policydb *policy, unsigned int start, const char *mntpnt, const char *devname, const char *type, long unsigned int flags, void *data, bool binary, struct aa_perms *perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175bd80)
Location: security/apparmor/mount.c:224
Inline: False
Direct callers:
  - security/apparmor/mount.c:match_mnt_path_str
```
**Symbols:**

```
ffffffff8175bd80-ffffffff8175bff5: do_match_mnt (STB_LOCAL)
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
In security/apparmor/mount.c (ffff8000105a5b78)
Location: security/apparmor/mount.c:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (c0755b30)
Location: security/apparmor/mount.c:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (c000000000721b38)
Location: security/apparmor/mount.c:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffe0003ef732)
Location: security/apparmor/mount.c:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff814a69f3)
Location: security/apparmor/mount.c:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff81497413)
Location: security/apparmor/mount.c:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff814a2a93)
Location: security/apparmor/mount.c:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
In security/apparmor/mount.c (ffffffff814bb253)
Location: security/apparmor/mount.c:239
Inline: True
Inline callers:
  - security/apparmor/mount.c:match_mnt_path_str
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_policydb *policy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct aa_dfa *dfa</code>
</li>
</ul>
</details>
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
