# Function: <code>pv_tlb_flush_supported</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pv_tlb_flush_supported();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107f54c)
Location: arch/x86/kernel/kvm.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
**Symbols:**

```
ffffffff8107f54c-ffffffff8107f57c: pv_tlb_flush_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pv_tlb_flush_supported();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81bd80d2)
Location: arch/x86/kernel/kvm.c:454
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
  - arch/x86/kernel/kvm.c:kvm_guest_init
```
**Symbols:**

```
ffffffff81bd80d2-ffffffff81bd8102: pv_tlb_flush_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pv_tlb_flush_supported();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81bc9ef1)
Location: arch/x86/kernel/kvm.c:456
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff81bc9ef1-ffffffff81bc9f21: pv_tlb_flush_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pv_tlb_flush_supported();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81c9f107)
Location: arch/x86/kernel/kvm.c:456
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff81c9f107-ffffffff81c9f142: pv_tlb_flush_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pv_tlb_flush_supported();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff81e4e84f)
Location: arch/x86/kernel/kvm.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff81e4e84f-ffffffff81e4e899: pv_tlb_flush_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pv_tlb_flush_supported();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810b7250)
Location: arch/x86/kernel/kvm.c:474
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff810b7250-ffffffff810b7299: pv_tlb_flush_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pv_tlb_flush_supported();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810ba440)
Location: arch/x86/kernel/kvm.c:474
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff810ba440-ffffffff810ba489: pv_tlb_flush_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pv_tlb_flush_supported();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810c1880)
Location: arch/x86/kernel/kvm.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_guest_init
  - arch/x86/kernel/kvm.c:kvm_alloc_cpumask
```
**Symbols:**

```
ffffffff810c1880-ffffffff810c18c9: pv_tlb_flush_supported (STB_LOCAL)
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
