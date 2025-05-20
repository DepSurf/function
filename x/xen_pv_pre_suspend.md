# Function: <code>xen_pv_pre_suspend</code>

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
In arch/x86/xen/suspend.c (ffffffff81023eba)
Location: arch/x86/xen/suspend.c:17
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
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
In arch/x86/xen/suspend.c (ffffffff8102315a)
Location: arch/x86/xen/suspend.c:17
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
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
In arch/x86/xen/suspend.c (ffffffff810238aa)
Location: arch/x86/xen/suspend.c:17
Inline: True
Inline callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff8101cdb0)
Location: arch/x86/xen/suspend_pv.c:10
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff8101cdb0-ffffffff8101d04b: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff8101da60)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff8101da60-ffffffff8101dd12: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff8101e4c0)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff8101e4c0-ffffffff8101e755: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff8101dd50)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff8101dd50-ffffffff8101dfc8: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff8101f8f0)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff8101f8f0-ffffffff8101fb5e: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff81020250)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff81020250-ffffffff810204be: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff810228a0)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff810228a0-ffffffff81022b11: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff81022e70)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff81022e70-ffffffff810230e1: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff81025190)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff81025190-ffffffff810253fe: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff810296a0)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff810296a0-ffffffff8102990e: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff8102e140)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff8102e140-ffffffff8102e1bd: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff81035550)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff81035550-ffffffff810355cf: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff810354d0)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff810354d0-ffffffff8103554f: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff8103b6d0)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff8103b6d0-ffffffff8103b74f: xen_pv_pre_suspend (STB_GLOBAL)
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
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff810203b0)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff810203b0-ffffffff8102061e: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff81020210)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff81020210-ffffffff8102047e: xen_pv_pre_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_pv_pre_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_pv.c (ffffffff81020460)
Location: arch/x86/xen/suspend_pv.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_pre_suspend
```
**Symbols:**

```
ffffffff81020460-ffffffff810206ce: xen_pv_pre_suspend (STB_GLOBAL)
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
