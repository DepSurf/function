# Function: <code>snp_prep_memory</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void snp_prep_memory(long unsigned int paddr, unsigned int sz, enum psc_op op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83471535)
Location: arch/x86/kernel/sev.c:742
Inline: False
Direct callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
```
**Symbols:**

```
ffffffff83471535-ffffffff83471592: snp_prep_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void snp_prep_memory(long unsigned int paddr, unsigned int sz, enum psc_op op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83e98670)
Location: arch/x86/kernel/sev.c:742
Inline: False
Direct callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
```
**Symbols:**

```
ffffffff83e98670-ffffffff83e98711: snp_prep_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void snp_prep_memory(long unsigned int paddr, unsigned int sz, enum psc_op op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff836bc0b0)
Location: arch/x86/kernel/sev.c:750
Inline: False
Direct callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
```
**Symbols:**

```
ffffffff836bc0b0-ffffffff836bc149: snp_prep_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void snp_prep_memory(long unsigned int paddr, unsigned int sz, enum psc_op op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff838eca90)
Location: arch/x86/kernel/sev.c:777
Inline: False
Direct callers:
  - arch/x86/kernel/probe_roms.c:probe_roms
```
**Symbols:**

```
ffffffff838eca90-ffffffff838ecb29: snp_prep_memory (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
