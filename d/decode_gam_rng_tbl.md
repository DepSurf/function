# Function: <code>decode_gam_rng_tbl</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bcbae)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1196
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void decode_gam_rng_tbl(long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82cdfa9b)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1188
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:decode_uv_systab
```
**Symbols:**

```
ffffffff82cdfa9b-ffffffff82cdfcc6: decode_gam_rng_tbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void decode_gam_rng_tbl(long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fcbf94)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1344
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:decode_uv_systab
```
**Symbols:**

```
ffffffff82fcbf94-ffffffff82fcc1bf: decode_gam_rng_tbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void decode_gam_rng_tbl(long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d68e5)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1340
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:decode_uv_systab
```
**Symbols:**

```
ffffffff831d68e5-ffffffff831d6b0d: decode_gam_rng_tbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void decode_gam_rng_tbl(long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832b95c3)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1340
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:decode_uv_systab
```
**Symbols:**

```
ffffffff832b95c3-ffffffff832b9827: decode_gam_rng_tbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void decode_gam_rng_tbl(long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346b2ec)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1346
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:decode_uv_systab
```
**Symbols:**

```
ffffffff8346b2ec-ffffffff8346b587: decode_gam_rng_tbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void decode_gam_rng_tbl(long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e90520)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1346
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:decode_uv_systab
```
**Symbols:**

```
ffffffff83e90520-ffffffff83e9088b: decode_gam_rng_tbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void decode_gam_rng_tbl(long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b3db0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1349
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:decode_uv_systab
```
**Symbols:**

```
ffffffff836b3db0-ffffffff836b4129: decode_gam_rng_tbl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void decode_gam_rng_tbl(long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e4860)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1310
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:decode_uv_systab
```
**Symbols:**

```
ffffffff838e4860-ffffffff838e4bd9: decode_gam_rng_tbl (STB_LOCAL)
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
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bdbdb)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1196
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
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
