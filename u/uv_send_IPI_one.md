# Function: <code>uv_send_IPI_one</code>

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
void uv_send_IPI_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d160)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
```
**Symbols:**

```
ffffffff8106d160-ffffffff8106d227: uv_send_IPI_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uv_send_IPI_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074870)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:567
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff81074870-ffffffff81074941: uv_send_IPI_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uv_send_IPI_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810751d0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:724
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff810751d0-ffffffff81075299: uv_send_IPI_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uv_send_IPI_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075c70)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:720
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff81075c70-ffffffff81075d39: uv_send_IPI_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void uv_send_IPI_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:720
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff810831f0-ffffffff8108330b: uv_send_IPI_one (STB_LOCAL)
ffffffff81c9e68a-ffffffff81c9e6d6: uv_send_IPI_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void uv_send_IPI_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:726
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
```
**Symbols:**

```
ffffffff81093090-ffffffff810931ab: uv_send_IPI_one (STB_LOCAL)
ffffffff81e4dad2-ffffffff81e4db1e: uv_send_IPI_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void uv_send_IPI_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:726
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
```
**Symbols:**

```
ffffffff810a8410-ffffffff810a852b: uv_send_IPI_one (STB_LOCAL)
ffffffff82053eb2-ffffffff82053efe: uv_send_IPI_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void uv_send_IPI_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:727
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
```
**Symbols:**

```
ffffffff810ab680-ffffffff810ab79b: uv_send_IPI_one (STB_LOCAL)
ffffffff820d24d4-ffffffff820d2520: uv_send_IPI_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void uv_send_IPI_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:728
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
```
**Symbols:**

```
ffffffff810b24f0-ffffffff810b2604: uv_send_IPI_one (STB_LOCAL)
ffffffff821ad205-ffffffff821ad251: uv_send_IPI_one.cold (STB_LOCAL)
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
void uv_send_IPI_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e820)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask
```
**Symbols:**

```
ffffffff8106e820-ffffffff8106e8e7: uv_send_IPI_one (STB_LOCAL)
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
