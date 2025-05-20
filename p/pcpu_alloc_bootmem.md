# Function: <code>pcpu_alloc_bootmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff81f6fcaf)
Location: arch/x86/kernel/setup_percpu.c:98
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff81f983a4)
Location: arch/x86/kernel/setup_percpu.c:98
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff81fd386e)
Location: arch/x86/kernel/setup_percpu.c:99
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff820b4529)
Location: arch/x86/kernel/setup_percpu.c:99
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff826bac5c)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff826e4a27)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff8289b4fc)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff828b32d9)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff828b6730)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *pcpu_alloc_bootmem(unsigned int cpu, long unsigned int size, long unsigned int align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff82cdb7e8)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
**Symbols:**

```
ffffffff82cdb7e8-ffffffff82cdb92c: pcpu_alloc_bootmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *pcpu_alloc_bootmem(unsigned int cpu, long unsigned int size, long unsigned int align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff82fc7c3e)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
**Symbols:**

```
ffffffff82fc7c3e-ffffffff82fc7d82: pcpu_alloc_bootmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *pcpu_alloc_bootmem(unsigned int cpu, long unsigned int size, long unsigned int align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff831d259e)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
**Symbols:**

```
ffffffff831d259e-ffffffff831d26e3: pcpu_alloc_bootmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *pcpu_alloc_bootmem(unsigned int cpu, long unsigned int size, long unsigned int align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff832b4e10)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
**Symbols:**

```
ffffffff832b4e10-ffffffff832b4f4f: pcpu_alloc_bootmem (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff828a4737)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff8289c879)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff828b7647)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff828b7748)
Location: arch/x86/kernel/setup_percpu.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
</ul>
