# Function: <code>xen_send_IPI_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c9770)
Location: drivers/xen/events/events_base.c:1197
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff814c9770-ffffffff814c97cb: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8151a290)
Location: drivers/xen/events/events_base.c:1208
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff8151a290-ffffffff8151a2fe: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81546780)
Location: drivers/xen/events/events_base.c:1207
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff81546780-ffffffff815467ee: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8155a5a0)
Location: drivers/xen/events/events_base.c:1199
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff8155a5a0-ffffffff8155a60e: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815be9e0)
Location: drivers/xen/events/events_base.c:1199
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff815be9e0-ffffffff815bea4e: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1197
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff815f7612-ffffffff815f7627: xen_send_IPI_one.cold.26 (STB_LOCAL)
ffffffff815f7010-ffffffff815f7072: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1197
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff816126cc-ffffffff816126e1: xen_send_IPI_one.cold.25 (STB_LOCAL)
ffffffff816120a0-ffffffff81612102: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1198
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff816464f7-ffffffff8164650d: xen_send_IPI_one.cold (STB_LOCAL)
ffffffff81645df0-ffffffff81645e91: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1198
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff816689b4-ffffffff816689ca: xen_send_IPI_one.cold (STB_LOCAL)
ffffffff81668370-ffffffff81668411: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1213
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff81718ad6-ffffffff81718aec: xen_send_IPI_one.cold (STB_LOCAL)
ffffffff81718500-ffffffff817185a1: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1595
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff81c04fe7-ffffffff81c04ffd: xen_send_IPI_one.cold (STB_LOCAL)
ffffffff81735aa0-ffffffff81735b71: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1632
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff81bf6c2c-ffffffff81bf6c40: xen_send_IPI_one.cold (STB_LOCAL)
ffffffff81719280-ffffffff81719353: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1638
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff81cf58f3-ffffffff81cf5907: xen_send_IPI_one.cold (STB_LOCAL)
ffffffff81797070-ffffffff817971d0: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1638
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:xen_send_IPI_all
  - arch/x86/xen/smp.c:xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_call_function_single_ipi
  - arch/x86/xen/smp.c:xen_smp_send_call_function_ipi
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
```
**Symbols:**

```
ffffffff81ebda3b-ffffffff81ebda4f: xen_send_IPI_one.cold (STB_LOCAL)
ffffffff818d0010-ffffffff818d0182: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a21790)
Location: drivers/xen/events/events_base.c:1640
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
```
**Symbols:**

```
ffffffff81a21790-ffffffff81a21911: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6ab20)
Location: drivers/xen/events/events_base.c:1634
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
```
**Symbols:**

```
ffffffff81a6ab20-ffffffff81a6aca1: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abcdf0)
Location: drivers/xen/events/events_base.c:1624
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
```
**Symbols:**

```
ffffffff81abcdf0-ffffffff81abcf18: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108323c8)
Location: drivers/xen/events/events_base.c:1198
Inline: False
```
**Symbols:**

```
ffff8000108323c8-ffff800010832418: xen_send_IPI_one (STB_GLOBAL)
```
</details>
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
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1202
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff8162e7e4-ffffffff8162e7fa: xen_send_IPI_one.cold (STB_LOCAL)
ffffffff8162e0a0-ffffffff8162e141: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1198
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff8165c7f4-ffffffff8165c80a: xen_send_IPI_one.cold (STB_LOCAL)
ffffffff8165c1b0-ffffffff8165c251: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_one(unsigned int cpu, enum ipi_vector vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1198
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_mask_allbutself
  - arch/x86/xen/smp.c:xen_send_IPI_self
  - arch/x86/xen/smp.c:__xen_send_IPI_mask
  - arch/x86/xen/smp.c:xen_smp_send_reschedule
  - arch/x86/xen/spinlock.c:xen_qlock_kick
```
**Symbols:**

```
ffffffff81676de4-ffffffff81676dfa: xen_send_IPI_one.cold (STB_LOCAL)
ffffffff816767a0-ffffffff81676841: xen_send_IPI_one (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
