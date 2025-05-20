# Function: <code>keyctl_capabilities</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81430381)
Location: security/keys/keyctl.c:1694
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8142e9e0-ffffffff8142ea5c: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffff81430780-ffffffff8143079b: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff8144a0e1)
Location: security/keys/keyctl.c:1694
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81447f40-ffffffff81447fbc: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffff8144a4e0-ffffffff8144a4fb: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff8149be98)
Location: security/keys/keyctl.c:1849
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81499da0-ffffffff81499e1c: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffff8149bff0-ffffffff8149c00b: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b9938)
Location: security/keys/keyctl.c:1849
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814b7830-ffffffff814b78ac: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffff814b9a90-ffffffff814b9aab: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff814bf7a1)
Location: security/keys/keyctl.c:1849
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814bd6a0-ffffffff814bd71a: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffff814bf910-ffffffff814bf92b: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff815181c1)
Location: security/keys/keyctl.c:1849
Inline: True
Inline callers:
  - security/keys/keyctl.c:__do_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81515ad0-ffffffff81515b4a: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffff81518330-ffffffff8151834b: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815aa9f0)
Location: security/keys/keyctl.c:1849
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff815aa9f0-ffffffff815aaa8e: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81654d20)
Location: security/keys/keyctl.c:1849
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81654d20-ffffffff81654df5: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168d560)
Location: security/keys/keyctl.c:1854
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8168d560-ffffffff8168d62f: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c9ab0)
Location: security/keys/keyctl.c:1853
Inline: False
Direct callers:
  - security/keys/keyctl.c:__do_sys_keyctl
  - security/keys/compat.c:__do_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816c9ab0-ffffffff816c9b7f: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffff800010533fdc)
Location: security/keys/keyctl.c:1694
Inline: True
Inline callers:
  - security/keys/keyctl.c:__arm64_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__arm64_sys_keyctl
  - security/keys/compat.c:__arm64_compat_sys_keyctl
```
**Symbols:**

```
ffff8000105320a8-ffff800010532260: keyctl_capabilities.part.0 (STB_LOCAL)
ffff800010534028-ffff800010534064: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (c06eb804)
Location: security/keys/keyctl.c:1694
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
c06e9694-c06e97a8: keyctl_capabilities.part.0 (STB_LOCAL)
c06eb5f0-c06eb61c: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (c000000000682060)
Location: security/keys/keyctl.c:1694
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
  - security/keys/compat.c:__se_compat_sys_keyctl
```
**Symbols:**

```
c00000000067f740-c00000000067f87c: keyctl_capabilities.part.0 (STB_LOCAL)
c000000000682100-c000000000682128: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffe00039435c)
Location: security/keys/keyctl.c:1694
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__se_sys_keyctl
```
**Symbols:**

```
ffffffe0003928ac-ffffffe00039293a: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffe0003940f4-ffffffe00039412a: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff814426c1)
Location: security/keys/keyctl.c:1694
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81440520-ffffffff8144059c: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffff81442ac0-ffffffff81442adb: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81433111)
Location: security/keys/keyctl.c:1694
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81430f90-ffffffff8143100c: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffff81433510-ffffffff8143352b: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff8143e861)
Location: security/keys/keyctl.c:1694
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8143c6c0-ffffffff8143c73c: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffff8143ec60-ffffffff8143ec7b: keyctl_capabilities (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
long int keyctl_capabilities(unsigned char *_buffer, size_t buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/keys/keyctl.c (ffffffff81455a11)
Location: security/keys/keyctl.c:1694
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81453850-ffffffff814538cc: keyctl_capabilities.part.0 (STB_LOCAL)
ffffffff81455e10-ffffffff81455e2b: keyctl_capabilities (STB_GLOBAL)
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
