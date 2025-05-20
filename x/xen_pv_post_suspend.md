# Function: <code>xen_pv_post_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend.c (ffffffff810241fc)
Location: arch/x86/xen/suspend.c:49
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend.c (ffffffff810234bc)
Location: arch/x86/xen/suspend.c:49
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend.c (ffffffff81023c0e)
Location: arch/x86/xen/suspend.c:49
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff8101d050)
Location: arch/x86/xen/suspend_pv.c:26
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101d050-ffffffff8101d1ef: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff8101dd20)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101dd20-ffffffff8101debf: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101e908-ffffffff8101e914: xen_pv_post_suspend.cold.4 (STB_LOCAL)
ffffffff8101e760-ffffffff8101e908: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101e1b7-ffffffff8101e1c3: xen_pv_post_suspend.cold.4 (STB_LOCAL)
ffffffff8101dfd0-ffffffff8101e1b7: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101fd3b-ffffffff8101fd47: xen_pv_post_suspend.cold (STB_LOCAL)
ffffffff8101fb60-ffffffff8101fd3b: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8102069b-ffffffff810206a7: xen_pv_post_suspend.cold (STB_LOCAL)
ffffffff810204c0-ffffffff8102069b: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81022d01-ffffffff81022d0d: xen_pv_post_suspend.cold (STB_LOCAL)
ffffffff81022b20-ffffffff81022d01: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81bd2b47-ffffffff81bd2b53: xen_pv_post_suspend.cold (STB_LOCAL)
ffffffff810230f0-ffffffff810232d1: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81bc4ce3-ffffffff81bc4cef: xen_pv_post_suspend.cold (STB_LOCAL)
ffffffff81025400-ffffffff810255e0: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81c97493-ffffffff81c9749f: xen_pv_post_suspend.cold (STB_LOCAL)
ffffffff81029910-ffffffff81029af0: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81e468ef-ffffffff81e468fb: xen_pv_post_suspend.cold (STB_LOCAL)
ffffffff8102e1c0-ffffffff8102e3be: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff810355e0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff810355e0-ffffffff810357ea: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff81035560)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81035560-ffffffff8103576a: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff8103b760)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8103b760-ffffffff8103b96a: xen_pv_post_suspend (STB_GLOBAL)
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
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff810207fb-ffffffff81020807: xen_pv_post_suspend.cold (STB_LOCAL)
ffffffff81020620-ffffffff810207fb: xen_pv_post_suspend (STB_GLOBAL)
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
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8102065b-ffffffff81020667: xen_pv_post_suspend.cold (STB_LOCAL)
ffffffff81020480-ffffffff8102065b: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xen_pv_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_pv.c (0)
Location: arch/x86/xen/suspend_pv.c:27
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff810208ab-ffffffff810208b7: xen_pv_post_suspend.cold (STB_LOCAL)
ffffffff810206d0-ffffffff810208ab: xen_pv_post_suspend (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
