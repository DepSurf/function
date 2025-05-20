# Function: <code>map_high</code>

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
void map_high(char *id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828ba8ef)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:734
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
**Symbols:**

```
ffffffff828ba8ef-ffffffff828ba96f: map_high (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void map_high(char *id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce03f2)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:768
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
**Symbols:**

```
ffffffff82ce03f2-ffffffff82ce0472: map_high (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void map_high(char *id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fccb43)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:913
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
**Symbols:**

```
ffffffff82fccb43-ffffffff82fccbcd: map_high (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void map_high(char *id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d75c3)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:909
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
**Symbols:**

```
ffffffff831d75c3-ffffffff831d764d: map_high (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void map_high(char *id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832ba3d1)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:909
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
**Symbols:**

```
ffffffff832ba3d1-ffffffff832ba4bc: map_high (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void map_high(char *id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346bff7)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
**Symbols:**

```
ffffffff8346bff7-ffffffff8346c0fa: map_high (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void map_high(char *id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e90bd0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:915
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
**Symbols:**

```
ffffffff83e90bd0-ffffffff83e90d1b: map_high (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void map_high(char *id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b45a0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:916
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
**Symbols:**

```
ffffffff836b45a0-ffffffff836b46ef: map_high (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void map_high(char *id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e4ee0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:877
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmr_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
**Symbols:**

```
ffffffff838e4ee0-ffffffff838e502f: map_high (STB_LOCAL)
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
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void map_high(char *id, long unsigned int base, int pshift, int bshift, int max_pnode, enum map_type map_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bb91c)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:734
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_gru_high
```
**Symbols:**

```
ffffffff828bb91c-ffffffff828bb99c: map_high (STB_LOCAL)
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
