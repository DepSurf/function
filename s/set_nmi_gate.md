# Function: <code>set_nmi_gate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_nmi_gate(int gate, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8107ca62)
Location: arch/x86/include/asm/desc.h:307
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff8107ca62-ffffffff8107cacf: set_nmi_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_nmi_gate(int gate, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8107e4cf)
Location: arch/x86/include/asm/desc.h:307
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff8107e4cf-ffffffff8107e53c: set_nmi_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_nmi_gate(int gate, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81082ae2)
Location: arch/x86/include/asm/desc.h:307
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff81082ae2-ffffffff81082b4f: set_nmi_gate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_nmi_gate(int gate, void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102d17d)
Location: arch/x86/include/asm/desc.h:414
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:trap_init
  - arch/x86/kernel/traps.c:trap_init
```
**Symbols:**

```
ffffffff8102d17d-ffffffff8102d1e3: set_nmi_gate (STB_LOCAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
