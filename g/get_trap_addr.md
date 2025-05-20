# Function: <code>get_trap_addr</code>

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
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81988220)
Location: arch/x86/xen/enlighten_pv.c:627
Inline: False
```
**Symbols:**

```
ffffffff81988220-ffffffff819882af: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff819e4be0)
Location: arch/x86/xen/enlighten_pv.c:603
Inline: False
```
**Symbols:**

```
ffffffff819e4be0-ffffffff819e4c6f: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81a1fd10)
Location: arch/x86/xen/enlighten_pv.c:625
Inline: False
```
**Symbols:**

```
ffffffff81a1fd10-ffffffff81a1fdab: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81a90500)
Location: arch/x86/xen/enlighten_pv.c:625
Inline: False
```
**Symbols:**

```
ffffffff81a90500-ffffffff81a905a7: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81ac7890)
Location: arch/x86/xen/enlighten_pv.c:633
Inline: False
```
**Symbols:**

```
ffffffff81ac7890-ffffffff81ac792c: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81bc0270)
Location: arch/x86/xen/enlighten_pv.c:665
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
```
**Symbols:**

```
ffffffff81bc0270-ffffffff81bc030c: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81c39240)
Location: arch/x86/xen/enlighten_pv.c:637
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
```
**Symbols:**

```
ffffffff81c39240-ffffffff81c392cd: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81c2b690)
Location: arch/x86/xen/enlighten_pv.c:659
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
```
**Symbols:**

```
ffffffff81c2b690-ffffffff81c2b720: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81d49d00)
Location: arch/x86/xen/enlighten_pv.c:630
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_write_idt_entry
```
**Symbols:**

```
ffffffff81d49d00-ffffffff81d49df9: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81f19250)
Location: arch/x86/xen/enlighten_pv.c:636
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_convert_trap_info
```
**Symbols:**

```
ffffffff81f19250-ffffffff81f1935a: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff820c0d40)
Location: arch/x86/xen/enlighten_pv.c:647
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_convert_trap_info
```
**Symbols:**

```
ffffffff820c0d40-ffffffff820c0e4a: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff821449f0)
Location: arch/x86/xen/enlighten_pv.c:702
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_convert_trap_info
```
**Symbols:**

```
ffffffff821449f0-ffffffff82144afa: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff82227110)
Location: arch/x86/xen/enlighten_pv.c:728
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_convert_trap_info
```
**Symbols:**

```
ffffffff82227110-ffffffff8222721a: get_trap_addr (STB_LOCAL)
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
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81a66700)
Location: arch/x86/xen/enlighten_pv.c:633
Inline: False
```
**Symbols:**

```
ffffffff81a66700-ffffffff81a6679c: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81ad2b10)
Location: arch/x86/xen/enlighten_pv.c:633
Inline: False
```
**Symbols:**

```
ffffffff81ad2b10-ffffffff81ad2bac: get_trap_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool get_trap_addr(void **addr, unsigned int ist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81adf010)
Location: arch/x86/xen/enlighten_pv.c:633
Inline: False
```
**Symbols:**

```
ffffffff81adf010-ffffffff81adf0ac: get_trap_addr (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
