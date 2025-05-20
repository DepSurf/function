# Function: <code>__irq_msi_compose_msg</code>

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
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106c310)
Location: arch/x86/kernel/apic/msi.c:26
Inline: True
Direct callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_update_msg
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
**Symbols:**

```
ffffffff8106c310-ffffffff8106c3cc: __irq_msi_compose_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg *cfg, struct msi_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff81073630)
Location: arch/x86/kernel/apic/msi.c:26
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
**Symbols:**

```
ffffffff81073630-ffffffff810736e0: __irq_msi_compose_msg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg *cfg, struct msi_msg *msg, bool dmar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106f690)
Location: arch/x86/kernel/apic/apic.c:2509
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff8106f690-ffffffff8106f735: __irq_msi_compose_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg *cfg, struct msi_msg *msg, bool dmar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810701c0)
Location: arch/x86/kernel/apic/apic.c:2517
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff810701c0-ffffffff81070265: __irq_msi_compose_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg *cfg, struct msi_msg *msg, bool dmar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2514
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff81c9dcaf-ffffffff81c9dcd9: __irq_msi_compose_msg.cold (STB_LOCAL)
ffffffff8107bce0-ffffffff8107bdc3: __irq_msi_compose_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg *cfg, struct msi_msg *msg, bool dmar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2522
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff81e4d130-ffffffff81e4d15a: __irq_msi_compose_msg.cold (STB_LOCAL)
ffffffff8108af10-ffffffff8108b00a: __irq_msi_compose_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg *cfg, struct msi_msg *msg, bool dmar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2556
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff82053c8e-ffffffff82053cb8: __irq_msi_compose_msg.cold (STB_LOCAL)
ffffffff8109f0f0-ffffffff8109f1ea: __irq_msi_compose_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg *cfg, struct msi_msg *msg, bool dmar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2573
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff820d2285-ffffffff820d22af: __irq_msi_compose_msg.cold (STB_LOCAL)
ffffffff810a2080-ffffffff810a217a: __irq_msi_compose_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __irq_msi_compose_msg(struct irq_cfg *cfg, struct msi_msg *msg, bool dmar);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:2457
Inline: False
Direct callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
```
**Symbols:**

```
ffffffff821acf1f-ffffffff821acf34: __irq_msi_compose_msg.cold (STB_LOCAL)
ffffffff810a8e10-ffffffff810a8eed: __irq_msi_compose_msg (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106be00)
Location: arch/x86/kernel/apic/msi.c:26
Inline: True
Direct callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_update_msg
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
**Symbols:**

```
ffffffff8106be00-ffffffff8106bebc: __irq_msi_compose_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8105c120)
Location: arch/x86/kernel/apic/msi.c:26
Inline: True
Direct callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_update_msg
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
**Symbols:**

```
ffffffff8105c120-ffffffff8105c1de: __irq_msi_compose_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106c2b0)
Location: arch/x86/kernel/apic/msi.c:26
Inline: True
Direct callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_update_msg
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
**Symbols:**

```
ffffffff8106c2b0-ffffffff8106c36c: __irq_msi_compose_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/msi.c (ffffffff8106d9b0)
Location: arch/x86/kernel/apic/msi.c:26
Inline: True
Direct callers:
  - arch/x86/kernel/apic/msi.c:irq_msi_update_msg
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
```
**Symbols:**

```
ffffffff8106d9b0-ffffffff8106da6c: __irq_msi_compose_msg.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool dmar</code>
</li>
</ul>
</details>
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
