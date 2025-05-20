# Function: <code>__sysvec_xen_hvm_callback</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sysvec_xen_hvm_callback(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81021060)
Location: arch/x86/xen/enlighten_hvm.c:122
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
**Symbols:**

```
ffffffff81021060-ffffffff81021094: __sysvec_xen_hvm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sysvec_xen_hvm_callback(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff810218d0)
Location: arch/x86/xen/enlighten_hvm.c:123
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
**Symbols:**

```
ffffffff810218d0-ffffffff81021904: __sysvec_xen_hvm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __sysvec_xen_hvm_callback(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81023c60)
Location: arch/x86/xen/enlighten_hvm.c:123
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
**Symbols:**

```
ffffffff81023c60-ffffffff81023c94: __sysvec_xen_hvm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __sysvec_xen_hvm_callback(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff81027f00)
Location: arch/x86/xen/enlighten_hvm.c:123
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
**Symbols:**

```
ffffffff81027f00-ffffffff81027f34: __sysvec_xen_hvm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __sysvec_xen_hvm_callback(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (ffffffff8102c450)
Location: arch/x86/xen/enlighten_hvm.c:125
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
**Symbols:**

```
ffffffff8102c450-ffffffff8102c48a: __sysvec_xen_hvm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __sysvec_xen_hvm_callback(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (0)
Location: arch/x86/xen/enlighten_hvm.c:130
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
**Symbols:**

```
ffffffff81033450-ffffffff810334ba: __sysvec_xen_hvm_callback (STB_LOCAL)
ffffffff8205183f-ffffffff82051853: __sysvec_xen_hvm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __sysvec_xen_hvm_callback(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (0)
Location: arch/x86/xen/enlighten_hvm.c:130
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
**Symbols:**

```
ffffffff810333f0-ffffffff8103345a: __sysvec_xen_hvm_callback (STB_LOCAL)
ffffffff820cfd2b-ffffffff820cfd3f: __sysvec_xen_hvm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __sysvec_xen_hvm_callback(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/enlighten_hvm.c (0)
Location: arch/x86/xen/enlighten_hvm.c:130
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:sysvec_xen_hvm_callback
```
**Symbols:**

```
ffffffff81039700-ffffffff8103975b: __sysvec_xen_hvm_callback (STB_LOCAL)
ffffffff821aa699-ffffffff821aa6ad: __sysvec_xen_hvm_callback.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
