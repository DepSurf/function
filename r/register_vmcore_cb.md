# Function: <code>register_vmcore_cb</code>

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
void register_vmcore_cb(struct vmcore_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (0)
Location: fs/proc/vmcore.c:73
Inline: False
Direct callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/kernel/aperture_64.c:exclude_from_core
```
**Symbols:**

```
ffffffff81e7b1db-ffffffff81e7b21b: register_vmcore_cb.cold (STB_LOCAL)
ffffffff814afbf0-ffffffff814afc7d: register_vmcore_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void register_vmcore_cb(struct vmcore_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (0)
Location: fs/proc/vmcore.c:72
Inline: False
Direct callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/kernel/aperture_64.c:exclude_from_core
```
**Symbols:**

```
ffffffff8206bb6e-ffffffff8206bb96: register_vmcore_cb.cold (STB_LOCAL)
ffffffff815463c0-ffffffff8154645e: register_vmcore_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void register_vmcore_cb(struct vmcore_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (0)
Location: fs/proc/vmcore.c:72
Inline: False
Direct callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/kernel/aperture_64.c:exclude_from_core
```
**Symbols:**

```
ffffffff820eb9fc-ffffffff820eba24: register_vmcore_cb.cold (STB_LOCAL)
ffffffff8157df80-ffffffff8157e01e: register_vmcore_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void register_vmcore_cb(struct vmcore_cb *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/vmcore.c (0)
Location: fs/proc/vmcore.c:72
Inline: False
Direct callers:
  - arch/x86/xen/mmu_hvm.c:xen_hvm_init_mmu_ops
  - arch/x86/kernel/aperture_64.c:exclude_from_core
  - drivers/firmware/efi/unaccepted_memory.c:unaccepted_memory_init_kdump
```
**Symbols:**

```
ffffffff821c8c60-ffffffff821c8c88: register_vmcore_cb.cold (STB_LOCAL)
ffffffff815b69c0-ffffffff815b6a5e: register_vmcore_cb (STB_GLOBAL)
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
