# Function: <code>__send_ipi_mask</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bc30)
Location: arch/x86/hyperv/hv_apic.c:130
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
**Symbols:**

```
ffffffff8102bc30-ffffffff8102bf07: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cc00)
Location: arch/x86/hyperv/hv_apic.c:134
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/kvm.c (ffffffff81072920)
Location: arch/x86/kernel/kvm.c:450
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_all
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff8102cc00-ffffffff8102cf08: __send_ipi_mask (STB_LOCAL)
ffffffff81072920-ffffffff81072b45: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102eb50)
Location: arch/x86/hyperv/hv_apic.c:139
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/kvm.c (ffffffff81076790)
Location: arch/x86/kernel/kvm.c:434
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_all
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff8102eb50-ffffffff8102ecb7: __send_ipi_mask (STB_LOCAL)
ffffffff81076790-ffffffff810769bf: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f460)
Location: arch/x86/hyperv/hv_apic.c:139
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/kvm.c (ffffffff81077820)
Location: arch/x86/kernel/kvm.c:434
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff8102f460-ffffffff8102f5c7: __send_ipi_mask (STB_LOCAL)
ffffffff81077820-ffffffff81077a4f: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810319a0)
Location: arch/x86/hyperv/hv_apic.c:139
Inline: False
```
```
In arch/x86/kernel/kvm.c (ffffffff8107eb10)
Location: arch/x86/kernel/kvm.c:458
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff810319a0-ffffffff81031b14: __send_ipi_mask (STB_LOCAL)
ffffffff8107eb10-ffffffff8107ed3f: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810326a0)
Location: arch/x86/hyperv/hv_apic.c:139
Inline: False
```
```
In arch/x86/kernel/kvm.c (ffffffff8107e740)
Location: arch/x86/kernel/kvm.c:479
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff810326a0-ffffffff81032800: __send_ipi_mask (STB_LOCAL)
ffffffff8107e740-ffffffff8107e96f: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81033af0)
Location: arch/x86/hyperv/hv_apic.c:141
Inline: False
```
```
In arch/x86/kernel/kvm.c (ffffffff8107fc00)
Location: arch/x86/kernel/kvm.c:477
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff81033af0-ffffffff81033c51: __send_ipi_mask (STB_LOCAL)
ffffffff8107fc00-ffffffff8107fe31: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector, bool exclude_self);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81038eb0)
Location: arch/x86/hyperv/hv_apic.c:155
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:480
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff81038eb0-ffffffff8103904b: __send_ipi_mask (STB_LOCAL)
ffffffff8108e9e0-ffffffff8108ec7e: __send_ipi_mask (STB_LOCAL)
ffffffff81c9f080-ffffffff81c9f107: __send_ipi_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector, bool exclude_self);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8103fc80)
Location: arch/x86/hyperv/hv_apic.c:155
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:501
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff8103fc80-ffffffff8103fe5b: __send_ipi_mask (STB_LOCAL)
ffffffff8109f490-ffffffff8109f7b2: __send_ipi_mask (STB_LOCAL)
ffffffff81e4e7ca-ffffffff81e4e84f: __send_ipi_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector, bool exclude_self);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81048bd0)
Location: arch/x86/hyperv/hv_apic.c:155
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:500
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff81048bd0-ffffffff81048db5: __send_ipi_mask (STB_LOCAL)
ffffffff810b6d00-ffffffff810b7023: __send_ipi_mask (STB_LOCAL)
ffffffff8205441e-ffffffff820544a5: __send_ipi_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector, bool exclude_self);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81048e30)
Location: arch/x86/hyperv/hv_apic.c:157
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:500
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff81048e30-ffffffff81049015: __send_ipi_mask (STB_LOCAL)
ffffffff810b9ea0-ffffffff810ba1c3: __send_ipi_mask (STB_LOCAL)
ffffffff820d29f4-ffffffff820d2a7b: __send_ipi_mask.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector, bool exclude_self);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810500a0)
Location: arch/x86/hyperv/hv_apic.c:157
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:hv_send_ipi_allbutself
```
```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:501
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff810500a0-ffffffff81050279: __send_ipi_mask (STB_LOCAL)
ffffffff810c1260-ffffffff810c1576: __send_ipi_mask (STB_LOCAL)
ffffffff821ad858-ffffffff821ad8dd: __send_ipi_mask.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f5c0)
Location: arch/x86/hyperv/hv_apic.c:139
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/kvm.c (ffffffff81076820)
Location: arch/x86/kernel/kvm.c:434
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff8102f5c0-ffffffff8102f727: __send_ipi_mask (STB_LOCAL)
ffffffff81076820-ffffffff81076a4f: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ec40)
Location: arch/x86/hyperv/hv_apic.c:139
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/kvm.c (ffffffff81066820)
Location: arch/x86/kernel/kvm.c:434
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff8101ec40-ffffffff8101ef33: __send_ipi_mask (STB_LOCAL)
ffffffff81066820-ffffffff81066a29: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f420)
Location: arch/x86/hyperv/hv_apic.c:139
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/kvm.c (ffffffff810767d0)
Location: arch/x86/kernel/kvm.c:434
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff8102f420-ffffffff8102f587: __send_ipi_mask (STB_LOCAL)
ffffffff810767d0-ffffffff810769ff: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
bool __send_ipi_mask(const struct cpumask *mask, int vector);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81030260)
Location: arch/x86/hyperv/hv_apic.c:139
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_apic.c:__send_ipi_one
```
```
In arch/x86/kernel/kvm.c (ffffffff81078930)
Location: arch/x86/kernel/kvm.c:434
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask_allbutself
  - arch/x86/kernel/kvm.c:kvm_send_ipi_mask
```
**Symbols:**

```
ffffffff81030260-ffffffff810303e0: __send_ipi_mask (STB_LOCAL)
ffffffff81078930-ffffffff81078b5f: __send_ipi_mask (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exclude_self</code>
</li>
</ul>
</details>
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
