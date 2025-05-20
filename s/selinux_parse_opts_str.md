# Function: <code>selinux_parse_opts_str</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81341b50)
Location: security/selinux/hooks.c:949
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
```
**Symbols:**

```
ffffffff81341b50-ffffffff81341dd8: selinux_parse_opts_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137eef0)
Location: security/selinux/hooks.c:1020
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
```
**Symbols:**

```
ffffffff8137eef0-ffffffff8137f16d: selinux_parse_opts_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81395980)
Location: security/selinux/hooks.c:1021
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
```
**Symbols:**

```
ffffffff81395980-ffffffff81395bfd: selinux_parse_opts_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813aba20)
Location: security/selinux/hooks.c:1000
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
```
**Symbols:**

```
ffffffff813aba20-ffffffff813abcfb: selinux_parse_opts_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813d1a80)
Location: security/selinux/hooks.c:1003
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
```
**Symbols:**

```
ffffffff813d1a80-ffffffff813d1d61: selinux_parse_opts_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int selinux_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1085
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
```
**Symbols:**

```
ffffffff813fdb30-ffffffff813fddcf: selinux_parse_opts_str (STB_LOCAL)
ffffffff81402ae1-ffffffff81402b11: selinux_parse_opts_str.cold.78 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
</ul>
