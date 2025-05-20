# Function: <code>get_mn</code>

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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bb428)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1104
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
void get_mn(struct mn *mnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074de5)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1096
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff81074de5-ffffffff81074eb7: get_mn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_mn(struct mn *mnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bd77d5)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1254
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff81bd77d5-ffffffff81bd78cc: get_mn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d6ea4)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1250
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832b9bc2)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1250
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346b83f)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e92f89)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1256
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_mn(struct mn *mnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810aba90)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1258
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff810aba90-ffffffff810abb99: get_mn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_mn(struct mn *mnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2900)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1219
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_init_hub_info
```
**Symbols:**

```
ffffffff810b2900-ffffffff810b2a09: get_mn (STB_LOCAL)
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bc455)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1104
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
