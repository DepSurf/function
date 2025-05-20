# Function: <code>aa_new_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *orig_dev_name, struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8138f7b0)
Location: security/apparmor/mount.c:518
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8138f7b0-ffffffff8138fad5: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813cac00)
Location: security/apparmor/mount.c:497
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813cac00-ffffffff813caea3: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813e2280)
Location: security/apparmor/mount.c:498
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813e2280-ffffffff813e2523: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff813f0b00)
Location: security/apparmor/mount.c:499
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff813f0b00-ffffffff813f0d38: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81418b10)
Location: security/apparmor/mount.c:504
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81418b10-ffffffff81418d48: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8144af70)
Location: security/apparmor/mount.c:504
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8144af70-ffffffff8144b187: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81467ee0)
Location: security/apparmor/mount.c:505
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81467ee0-ffffffff814680f7: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81494f10)
Location: security/apparmor/mount.c:501
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81494f10-ffffffff81495134: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814aee40)
Location: security/apparmor/mount.c:501
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814aee40-ffffffff814af064: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8150e0d0)
Location: security/apparmor/mount.c:518
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8150e0d0-ffffffff8150e357: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8152af40)
Location: security/apparmor/mount.c:518
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8152af40-ffffffff8152b1c7: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81531150)
Location: security/apparmor/mount.c:518
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81531150-ffffffff815313d7: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8158f590)
Location: security/apparmor/mount.c:518
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8158f590-ffffffff8158f817: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81630640)
Location: security/apparmor/mount.c:505
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81630640-ffffffff816308fe: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aa_new_mount(const struct cred *subj_cred, struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff816e5330)
Location: security/apparmor/mount.c:521
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff816e5330-ffffffff816e55ef: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aa_new_mount(const struct cred *subj_cred, struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8171ea30)
Location: security/apparmor/mount.c:531
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8171ea30-ffffffff8171ecfe: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aa_new_mount(const struct cred *subj_cred, struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff8175d460)
Location: security/apparmor/mount.c:535
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff8175d460-ffffffff8175d72e: aa_new_mount (STB_GLOBAL)
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
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffff8000105a6580)
Location: security/apparmor/mount.c:501
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffff8000105a6580-ffff8000105a679c: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c075652c)
Location: security/apparmor/mount.c:501
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
c075652c-c0756760: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (c0000000007229f0)
Location: security/apparmor/mount.c:501
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
c0000000007229f0-c000000000722ca4: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffe0003f000e)
Location: security/apparmor/mount.c:501
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffe0003f000e-ffffffe0003f01aa: aa_new_mount (STB_GLOBAL)
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
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a7420)
Location: security/apparmor/mount.c:501
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814a7420-ffffffff814a7644: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff81497e40)
Location: security/apparmor/mount.c:501
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff81497e40-ffffffff81498064: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814a34c0)
Location: security/apparmor/mount.c:501
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814a34c0-ffffffff814a36e4: aa_new_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aa_new_mount(struct aa_label *label, const char *dev_name, const struct path *path, const char *type, long unsigned int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/mount.c (ffffffff814bbcf0)
Location: security/apparmor/mount.c:501
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_sb_mount
```
**Symbols:**

```
ffffffff814bbcf0-ffffffff814bbf45: aa_new_mount (STB_GLOBAL)
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
<code>const char *dev_name</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *orig_dev_name</code>
</li>
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
<code>label, dev_name, path, type, flags, data</code> ➡️ <code>subj_cred, label, dev_name, path, type, flags, data</code>
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
