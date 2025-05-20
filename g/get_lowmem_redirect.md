# Function: <code>get_lowmem_redirect</code>

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
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:698
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void get_lowmem_redirect(long unsigned int *base, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82cdf918)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:732
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff82cdf918-ffffffff82cdfa9b: get_lowmem_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_lowmem_redirect(long unsigned int *base, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fcbce9)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:876
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff82fcbce9-ffffffff82fcbf94: get_lowmem_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_lowmem_redirect(long unsigned int *base, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d6647)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:872
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff831d6647-ffffffff831d68e5: get_lowmem_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void get_lowmem_redirect(long unsigned int *base, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832b9325)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:872
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff832b9325-ffffffff832b95c3: get_lowmem_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void get_lowmem_redirect(long unsigned int *base, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346b0db)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:878
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff8346b0db-ffffffff8346b2ec: get_lowmem_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_lowmem_redirect(long unsigned int *base, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e92cb0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:878
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff83e92cb0-ffffffff83e92f43: get_lowmem_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_lowmem_redirect(long unsigned int *base, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b6aa0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:879
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff836b6aa0-ffffffff836b6d33: get_lowmem_redirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_lowmem_redirect(long unsigned int *base, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e73b0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff838e73b0-ffffffff838e7643: get_lowmem_redirect (STB_LOCAL)
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
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:698
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
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
