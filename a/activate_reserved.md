# Function: <code>activate_reserved</code>

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
In arch/x86/kernel/apic/vector.c (ffffffff8105c2f5)
Location: arch/x86/kernel/apic/vector.c:385
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
In arch/x86/kernel/apic/vector.c (ffffffff8105f34a)
Location: arch/x86/kernel/apic/vector.c:395
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
In arch/x86/kernel/apic/vector.c (ffffffff81064fc1)
Location: arch/x86/kernel/apic/vector.c:386
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
In arch/x86/kernel/apic/vector.c (ffffffff810686c8)
Location: arch/x86/kernel/apic/vector.c:383
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
In arch/x86/kernel/apic/vector.c (ffffffff81068fa8)
Location: arch/x86/kernel/apic/vector.c:383
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
int activate_reserved(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:384
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff8106f770-ffffffff8106f7ff: activate_reserved (STB_LOCAL)
ffffffff810704b2-ffffffff810704c6: activate_reserved.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int activate_reserved(struct irq_data *irqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/vector.c (0)
Location: arch/x86/kernel/apic/vector.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
**Symbols:**

```
ffffffff81070c90-ffffffff81070d1f: activate_reserved (STB_LOCAL)
ffffffff81bd7090-ffffffff81bd70a4: activate_reserved.cold (STB_LOCAL)
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
In arch/x86/kernel/apic/vector.c (ffffffff81071528)
Location: arch/x86/kernel/apic/vector.c:388
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
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
In arch/x86/kernel/apic/vector.c (ffffffff8107d318)
Location: arch/x86/kernel/apic/vector.c:388
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
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
In arch/x86/kernel/apic/vector.c (ffffffff8108c9e6)
Location: arch/x86/kernel/apic/vector.c:388
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
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
In arch/x86/kernel/apic/vector.c (ffffffff810a0fe6)
Location: arch/x86/kernel/apic/vector.c:388
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3fd6)
Location: arch/x86/kernel/apic/vector.c:388
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810ab006)
Location: arch/x86/kernel/apic/vector.c:399
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_activate
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
In arch/x86/kernel/apic/vector.c (ffffffff81068a98)
Location: arch/x86/kernel/apic/vector.c:383
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
In arch/x86/kernel/apic/vector.c (ffffffff81058e08)
Location: arch/x86/kernel/apic/vector.c:383
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
In arch/x86/kernel/apic/vector.c (ffffffff81068f48)
Location: arch/x86/kernel/apic/vector.c:383
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
In arch/x86/kernel/apic/vector.c (ffffffff8106a64c)
Location: arch/x86/kernel/apic/vector.c:383
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
</ul>
