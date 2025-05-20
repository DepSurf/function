# Function: <code>xen_send_IPI_self</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102bd10)
Location: arch/x86/xen/smp.c:670
Inline: False
```
**Symbols:**

```
ffffffff8102bd10-ffffffff8102bd7c: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102b020)
Location: arch/x86/xen/smp.c:680
Inline: False
```
**Symbols:**

```
ffffffff8102b020-ffffffff8102b08c: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102b6f0)
Location: arch/x86/xen/smp.c:674
Inline: False
```
**Symbols:**

```
ffffffff8102b6f0-ffffffff8102b75c: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028fd0)
Location: arch/x86/xen/smp.c:232
Inline: False
```
**Symbols:**

```
ffffffff81028fd0-ffffffff8102903e: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff810291e0)
Location: arch/x86/xen/smp.c:235
Inline: False
```
**Symbols:**

```
ffffffff810291e0-ffffffff8102924e: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029c40)
Location: arch/x86/xen/smp.c:235
Inline: False
```
**Symbols:**

```
ffffffff81029c40-ffffffff81029cae: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102a220)
Location: arch/x86/xen/smp.c:235
Inline: False
```
**Symbols:**

```
ffffffff8102a220-ffffffff8102a28e: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:235
Inline: False
```
**Symbols:**

```
ffffffff8102c18d-ffffffff8102c1a0: xen_send_IPI_self.cold (STB_LOCAL)
ffffffff8102bfe0-ffffffff8102c04d: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:235
Inline: False
```
**Symbols:**

```
ffffffff8102ca6d-ffffffff8102ca80: xen_send_IPI_self.cold (STB_LOCAL)
ffffffff8102c8c0-ffffffff8102c92d: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:235
Inline: False
```
**Symbols:**

```
ffffffff8102eaed-ffffffff8102eb00: xen_send_IPI_self.cold (STB_LOCAL)
ffffffff8102e940-ffffffff8102e9ad: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:238
Inline: False
```
**Symbols:**

```
ffffffff81bd2cf3-ffffffff81bd2d06: xen_send_IPI_self.cold (STB_LOCAL)
ffffffff8102f7a0-ffffffff8102f80d: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:238
Inline: False
```
**Symbols:**

```
ffffffff81bc5042-ffffffff81bc5055: xen_send_IPI_self.cold (STB_LOCAL)
ffffffff810302c0-ffffffff8103032d: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:238
Inline: False
```
**Symbols:**

```
ffffffff81c97b91-ffffffff81c97ba4: xen_send_IPI_self.cold (STB_LOCAL)
ffffffff81035100-ffffffff8103516d: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:214
Inline: False
```
**Symbols:**

```
ffffffff81e46f57-ffffffff81e46f6a: xen_send_IPI_self.cold (STB_LOCAL)
ffffffff8103ae70-ffffffff8103aee7: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81043500)
Location: arch/x86/xen/smp.c:214
Inline: False
```
**Symbols:**

```
ffffffff81043500-ffffffff81043588: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81043730)
Location: arch/x86/xen/smp.c:214
Inline: False
```
**Symbols:**

```
ffffffff81043730-ffffffff810437b8: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81049c30)
Location: arch/x86/xen/smp.c:226
Inline: False
```
**Symbols:**

```
ffffffff81049c30-ffffffff81049cb8: xen_send_IPI_self (STB_GLOBAL)
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
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:235
Inline: False
```
**Symbols:**

```
ffffffff8102cbcd-ffffffff8102cbe0: xen_send_IPI_self.cold (STB_LOCAL)
ffffffff8102ca20-ffffffff8102ca8d: xen_send_IPI_self (STB_GLOBAL)
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
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:235
Inline: False
```
**Symbols:**

```
ffffffff8102ca2d-ffffffff8102ca40: xen_send_IPI_self.cold (STB_LOCAL)
ffffffff8102c880-ffffffff8102c8ed: xen_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:235
Inline: False
```
**Symbols:**

```
ffffffff8102d81d-ffffffff8102d830: xen_send_IPI_self.cold (STB_LOCAL)
ffffffff8102d670-ffffffff8102d6dd: xen_send_IPI_self (STB_GLOBAL)
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
