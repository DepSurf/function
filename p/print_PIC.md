# Function: <code>print_PIC</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81f7240d)
Location: arch/x86/kernel/apic/vector.c:837
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81f9ac1c)
Location: arch/x86/kernel/apic/vector.c:890
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81fd60e3)
Location: arch/x86/kernel/apic/vector.c:907
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff820b6dfd)
Location: arch/x86/kernel/apic/vector.c:928
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff826bd71b)
Location: arch/x86/kernel/apic/vector.c:1174
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff826e6f35)
Location: arch/x86/kernel/apic/vector.c:1190
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8289da7e)
Location: arch/x86/kernel/apic/vector.c:1181
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828b5918)
Location: arch/x86/kernel/apic/vector.c:1178
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828b8dd9)
Location: arch/x86/kernel/apic/vector.c:1189
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_PIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff82cdddbd)
Location: arch/x86/kernel/apic/vector.c:1189
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
**Symbols:**

```
ffffffff82cdddbd-ffffffff82cdded7: print_PIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_PIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff82fca17b)
Location: arch/x86/kernel/apic/vector.c:1241
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
**Symbols:**

```
ffffffff82fca17b-ffffffff82fca295: print_PIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_PIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff831d4a9e)
Location: arch/x86/kernel/apic/vector.c:1274
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
**Symbols:**

```
ffffffff831d4a9e-ffffffff831d4bba: print_PIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void print_PIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff832b762a)
Location: arch/x86/kernel/apic/vector.c:1274
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
**Symbols:**

```
ffffffff832b762a-ffffffff832b7737: print_PIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void print_PIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff83469257)
Location: arch/x86/kernel/apic/vector.c:1274
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
**Symbols:**

```
ffffffff83469257-ffffffff83469380: print_PIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_PIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff83e8dd90)
Location: arch/x86/kernel/apic/vector.c:1270
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
**Symbols:**

```
ffffffff83e8dd90-ffffffff83e8dee5: print_PIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_PIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff836b1630)
Location: arch/x86/kernel/apic/vector.c:1270
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
**Symbols:**

```
ffffffff836b1630-ffffffff836b1785: print_PIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_PIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff838e1ac0)
Location: arch/x86/kernel/apic/vector.c:1328
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
**Symbols:**

```
ffffffff838e1ac0-ffffffff838e1c15: print_PIC (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828a6de0)
Location: arch/x86/kernel/apic/vector.c:1189
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8289eee8)
Location: arch/x86/kernel/apic/vector.c:1189
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828b9cf0)
Location: arch/x86/kernel/apic/vector.c:1189
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff828b9df1)
Location: arch/x86/kernel/apic/vector.c:1189
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:print_ICs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
