# Function: <code>xen_pin_vcpu</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ba50)
Location: arch/x86/xen/enlighten.c:1958
Inline: False
```
**Symbols:**

```
ffffffff8101ba50-ffffffff8101baff: xen_pin_vcpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81019d90)
Location: arch/x86/xen/enlighten.c:282
Inline: False
```
**Symbols:**

```
ffffffff81019d90-ffffffff81019e46: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101a620)
Location: arch/x86/xen/enlighten.c:286
Inline: False
```
**Symbols:**

```
ffffffff8101a620-ffffffff8101a6dc: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:294
Inline: False
```
**Symbols:**

```
ffffffff8101b0ae-ffffffff8101b0db: xen_pin_vcpu.cold.4 (STB_LOCAL)
ffffffff8101afe0-ffffffff8101b075: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:296
Inline: False
```
**Symbols:**

```
ffffffff8101b892-ffffffff8101b8bf: xen_pin_vcpu.cold.4 (STB_LOCAL)
ffffffff8101b7b0-ffffffff8101b859: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:296
Inline: False
```
**Symbols:**

```
ffffffff8101d3c8-ffffffff8101d3f7: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff8101d2e0-ffffffff8101d38e: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:318
Inline: False
```
**Symbols:**

```
ffffffff8101dd68-ffffffff8101dd97: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff8101dc80-ffffffff8101dd2e: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:318
Inline: False
```
**Symbols:**

```
ffffffff81020158-ffffffff81020187: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff81020070-ffffffff8102011e: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:318
Inline: False
```
**Symbols:**

```
ffffffff81bd26c5-ffffffff81bd26f4: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff81020b10-ffffffff81020bbe: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:318
Inline: False
```
**Symbols:**

```
ffffffff81bc4938-ffffffff81bc4967: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff81022eb0-ffffffff81022f5e: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:361
Inline: False
```
**Symbols:**

```
ffffffff81c96f3c-ffffffff81c96f7f: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff81027000-ffffffff810270c5: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:297
Inline: False
```
**Symbols:**

```
ffffffff81e4633a-ffffffff81e4637c: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff8102b1c0-ffffffff8102b29e: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:297
Inline: False
```
**Symbols:**

```
ffffffff820517de-ffffffff820517f3: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff81031eb0-ffffffff81031fa3: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:297
Inline: False
```
**Symbols:**

```
ffffffff820cfcca-ffffffff820cfcdf: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff81031eb0-ffffffff81031fa3: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:301
Inline: False
```
**Symbols:**

```
ffffffff821aa638-ffffffff821aa64d: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff810381a0-ffffffff81038293: xen_pin_vcpu (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:318
Inline: False
```
**Symbols:**

```
ffffffff8101dd68-ffffffff8101dd97: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff8101dc80-ffffffff8101dd2e: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:318
Inline: False
```
**Symbols:**

```
ffffffff8101dd28-ffffffff8101dd57: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff8101dc40-ffffffff8101dcee: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_pin_vcpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten.c (0)
Location: arch/x86/xen/enlighten.c:318
Inline: False
```
**Symbols:**

```
ffffffff8101df78-ffffffff8101dfa7: xen_pin_vcpu.cold (STB_LOCAL)
ffffffff8101de90-ffffffff8101df3e: xen_pin_vcpu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
