# Function: <code>lapic_update_legacy_vectors</code>

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
void lapic_update_legacy_vectors();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff831d523b)
Location: arch/x86/kernel/apic/vector.c:741
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff831d523b-ffffffff831d527c: lapic_update_legacy_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lapic_update_legacy_vectors();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff832b7d6d)
Location: arch/x86/kernel/apic/vector.c:741
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff832b7d6d-ffffffff832b7dae: lapic_update_legacy_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lapic_update_legacy_vectors();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff83469a0c)
Location: arch/x86/kernel/apic/vector.c:741
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff83469a0c-ffffffff83469a65: lapic_update_legacy_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lapic_update_legacy_vectors();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff83e8e6c0)
Location: arch/x86/kernel/apic/vector.c:737
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff83e8e6c0-ffffffff83e8e72d: lapic_update_legacy_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void lapic_update_legacy_vectors();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff836b1f60)
Location: arch/x86/kernel/apic/vector.c:737
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff836b1f60-ffffffff836b1fcd: lapic_update_legacy_vectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void lapic_update_legacy_vectors();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff838e2420)
Location: arch/x86/kernel/apic/vector.c:748
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:apic_intr_mode_init
```
**Symbols:**

```
ffffffff838e2420-ffffffff838e248d: lapic_update_legacy_vectors (STB_GLOBAL)
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
