# Function: <code>tsx_disable</code>

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
void tsx_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104a270)
Location: arch/x86/kernel/cpu/tsx.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8104a270-ffffffff8104a2a2: tsx_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tsx_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104e880)
Location: arch/x86/kernel/cpu/tsx.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8104e880-ffffffff8104e8b5: tsx_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tsx_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104db90)
Location: arch/x86/kernel/cpu/tsx.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8104db90-ffffffff8104dbc5: tsx_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tsx_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104f820)
Location: arch/x86/kernel/cpu/tsx.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8104f820-ffffffff8104f855: tsx_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tsx_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81057a00)
Location: arch/x86/kernel/cpu/tsx.c:22
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81057a00-ffffffff81057a35: tsx_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81063f10)
Location: arch/x86/kernel/cpu/tsx.c:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81073080)
Location: arch/x86/kernel/cpu/tsx.c:22
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81074c60)
Location: arch/x86/kernel/cpu/tsx.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff8107c130)
Location: arch/x86/kernel/cpu/tsx.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
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
void tsx_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104a3e0)
Location: arch/x86/kernel/cpu/tsx.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8104a3e0-ffffffff8104a412: tsx_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tsx_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81039820)
Location: arch/x86/kernel/cpu/tsx.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81039820-ffffffff81039880: tsx_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tsx_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104a220)
Location: arch/x86/kernel/cpu/tsx.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8104a220-ffffffff8104a252: tsx_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tsx_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff8104b630)
Location: arch/x86/kernel/cpu/tsx.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8104b630-ffffffff8104b662: tsx_disable (STB_GLOBAL)
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
