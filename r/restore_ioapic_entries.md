# Function: <code>restore_ioapic_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056f90)
Location: arch/x86/kernel/apic/io_apic.c:684
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff81056f90-ffffffff81057004: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81057200)
Location: arch/x86/kernel/apic/io_apic.c:684
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff81057200-ffffffff81057274: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059f90)
Location: arch/x86/kernel/apic/io_apic.c:683
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff81059f90-ffffffff8105a004: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810595e0)
Location: arch/x86/kernel/apic/io_apic.c:683
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff810595e0-ffffffff81059654: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105dad0)
Location: arch/x86/kernel/apic/io_apic.c:684
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff8105dad0-ffffffff8105db44: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81060858)
Location: arch/x86/kernel/apic/io_apic.c:685
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff81060730-ffffffff810607a0: restore_ioapic_entries.part.11 (STB_LOCAL)
ffffffff81060c50-ffffffff81060c62: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810666a8)
Location: arch/x86/kernel/apic/io_apic.c:685
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff81066580-ffffffff810665f0: restore_ioapic_entries.part.10 (STB_LOCAL)
ffffffff81066930-ffffffff81066942: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069fc0)
Location: arch/x86/kernel/apic/io_apic.c:686
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff81069fc0-ffffffff8106a034: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a960)
Location: arch/x86/kernel/apic/io_apic.c:686
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff8106a960-ffffffff8106a9d4: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071d20)
Location: arch/x86/kernel/apic/io_apic.c:673
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff81071d20-ffffffff81071dbf: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810731d0)
Location: arch/x86/kernel/apic/io_apic.c:660
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff810731d0-ffffffff8107326f: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073ca0)
Location: arch/x86/kernel/apic/io_apic.c:660
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff81073ca0-ffffffff81073d3f: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81081270)
Location: arch/x86/kernel/apic/io_apic.c:660
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff81081270-ffffffff81081396: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81090d10)
Location: arch/x86/kernel/apic/io_apic.c:661
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff81090d10-ffffffff81090e4f: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a58a0)
Location: arch/x86/kernel/apic/io_apic.c:661
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff810a58a0-ffffffff810a59df: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a8a70)
Location: arch/x86/kernel/apic/io_apic.c:662
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff810a8a70-ffffffff810a8bca: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810afb00)
Location: arch/x86/kernel/apic/io_apic.c:662
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff810afb00-ffffffff810afc5a: restore_ioapic_entries (STB_GLOBAL)
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
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a450)
Location: arch/x86/kernel/apic/io_apic.c:686
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff8106a450-ffffffff8106a4c4: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a7b0)
Location: arch/x86/kernel/apic/io_apic.c:686
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff8105a7b0-ffffffff8105a824: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a900)
Location: arch/x86/kernel/apic/io_apic.c:686
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff8106a900-ffffffff8106a974: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int restore_ioapic_entries();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106c000)
Location: arch/x86/kernel/apic/io_apic.c:686
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:enable_IR_x2apic
  - arch/x86/kernel/apic/io_apic.c:ioapic_resume
```
**Symbols:**

```
ffffffff8106c000-ffffffff8106c074: restore_ioapic_entries (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
