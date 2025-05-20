# Function: <code>paravirt_set_cap</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void paravirt_set_cap();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt-spinlocks.c (ffffffff831db32d)
Location: arch/x86/kernel/paravirt-spinlocks.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff831db32d-ffffffff831db387: paravirt_set_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void paravirt_set_cap();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt-spinlocks.c (ffffffff832be6a2)
Location: arch/x86/kernel/paravirt-spinlocks.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff832be6a2-ffffffff832be6fc: paravirt_set_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void paravirt_set_cap();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt-spinlocks.c (ffffffff834703f9)
Location: arch/x86/kernel/paravirt-spinlocks.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff834703f9-ffffffff83470438: paravirt_set_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void paravirt_set_cap();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt-spinlocks.c (ffffffff83e96f50)
Location: arch/x86/kernel/paravirt-spinlocks.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff83e96f50-ffffffff83e96f8f: paravirt_set_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void paravirt_set_cap();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt-spinlocks.c (ffffffff836bab00)
Location: arch/x86/kernel/paravirt-spinlocks.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff836bab00-ffffffff836bab3f: paravirt_set_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void paravirt_set_cap();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt-spinlocks.c (ffffffff838eb4f0)
Location: arch/x86/kernel/paravirt-spinlocks.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
```
**Symbols:**

```
ffffffff838eb4f0-ffffffff838eb52f: paravirt_set_cap (STB_GLOBAL)
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
