# Function: <code>print_IO_APIC</code>

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
In arch/x86/kernel/apic/io_apic.c (ffffffff81f730d7)
Location: arch/x86/kernel/apic/io_apic.c:1279
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9b8f2)
Location: arch/x86/kernel/apic/io_apic.c:1280
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd6e3b)
Location: arch/x86/kernel/apic/io_apic.c:1279
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff820b7b51)
Location: arch/x86/kernel/apic/io_apic.c:1257
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff826be4ff)
Location: arch/x86/kernel/apic/io_apic.c:1259
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff826e82c7)
Location: arch/x86/kernel/apic/io_apic.c:1260
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8289ee1c)
Location: arch/x86/kernel/apic/io_apic.c:1260
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828b6d48)
Location: arch/x86/kernel/apic/io_apic.c:1263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828ba21d)
Location: arch/x86/kernel/apic/io_apic.c:1263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_IO_APIC(int ioapic_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cde70c)
Location: arch/x86/kernel/apic/io_apic.c:1250
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
```
**Symbols:**

```
ffffffff82cde70c-ffffffff82cde8c8: print_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_IO_APIC(int ioapic_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcaabe)
Location: arch/x86/kernel/apic/io_apic.c:1259
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
```
**Symbols:**

```
ffffffff82fcaabe-ffffffff82fcac7a: print_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_IO_APIC(int ioapic_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d541d)
Location: arch/x86/kernel/apic/io_apic.c:1259
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
```
**Symbols:**

```
ffffffff831d541d-ffffffff831d55d9: print_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void print_IO_APIC(int ioapic_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b7f4f)
Location: arch/x86/kernel/apic/io_apic.c:1259
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
```
**Symbols:**

```
ffffffff832b7f4f-ffffffff832b8128: print_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void print_IO_APIC(int ioapic_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff83469c40)
Location: arch/x86/kernel/apic/io_apic.c:1260
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
```
**Symbols:**

```
ffffffff83469c40-ffffffff83469e2b: print_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_IO_APIC(int ioapic_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8ee00)
Location: arch/x86/kernel/apic/io_apic.c:1260
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
```
**Symbols:**

```
ffffffff83e8ee00-ffffffff83e8f002: print_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_IO_APIC(int ioapic_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b26a0)
Location: arch/x86/kernel/apic/io_apic.c:1261
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
```
**Symbols:**

```
ffffffff836b26a0-ffffffff836b28a4: print_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_IO_APIC(int ioapic_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e2f80)
Location: arch/x86/kernel/apic/io_apic.c:1261
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
```
**Symbols:**

```
ffffffff838e2f80-ffffffff838e3184: print_IO_APIC (STB_LOCAL)
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828a8235)
Location: arch/x86/kernel/apic/io_apic.c:1263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828a0308)
Location: arch/x86/kernel/apic/io_apic.c:1263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828bb134)
Location: arch/x86/kernel/apic/io_apic.c:1263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828bb24a)
Location: arch/x86/kernel/apic/io_apic.c:1263
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:print_IO_APICs
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
