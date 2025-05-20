# Function: <code>sev_es_setup_ap_jump_table</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sev_es_setup_ap_jump_table(struct real_mode_header *rmh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81084230)
Location: arch/x86/kernel/sev-es.c:485
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
**Symbols:**

```
ffffffff81084230-ffffffff810842a1: sev_es_setup_ap_jump_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sev_es_setup_ap_jump_table(struct real_mode_header *rmh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81084f90)
Location: arch/x86/kernel/sev.c:564
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
**Symbols:**

```
ffffffff81084f90-ffffffff81085004: sev_es_setup_ap_jump_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sev_es_setup_ap_jump_table(struct real_mode_header *rmh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81094150)
Location: arch/x86/kernel/sev.c:561
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
**Symbols:**

```
ffffffff81094150-ffffffff810941c4: sev_es_setup_ap_jump_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sev_es_setup_ap_jump_table(struct real_mode_header *rmh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83471678)
Location: arch/x86/kernel/sev.c:1147
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
**Symbols:**

```
ffffffff83471678-ffffffff834716e7: sev_es_setup_ap_jump_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sev_es_setup_ap_jump_table(struct real_mode_header *rmh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83e98850)
Location: arch/x86/kernel/sev.c:1147
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
**Symbols:**

```
ffffffff83e98850-ffffffff83e988c4: sev_es_setup_ap_jump_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sev_es_setup_ap_jump_table(struct real_mode_header *rmh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff836bc280)
Location: arch/x86/kernel/sev.c:1105
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
**Symbols:**

```
ffffffff836bc280-ffffffff836bc2f4: sev_es_setup_ap_jump_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sev_es_setup_ap_jump_table(struct real_mode_header *rmh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff838eccf0)
Location: arch/x86/kernel/sev.c:1131
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
```
**Symbols:**

```
ffffffff838eccf0-ffffffff838ecd64: sev_es_setup_ap_jump_table (STB_GLOBAL)
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
