# Function: <code>vmalloc_sync_mappings</code>

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
void vmalloc_sync_mappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81081130)
Location: arch/x86/mm/fault.c:331
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff81081130-ffffffff81081161: vmalloc_sync_mappings (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void vmalloc_sync_mappings();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030db28)
Location: mm/vmalloc.c:3061
Inline: True
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffff80001030db28-ffff80001030db40: vmalloc_sync_mappings (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void vmalloc_sync_mappings();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0529588)
Location: mm/vmalloc.c:3061
Inline: True
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
c0529588-c05295a0: vmalloc_sync_mappings (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void vmalloc_sync_mappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003de730)
Location: mm/vmalloc.c:3061
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
c0000000003de730-c0000000003de73c: vmalloc_sync_mappings (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void vmalloc_sync_mappings();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000216818)
Location: mm/vmalloc.c:3061
Inline: True
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
ffffffe000216818-ffffffe000216832: vmalloc_sync_mappings (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void vmalloc_sync_mappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080130)
Location: arch/x86/mm/fault.c:331
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
ffffffff81080130-ffffffff81080161: vmalloc_sync_mappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vmalloc_sync_mappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106eef0)
Location: arch/x86/mm/fault.c:331
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
ffffffff8106eef0-ffffffff8106ef21: vmalloc_sync_mappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vmalloc_sync_mappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810800e0)
Location: arch/x86/mm/fault.c:331
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff810800e0-ffffffff81080111: vmalloc_sync_mappings (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vmalloc_sync_mappings();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81082200)
Location: arch/x86/mm/fault.c:331
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff81082200-ffffffff81082231: vmalloc_sync_mappings (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
