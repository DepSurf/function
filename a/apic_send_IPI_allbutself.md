# Function: <code>apic_send_IPI_allbutself</code>

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
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810678c0)
Location: arch/x86/kernel/apic/ipi.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff810678c0-ffffffff81067907: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8106e610)
Location: arch/x86/kernel/apic/ipi.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff8106e610-ffffffff8106e657: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8106fa90)
Location: arch/x86/kernel/apic/ipi.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff8106fa90-ffffffff8106fad7: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810705c0)
Location: arch/x86/kernel/apic/ipi.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff810705c0-ffffffff81070607: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c160)
Location: arch/x86/kernel/apic/ipi.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff8107c160-ffffffff8107c1a4: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8108b480)
Location: arch/x86/kernel/apic/ipi.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff8108b480-ffffffff8108b4e2: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8109f830)
Location: arch/x86/kernel/apic/ipi.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff8109f830-ffffffff8109f892: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810a27c0)
Location: arch/x86/kernel/apic/ipi.c:49
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff810a27c0-ffffffff810a2822: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810a94b0)
Location: arch/x86/kernel/apic/ipi.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:nmi_shootdown_cpus
  - arch/x86/kernel/smp.c:native_stop_other_cpus
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff810a94b0-ffffffff810a94fc: apic_send_IPI_allbutself (STB_GLOBAL)
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
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810673b0)
Location: arch/x86/kernel/apic/ipi.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff810673b0-ffffffff810673f7: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057770)
Location: arch/x86/kernel/apic/ipi.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff81057770-ffffffff810577b7: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067860)
Location: arch/x86/kernel/apic/ipi.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff81067860-ffffffff810678a7: apic_send_IPI_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void apic_send_IPI_allbutself(unsigned int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81068e40)
Location: arch/x86/kernel/apic/ipi.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_roundup_cpus
```
**Symbols:**

```
ffffffff81068e40-ffffffff81068e87: apic_send_IPI_allbutself (STB_GLOBAL)
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
