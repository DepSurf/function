# Function: <code>tdx_get_ve_info</code>

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
void tdx_get_ve_info(struct ve_info *ve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (0)
Location: arch/x86/coco/tdx/tdx.c:542
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve
  - arch/x86/kernel/traps.c:exc_virtualization_exception
```
**Symbols:**

```
ffffffff81e43dfa-ffffffff81e43e0b: tdx_get_ve_info.cold (STB_LOCAL)
ffffffff81003890-ffffffff8100392e: tdx_get_ve_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tdx_get_ve_info(struct ve_info *ve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff810040e0)
Location: arch/x86/coco/tdx/tdx.c:584
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve
  - arch/x86/kernel/traps.c:exc_virtualization_exception
```
**Symbols:**

```
ffffffff810040e0-ffffffff8100418b: tdx_get_ve_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tdx_get_ve_info(struct ve_info *ve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81003870)
Location: arch/x86/coco/tdx/tdx.c:578
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve
  - arch/x86/kernel/traps.c:exc_virtualization_exception
```
**Symbols:**

```
ffffffff81003870-ffffffff81003914: tdx_get_ve_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tdx_get_ve_info(struct ve_info *ve);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81003c20)
Location: arch/x86/coco/tdx/tdx.c:603
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_early_handle_ve
  - arch/x86/kernel/traps.c:exc_virtualization_exception
```
**Symbols:**

```
ffffffff81003c20-ffffffff81003cb6: tdx_get_ve_info (STB_GLOBAL)
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
