# Function: <code>irq_msi_update_msg</code>

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
void irq_msi_update_msg(struct irq_data *irqd, struct irq_cfg *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106c400)
Location: arch/x86/kernel/apic/msi.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff8106c400-ffffffff8106c47d: irq_msi_update_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81073811)
Location: arch/x86/kernel/apic/msi.c:53
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff810745f3)
Location: arch/x86/kernel/apic/msi.c:25
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
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
In arch/x86/kernel/apic/msi.c (ffffffff810750ba)
Location: arch/x86/kernel/apic/msi.c:25
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
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
In arch/x86/kernel/apic/msi.c (ffffffff81082574)
Location: arch/x86/kernel/apic/msi.c:25
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
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
In arch/x86/kernel/apic/msi.c (ffffffff81092160)
Location: arch/x86/kernel/apic/msi.c:26
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
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
In arch/x86/kernel/apic/msi.c (ffffffff810a7150)
Location: arch/x86/kernel/apic/msi.c:26
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
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
In arch/x86/kernel/apic/msi.c (ffffffff810aa3b0)
Location: arch/x86/kernel/apic/msi.c:26
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
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
In arch/x86/kernel/apic/msi.c (ffffffff810b1440)
Location: arch/x86/kernel/apic/msi.c:26
Inline: True
Inline callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
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
<summary>In <code>aws</code>: ✅</summary>

```c
void irq_msi_update_msg(struct irq_data *irqd, struct irq_cfg *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106bef0)
Location: arch/x86/kernel/apic/msi.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff8106bef0-ffffffff8106bf6d: irq_msi_update_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_msi_update_msg(struct irq_data *irqd, struct irq_cfg *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8105c210)
Location: arch/x86/kernel/apic/msi.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff8105c210-ffffffff8105c28d: irq_msi_update_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_msi_update_msg(struct irq_data *irqd, struct irq_cfg *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106c3a0)
Location: arch/x86/kernel/apic/msi.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff8106c3a0-ffffffff8106c41d: irq_msi_update_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_msi_update_msg(struct irq_data *irqd, struct irq_cfg *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106daa0)
Location: arch/x86/kernel/apic/msi.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff8106daa0-ffffffff8106db1d: irq_msi_update_msg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
