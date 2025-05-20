# Function: <code>keyctl_pkey_e_d_s</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81407a60)
Location: security/keys/keyctl_pkey.c:210
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81407a60-ffffffff81407bd2: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81434c50)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81434c50-ffffffff81434dc3: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8144e9d0)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8144e9d0-ffffffff8144eb43: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814a0a00)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814a0a00-ffffffff814a0b73: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814be3d0)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814be3d0-ffffffff814be543: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff814c4210)
Location: security/keys/keyctl_pkey.c:204
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814c4210-ffffffff814c4386: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8151cbe0)
Location: security/keys/keyctl_pkey.c:204
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8151cbe0-ffffffff8151cd56: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff815afe40)
Location: security/keys/keyctl_pkey.c:212
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff815afe40-ffffffff815affdd: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8165a6b0)
Location: security/keys/keyctl_pkey.c:212
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8165a6b0-ffffffff8165a84d: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81692f80)
Location: security/keys/keyctl_pkey.c:212
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81692f80-ffffffff81693121: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff816cf550)
Location: security/keys/keyctl_pkey.c:212
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816cf550-ffffffff816cf6f1: keyctl_pkey_e_d_s (STB_GLOBAL)
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
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffff800010539310)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__arm64_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
```
**Symbols:**

```
ffff800010539310-ffff8000105395b4: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (c06efb20)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
c06efb20-c06efce0: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (c000000000688050)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
```
**Symbols:**

```
c000000000688050-c000000000688234: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffe000397b70)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
ffffffe000397b70-ffffffe000397c90: keyctl_pkey_e_d_s (STB_GLOBAL)
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
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81446fb0)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81446fb0-ffffffff81447123: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81437a00)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81437a00-ffffffff81437b73: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff81443050)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81443050-ffffffff814431c3: keyctl_pkey_e_d_s (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int keyctl_pkey_e_d_s(int op, const struct keyctl_pkey_params *_params, const char *_info, const void *_in, void *_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl_pkey.c (ffffffff8145a380)
Location: security/keys/keyctl_pkey.c:206
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8145a380-ffffffff8145a4f3: keyctl_pkey_e_d_s (STB_GLOBAL)
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
