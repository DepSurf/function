# Function: <code>xen_hvm_post_suspend</code>

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
In arch/x86/xen/suspend.c (ffffffff81024199)
Location: arch/x86/xen/suspend.c:33
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
In arch/x86/xen/suspend.c (ffffffff81023459)
Location: arch/x86/xen/suspend.c:33
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
In arch/x86/xen/suspend.c (ffffffff81023ba9)
Location: arch/x86/xen/suspend.c:33
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
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff8101bbc0)
Location: arch/x86/xen/suspend_hvm.c:9
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101bbc0-ffffffff8101bbe3: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff8101c8b0)
Location: arch/x86/xen/suspend_hvm.c:10
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101c8b0-ffffffff8101c8d3: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff8101d2d0)
Location: arch/x86/xen/suspend_hvm.c:10
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101d2d0-ffffffff8101d2ff: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff8101c9b0)
Location: arch/x86/xen/suspend_hvm.c:10
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101c9b0-ffffffff8101c9df: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff8101e4d0)
Location: arch/x86/xen/suspend_hvm.c:10
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101e4d0-ffffffff8101e4ff: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff8101ee50)
Location: arch/x86/xen/suspend_hvm.c:10
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101ee50-ffffffff8101ee7f: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff81021400)
Location: arch/x86/xen/suspend_hvm.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81021400-ffffffff8102142f: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff81021bc0)
Location: arch/x86/xen/suspend_hvm.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81021bc0-ffffffff81021bef: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff81023f50)
Location: arch/x86/xen/suspend_hvm.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff81023f50-ffffffff81023f7f: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff810282b0)
Location: arch/x86/xen/suspend_hvm.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff810282b0-ffffffff810282df: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff8102c890)
Location: arch/x86/xen/suspend_hvm.c:11
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8102c890-ffffffff8102c8cb: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (0)
Location: arch/x86/xen/suspend_hvm.c:12
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff820518ba-ffffffff820518cf: xen_hvm_post_suspend.cold (STB_LOCAL)
ffffffff81033970-ffffffff810339f2: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (0)
Location: arch/x86/xen/suspend_hvm.c:12
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff820cfda6-ffffffff820cfdbb: xen_hvm_post_suspend.cold (STB_LOCAL)
ffffffff81033900-ffffffff81033982: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (0)
Location: arch/x86/xen/suspend_hvm.c:12
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff821aa714-ffffffff821aa729: xen_hvm_post_suspend.cold (STB_LOCAL)
ffffffff81039c00-ffffffff81039c82: xen_hvm_post_suspend (STB_GLOBAL)
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
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff8101efb0)
Location: arch/x86/xen/suspend_hvm.c:10
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101efb0-ffffffff8101efdf: xen_hvm_post_suspend (STB_GLOBAL)
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
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff8101ee10)
Location: arch/x86/xen/suspend_hvm.c:10
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101ee10-ffffffff8101ee3f: xen_hvm_post_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_hvm_post_suspend(int suspend_cancelled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/suspend_hvm.c (ffffffff8101f060)
Location: arch/x86/xen/suspend_hvm.c:10
Inline: False
Direct callers:
  - arch/x86/xen/suspend.c:xen_arch_post_suspend
```
**Symbols:**

```
ffffffff8101f060-ffffffff8101f08f: xen_hvm_post_suspend (STB_GLOBAL)
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
