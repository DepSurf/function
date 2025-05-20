# Function: <code>security_lock_kernel_down</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814556d0)
Location: security/security.c:2614
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff814556d0-ffffffff81455714: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a7f00)
Location: security/security.c:2985
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff814a7f00-ffffffff814a7f44: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5480)
Location: security/security.c:3003
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff814c5480-ffffffff814c54c4: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cb970)
Location: security/security.c:3066
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff814cb970-ffffffff814cb9b4: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524670)
Location: security/security.c:3074
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81524670-ffffffff815246b4: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8760)
Location: security/security.c:3152
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff815b8760-ffffffff815b87bd: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81663d80)
Location: security/security.c:3132
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81663d80-ffffffff81663ddd: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c280)
Location: security/security.c:5595
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff8169c280-ffffffff8169c2dd: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d8f20)
Location: security/security.c:5736
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff816d8f20-ffffffff816d8f7d: security_lock_kernel_down (STB_GLOBAL)
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
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540bc0)
Location: security/security.c:2614
Inline: False
Direct callers:
  - drivers/firmware/efi/arm-init.c:efi_init
```
**Symbols:**

```
ffff800010540bc0-ffff800010540c20: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f6c28)
Location: security/security.c:2614
Inline: False
Direct callers:
  - drivers/firmware/efi/arm-init.c:efi_init
```
**Symbols:**

```
c06f6c28-c06f6c84: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000692c60)
Location: security/security.c:2614
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:setup_arch
```
**Symbols:**

```
c000000000692c60-c000000000692d1c: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039db28)
Location: security/security.c:2614
Inline: False
```
**Symbols:**

```
ffffffe00039db28-ffffffe00039db6c: security_lock_kernel_down (STB_GLOBAL)
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
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144dcb0)
Location: security/security.c:2614
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff8144dcb0-ffffffff8144dcf4: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e700)
Location: security/security.c:2614
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff8143e700-ffffffff8143e744: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449d50)
Location: security/security.c:2614
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81449d50-ffffffff81449d94: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_lock_kernel_down(const char *where, enum lockdown_reason level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461120)
Location: security/security.c:2614
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81461120-ffffffff81461164: security_lock_kernel_down (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
