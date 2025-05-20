# Function: <code>handle_mmio</code>

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
int handle_mmio(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:343
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
```
**Symbols:**

```
ffffffff810031b0-ffffffff81003693: handle_mmio (STB_LOCAL)
ffffffff81e43dc5-ffffffff81e43de5: handle_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int handle_mmio(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:385
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
```
**Symbols:**

```
ffffffff810039b0-ffffffff81003e9f: handle_mmio (STB_LOCAL)
ffffffff82050116-ffffffff8205012a: handle_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int handle_mmio(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:379
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
```
**Symbols:**

```
ffffffff81002fa0-ffffffff810033b6: handle_mmio (STB_LOCAL)
ffffffff820ce58a-ffffffff820ce59e: handle_mmio.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int handle_mmio(struct pt_regs *regs, struct ve_info *ve);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:404
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
```
**Symbols:**

```
ffffffff81003590-ffffffff810039a6: handle_mmio (STB_LOCAL)
ffffffff821a8dde-ffffffff821a8df2: handle_mmio.cold (STB_LOCAL)
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
