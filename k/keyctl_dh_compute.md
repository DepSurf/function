# Function: <code>keyctl_dh_compute</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, void *reserved);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8136b580)
Location: security/keys/dh.c:80
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff8136b580-ffffffff8136b782: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, void *reserved);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81381d90)
Location: security/keys/dh.c:80
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
  - security/keys/compat.c:compat_SyS_keyctl
```
**Symbols:**

```
ffffffff81381d90-ffffffff81381fa1: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff813965b0)
Location: security/keys/dh.c:422
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
```
**Symbols:**

```
ffffffff813965b0-ffffffff8139662f: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff813bbd40)
Location: security/keys/dh.c:422
Inline: False
Direct callers:
  - security/keys/keyctl.c:SyS_keyctl
```
**Symbols:**

```
ffffffff813bbd40-ffffffff813bbdbf: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff813ecaa0)
Location: security/keys/dh.c:415
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff813ecaa0-ffffffff813ecb1f: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81407680)
Location: security/keys/dh.c:415
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff81407680-ffffffff814076ff: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81434840)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff81434840-ffffffff814348ca: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8144e5c0)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff8144e5c0-ffffffff8144e64a: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814a05f0)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
```
**Symbols:**

```
ffffffff814a05f0-ffffffff814a067a: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814be000)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
```
**Symbols:**

```
ffffffff814be000-ffffffff814be08a: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814c3e70)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
```
**Symbols:**

```
ffffffff814c3e70-ffffffff814c3efa: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8151c840)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
```
**Symbols:**

```
ffffffff8151c840-ffffffff8151c8ca: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff815af9d0)
Location: security/keys/dh.c:320
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
```
**Symbols:**

```
ffffffff815af9d0-ffffffff815afa6c: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff8165a1e0)
Location: security/keys/dh.c:320
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
```
**Symbols:**

```
ffffffff8165a1e0-ffffffff8165a27c: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81692ab0)
Location: security/keys/dh.c:300
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
```
**Symbols:**

```
ffffffff81692ab0-ffffffff81692b4c: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff816cf080)
Location: security/keys/dh.c:300
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
```
**Symbols:**

```
ffffffff816cf080-ffffffff816cf11c: keyctl_dh_compute (STB_GLOBAL)
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
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffff800010538af8)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__arm64_sys_keyctl
```
**Symbols:**

```
ffff800010538af8-ffff800010538bac: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (c06ef5b4)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
c06ef5b4-c06ef68c: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (c000000000687a10)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
c000000000687a10-c000000000687af8: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffe000397784)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
ffffffe000397784-ffffffe000397802: keyctl_dh_compute (STB_GLOBAL)
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
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81446ba0)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff81446ba0-ffffffff81446c2a: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff814375f0)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff814375f0-ffffffff8143767a: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81442c40)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff81442c40-ffffffff81442cca: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int keyctl_dh_compute(struct keyctl_dh_params *params, char *buffer, size_t buflen, struct keyctl_kdf_params *kdf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/dh.c (ffffffff81459f70)
Location: security/keys/dh.c:410
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff81459f70-ffffffff81459ffa: keyctl_dh_compute (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct keyctl_kdf_params *kdf</code>
</li>
<li>
<b>Param removed. </b>
<code>void *reserved</code>
</li>
</ul>
</details>
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
