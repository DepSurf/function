# Function: <code>parse_crashkernel_high</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81f813f5)
Location: kernel/kexec_core.c:1292
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81f813f5-ffffffff81f81407: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81faa784)
Location: kernel/kexec_core.c:1339
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81faa784-ffffffff81faa796: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81fe6790)
Location: kernel/kexec_core.c:1341
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81fe6790-ffffffff81fe67a2: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff820c6d42)
Location: kernel/crash_core.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff820c6d42-ffffffff820c6d59: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff826cf385)
Location: kernel/crash_core.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff826cf385-ffffffff826cf39c: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff826f9aa0)
Location: kernel/crash_core.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff826f9aa0-ffffffff826f9ab7: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828b0975)
Location: kernel/crash_core.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff828b0975-ffffffff828b098c: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828c9525)
Location: kernel/crash_core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828c9525-ffffffff828c953c: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828d1a83)
Location: kernel/crash_core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828d1a83-ffffffff828d1a9a: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff82cf27bf)
Location: kernel/crash_core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff82cf27bf-ffffffff82cf27d6: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff82fdf24f)
Location: kernel/crash_core.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff82fdf24f-ffffffff82fdf266: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff831e9d5e)
Location: kernel/crash_core.c:279
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff831e9d5e-ffffffff831e9d75: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff832ce411)
Location: kernel/crash_core.c:281
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff832ce411-ffffffff832ce428: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff83482106)
Location: kernel/crash_core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff83482106-ffffffff8348212c: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff83eaf5c0)
Location: kernel/crash_core.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff83eaf5c0-ffffffff83eaf5e6: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff836d4610)
Location: kernel/crash_core.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff836d4610-ffffffff836d4636: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffff800011449f48)
Location: kernel/crash_core.c:277
Inline: False
```
**Symbols:**

```
ffff800011449f48-ffff800011449f9c: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c15241d4)
Location: kernel/crash_core.c:277
Inline: False
```
**Symbols:**

```
c15241d4-c1524214: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c00000000136f448)
Location: kernel/crash_core.c:277
Inline: False
```
**Symbols:**

```
c00000000136f448-c00000000136f464: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffe00000b284)
Location: kernel/crash_core.c:277
Inline: False
```
**Symbols:**

```
ffffffe00000b284-ffffffe00000b2ce: parse_crashkernel_high (STB_GLOBAL)
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
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828ba934)
Location: kernel/crash_core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828ba934-ffffffff828ba94b: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828b2fc7)
Location: kernel/crash_core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828b2fc7-ffffffff828b2fde: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828cd6b7)
Location: kernel/crash_core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828cd6b7-ffffffff828cd6ce: parse_crashkernel_high (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int parse_crashkernel_high(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828d2ab1)
Location: kernel/crash_core.c:277
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828d2ab1-ffffffff828d2ac8: parse_crashkernel_high (STB_GLOBAL)
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
