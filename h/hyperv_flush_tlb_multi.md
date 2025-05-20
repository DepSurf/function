# Function: <code>hyperv_flush_tlb_multi</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hyperv_flush_tlb_multi(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81032870)
Location: arch/x86/hyperv/mmu.c:55
Inline: False
```
**Symbols:**

```
ffffffff81032870-ffffffff81032c8b: hyperv_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hyperv_flush_tlb_multi(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81037a00)
Location: arch/x86/hyperv/mmu.c:55
Inline: False
```
**Symbols:**

```
ffffffff81037a00-ffffffff81037e33: hyperv_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hyperv_flush_tlb_multi(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8103dc20)
Location: arch/x86/hyperv/mmu.c:55
Inline: False
```
**Symbols:**

```
ffffffff8103dc20-ffffffff8103e081: hyperv_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hyperv_flush_tlb_multi(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81046a60)
Location: arch/x86/hyperv/mmu.c:55
Inline: False
```
**Symbols:**

```
ffffffff81046a60-ffffffff81046ed4: hyperv_flush_tlb_multi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hyperv_flush_tlb_multi(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:60
Inline: False
```
**Symbols:**

```
ffffffff81046cb0-ffffffff810471a0: hyperv_flush_tlb_multi (STB_LOCAL)
ffffffff820d03c3-ffffffff820d03ee: hyperv_flush_tlb_multi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hyperv_flush_tlb_multi(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:60
Inline: False
```
**Symbols:**

```
ffffffff8104d430-ffffffff8104d83c: hyperv_flush_tlb_multi (STB_LOCAL)
ffffffff821aad83-ffffffff821aadae: hyperv_flush_tlb_multi.cold (STB_LOCAL)
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
