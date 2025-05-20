# Function: <code>setup_ghcb</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void setup_ghcb();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a62a0)
Location: arch/x86/kernel/sev.c:1248
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_setup_idt
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff810a62a0-ffffffff810a63b2: setup_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void setup_ghcb();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bea80)
Location: arch/x86/kernel/sev.c:1248
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_setup_idt
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff810bea80-ffffffff810beb92: setup_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void setup_ghcb();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c2100)
Location: arch/x86/kernel/sev.c:1206
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_setup_idt
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff810c2100-ffffffff810c2246: setup_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void setup_ghcb();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c9580)
Location: arch/x86/kernel/sev.c:1232
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:early_setup_idt
  - arch/x86/kernel/cpu/common.c:cpu_init_exception_handling
```
**Symbols:**

```
ffffffff810c9580-ffffffff810c96ba: setup_ghcb (STB_GLOBAL)
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
