# Function: <code>tlb_is_not_lazy</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81083880)
Location: arch/x86/mm/tlb.c:657
Inline: False
```
**Symbols:**

```
ffffffff81083880-ffffffff810838a4: tlb_is_not_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087520)
Location: arch/x86/mm/tlb.c:658
Inline: False
```
**Symbols:**

```
ffffffff81087520-ffffffff81087544: tlb_is_not_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088210)
Location: arch/x86/mm/tlb.c:658
Inline: False
```
**Symbols:**

```
ffffffff81088210-ffffffff81088234: tlb_is_not_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108a7e0)
Location: arch/x86/mm/tlb.c:834
Inline: False
```
**Symbols:**

```
ffffffff8108a7e0-ffffffff8108a804: tlb_is_not_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108aa80)
Location: arch/x86/mm/tlb.c:793
Inline: False
```
**Symbols:**

```
ffffffff8108aa80-ffffffff8108aaa4: tlb_is_not_lazy (STB_LOCAL)
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
In arch/x86/mm/tlb.c (ffffffff8108c1cd)
Location: arch/x86/mm/tlb.c:798
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
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
In arch/x86/mm/tlb.c (ffffffff8109b9bd)
Location: arch/x86/mm/tlb.c:857
Inline: True
Inline callers:
  - arch/x86/mm/tlb.c:native_flush_tlb_multi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:858
Inline: False
```
**Symbols:**

```
ffffffff810adff0-ffffffff810ae050: tlb_is_not_lazy (STB_LOCAL)
ffffffff81e50798-ffffffff81e507b3: tlb_is_not_lazy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:881
Inline: False
```
**Symbols:**

```
ffffffff810c8270-ffffffff810c82d0: tlb_is_not_lazy (STB_LOCAL)
ffffffff82054c1d-ffffffff82054c38: tlb_is_not_lazy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:900
Inline: False
```
**Symbols:**

```
ffffffff810cb9b0-ffffffff810cba10: tlb_is_not_lazy (STB_LOCAL)
ffffffff820d31fb-ffffffff820d3216: tlb_is_not_lazy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:901
Inline: False
```
**Symbols:**

```
ffffffff810d4040-ffffffff810d40a0: tlb_is_not_lazy (STB_LOCAL)
ffffffff821ae069-ffffffff821ae084: tlb_is_not_lazy.cold (STB_LOCAL)
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
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087210)
Location: arch/x86/mm/tlb.c:658
Inline: False
```
**Symbols:**

```
ffffffff81087210-ffffffff81087234: tlb_is_not_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81075de0)
Location: arch/x86/mm/tlb.c:658
Inline: False
```
**Symbols:**

```
ffffffff81075de0-ffffffff81075e04: tlb_is_not_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810871c0)
Location: arch/x86/mm/tlb.c:658
Inline: False
```
**Symbols:**

```
ffffffff810871c0-ffffffff810871e4: tlb_is_not_lazy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tlb_is_not_lazy(int cpu, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810892f0)
Location: arch/x86/mm/tlb.c:658
Inline: False
```
**Symbols:**

```
ffffffff810892f0-ffffffff81089314: tlb_is_not_lazy (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
