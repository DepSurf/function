# Function: <code>early_detect_mem_encrypt</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff81045b58)
Location: arch/x86/kernel/cpu/amd.c:575
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff810475b2)
Location: arch/x86/kernel/cpu/amd.c:574
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104a31e)
Location: arch/x86/kernel/cpu/amd.c:578
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104acae)
Location: arch/x86/kernel/cpu/amd.c:580
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void early_detect_mem_encrypt(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104f010)
Location: arch/x86/kernel/cpu/amd.c:605
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
**Symbols:**

```
ffffffff8104f010-ffffffff8104f0ca: early_detect_mem_encrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void early_detect_mem_encrypt(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104e380)
Location: arch/x86/kernel/cpu/amd.c:578
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
```
**Symbols:**

```
ffffffff8104e380-ffffffff8104e444: early_detect_mem_encrypt (STB_LOCAL)
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
In arch/x86/kernel/cpu/amd.c (ffffffff810503b2)
Location: arch/x86/kernel/cpu/amd.c:578
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff810586ad)
Location: arch/x86/kernel/cpu/amd.c:578
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81064ea6)
Location: arch/x86/kernel/cpu/amd.c:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81074166)
Location: arch/x86/kernel/cpu/amd.c:549
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81076016)
Location: arch/x86/kernel/cpu/amd.c:621
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8107d08e)
Location: arch/x86/kernel/cpu/amd.c:596
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104ae1e)
Location: arch/x86/kernel/cpu/amd.c:580
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8103a2b5)
Location: arch/x86/kernel/cpu/amd.c:580
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104ac5e)
Location: arch/x86/kernel/cpu/amd.c:580
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104c06e)
Location: arch/x86/kernel/cpu/amd.c:580
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:early_init_amd
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
