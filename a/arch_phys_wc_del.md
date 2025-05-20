# Function: <code>arch_phys_wc_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104ab50)
Location: arch/x86/kernel/cpu/mtrr/main.c:581
Inline: False
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
  - drivers/video/fbdev/vesafb.c:vesafb_probe
```
**Symbols:**

```
ffffffff8104ab50-ffffffff8104ab8e: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104aca0)
Location: arch/x86/kernel/cpu/mtrr/main.c:581
Inline: False
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff8104aca0-ffffffff8104acde: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104d100)
Location: arch/x86/kernel/cpu/mtrr/main.c:581
Inline: False
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff8104d100-ffffffff8104d13e: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104d0c0)
Location: arch/x86/kernel/cpu/mtrr/main.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff8104d0c0-ffffffff8104d0ec: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff810509c0)
Location: arch/x86/kernel/cpu/mtrr/main.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff810509c0-ffffffff810509ec: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810535b0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff810535b0-ffffffff810535db: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81050c30)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff81050c30-ffffffff81050c5b: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053d1c)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff81054123-ffffffff81054136: arch_phys_wc_del.cold (STB_LOCAL)
ffffffff81053d00-ffffffff81053d2f: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810545f0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff810545f0-ffffffff8105461b: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81059620)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff81059620-ffffffff81059654: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810583f0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff810583f0-ffffffff81058424: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058d40)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:591
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff81058d40-ffffffff81058d74: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81061eb9)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:591
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff81c9be82-ffffffff81c9be96: arch_phys_wc_del.cold (STB_LOCAL)
ffffffff81061eb0-ffffffff81061efa: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8106e8b9)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:591
Inline: True
Direct callers:
  - lib/devres.c:devm_arch_phys_ac_add_release
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff81e4b2b7-ffffffff81e4b2cc: arch_phys_wc_del.cold (STB_LOCAL)
ffffffff8106e8b0-ffffffff8106e913: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8107ec40)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:548
Inline: True
Direct callers:
  - lib/devres.c:devm_arch_phys_ac_add_release
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff8107ec40-ffffffff8107ec8d: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81080dc0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:516
Inline: True
Direct callers:
  - lib/devres.c:devm_arch_phys_ac_add_release
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff81080dc0-ffffffff81080e0d: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810888d0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:516
Inline: True
Direct callers:
  - lib/devres.c:devm_arch_phys_ac_add_release
```
**Symbols:**

```
ffffffff810888d0-ffffffff8108891d: arch_phys_wc_del (STB_GLOBAL)
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
Location: include/linux/io.h:132
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81054170)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff81054170-ffffffff8105419b: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81044240)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:593
Inline: True
```
**Symbols:**

```
ffffffff81044240-ffffffff8104426b: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810545a0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff810545a0-ffffffff810545cb: arch_phys_wc_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void arch_phys_wc_del(int handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81055a20)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:593
Inline: True
Direct callers:
  - drivers/video/fbdev/vesafb.c:vesafb_probe
  - drivers/video/fbdev/vesafb.c:vesafb_destroy
```
**Symbols:**

```
ffffffff81055a20-ffffffff81055a4b: arch_phys_wc_del (STB_GLOBAL)
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
