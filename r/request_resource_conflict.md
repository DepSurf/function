# Function: <code>request_resource_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81085fe2)
Location: kernel/resource.c:292
Inline: True
Inline callers:
  - kernel/resource.c:request_resource
  - kernel/resource.c:devm_request_resource
Direct callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/pci/setup-res.c:pci_assign_resource
```
**Symbols:**

```
ffffffff81086d30-ffffffff81086d65: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108952c)
Location: kernel/resource.c:311
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:request_resource
Direct callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
```
**Symbols:**

```
ffffffff81089d60-ffffffff81089d95: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e47c)
Location: kernel/resource.c:311
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:request_resource
Direct callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
```
**Symbols:**

```
ffffffff8108ecb0-ffffffff8108ece5: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b49c)
Location: kernel/resource.c:311
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:request_resource
Direct callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
```
**Symbols:**

```
ffffffff8108bc70-ffffffff8108bca5: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109217c)
Location: kernel/resource.c:311
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
  - kernel/resource.c:request_resource
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810929f0-ffffffff81092a25: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810963b0)
Location: kernel/resource.c:278
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - mm/memory_hotplug.c:add_memory
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810963b0-ffffffff810963e5: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e720)
Location: kernel/resource.c:278
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - mm/memory_hotplug.c:__add_memory
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8109e720-ffffffff8109e755: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2d90)
Location: kernel/resource.c:279
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810a2d90-ffffffff810a2dc7: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a93d0)
Location: kernel/resource.c:279
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810a93d0-ffffffff810a9407: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b07c7)
Location: kernel/resource.c:279
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
Direct callers:
  - kernel/resource.c:reserve_setup
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_revert_fw_address
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810b0f20-ffffffff810b0fa0: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810abee7)
Location: kernel/resource.c:279
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
Direct callers:
  - kernel/resource.c:reserve_setup
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_revert_fw_address
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810ac680-ffffffff810ac700: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810acfe7)
Location: kernel/resource.c:278
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
Direct callers:
  - kernel/resource.c:reserve_setup
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810ad890-ffffffff810ad910: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810beb5e)
Location: kernel/resource.c:278
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
Direct callers:
  - kernel/resource.c:reserve_setup
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810bf410-ffffffff810bf490: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d5c6d)
Location: kernel/resource.c:265
Inline: True
Inline callers:
  - kernel/resource.c:devm_request_resource
Direct callers:
  - kernel/resource.c:reserve_setup
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810d67b0-ffffffff810d6840: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff83ea5e9a)
Location: kernel/resource.c:265
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
Direct callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810f61a0-ffffffff810f6230: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff836ca56a)
Location: kernel/resource.c:265
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
Direct callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff811025f0-ffffffff81102680: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff838fb21a)
Location: kernel/resource.c:265
Inline: True
Inline callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
Direct callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff8110bd80-ffffffff8110be10: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000101010a0)
Location: kernel/resource.c:279
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
ffff8000101010a0-ffff80001010113c: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d76c)
Location: kernel/resource.c:279
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/pci/ecam.c:pci_ecam_create
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
**Symbols:**

```
c035d76c-c035d7bc: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c0000000001487f0)
Location: kernel/resource.c:279
Inline: False
Direct callers:
  - arch/powerpc/platforms/pseries/setup.c:of_pci_parse_iov_addrs
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/pci/ecam.c:pci_ecam_create
```
**Symbols:**

```
c0000000001487f0-c000000000148858: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c84ca)
Location: kernel/resource.c:279
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/pci/ecam.c:pci_ecam_create
```
**Symbols:**

```
ffffffe0000c84ca-ffffffe0000c8518: request_resource_conflict (STB_GLOBAL)
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
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2cf0)
Location: kernel/resource.c:279
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810a2cf0-ffffffff810a2d27: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810916d0)
Location: kernel/resource.c:279
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810916d0-ffffffff81091707: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2ca0)
Location: kernel/resource.c:279
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810a2ca0-ffffffff810a2cd7: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct resource *request_resource_conflict(struct resource *root, struct resource *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aad30)
Location: kernel/resource.c:279
Inline: False
Direct callers:
  - kernel/resource.c:reserve_setup
  - kernel/resource.c:devm_request_resource
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
**Symbols:**

```
ffffffff810aad30-ffffffff810aad72: request_resource_conflict (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
