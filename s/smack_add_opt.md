# Function: <code>smack_add_opt</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81435ec1)
Location: security/smack/smack_lsm.c:587
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:587
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff814634a0-ffffffff81463599: smack_add_opt (STB_LOCAL)
ffffffff81467224-ffffffff8146723a: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:587
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff8147d270-ffffffff8147d369: smack_add_opt (STB_LOCAL)
ffffffff81481004-ffffffff8148101a: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:583
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff814d3500-ffffffff814d35f9: smack_add_opt (STB_LOCAL)
ffffffff814d6f51-ffffffff814d6f67: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:583
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff814f06c0-ffffffff814f07b9: smack_add_opt (STB_LOCAL)
ffffffff81bf11f9-ffffffff81bf120f: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:566
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff814f7640-ffffffff814f7739: smack_add_opt (STB_LOCAL)
ffffffff81be337a-ffffffff81be3390: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:566
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff815521e0-ffffffff815522d9: smack_add_opt (STB_LOCAL)
ffffffff81cd54b0-ffffffff81cd54c6: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:569
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff815ebc40-ffffffff815ebd13: smack_add_opt (STB_LOCAL)
ffffffff81e882e5-ffffffff81e882fb: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169b880)
Location: security/smack/smack_lsm.c:568
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff8169b880-ffffffff8169b952: smack_add_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d40a0)
Location: security/smack/smack_lsm.c:566
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff816d40a0-ffffffff816d41ba: smack_add_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81710070)
Location: security/smack/smack_lsm.c:589
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff81710070-ffffffff817101a7: smack_add_opt (STB_LOCAL)
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
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056df08)
Location: security/smack/smack_lsm.c:587
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffff80001056df08-ffff80001056e034: smack_add_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c07218f0)
Location: security/smack/smack_lsm.c:587
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
c07218f0-c07219f4: smack_add_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d5200)
Location: security/smack/smack_lsm.c:587
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
c0000000006d5200-c0000000006d53bc: smack_add_opt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c29c8)
Location: security/smack/smack_lsm.c:587
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffe0003c29c8-ffffffe0003c2ac0: smack_add_opt (STB_LOCAL)
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
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:587
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff81475850-ffffffff81475949: smack_add_opt (STB_LOCAL)
ffffffff814795e4-ffffffff814795fa: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:587
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff81466270-ffffffff81466369: smack_add_opt (STB_LOCAL)
ffffffff8146a004-ffffffff8146a01a: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:587
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff814718f0-ffffffff814719e9: smack_add_opt (STB_LOCAL)
ffffffff81475684-ffffffff8147569a: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int smack_add_opt(int token, const char *s, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:587
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
  - security/smack/smack_lsm.c:smack_fs_context_parse_param
```
**Symbols:**

```
ffffffff814891e0-ffffffff814892d9: smack_add_opt (STB_LOCAL)
ffffffff8148d082-ffffffff8148d098: smack_add_opt.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
