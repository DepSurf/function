# Function: <code>arch_get_ima_policy</code>

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
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ima_arch.c (ffffffff81078cd0)
Location: arch/x86/kernel/ima_arch.c:70
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff81078cd0-ffffffff81078cdd: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ima_arch.c (ffffffff8107c8a0)
Location: arch/x86/kernel/ima_arch.c:88
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff8107c8a0-ffffffff8107c8ad: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ima_arch.c (ffffffff8107d950)
Location: arch/x86/kernel/ima_arch.c:86
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff8107d950-ffffffff8107d95d: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/ima.h:43
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/ima.h:54
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/ima.h:60
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/ima.h:62
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_efi.c (0)
Location: security/integrity/ima/ima_efi.c:65
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff81e8a796-ffffffff81e8a7aa: arch_get_ima_policy.cold (STB_LOCAL)
ffffffff81648990-ffffffff81648a12: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_efi.c (0)
Location: security/integrity/ima/ima_efi.c:65
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff8207563c-ffffffff82075650: arch_get_ima_policy.cold (STB_LOCAL)
ffffffff81701760-ffffffff817017e2: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_efi.c (0)
Location: security/integrity/ima/ima_efi.c:65
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff820f519e-ffffffff820f51b2: arch_get_ima_policy.cold (STB_LOCAL)
ffffffff8173b800-ffffffff8173b882: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_efi.c (0)
Location: security/integrity/ima/ima_efi.c:68
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff821d2348-ffffffff821d235c: arch_get_ima_policy.cold (STB_LOCAL)
ffffffff8177c3c0-ffffffff8177c442: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/ima.h:42
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/ima.h:42
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ima_arch.c (c0000000000855d0)
Location: arch/powerpc/kernel/ima_arch.c:63
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
c0000000000855d0-c000000000085678: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/ima.h:42
Inline: True
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
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ima_arch.c (ffffffff8107c950)
Location: arch/x86/kernel/ima_arch.c:86
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff8107c950-ffffffff8107c95d: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ima_arch.c (ffffffff8106c0c0)
Location: arch/x86/kernel/ima_arch.c:86
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff8106c0c0-ffffffff8106c0cd: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ima_arch.c (ffffffff8107c900)
Location: arch/x86/kernel/ima_arch.c:86
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff8107c900-ffffffff8107c90d: arch_get_ima_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const const char * *arch_get_ima_policy();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ima_arch.c (ffffffff8107ea00)
Location: arch/x86/kernel/ima_arch.c:86
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_init_arch_policy
```
**Symbols:**

```
ffffffff8107ea00-ffffffff8107ea0d: arch_get_ima_policy (STB_GLOBAL)
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
