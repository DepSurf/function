# Function: <code>selinux_add_opt</code>

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
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:968
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff81416220-ffffffff81416322: selinux_add_opt (STB_LOCAL)
ffffffff8141e640-ffffffff8141e656: selinux_add_opt.cold.71 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:993
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff81443c80-ffffffff81443d7c: selinux_add_opt (STB_LOCAL)
ffffffff8144c230-ffffffff8144c246: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:995
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff8145d7f0-ffffffff8145d8ec: selinux_add_opt (STB_LOCAL)
ffffffff81466020-ffffffff81466036: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:946
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff814b1ee0-ffffffff814b1fdc: selinux_add_opt (STB_LOCAL)
ffffffff814b9d70-ffffffff814b9d86: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:947
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff814cf260-ffffffff814cf35c: selinux_add_opt (STB_LOCAL)
ffffffff81bf021a-ffffffff81bf0230: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1005
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff814d59a0-ffffffff814d5a9c: selinux_add_opt (STB_LOCAL)
ffffffff81be2299-ffffffff81be22af: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:987
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff8152e4c0-ffffffff8152e5d6: selinux_add_opt (STB_LOCAL)
ffffffff81cd3674-ffffffff81cd368a: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:948
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff815c75e0-ffffffff815c7789: selinux_add_opt (STB_LOCAL)
ffffffff81e868ab-ffffffff81e86900: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:953
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff81674490-ffffffff81674618: selinux_add_opt (STB_LOCAL)
ffffffff820733cc-ffffffff820733e9: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:965
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff816acb30-ffffffff816acc8f: selinux_add_opt (STB_LOCAL)
ffffffff820f2ff9-ffffffff820f3016: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1006
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff816e9f20-ffffffff816ea07f: selinux_add_opt (STB_LOCAL)
ffffffff821d030d-ffffffff821d032a: selinux_add_opt.cold (STB_LOCAL)
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
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054a718)
Location: security/selinux/hooks.c:995
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffff80001054a718-ffff80001054a844: selinux_add_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0700590)
Location: security/selinux/hooks.c:995
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
c0700590-c070069c: selinux_add_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006ad480)
Location: security/selinux/hooks.c:995
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
c0000000006ad480-c0000000006ad644: selinux_add_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a5258)
Location: security/selinux/hooks.c:995
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffe0003a5258-ffffffe0003a5350: selinux_add_opt (STB_LOCAL)
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
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:995
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff81455dd0-ffffffff81455ecc: selinux_add_opt (STB_LOCAL)
ffffffff8145e600-ffffffff8145e616: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:995
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff81446810-ffffffff8144690c: selinux_add_opt (STB_LOCAL)
ffffffff8144f030-ffffffff8144f046: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:995
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff81451e70-ffffffff81451f6c: selinux_add_opt (STB_LOCAL)
ffffffff8145a6a0-ffffffff8145a6b6: selinux_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int selinux_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:995
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_fs_context_parse_param
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff81468c00-ffffffff81468cfc: selinux_add_opt (STB_LOCAL)
ffffffff81471e40-ffffffff81471e56: selinux_add_opt.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
