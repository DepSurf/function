# Function: <code>uv_bios_call_irqsave</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810980f0)
Location: arch/x86/platform/uv/bios_uv.c:59
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa
  - arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info
```
**Symbols:**

```
ffffffff810980f0-ffffffff81098188: uv_bios_call_irqsave (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff8109d740)
Location: arch/x86/platform/uv/bios_uv.c:62
Inline: True
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa
  - arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info
```
**Symbols:**

```
ffffffff8109d740-ffffffff8109d7d0: uv_bios_call_irqsave.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff81099080)
Location: arch/x86/platform/uv/bios_uv.c:54
Inline: True
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa
  - arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info
```
**Symbols:**

```
ffffffff81099080-ffffffff81099113: uv_bios_call_irqsave.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810998a0)
Location: arch/x86/platform/uv/bios_uv.c:54
Inline: True
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa
  - arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info
```
**Symbols:**

```
ffffffff810998a0-ffffffff8109993b: uv_bios_call_irqsave.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810a98c0)
Location: arch/x86/platform/uv/bios_uv.c:54
Inline: True
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa
  - arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info
```
**Symbols:**

```
ffffffff810a98c0-ffffffff810a995b: uv_bios_call_irqsave.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810bf1d0)
Location: arch/x86/platform/uv/bios_uv.c:54
Inline: True
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa
  - arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info
```
**Symbols:**

```
ffffffff810bf1d0-ffffffff810bf278: uv_bios_call_irqsave.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810daf20)
Location: arch/x86/platform/uv/bios_uv.c:54
Inline: True
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa
  - arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info
```
**Symbols:**

```
ffffffff810daf20-ffffffff810dafc8: uv_bios_call_irqsave.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810e64b0)
Location: arch/x86/platform/uv/bios_uv.c:54
Inline: True
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa
  - arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info
```
**Symbols:**

```
ffffffff810e64b0-ffffffff810e6558: uv_bios_call_irqsave.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810ee830)
Location: arch/x86/platform/uv/bios_uv.c:54
Inline: True
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa
  - arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info
```
**Symbols:**

```
ffffffff810ee830-ffffffff810ee8d8: uv_bios_call_irqsave.constprop.0 (STB_LOCAL)
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
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
s64 uv_bios_call_irqsave(enum uv_bios_cmd which, u64 a1, u64 a2, u64 a3, u64 a4, u64 a5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810995c0)
Location: arch/x86/platform/uv/bios_uv.c:59
Inline: False
Direct callers:
  - arch/x86/platform/uv/bios_uv.c:uv_bios_reserved_page_pa
  - arch/x86/platform/uv/bios_uv.c:uv_bios_change_memprotect
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_free
  - arch/x86/platform/uv/bios_uv.c:uv_bios_mq_watchlist_alloc
  - arch/x86/platform/uv/bios_uv.c:uv_bios_get_sn_info
```
**Symbols:**

```
ffffffff810995c0-ffffffff81099658: uv_bios_call_irqsave (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
