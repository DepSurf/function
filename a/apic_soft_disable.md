# Function: <code>apic_soft_disable</code>

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
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066bd0)
Location: arch/x86/kernel/apic/apic.c:1246
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff81066bd0-ffffffff81066c0f: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106d7d0)
Location: arch/x86/kernel/apic/apic.c:1198
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff8106d7d0-ffffffff8106d80f: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106ef50)
Location: arch/x86/kernel/apic/apic.c:1207
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff8106ef50-ffffffff8106ef8f: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106fa70)
Location: arch/x86/kernel/apic/apic.c:1207
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff8106fa70-ffffffff8106faaf: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8107b4a0)
Location: arch/x86/kernel/apic/apic.c:1204
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff8107b4a0-ffffffff8107b4df: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8108a5f0)
Location: arch/x86/kernel/apic/apic.c:1213
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff8108a5f0-ffffffff8108a639: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109e5f0)
Location: arch/x86/kernel/apic/apic.c:1209
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff8109e5f0-ffffffff8109e639: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a15d0)
Location: arch/x86/kernel/apic/apic.c:1211
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff810a15d0-ffffffff810a1619: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a8779)
Location: arch/x86/kernel/apic/apic.c:1177
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:disable_local_APIC
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
```
**Symbols:**

```
ffffffff810a8700-ffffffff810a8747: apic_soft_disable (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810666c0)
Location: arch/x86/kernel/apic/apic.c:1246
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff810666c0-ffffffff810666ff: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81056ac0)
Location: arch/x86/kernel/apic/apic.c:1246
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff81056ac0-ffffffff81056aff: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066b70)
Location: arch/x86/kernel/apic/apic.c:1246
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff81066b70-ffffffff81066baf: apic_soft_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void apic_soft_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81068150)
Location: arch/x86/kernel/apic/apic.c:1246
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_disable
  - arch/x86/kernel/apic/apic.c:lapic_shutdown
```
**Symbols:**

```
ffffffff81068150-ffffffff8106818f: apic_soft_disable (STB_GLOBAL)
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
