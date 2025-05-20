# Function: <code>kvm_send_ipi_mask_allbutself</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:509
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_allbutself
```
**Symbols:**

```
ffffffff81072e60-ffffffff81072ef6: kvm_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff81073633-ffffffff8107363f: kvm_send_ipi_mask_allbutself.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:493
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_send_ipi_allbutself
```
**Symbols:**

```
ffffffff810769e0-ffffffff81076a76: kvm_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff810771bb-ffffffff810771c7: kvm_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:493
Inline: False
```
**Symbols:**

```
ffffffff81077a50-ffffffff81077ae6: kvm_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff8107821a-ffffffff81078226: kvm_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107ed40)
Location: arch/x86/kernel/kvm.c:517
Inline: False
```
**Symbols:**

```
ffffffff8107ed40-ffffffff8107ed92: kvm_send_ipi_mask_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107e970)
Location: arch/x86/kernel/kvm.c:540
Inline: False
```
**Symbols:**

```
ffffffff8107e970-ffffffff8107e9c2: kvm_send_ipi_mask_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8107fe40)
Location: arch/x86/kernel/kvm.c:538
Inline: False
```
**Symbols:**

```
ffffffff8107fe40-ffffffff8107fe92: kvm_send_ipi_mask_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8108ec80)
Location: arch/x86/kernel/kvm.c:541
Inline: False
```
**Symbols:**

```
ffffffff8108ec80-ffffffff8108ecd2: kvm_send_ipi_mask_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8109f7c0)
Location: arch/x86/kernel/kvm.c:562
Inline: False
```
**Symbols:**

```
ffffffff8109f7c0-ffffffff8109f824: kvm_send_ipi_mask_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810b7040)
Location: arch/x86/kernel/kvm.c:561
Inline: False
```
**Symbols:**

```
ffffffff810b7040-ffffffff810b70a4: kvm_send_ipi_mask_allbutself (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:561
Inline: False
```
**Symbols:**

```
ffffffff810ba1e0-ffffffff810ba2a0: kvm_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff820d2a7b-ffffffff820d2a96: kvm_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:562
Inline: False
```
**Symbols:**

```
ffffffff810c1590-ffffffff810c1650: kvm_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff821ad8dd-ffffffff821ad8f8: kvm_send_ipi_mask_allbutself.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:493
Inline: False
```
**Symbols:**

```
ffffffff81076a50-ffffffff81076ae6: kvm_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff8107721a-ffffffff81077226: kvm_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:493
Inline: False
```
**Symbols:**

```
ffffffff81066a30-ffffffff81066ac6: kvm_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff81067306-ffffffff81067312: kvm_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:493
Inline: False
```
**Symbols:**

```
ffffffff81076a00-ffffffff81076a96: kvm_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff810771ca-ffffffff810771d6: kvm_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void kvm_send_ipi_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kvm.c (0)
Location: arch/x86/kernel/kvm.c:493
Inline: False
```
**Symbols:**

```
ffffffff81078b60-ffffffff81078bf6: kvm_send_ipi_mask_allbutself (STB_LOCAL)
ffffffff8107923a-ffffffff81079246: kvm_send_ipi_mask_allbutself.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
