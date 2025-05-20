# Function: <code>__alloc_bootmem_nopanic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81f8aec9)
Location: mm/nobootmem.c:272
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
**Symbols:**

```
ffffffff81f8aec9-ffffffff81f8aed8: __alloc_bootmem_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81fb4b0c)
Location: mm/nobootmem.c:273
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
**Symbols:**

```
ffffffff81fb4b0c-ffffffff81fb4b1b: __alloc_bootmem_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81ff14f2)
Location: mm/nobootmem.c:276
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
**Symbols:**

```
ffffffff81ff14f2-ffffffff81ff1501: __alloc_bootmem_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff820d3972)
Location: mm/nobootmem.c:260
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
**Symbols:**

```
ffffffff820d3972-ffffffff820d3986: __alloc_bootmem_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff826dc392)
Location: mm/nobootmem.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
**Symbols:**

```
ffffffff826dc392-ffffffff826dc3a6: __alloc_bootmem_nopanic (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__alloc_bootmem_nopanic(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff82706850)
Location: mm/nobootmem.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
**Symbols:**

```
ffffffff82706850-ffffffff82706864: __alloc_bootmem_nopanic (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
</ul>
