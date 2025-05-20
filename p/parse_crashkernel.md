# Function: <code>parse_crashkernel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81f813e7)
Location: kernel/kexec_core.c:1283
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81f813e7-ffffffff81f813f5: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81faa776)
Location: kernel/kexec_core.c:1330
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81faa776-ffffffff81faa784: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81fe6782)
Location: kernel/kexec_core.c:1332
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81fe6782-ffffffff81fe6790: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff820c6d2f)
Location: kernel/crash_core.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff820c6d2f-ffffffff820c6d42: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff826cf372)
Location: kernel/crash_core.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff826cf372-ffffffff826cf385: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff826f9a8d)
Location: kernel/crash_core.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff826f9a8d-ffffffff826f9aa0: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828b0962)
Location: kernel/crash_core.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff828b0962-ffffffff828b0975: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828c9512)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828c9512-ffffffff828c9525: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828d1a70)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828d1a70-ffffffff828d1a83: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff82cf27ac)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff82cf27ac-ffffffff82cf27bf: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff82fdf23c)
Location: kernel/crash_core.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff82fdf23c-ffffffff82fdf24f: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff831e9d4b)
Location: kernel/crash_core.c:270
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff831e9d4b-ffffffff831e9d5e: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff832ce3fe)
Location: kernel/crash_core.c:272
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff832ce3fe-ffffffff832ce411: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff834820e4)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff834820e4-ffffffff83482106: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff83eaf580)
Location: kernel/crash_core.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff83eaf580-ffffffff83eaf5a2: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff836d45d0)
Location: kernel/crash_core.c:280
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff836d45d0-ffffffff836d45f2: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base, long long unsigned int *low_size, bool *high);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff83906700)
Location: kernel/crash_core.c:307
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff83906700-ffffffff839067e6: parse_crashkernel (STB_GLOBAL)
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
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffff800011449ef8)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/arm64/mm/init.c:arm64_memblock_init
```
**Symbols:**

```
ffff800011449ef8-ffff800011449f48: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c1524198)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/arm/kernel/setup.c:setup_arch
```
**Symbols:**

```
c1524198-c15241d4: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (c00000000136f430)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/powerpc/kernel/fadump.c:fadump_reserve_mem
  - arch/powerpc/kernel/machine_kexec.c:reserve_crashkernel
```
**Symbols:**

```
c00000000136f430-c00000000136f448: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffe00000b240)
Location: kernel/crash_core.c:268
Inline: False
```
**Symbols:**

```
ffffffe00000b240-ffffffe00000b284: parse_crashkernel (STB_GLOBAL)
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
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828ba921)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828ba921-ffffffff828ba934: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828b2fb4)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828b2fb4-ffffffff828b2fc7: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828cd6a4)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828cd6a4-ffffffff828cd6b7: parse_crashkernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int parse_crashkernel(char *cmdline, long long unsigned int system_ram, long long unsigned int *crash_size, long long unsigned int *crash_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/crash_core.c (ffffffff828d2a9e)
Location: kernel/crash_core.c:268
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:reserve_crashkernel
```
**Symbols:**

```
ffffffff828d2a9e-ffffffff828d2ab1: parse_crashkernel (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long long unsigned int *low_size</code>
</li>
<li>
<b>Param added. </b>
<code>bool *high</code>
</li>
</ul>
</details>
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
