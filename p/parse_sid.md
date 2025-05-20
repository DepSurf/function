# Function: <code>parse_sid</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:606
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81414a20-ffffffff81414a58: parse_sid (STB_LOCAL)
ffffffff8141e61b-ffffffff8141e640: parse_sid.cold.70 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:629
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81442350-ffffffff8144238a: parse_sid (STB_LOCAL)
ffffffff8144c20b-ffffffff8144c230: parse_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:631
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff8145bdc0-ffffffff8145bdfa: parse_sid (STB_LOCAL)
ffffffff81465ffb-ffffffff81466020: parse_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b945b)
Location: security/selinux/hooks.c:580
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d606a)
Location: security/selinux/hooks.c:581
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
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
In security/selinux/hooks.c (ffffffff814dcee7)
Location: security/selinux/hooks.c:637
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
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
In security/selinux/hooks.c (ffffffff815363b7)
Location: security/selinux/hooks.c:614
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
</details>
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
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010548818)
Location: security/selinux/hooks.c:631
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffff800010548818-ffff800010548898: parse_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06fe4c4)
Location: security/selinux/hooks.c:631
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
c06fe4c4-c06fe52c: parse_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c00000000069fb20)
Location: security/selinux/hooks.c:631
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
c00000000069fb20-c00000000069fbb4: parse_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a3a24)
Location: security/selinux/hooks.c:631
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffe0003a3a24-ffffffe0003a3a90: parse_sid (STB_LOCAL)
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
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:631
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814543a0-ffffffff814543da: parse_sid (STB_LOCAL)
ffffffff8145e5db-ffffffff8145e600: parse_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:631
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81444de0-ffffffff81444e1a: parse_sid (STB_LOCAL)
ffffffff8144f00b-ffffffff8144f030: parse_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:631
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff81450440-ffffffff8145047a: parse_sid (STB_LOCAL)
ffffffff8145a67b-ffffffff8145a6a0: parse_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int parse_sid(struct super_block *sb, const char *s, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:631
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
```
**Symbols:**

```
ffffffff814679a0-ffffffff814679da: parse_sid (STB_LOCAL)
ffffffff81471e1b-ffffffff81471e40: parse_sid.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
