# Function: <code>arch_phys_wc_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104a890)
Location: arch/x86/kernel/cpu/mtrr/main.c:555
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff8104a890-ffffffff8104a903: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104a9d0)
Location: arch/x86/kernel/cpu/mtrr/main.c:555
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff8104a9d0-ffffffff8104aa41: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104ce30)
Location: arch/x86/kernel/cpu/mtrr/main.c:555
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff8104ce30-ffffffff8104cea1: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104cdf0)
Location: arch/x86/kernel/cpu/mtrr/main.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff8104cdf0-ffffffff8104ce61: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff810506e0)
Location: arch/x86/kernel/cpu/mtrr/main.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff810506e0-ffffffff81050751: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81053908-ffffffff81053921: arch_phys_wc_add.cold.8 (STB_LOCAL)
ffffffff81053350-ffffffff810533af: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81050a01)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81050f88-ffffffff81050fa1: arch_phys_wc_add.cold.9 (STB_LOCAL)
ffffffff810509d0-ffffffff81050a2f: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053ab3)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81054097-ffffffff810540b0: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff81053a80-ffffffff81053ae4: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810543a3)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81054987-ffffffff810549a0: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff81054370-ffffffff810543d4: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81059433)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81059a26-ffffffff81059a3f: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff81059400-ffffffff81059464: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058203)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81bd5cdf-ffffffff81bd5cf8: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff810581d0-ffffffff81058234: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058b53)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:565
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81bc8093-ffffffff81bc80ac: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff81058b20-ffffffff81058b84: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81061c82)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:565
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81c9bdf2-ffffffff81c9be20: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff81061c40-ffffffff81061cb3: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8106e65e)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:565
Inline: True
Direct callers:
  - lib/devres.c:devm_arch_phys_wc_add
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81e4b23b-ffffffff81e4b269: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff8106e610-ffffffff8106e69b: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8107e970)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:522
Inline: True
Direct callers:
  - lib/devres.c:devm_arch_phys_wc_add
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff8107e970-ffffffff8107e9e5: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81080ae0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:490
Inline: True
Direct callers:
  - lib/devres.c:devm_arch_phys_wc_add
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81080ae0-ffffffff81080b55: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810885f0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:490
Inline: True
Direct callers:
  - lib/devres.c:devm_arch_phys_wc_add
```
**Symbols:**

```
ffffffff810885f0-ffffffff81088665: arch_phys_wc_add (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/gxt4500.c (0)
Location: include/linux/io.h:126
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053f23)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81054507-ffffffff81054520: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff81053ef0-ffffffff81053f54: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81043ff3)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:567
Inline: True
```
**Symbols:**

```
ffffffff81044586-ffffffff8104459f: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff81043fc0-ffffffff81044024: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81054353)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81054937-ffffffff81054950: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff81054320-ffffffff81054384: arch_phys_wc_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int arch_phys_wc_add(long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810557d3)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:567
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff81055db7-ffffffff81055dd0: arch_phys_wc_add.cold (STB_LOCAL)
ffffffff810557a0-ffffffff81055804: arch_phys_wc_add (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
