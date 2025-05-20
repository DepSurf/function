# Function: <code>xen_send_IPI_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102bc80)
Location: arch/x86/xen/smp.c:662
Inline: False
```
**Symbols:**

```
ffffffff8102bc80-ffffffff8102bd10: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102af90)
Location: arch/x86/xen/smp.c:672
Inline: False
```
**Symbols:**

```
ffffffff8102af90-ffffffff8102b020: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102b660)
Location: arch/x86/xen/smp.c:666
Inline: False
```
**Symbols:**

```
ffffffff8102b660-ffffffff8102b6f0: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028f60)
Location: arch/x86/xen/smp.c:224
Inline: False
```
**Symbols:**

```
ffffffff81028f60-ffffffff81028fce: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029170)
Location: arch/x86/xen/smp.c:227
Inline: False
```
**Symbols:**

```
ffffffff81029170-ffffffff810291de: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029bd0)
Location: arch/x86/xen/smp.c:227
Inline: False
```
**Symbols:**

```
ffffffff81029bd0-ffffffff81029c3e: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102a1b0)
Location: arch/x86/xen/smp.c:227
Inline: False
```
**Symbols:**

```
ffffffff8102a1b0-ffffffff8102a21e: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:227
Inline: False
```
**Symbols:**

```
ffffffff8102c17a-ffffffff8102c18d: xen_send_IPI_all.cold (STB_LOCAL)
ffffffff8102bf70-ffffffff8102bfdd: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:227
Inline: False
```
**Symbols:**

```
ffffffff8102ca5a-ffffffff8102ca6d: xen_send_IPI_all.cold (STB_LOCAL)
ffffffff8102c850-ffffffff8102c8bd: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:227
Inline: False
```
**Symbols:**

```
ffffffff8102eada-ffffffff8102eaed: xen_send_IPI_all.cold (STB_LOCAL)
ffffffff8102e8a0-ffffffff8102e936: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:230
Inline: False
```
**Symbols:**

```
ffffffff81bd2ce0-ffffffff81bd2cf3: xen_send_IPI_all.cold (STB_LOCAL)
ffffffff8102f700-ffffffff8102f796: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:230
Inline: False
```
**Symbols:**

```
ffffffff81bc502f-ffffffff81bc5042: xen_send_IPI_all.cold (STB_LOCAL)
ffffffff81030220-ffffffff810302b6: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:230
Inline: False
```
**Symbols:**

```
ffffffff81c97b7e-ffffffff81c97b91: xen_send_IPI_all.cold (STB_LOCAL)
ffffffff81035060-ffffffff810350f6: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:206
Inline: False
```
**Symbols:**

```
ffffffff81e46f44-ffffffff81e46f57: xen_send_IPI_all.cold (STB_LOCAL)
ffffffff8103adc0-ffffffff8103ae68: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81043460)
Location: arch/x86/xen/smp.c:206
Inline: False
```
**Symbols:**

```
ffffffff81043460-ffffffff810434e8: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81043670)
Location: arch/x86/xen/smp.c:206
Inline: False
```
**Symbols:**

```
ffffffff81043670-ffffffff81043712: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81049b70)
Location: arch/x86/xen/smp.c:218
Inline: False
```
**Symbols:**

```
ffffffff81049b70-ffffffff81049c12: xen_send_IPI_all (STB_GLOBAL)
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
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:227
Inline: False
```
**Symbols:**

```
ffffffff8102cbba-ffffffff8102cbcd: xen_send_IPI_all.cold (STB_LOCAL)
ffffffff8102c9b0-ffffffff8102ca1d: xen_send_IPI_all (STB_GLOBAL)
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
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:227
Inline: False
```
**Symbols:**

```
ffffffff8102ca1a-ffffffff8102ca2d: xen_send_IPI_all.cold (STB_LOCAL)
ffffffff8102c810-ffffffff8102c87d: xen_send_IPI_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_all(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:227
Inline: False
```
**Symbols:**

```
ffffffff8102d80a-ffffffff8102d81d: xen_send_IPI_all.cold (STB_LOCAL)
ffffffff8102d600-ffffffff8102d66d: xen_send_IPI_all (STB_GLOBAL)
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
