# Function: <code>match_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const char *mntpnt, const char *devname, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8138eba0)
Location: security/apparmor/mount.c:309
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_remount
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_new_mount
```
**Symbols:**

```
ffffffff8138eba0-ffffffff8138eeef: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813c9f90)
Location: security/apparmor/mount.c:371
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff813c9f90-ffffffff813ca0d4: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813e1610)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff813e1610-ffffffff813e1754: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813f0991)
Location: security/apparmor/mount.c:373
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
```
**Symbols:**

```
ffffffff813f03c0-ffffffff813f04ad: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81418320)
Location: security/apparmor/mount.c:375
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff81418320-ffffffff8141841b: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8144a7a0)
Location: security/apparmor/mount.c:375
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff8144a7a0-ffffffff8144a89b: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81467710)
Location: security/apparmor/mount.c:376
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff81467710-ffffffff81467803: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81494770)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff81494770-ffffffff81494866: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814ae6a0)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff814ae6a0-ffffffff814ae796: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150df45)
Location: security/apparmor/mount.c:372
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
```
**Symbols:**

```
ffffffff8150d8a0-ffffffff8150d996: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152adb5)
Location: security/apparmor/mount.c:372
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
```
**Symbols:**

```
ffffffff8152a710-ffffffff8152a806: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, const struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81530fc5)
Location: security/apparmor/mount.c:372
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
```
**Symbols:**

```
ffffffff81530980-ffffffff81530a76: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, const struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158f405)
Location: security/apparmor/mount.c:372
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
```
**Symbols:**

```
ffffffff8158edc0-ffffffff8158eeb6: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, const struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81630475)
Location: security/apparmor/mount.c:357
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
```
**Symbols:**

```
ffffffff8162fbc0-ffffffff8162fccc: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int match_mnt(const struct cred *subj_cred, struct aa_profile *profile, const struct path *path, char *buffer, const struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e5149)
Location: security/apparmor/mount.c:365
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
```
**Symbols:**

```
ffffffff816e47f0-ffffffff816e4912: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int match_mnt(const struct cred *subj_cred, struct aa_profile *profile, const struct path *path, char *buffer, const struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171e7b9)
Location: security/apparmor/mount.c:365
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
```
**Symbols:**

```
ffffffff8171de40-ffffffff8171df6a: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int match_mnt(const struct cred *subj_cred, struct aa_profile *profile, const struct path *path, char *buffer, const struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175d1d9)
Location: security/apparmor/mount.c:365
Inline: True
Inline callers:
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_remount
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_bind_mount
```
**Symbols:**

```
ffffffff8175c890-ffffffff8175c9ba: match_mnt (STB_LOCAL)
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
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a5de8)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffff8000105a5de8-ffff8000105a5f0c: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c0755d90)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
c0755d90-c0755e94: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c000000000721e60)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
c000000000721e60-c000000000721fe0: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003ef99c)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffe0003ef99c-ffffffe0003efa66: match_mnt (STB_LOCAL)
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
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a6c80)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff814a6c80-ffffffff814a6d76: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814976a0)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff814976a0-ffffffff81497796: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a2d20)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff814a2d20-ffffffff814a2e16: match_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int match_mnt(struct aa_profile *profile, const struct path *path, char *buffer, struct path *devpath, char *devbuffer, const char *type, long unsigned int flags, void *data, bool binary);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814bb4e0)
Location: security/apparmor/mount.c:372
Inline: False
Direct callers:
  - security/apparmor/mount.c:aa_new_mount
  - security/apparmor/mount.c:aa_move_mount
  - security/apparmor/mount.c:aa_mount_change_type
  - security/apparmor/mount.c:aa_bind_mount
  - security/apparmor/mount.c:aa_remount
```
**Symbols:**

```
ffffffff814bb4e0-ffffffff814bb5d6: match_mnt (STB_LOCAL)
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
<b>Param added. </b>
<code>const struct path *path</code>
</li>
<li>
<b>Param added. </b>
<code>char *buffer</code>
</li>
<li>
<b>Param added. </b>
<code>struct path *devpath</code>
</li>
<li>
<b>Param added. </b>
<code>char *devbuffer</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *mntpnt</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *devname</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, mntpnt, devname, type, flags, data, binary</code> ➡️ <code>profile, path, buffer, devpath, devbuffer, type, flags, data, binary</code>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *devpath</code> ➡️ <code>const struct path *devpath</code>
</li>
</ul>
</details>
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
<code>profile, path, buffer, devpath, devbuffer, type, flags, data, binary</code> ➡️ <code>subj_cred, profile, path, buffer, devpath, devbuffer, type, flags, data, binary</code>
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
