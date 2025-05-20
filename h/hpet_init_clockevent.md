# Function: <code>hpet_init_clockevent</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff828b7fce)
Location: arch/x86/kernel/hpet.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff828be4cc)
Location: arch/x86/kernel/hpet.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void hpet_init_clockevent(struct hpet_channel *hc, unsigned int rating);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d1ba)
Location: arch/x86/kernel/hpet.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_legacy_clockevent_register
```
**Symbols:**

```
ffffffff8107cb70-ffffffff8107cbfd: hpet_init_clockevent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void hpet_init_clockevent(struct hpet_channel *hc, unsigned int rating);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d12a)
Location: arch/x86/kernel/hpet.c:397
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_legacy_clockevent_register
```
**Symbols:**

```
ffffffff8107c980-ffffffff8107ca0d: hpet_init_clockevent (STB_LOCAL)
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
In arch/x86/kernel/hpet.c (ffffffff831da7f3)
Location: arch/x86/kernel/hpet.c:397
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff832bd9b4)
Location: arch/x86/kernel/hpet.c:398
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff8346f3a4)
Location: arch/x86/kernel/hpet.c:398
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff83e95997)
Location: arch/x86/kernel/hpet.c:398
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff836b9518)
Location: arch/x86/kernel/hpet.c:398
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff838e9e49)
Location: arch/x86/kernel/hpet.c:398
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff828a94a2)
Location: arch/x86/kernel/hpet.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff828a154e)
Location: arch/x86/kernel/hpet.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff828bc3a1)
Location: arch/x86/kernel/hpet.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
In arch/x86/kernel/hpet.c (ffffffff828bf4f9)
Location: arch/x86/kernel/hpet.c:396
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_enable
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
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
