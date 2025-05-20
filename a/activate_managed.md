# Function: <code>activate_managed</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105c319)
Location: arch/x86/kernel/apic/vector.c:406
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105f2e5)
Location: arch/x86/kernel/apic/vector.c:416
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81064f55)
Location: arch/x86/kernel/apic/vector.c:407
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068671)
Location: arch/x86/kernel/apic/vector.c:404
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069096)
Location: arch/x86/kernel/apic/vector.c:415
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int activate_managed(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:416
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff8106f4c0-ffffffff8106f531: activate_managed (STB_LOCAL)
ffffffff81070480-ffffffff810704b2: activate_managed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int activate_managed(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff810709e0-ffffffff81070a51: activate_managed (STB_LOCAL)
ffffffff81bd705e-ffffffff81bd7090: activate_managed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int activate_managed(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81071200-ffffffff81071271: activate_managed (STB_LOCAL)
ffffffff81bc9214-ffffffff81bc9246: activate_managed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int activate_managed(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff8107cf90-ffffffff8107d001: activate_managed (STB_LOCAL)
ffffffff81c9dd00-ffffffff81c9dd32: activate_managed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int activate_managed(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff8108c620-ffffffff8108c69d: activate_managed (STB_LOCAL)
ffffffff81e4d18d-ffffffff81e4d1bf: activate_managed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int activate_managed(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a0ba0)
Location: arch/x86/kernel/apic/vector.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff810a0ba0-ffffffff810a0c53: activate_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int activate_managed(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3b90)
Location: arch/x86/kernel/apic/vector.c:420
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff810a3b90-ffffffff810a3c43: activate_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int activate_managed(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aabc0)
Location: arch/x86/kernel/apic/vector.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff810aabc0-ffffffff810aac73: activate_managed (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068b86)
Location: arch/x86/kernel/apic/vector.c:415
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058ef6)
Location: arch/x86/kernel/apic/vector.c:415
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069036)
Location: arch/x86/kernel/apic/vector.c:415
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106a73a)
Location: arch/x86/kernel/apic/vector.c:415
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
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
