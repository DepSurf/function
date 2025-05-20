# Function: <code>efi_status_to_str</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818450e0)
Location: drivers/firmware/efi/efi.c:966
Inline: False
Direct callers:
  - certs/load_uefi.c:get_cert_list
  - certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff818450e0-ffffffff8184511b: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81871200)
Location: drivers/firmware/efi/efi.c:1013
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff81871200-ffffffff8187123b: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818b5480)
Location: drivers/firmware/efi/efi.c:1017
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff818b5480-ffffffff818b54ba: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818e7e20)
Location: drivers/firmware/efi/efi.c:1007
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff818e7e20-ffffffff818e7e5a: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bb120)
Location: drivers/firmware/efi/efi.c:921
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff819bb120-ffffffff819bb15a: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bd380)
Location: drivers/firmware/efi/efi.c:929
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff819bd380-ffffffff819bd3ba: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819a1b10)
Location: drivers/firmware/efi/efi.c:929
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff819a1b10-ffffffff819a1b4a: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81a4ead0)
Location: drivers/firmware/efi/efi.c:936
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff81a4ead0-ffffffff81a4eb0a: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81bbd770)
Location: drivers/firmware/efi/efi.c:950
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff81bbd770-ffffffff81bbd7c8: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81d633f0)
Location: drivers/firmware/efi/efi.c:974
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff81d633f0-ffffffff81d63448: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81dce4d0)
Location: drivers/firmware/efi/efi.c:1041
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff81dce4d0-ffffffff81dce528: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81e871d0)
Location: drivers/firmware/efi/efi.c:1078
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff81e871d0-ffffffff81e87228: efi_status_to_str (STB_GLOBAL)
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
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff800010b5af90)
Location: drivers/firmware/efi/efi.c:1007
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffff800010b5af90-ffff800010b5aff4: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c0c3bb98)
Location: drivers/firmware/efi/efi.c:1007
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
c0c3bb98-c0c3bbe8: efi_status_to_str (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8188aba0)
Location: drivers/firmware/efi/efi.c:1007
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff8188aba0-ffffffff8188abda: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81842520)
Location: drivers/firmware/efi/efi.c:1007
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff81842520-ffffffff8184255a: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818dcc80)
Location: drivers/firmware/efi/efi.c:1007
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff818dcc80-ffffffff818dccba: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *efi_status_to_str(efi_status_t status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818f9790)
Location: drivers/firmware/efi/efi.c:1007
Inline: False
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
  - security/integrity/platform_certs/load_uefi.c:get_cert_list
```
**Symbols:**

```
ffffffff818f9790-ffffffff818f97ca: efi_status_to_str (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
