# Function: <code>xen_send_IPI_mask_allbutself</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102bd80)
Location: arch/x86/xen/smp.c:678
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8102bd80-ffffffff8102be6a: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102b090)
Location: arch/x86/xen/smp.c:688
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8102b090-ffffffff8102b17e: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102b760)
Location: arch/x86/xen/smp.c:682
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8102b760-ffffffff8102b850: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029040)
Location: arch/x86/xen/smp.c:240
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81029040-ffffffff81029129: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029250)
Location: arch/x86/xen/smp.c:243
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81029250-ffffffff81029339: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029cb0)
Location: arch/x86/xen/smp.c:243
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81029cb0-ffffffff81029d9b: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102a290)
Location: arch/x86/xen/smp.c:243
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8102a290-ffffffff8102a37b: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:243
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8102c1a0-ffffffff8102c1b6: xen_send_IPI_mask_allbutself.cold (STB_LOCAL)
ffffffff8102c050-ffffffff8102c145: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:243
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8102ca80-ffffffff8102ca97: xen_send_IPI_mask_allbutself.cold (STB_LOCAL)
ffffffff8102c930-ffffffff8102ca2a: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:243
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8102eb00-ffffffff8102eb17: xen_send_IPI_mask_allbutself.cold (STB_LOCAL)
ffffffff8102e9b0-ffffffff8102eaaa: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:246
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81bd2d06-ffffffff81bd2d1d: xen_send_IPI_mask_allbutself.cold (STB_LOCAL)
ffffffff8102f810-ffffffff8102f90a: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:246
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81bc5055-ffffffff81bc506c: xen_send_IPI_mask_allbutself.cold (STB_LOCAL)
ffffffff81030330-ffffffff8103042a: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:246
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81c97ba4-ffffffff81c97bbb: xen_send_IPI_mask_allbutself.cold (STB_LOCAL)
ffffffff81035170-ffffffff8103526a: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:222
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81e46f6a-ffffffff81e46f81: xen_send_IPI_mask_allbutself.cold (STB_LOCAL)
ffffffff8103aef0-ffffffff8103aff2: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff810435a0)
Location: arch/x86/xen/smp.c:222
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff810435a0-ffffffff810436e3: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff810437d0)
Location: arch/x86/xen/smp.c:222
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff810437d0-ffffffff81043905: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81049cd0)
Location: arch/x86/xen/smp.c:234
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff81049cd0-ffffffff81049e05: xen_send_IPI_mask_allbutself (STB_GLOBAL)
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
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:243
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8102cbe0-ffffffff8102cbf7: xen_send_IPI_mask_allbutself.cold (STB_LOCAL)
ffffffff8102ca90-ffffffff8102cb8a: xen_send_IPI_mask_allbutself (STB_GLOBAL)
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
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:243
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8102ca40-ffffffff8102ca57: xen_send_IPI_mask_allbutself.cold (STB_LOCAL)
ffffffff8102c8f0-ffffffff8102c9ea: xen_send_IPI_mask_allbutself (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_mask_allbutself(const struct cpumask *mask, int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:243
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_send_IPI_allbutself
```
**Symbols:**

```
ffffffff8102d830-ffffffff8102d847: xen_send_IPI_mask_allbutself.cold (STB_LOCAL)
ffffffff8102d6e0-ffffffff8102d7da: xen_send_IPI_mask_allbutself (STB_GLOBAL)
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
