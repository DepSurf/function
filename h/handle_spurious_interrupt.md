# Function: <code>handle_spurious_interrupt</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void handle_spurious_interrupt(u8 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2145
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:__spurious_interrupt
```
**Symbols:**

```
ffffffff8106edd0-ffffffff8106ee5c: handle_spurious_interrupt (STB_LOCAL)
ffffffff81bc8fdd-ffffffff81bc906d: handle_spurious_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void handle_spurious_interrupt(u8 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2142
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:__spurious_interrupt
```
**Symbols:**

```
ffffffff8107a7d0-ffffffff8107a859: handle_spurious_interrupt (STB_LOCAL)
ffffffff81c9da3a-ffffffff81c9dac7: handle_spurious_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void handle_spurious_interrupt(u8 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2150
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:__spurious_interrupt
```
**Symbols:**

```
ffffffff81089780-ffffffff81089823: handle_spurious_interrupt (STB_LOCAL)
ffffffff81e4ce99-ffffffff81e4cf50: handle_spurious_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_spurious_interrupt(u8 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109d6b0)
Location: arch/x86/kernel/apic/apic.c:2184
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:__spurious_interrupt
```
**Symbols:**

```
ffffffff8109d6b0-ffffffff8109d807: handle_spurious_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void handle_spurious_interrupt(u8 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a0690)
Location: arch/x86/kernel/apic/apic.c:2187
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:__spurious_interrupt
```
**Symbols:**

```
ffffffff810a0690-ffffffff810a07e7: handle_spurious_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void handle_spurious_interrupt(u8 vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a7bd0)
Location: arch/x86/kernel/apic/apic.c:2125
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_spurious_apic_interrupt
  - arch/x86/kernel/apic/apic.c:__spurious_interrupt
```
**Symbols:**

```
ffffffff810a7bd0-ffffffff810a7d08: handle_spurious_interrupt (STB_LOCAL)
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
