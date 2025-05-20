# Function: <code>__send_ipi_one</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bf10)
Location: arch/x86/hyperv/hv_apic.c:183
Inline: False
```
**Symbols:**

```
ffffffff8102bf10-ffffffff8102bf6b: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cf10)
Location: arch/x86/hyperv/hv_apic.c:190
Inline: False
```
**Symbols:**

```
ffffffff8102cf10-ffffffff8102cf6b: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ecc0)
Location: arch/x86/hyperv/hv_apic.c:195
Inline: False
```
**Symbols:**

```
ffffffff8102ecc0-ffffffff8102ed1c: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f5d0)
Location: arch/x86/hyperv/hv_apic.c:195
Inline: False
```
**Symbols:**

```
ffffffff8102f5d0-ffffffff8102f62c: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81031d90)
Location: arch/x86/hyperv/hv_apic.c:195
Inline: False
```
**Symbols:**

```
ffffffff81031d90-ffffffff81031e94: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81032a70)
Location: arch/x86/hyperv/hv_apic.c:195
Inline: False
```
**Symbols:**

```
ffffffff81032a70-ffffffff81032b55: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81033ed0)
Location: arch/x86/hyperv/hv_apic.c:197
Inline: False
```
**Symbols:**

```
ffffffff81033ed0-ffffffff81033fb5: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/hyperv/hv_apic.c:223
Inline: False
```
**Symbols:**

```
ffffffff81039160-ffffffff81039260: __send_ipi_one (STB_LOCAL)
ffffffff81c97f7b-ffffffff81c97f9b: __send_ipi_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/hyperv/hv_apic.c:223
Inline: False
```
**Symbols:**

```
ffffffff8103ff80-ffffffff810400d7: __send_ipi_one (STB_LOCAL)
ffffffff81e47401-ffffffff81e47421: __send_ipi_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/hyperv/hv_apic.c:223
Inline: False
```
**Symbols:**

```
ffffffff810491b0-ffffffff81049307: __send_ipi_one (STB_LOCAL)
ffffffff82051f67-ffffffff82051f87: __send_ipi_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/hyperv/hv_apic.c:225
Inline: False
```
**Symbols:**

```
ffffffff81049410-ffffffff81049567: __send_ipi_one (STB_LOCAL)
ffffffff820d045d-ffffffff820d047d: __send_ipi_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/hyperv/hv_apic.c:228
Inline: False
```
**Symbols:**

```
ffffffff81050390-ffffffff810504da: __send_ipi_one (STB_LOCAL)
ffffffff821aaf4f-ffffffff821aaf68: __send_ipi_one.cold (STB_LOCAL)
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
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f730)
Location: arch/x86/hyperv/hv_apic.c:195
Inline: False
```
**Symbols:**

```
ffffffff8102f730-ffffffff8102f78c: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8101ef40)
Location: arch/x86/hyperv/hv_apic.c:195
Inline: False
```
**Symbols:**

```
ffffffff8101ef40-ffffffff8101ef9c: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f590)
Location: arch/x86/hyperv/hv_apic.c:195
Inline: False
```
**Symbols:**

```
ffffffff8102f590-ffffffff8102f5ec: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __send_ipi_one(int cpu, int vector);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810303e0)
Location: arch/x86/hyperv/hv_apic.c:195
Inline: False
```
**Symbols:**

```
ffffffff810303e0-ffffffff8103043c: __send_ipi_one (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
