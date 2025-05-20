# Function: <code>uv_bios_init</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void uv_bios_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (0)
Location: arch/x86/platform/uv/bios_uv.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff810983f8-ffffffff8109844b: uv_bios_init.cold (STB_LOCAL)
ffffffff81098340-ffffffff810983f8: uv_bios_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int uv_bios_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (0)
Location: arch/x86/platform/uv/bios_uv.c:182
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff8109db76-ffffffff8109dbe0: uv_bios_init.cold (STB_LOCAL)
ffffffff8109da30-ffffffff8109daee: uv_bios_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int uv_bios_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (0)
Location: arch/x86/platform/uv/bios_uv.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff81bda50b-ffffffff81bda57a: uv_bios_init.cold (STB_LOCAL)
ffffffff810996d0-ffffffff810997a5: uv_bios_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int uv_bios_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (0)
Location: arch/x86/platform/uv/bios_uv.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff81bcc633-ffffffff81bcc6a2: uv_bios_init.cold (STB_LOCAL)
ffffffff81099ee0-ffffffff81099fb8: uv_bios_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int uv_bios_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (0)
Location: arch/x86/platform/uv/bios_uv.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff81ca28df-ffffffff81ca294e: uv_bios_init.cold (STB_LOCAL)
ffffffff810a9f00-ffffffff810a9fd8: uv_bios_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int uv_bios_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (0)
Location: arch/x86/platform/uv/bios_uv.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff81e52147-ffffffff81e521b0: uv_bios_init.cold (STB_LOCAL)
ffffffff810bf920-ffffffff810bf9fd: uv_bios_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uv_bios_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810db780)
Location: arch/x86/platform/uv/bios_uv.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff810db780-ffffffff810db8b0: uv_bios_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uv_bios_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810e6d10)
Location: arch/x86/platform/uv/bios_uv.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff810e6d10-ffffffff810e6e40: uv_bios_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uv_bios_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810ef090)
Location: arch/x86/platform/uv/bios_uv.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff810ef090-ffffffff810ef1c0: uv_bios_init (STB_GLOBAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void uv_bios_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (0)
Location: arch/x86/platform/uv/bios_uv.c:187
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff810998c8-ffffffff8109991b: uv_bios_init.cold (STB_LOCAL)
ffffffff81099810-ffffffff810998c8: uv_bios_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
