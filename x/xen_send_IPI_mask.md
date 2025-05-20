# Function: <code>xen_send_IPI_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102bc00)
Location: arch/x86/xen/smp.c:653
Inline: False
```
**Symbols:**

```
ffffffff8102bc00-ffffffff8102bc74: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102af10)
Location: arch/x86/xen/smp.c:663
Inline: False
```
**Symbols:**

```
ffffffff8102af10-ffffffff8102af84: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102b5e0)
Location: arch/x86/xen/smp.c:657
Inline: False
```
**Symbols:**

```
ffffffff8102b5e0-ffffffff8102b654: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028ef0)
Location: arch/x86/xen/smp.c:215
Inline: False
```
**Symbols:**

```
ffffffff81028ef0-ffffffff81028f57: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029100)
Location: arch/x86/xen/smp.c:218
Inline: False
```
**Symbols:**

```
ffffffff81029100-ffffffff81029167: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029b60)
Location: arch/x86/xen/smp.c:218
Inline: False
```
**Symbols:**

```
ffffffff81029b60-ffffffff81029bc7: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102a140)
Location: arch/x86/xen/smp.c:218
Inline: False
```
**Symbols:**

```
ffffffff8102a140-ffffffff8102a1a7: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:218
Inline: False
```
**Symbols:**

```
ffffffff8102c169-ffffffff8102c17a: xen_send_IPI_mask.cold (STB_LOCAL)
ffffffff8102bf00-ffffffff8102bf66: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:218
Inline: False
```
**Symbols:**

```
ffffffff8102ca49-ffffffff8102ca5a: xen_send_IPI_mask.cold (STB_LOCAL)
ffffffff8102c7e0-ffffffff8102c846: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:218
Inline: False
```
**Symbols:**

```
ffffffff8102eac9-ffffffff8102eada: xen_send_IPI_mask.cold (STB_LOCAL)
ffffffff8102e7f0-ffffffff8102e893: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:221
Inline: False
```
**Symbols:**

```
ffffffff81bd2ccf-ffffffff81bd2ce0: xen_send_IPI_mask.cold (STB_LOCAL)
ffffffff8102f650-ffffffff8102f6f3: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:221
Inline: False
```
**Symbols:**

```
ffffffff81bc501e-ffffffff81bc502f: xen_send_IPI_mask.cold (STB_LOCAL)
ffffffff81030170-ffffffff81030213: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:221
Inline: False
```
**Symbols:**

```
ffffffff81c97b6d-ffffffff81c97b7e: xen_send_IPI_mask.cold (STB_LOCAL)
ffffffff81034fb0-ffffffff81035053: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:197
Inline: False
```
**Symbols:**

```
ffffffff81e46f33-ffffffff81e46f44: xen_send_IPI_mask.cold (STB_LOCAL)
ffffffff8103ad10-ffffffff8103adbf: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff810433d0)
Location: arch/x86/xen/smp.c:197
Inline: False
```
**Symbols:**

```
ffffffff810433d0-ffffffff8104344f: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff810435d0)
Location: arch/x86/xen/smp.c:197
Inline: False
```
**Symbols:**

```
ffffffff810435d0-ffffffff8104365e: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81049ad0)
Location: arch/x86/xen/smp.c:209
Inline: False
```
**Symbols:**

```
ffffffff81049ad0-ffffffff81049b5e: xen_send_IPI_mask (STB_GLOBAL)
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
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:218
Inline: False
```
**Symbols:**

```
ffffffff8102cba9-ffffffff8102cbba: xen_send_IPI_mask.cold (STB_LOCAL)
ffffffff8102c940-ffffffff8102c9a6: xen_send_IPI_mask (STB_GLOBAL)
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
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:218
Inline: False
```
**Symbols:**

```
ffffffff8102ca09-ffffffff8102ca1a: xen_send_IPI_mask.cold (STB_LOCAL)
ffffffff8102c7a0-ffffffff8102c806: xen_send_IPI_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:218
Inline: False
```
**Symbols:**

```
ffffffff8102d7f9-ffffffff8102d80a: xen_send_IPI_mask.cold (STB_LOCAL)
ffffffff8102d590-ffffffff8102d5f6: xen_send_IPI_mask (STB_GLOBAL)
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
