# Function: <code>perf_msr_probe</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/probe.c (ffffffff81008600)
Location: arch/x86/events/probe.c:14
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff81008600-ffffffff810086d4: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/probe.c (ffffffff81008900)
Location: arch/x86/events/probe.c:14
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff81008900-ffffffff810089d4: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/probe.c (ffffffff81009a70)
Location: arch/x86/events/probe.c:19
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff81009a70-ffffffff81009b58: perf_msr_probe.part.0 (STB_LOCAL)
ffffffff81009b60-ffffffff81009b7b: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/probe.c (ffffffff810088f0)
Location: arch/x86/events/probe.c:19
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff810088f0-ffffffff810089d8: perf_msr_probe.part.0 (STB_LOCAL)
ffffffff810089e0-ffffffff810089fb: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/probe.c (ffffffff81009280)
Location: arch/x86/events/probe.c:19
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff81009280-ffffffff81009384: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/probe.c (0)
Location: arch/x86/events/probe.c:19
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff81c95453-ffffffff81c95480: perf_msr_probe.cold (STB_LOCAL)
ffffffff8100a190-ffffffff8100a2b8: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/probe.c (0)
Location: arch/x86/events/probe.c:19
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff81e446ff-ffffffff81e4472d: perf_msr_probe.cold (STB_LOCAL)
ffffffff810098c0-ffffffff810099fb: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/probe.c (0)
Location: arch/x86/events/probe.c:19
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff82050406-ffffffff82050434: perf_msr_probe.cold (STB_LOCAL)
ffffffff8100ada0-ffffffff8100aedb: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/probe.c (0)
Location: arch/x86/events/probe.c:19
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff820ce85b-ffffffff820ce889: perf_msr_probe.cold (STB_LOCAL)
ffffffff8100a590-ffffffff8100a6cb: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/probe.c (ffffffff8100fe00)
Location: arch/x86/events/probe.c:19
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff8100fcb0-ffffffff8100fde9: perf_msr_probe.part.0 (STB_LOCAL)
ffffffff821a9097-ffffffff821a90c5: perf_msr_probe.part.0.cold (STB_LOCAL)
ffffffff8100fe00-ffffffff8100fe33: perf_msr_probe (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/probe.c (ffffffff81008900)
Location: arch/x86/events/probe.c:14
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff81008900-ffffffff810089d4: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/probe.c (ffffffff81007110)
Location: arch/x86/events/probe.c:14
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff81007110-ffffffff810071ec: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/probe.c (ffffffff810088c0)
Location: arch/x86/events/probe.c:14
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff810088c0-ffffffff81008994: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int perf_msr_probe(struct perf_msr *msr, int cnt, bool zero, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/probe.c (ffffffff81008a20)
Location: arch/x86/events/probe.c:14
Inline: True
Direct callers:
  - arch/x86/events/msr.c:msr_init
```
**Symbols:**

```
ffffffff81008a20-ffffffff81008af4: perf_msr_probe (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
