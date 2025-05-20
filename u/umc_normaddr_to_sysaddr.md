# Function: <code>umc_normaddr_to_sysaddr</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049e40)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:557
Inline: False
```
**Symbols:**

```
ffffffff81049e40-ffffffff8104a311: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff81049810)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:544
Inline: False
```
**Symbols:**

```
ffffffff81049810-ffffffff81049cd8: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (ffffffff8104d250)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:541
Inline: False
```
**Symbols:**

```
ffffffff8104d250-ffffffff8104d728: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce_amd.c (0)
Location: arch/x86/kernel/cpu/mcheck/mce_amd.c:582
Inline: False
```
**Symbols:**

```
ffffffff8105157b-ffffffff81051627: umc_normaddr_to_sysaddr.cold.19 (STB_LOCAL)
ffffffff8104fd10-ffffffff8105013f: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:582
Inline: False
```
**Symbols:**

```
ffffffff8104ec22-ffffffff8104ecab: umc_normaddr_to_sysaddr.cold.18 (STB_LOCAL)
ffffffff8104d5a0-ffffffff8104da0e: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:662
Inline: False
```
**Symbols:**

```
ffffffff81051cdf-ffffffff81051d86: umc_normaddr_to_sysaddr.cold (STB_LOCAL)
ffffffff810504f0-ffffffff8105096b: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:664
Inline: False
```
**Symbols:**

```
ffffffff810525e6-ffffffff8105268d: umc_normaddr_to_sysaddr.cold (STB_LOCAL)
ffffffff81050e60-ffffffff810512db: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:678
Inline: False
```
**Symbols:**

```
ffffffff81056e2a-ffffffff81056ed1: umc_normaddr_to_sysaddr.cold (STB_LOCAL)
ffffffff81054fc0-ffffffff8105543a: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:678
Inline: False
```
**Symbols:**

```
ffffffff81bd5924-ffffffff81bd59cb: umc_normaddr_to_sysaddr.cold (STB_LOCAL)
ffffffff81053ee0-ffffffff8105435a: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:678
Inline: False
```
**Symbols:**

```
ffffffff81bc7d83-ffffffff81bc7e2a: umc_normaddr_to_sysaddr.cold (STB_LOCAL)
ffffffff810557b0-ffffffff81055c29: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:691
Inline: False
```
**Symbols:**

```
ffffffff81c9b9a0-ffffffff81c9ba47: umc_normaddr_to_sysaddr.cold (STB_LOCAL)
ffffffff8105e170-ffffffff8105e5d0: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:664
Inline: False
```
**Symbols:**

```
ffffffff810526e6-ffffffff8105278d: umc_normaddr_to_sysaddr.cold (STB_LOCAL)
ffffffff81050f60-ffffffff810513db: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:664
Inline: False
```
**Symbols:**

```
ffffffff8104207e-ffffffff81042125: umc_normaddr_to_sysaddr.cold (STB_LOCAL)
ffffffff810400c0-ffffffff8104053b: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:664
Inline: False
```
**Symbols:**

```
ffffffff81052596-ffffffff8105263d: umc_normaddr_to_sysaddr.cold (STB_LOCAL)
ffffffff81050e10-ffffffff8105128b: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int umc_normaddr_to_sysaddr(u64 norm_addr, u16 nid, u8 umc, u64 *sys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/amd.c (0)
Location: arch/x86/kernel/cpu/mce/amd.c:664
Inline: False
```
**Symbols:**

```
ffffffff810539d6-ffffffff81053a7d: umc_normaddr_to_sysaddr.cold (STB_LOCAL)
ffffffff81052250-ffffffff810526cb: umc_normaddr_to_sysaddr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
