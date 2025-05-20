# Function: <code>security_kernel_load_data</code>

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
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140efb0)
Location: security/security.c:1668
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff8140efb0-ffffffff8140eff0: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143c380)
Location: security/security.c:1687
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff8143c380-ffffffff8143c3c7: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455f10)
Location: security/security.c:1726
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff81455f10-ffffffff81455f50: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8d40)
Location: security/security.c:1910
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff814a8d40-ffffffff814a8d80: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c62c0)
Location: security/security.c:1913
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff814c62c0-ffffffff814c630e: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc570)
Location: security/security.c:1963
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff814cc570-ffffffff814cc5be: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525400)
Location: security/security.c:1971
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff81525400-ffffffff8152544e: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b93d0)
Location: security/security.c:1976
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_init_module
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff815b93d0-ffffffff815b9437: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664b80)
Location: security/security.c:2023
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_init_module
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff81664b80-ffffffff81664be7: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169d060)
Location: security/security.c:3243
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_init_module
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff8169d060-ffffffff8169d0c7: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id, bool contents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9b40)
Location: security/security.c:3315
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_init_module
  - kernel/kexec.c:__do_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
  - drivers/base/firmware_loader/fallback_platform.c:firmware_fallback_platform
```
**Symbols:**

```
ffffffff816d9b40-ffffffff816d9ba7: security_kernel_load_data (STB_GLOBAL)
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
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010541648)
Location: security/security.c:1726
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__arm64_compat_sys_kexec_load
  - kernel/kexec.c:__arm64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffff800010541648-ffff80001054169c: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f7640)
Location: security/security.c:1726
Inline: False
Direct callers:
  - kernel/module.c:__se_sys_init_module
  - kernel/kexec.c:__se_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
c06f7640-c06f7698: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000693e70)
Location: security/security.c:1726
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__se_compat_sys_kexec_load
  - kernel/kexec.c:__se_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
c000000000693e70-c000000000693efc: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039e31c)
Location: security/security.c:1726
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffe00039e31c-ffffffe00039e360: security_kernel_load_data (STB_GLOBAL)
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
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e4f0)
Location: security/security.c:1726
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff8144e4f0-ffffffff8144e530: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ef40)
Location: security/security.c:1726
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff8143ef40-ffffffff8143ef80: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a590)
Location: security/security.c:1726
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff8144a590-ffffffff8144a5d0: security_kernel_load_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_kernel_load_data(enum kernel_load_data_id id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461960)
Location: security/security.c:1726
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_init_module
  - kernel/kexec.c:__x32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_compat_sys_kexec_load
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
  - drivers/base/firmware_loader/fallback.c:firmware_fallback_sysfs
```
**Symbols:**

```
ffffffff81461960-ffffffff814619a0: security_kernel_load_data (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool contents</code>
</li>
</ul>
</details>
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
