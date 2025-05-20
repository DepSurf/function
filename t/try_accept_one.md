# Function: <code>try_accept_one</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool try_accept_one(phys_addr_t *start, long unsigned int len, enum pg_level pg_level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81003768)
Location: arch/x86/coco/tdx/tdx.c:662
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
```
**Symbols:**

```
ffffffff81002b90-ffffffff81002c03: try_accept_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool try_accept_one(phys_addr_t *start, long unsigned int len, enum pg_level pg_level);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81003f78)
Location: arch/x86/coco/tdx/tdx.c:704
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
Direct callers:
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
  - arch/x86/coco/tdx/tdx.c:tdx_enc_status_changed
```
**Symbols:**

```
ffffffff810035d0-ffffffff81003643: try_accept_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx-shared.c (ffffffff81003b6b)
Location: arch/x86/coco/tdx/tdx-shared.c:4
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory
  - arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory
  - arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int try_accept_one(phys_addr_t start, long unsigned int len, enum pg_level pg_level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx-shared.c (ffffffff81003df0)
Location: arch/x86/coco/tdx/tdx-shared.c:4
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory
  - arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory
  - arch/x86/coco/tdx/tdx-shared.c:tdx_accept_memory
```
**Symbols:**

```
ffffffff81003df0-ffffffff81003e8e: try_accept_one (STB_LOCAL)
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
</ul>
