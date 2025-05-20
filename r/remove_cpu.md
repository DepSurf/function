# Function: <code>remove_cpu</code>

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
int remove_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a9060)
Location: kernel/cpu.c:1083
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
**Symbols:**

```
ffffffff810a9060-ffffffff810a9094: remove_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int remove_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4ab0)
Location: kernel/cpu.c:1087
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
**Symbols:**

```
ffffffff810a4ab0-ffffffff810a4ae4: remove_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int remove_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5780)
Location: kernel/cpu.c:1192
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
**Symbols:**

```
ffffffff810a5780-ffffffff810a57b4: remove_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int remove_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b6f50)
Location: kernel/cpu.c:1218
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_cpus_done
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
**Symbols:**

```
ffffffff810b6f50-ffffffff810b6f84: remove_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int remove_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cd6b0)
Location: kernel/cpu.c:1230
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
**Symbols:**

```
ffffffff810cd6b0-ffffffff810cd6e5: remove_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int remove_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eb7a0)
Location: kernel/cpu.c:1256
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
**Symbols:**

```
ffffffff810eb7a0-ffffffff810eb7d5: remove_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int remove_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f7480)
Location: kernel/cpu.c:1530
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
**Symbols:**

```
ffffffff810f7480-ffffffff810f74b5: remove_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int remove_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81100830)
Location: kernel/cpu.c:1568
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:enter_uniprocessor
```
**Symbols:**

```
ffffffff81100830-ffffffff81100865: remove_cpu (STB_GLOBAL)
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
