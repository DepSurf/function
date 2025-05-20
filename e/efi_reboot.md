# Function: <code>efi_reboot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffffffff816d2100)
Location: drivers/firmware/efi/reboot.c:10
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff816d2100-ffffffff816d2142: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffffffff817350a0)
Location: drivers/firmware/efi/reboot.c:10
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff817350a0-ffffffff81735167: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffffffff81768220)
Location: drivers/firmware/efi/reboot.c:10
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81768220-ffffffff817682e7: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffffffff81786b00)
Location: drivers/firmware/efi/reboot.c:10
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81786b00-ffffffff81786bc5: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffffffff817fcf80)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff817fcf80-ffffffff817fd04b: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8184684d-ffffffff8184686e: efi_reboot.cold.0 (STB_LOCAL)
ffffffff81846780-ffffffff81846831: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81872aad-ffffffff81872ace: efi_reboot.cold.0 (STB_LOCAL)
ffffffff818729e0-ffffffff81872a91: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff818b6c8d-ffffffff818b6caf: efi_reboot.cold (STB_LOCAL)
ffffffff818b6bd0-ffffffff818b6c80: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff818e95ed-ffffffff818e960f: efi_reboot.cold (STB_LOCAL)
ffffffff818e9530-ffffffff818e95e0: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff819bca1d-ffffffff819bca3f: efi_reboot.cold (STB_LOCAL)
ffffffff819bc960-ffffffff819bca0d: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81c2b818-ffffffff81c2b83a: efi_reboot.cold (STB_LOCAL)
ffffffff819bea40-ffffffff819beaed: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81c1dcba-ffffffff81c1dcdc: efi_reboot.cold (STB_LOCAL)
ffffffff819a3130-ffffffff819a31dd: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffffffff81a50340)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81a50340-ffffffff81a5045b: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffffffff81bbf1a0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81bbf1a0-ffffffff81bbf2c9: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffffffff81d63980)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81d63980-ffffffff81d63aad: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffffffff81dcead0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81dcead0-ffffffff81dcebfc: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffffffff81e87800)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81e87800-ffffffff81e8792c: efi_reboot (STB_GLOBAL)
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
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (ffff800010b5c820)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/arm64/kernel/process.c:machine_restart
```
**Symbols:**

```
ffff800010b5c820-ffff800010b5c914: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/reboot.c (c0c3d3c8)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
```
**Symbols:**

```
c0c3d3c8-c0c3d4c8: efi_reboot (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8188c36d-ffffffff8188c38f: efi_reboot.cold (STB_LOCAL)
ffffffff8188c2b0-ffffffff8188c360: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81843ced-ffffffff81843d0f: efi_reboot.cold (STB_LOCAL)
ffffffff81843c30-ffffffff81843ce0: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff818de44d-ffffffff818de46f: efi_reboot.cold (STB_LOCAL)
ffffffff818de390-ffffffff818de440: efi_reboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/reboot.c (0)
Location: drivers/firmware/efi/reboot.c:13
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff818faf5d-ffffffff818faf7f: efi_reboot.cold (STB_LOCAL)
ffffffff818faea0-ffffffff818faf50: efi_reboot (STB_GLOBAL)
```
</details>
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
