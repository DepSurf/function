# Function: <code>handle_io</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int handle_io(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:496
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve
```
**Symbols:**

```
ffffffff81002cd0-ffffffff81002e36: handle_io (STB_LOCAL)
ffffffff81e43d8f-ffffffff81e43dc5: handle_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int handle_io(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:538
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve
```
**Symbols:**

```
ffffffff81003730-ffffffff81003896: handle_io (STB_LOCAL)
ffffffff820500e0-ffffffff82050116: handle_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int handle_io(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:532
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve
```
**Symbols:**

```
ffffffff810036f0-ffffffff8100385e: handle_io (STB_LOCAL)
ffffffff820ce59e-ffffffff820ce5d7: handle_io.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int handle_io(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:557
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve
```
**Symbols:**

```
ffffffff81003250-ffffffff81003312: handle_io (STB_LOCAL)
ffffffff821a8dbf-ffffffff821a8dde: handle_io.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
