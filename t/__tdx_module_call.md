# Function: <code>__tdx_module_call</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void __tdx_module_call();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdcall.S (ffffffff81003af0)
Location: arch/x86/coco/tdx/tdcall.S
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_get_report
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_get_ve_info
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
```
**Symbols:**

```
ffffffff81003af0-ffffffff81003b34: __tdx_module_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __tdx_module_call();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdcall.S (ffffffff81004370)
Location: arch/x86/coco/tdx/tdcall.S
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_get_ve_info
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
```
**Symbols:**

```
ffffffff81004370-ffffffff810043b4: __tdx_module_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __tdx_module_call();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdcall.S (ffffffff82139670)
Location: arch/x86/coco/tdx/tdcall.S
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_get_ve_info
  - arch/x86/coco/tdx/tdx.c:tdx_mcall_get_report0
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
  - arch/x86/coco/tdx/tdx.c:tdx_early_init
  - arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory
  - arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory
  - arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory
```
**Symbols:**

```
ffffffff82139670-ffffffff821396b4: __tdx_module_call (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
