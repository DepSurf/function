# Function: <code>compat_keyctl_dh_compute</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff813950d0)
Location: security/keys/compat_dh.c:20
Inline: False
Direct callers:
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff813950d0-ffffffff81395189: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff813ba820)
Location: security/keys/compat_dh.c:20
Inline: False
Direct callers:
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff813ba820-ffffffff813ba8d9: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff813eb680)
Location: security/keys/compat_dh.c:20
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff813eb680-ffffffff813eb739: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff81406280)
Location: security/keys/compat_dh.c:20
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81406280-ffffffff81406339: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff814333b0)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814333b0-ffffffff81433474: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff8144d120)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8144d120-ffffffff8144d1e4: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff8149f010)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8149f010-ffffffff8149f0d4: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff814bca40)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814bca40-ffffffff814bcb04: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff814c28e0)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814c28e0-ffffffff814c29a4: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff8151b2d0)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8151b2d0-ffffffff8151b394: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff815ae470)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff815ae470-ffffffff815ae57c: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff81658ba0)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81658ba0-ffffffff81658cac: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff81691440)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81691440-ffffffff8169154c: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff816cda10)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816cda10-ffffffff816cdb1c: compat_keyctl_dh_compute (STB_GLOBAL)
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
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffff800010537070)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__arm64_compat_sys_keyctl
```
**Symbols:**

```
ffff800010537070-ffff800010537264: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (c000000000685ea0)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__se_compat_sys_keyctl
```
**Symbols:**

```
c000000000685ea0-c000000000685fc8: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff81445700)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81445700-ffffffff814457c4: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff81436150)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81436150-ffffffff81436214: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff814417a0)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814417a0-ffffffff81441864: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int compat_keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct compat_keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat_dh.c (ffffffff81458ab0)
Location: security/keys/compat_dh.c:16
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81458ab0-ffffffff81458b74: compat_keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
