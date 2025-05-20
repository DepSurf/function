# Function: <code>load_percpu_segment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040400)
Location: arch/x86/kernel/cpu/common.c:371
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/kernel/cpu/common.c:switch_to_new_gdt
```
**Symbols:**

```
ffffffff81040400-ffffffff8104042e: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040250)
Location: arch/x86/kernel/cpu/common.c:435
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/kernel/cpu/common.c:switch_to_new_gdt
```
**Symbols:**

```
ffffffff81040250-ffffffff8104027e: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103fc90)
Location: arch/x86/kernel/cpu/common.c:438
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_setup_gdt
  - arch/x86/kernel/cpu/common.c:switch_to_new_gdt
```
**Symbols:**

```
ffffffff8103fc90-ffffffff8103fcbe: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103dc00)
Location: arch/x86/kernel/cpu/common.c:440
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:switch_to_new_gdt
```
**Symbols:**

```
ffffffff8103dc00-ffffffff8103dc2e: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040790)
Location: arch/x86/kernel/cpu/common.c:484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81040790-ffffffff810407be: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81041fe0)
Location: arch/x86/kernel/cpu/common.c:494
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81041fe0-ffffffff8104200e: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81043600)
Location: arch/x86/kernel/cpu/common.c:494
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81043600-ffffffff8104362e: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81045b60)
Location: arch/x86/kernel/cpu/common.c:571
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81045b60-ffffffff81045b8e: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810462c0)
Location: arch/x86/kernel/cpu/common.c:571
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff810462c0-ffffffff810462ee: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a270)
Location: arch/x86/kernel/cpu/common.c:576
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff8104a270-ffffffff8104a29e: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049710)
Location: arch/x86/kernel/cpu/common.c:594
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81049710-ffffffff8104973e: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104ae90)
Location: arch/x86/kernel/cpu/common.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff8104ae90-ffffffff8104aebe: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81051f30)
Location: arch/x86/kernel/cpu/common.c:596
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81051f30-ffffffff81051f89: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105d890)
Location: arch/x86/kernel/cpu/common.c:704
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff8105d890-ffffffff8105d902: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046440)
Location: arch/x86/kernel/cpu/common.c:571
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81046440-ffffffff8104646e: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81035730)
Location: arch/x86/kernel/cpu/common.c:571
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81035730-ffffffff8103576f: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046280)
Location: arch/x86/kernel/cpu/common.c:571
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81046280-ffffffff810462ae: load_percpu_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void load_percpu_segment(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047680)
Location: arch/x86/kernel/cpu/common.c:571
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_init
```
**Symbols:**

```
ffffffff81047680-ffffffff810476ae: load_percpu_segment (STB_GLOBAL)
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
