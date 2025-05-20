# Function: <code>idt_invalidate</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102e070)
Location: arch/x86/kernel/idt.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8102e070-ffffffff8102e0b7: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8102f0f0)
Location: arch/x86/kernel/idt.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8102f0f0-ffffffff8102f137: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81030380)
Location: arch/x86/kernel/idt.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81030380-ffffffff810303c7: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032160)
Location: arch/x86/kernel/idt.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81032160-ffffffff810321a7: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032a20)
Location: arch/x86/kernel/idt.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81032a20-ffffffff81032a67: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81034810)
Location: arch/x86/kernel/idt.c:364
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81034810-ffffffff81034857: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81035020)
Location: arch/x86/kernel/idt.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81035020-ffffffff81035067: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81036a60)
Location: arch/x86/kernel/idt.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81036a60-ffffffff81036aa7: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void idt_invalidate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8103bd60)
Location: arch/x86/kernel/idt.c:319
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8103bd60-ffffffff8103bd79: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void idt_invalidate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81042df0)
Location: arch/x86/kernel/idt.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81042df0-ffffffff81042e22: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void idt_invalidate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8104c850)
Location: arch/x86/kernel/idt.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8104c850-ffffffff8104c882: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void idt_invalidate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff8104d0c0)
Location: arch/x86/kernel/idt.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff8104d0c0-ffffffff8104d0f2: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void idt_invalidate();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81054340)
Location: arch/x86/kernel/idt.c:333
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81054340-ffffffff81054372: idt_invalidate (STB_GLOBAL)
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
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81032b80)
Location: arch/x86/kernel/idt.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81032b80-ffffffff81032bc7: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810224d0)
Location: arch/x86/kernel/idt.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff810224d0-ffffffff81022510: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff810329e0)
Location: arch/x86/kernel/idt.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff810329e0-ffffffff81032a27: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void idt_invalidate(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/idt.c (ffffffff81033940)
Location: arch/x86/kernel/idt.c:348
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_emergency_restart
```
**Symbols:**

```
ffffffff81033940-ffffffff81033987: idt_invalidate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *addr</code>
</li>
</ul>
</details>
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
