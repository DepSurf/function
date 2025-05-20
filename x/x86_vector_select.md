# Function: <code>x86_vector_select</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int x86_vector_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070040)
Location: arch/x86/kernel/apic/vector.c:671
Inline: True
```
**Symbols:**

```
ffffffff81070040-ffffffff810700b1: x86_vector_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int x86_vector_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070b90)
Location: arch/x86/kernel/apic/vector.c:679
Inline: True
```
**Symbols:**

```
ffffffff81070b90-ffffffff81070c01: x86_vector_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int x86_vector_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107c810)
Location: arch/x86/kernel/apic/vector.c:679
Inline: True
```
**Symbols:**

```
ffffffff8107c810-ffffffff8107c881: x86_vector_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int x86_vector_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108bbf0)
Location: arch/x86/kernel/apic/vector.c:679
Inline: False
```
**Symbols:**

```
ffffffff8108bbf0-ffffffff8108bc6b: x86_vector_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x86_vector_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a00a0)
Location: arch/x86/kernel/apic/vector.c:675
Inline: False
```
**Symbols:**

```
ffffffff810a00a0-ffffffff810a011b: x86_vector_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x86_vector_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3020)
Location: arch/x86/kernel/apic/vector.c:675
Inline: False
```
**Symbols:**

```
ffffffff810a3020-ffffffff810a309b: x86_vector_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int x86_vector_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a9f60)
Location: arch/x86/kernel/apic/vector.c:686
Inline: False
```
**Symbols:**

```
ffffffff810a9f60-ffffffff810a9fd2: x86_vector_select (STB_LOCAL)
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
