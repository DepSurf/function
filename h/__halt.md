# Function: <code>__halt</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81003a68)
Location: arch/x86/coco/tdx/tdx.c:181
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_safe_halt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff810042c5)
Location: arch/x86/coco/tdx/tdx.c:223
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_safe_halt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 __halt(const bool irq_disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff82142e90)
Location: arch/x86/coco/tdx/tdx.c:229
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_safe_halt
```
**Symbols:**

```
ffffffff82142e90-ffffffff82142eed: __halt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 __halt(const bool irq_disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff82225580)
Location: arch/x86/coco/tdx/tdx.c:253
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_handle_virt_exception
  - arch/x86/coco/tdx/tdx.c:tdx_safe_halt
```
**Symbols:**

```
ffffffff82225580-ffffffff822255dd: __halt (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
