# Function: <code>acpi_resource_to_address64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff814a3f49)
Location: drivers/acpi/acpica/rsxface.c:368
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/char/hpet.c:hpet_resources
```
**Symbols:**

```
ffffffff814a3f49-ffffffff814a4048: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff814f328c)
Location: drivers/acpi/acpica/rsxface.c:368
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/char/hpet.c:hpet_resources
```
**Symbols:**

```
ffffffff814f328c-ffffffff814f338b: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81515dda)
Location: drivers/acpi/acpica/rsxface.c:368
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/char/hpet.c:hpet_resources
```
**Symbols:**

```
ffffffff81515dda-ffffffff81515ed9: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81526753)
Location: drivers/acpi/acpica/rsxface.c:368
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff81526753-ffffffff81526852: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff8157d76d)
Location: drivers/acpi/acpica/rsxface.c:368
Inline: True
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff8157d76d-ffffffff8157d86c: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815b4943)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff815b4943-ffffffff815b4a47: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815cdcff)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff815cdcff-ffffffff815cde03: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815ff55d)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff815ff55d-ffffffff815ff667: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81620a07)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff81620a07-ffffffff81620b11: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816ccf96)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_address_option
  - drivers/char/hpet.c:hpet_resources
```
**Symbols:**

```
ffffffff816ccf96-ffffffff816cd0a0: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816eafad)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_parse_address_option
  - drivers/char/hpet.c:hpet_resources
```
**Symbols:**

```
ffffffff816eafad-ffffffff816eb0b7: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff816ccebf)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/char/hpet.c:hpet_resources
```
**Symbols:**

```
ffffffff816ccebf-ffffffff816ccfc9: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff8174438f)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/char/hpet.c:hpet_resources
```
**Symbols:**

```
ffffffff8174438f-ffffffff81744499: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81876098)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/char/hpet.c:hpet_resources
  - arch/x86/pci/mmconfig-shared.c:check_mcfg_resource
```
**Symbols:**

```
ffffffff81876098-ffffffff818761ac: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff819b7cf0)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/char/hpet.c:hpet_resources
  - arch/x86/pci/mmconfig-shared.c:check_mcfg_resource
```
**Symbols:**

```
ffffffff819b7cf0-ffffffff819b7e61: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff819fee40)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/char/hpet.c:hpet_resources
  - arch/x86/pci/mmconfig-shared.c:check_mcfg_resource
```
**Symbols:**

```
ffffffff819fee40-ffffffff819fefb1: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81a49cc0)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/char/hpet.c:hpet_resources
  - arch/x86/pci/mmconfig-shared.c:check_mcfg_resource
```
**Symbols:**

```
ffffffff81a49cc0-ffffffff81a49e31: acpi_resource_to_address64 (STB_GLOBAL)
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
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffff800010796304)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffff800010796304-ffff800010796444: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815fb2e2)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff815fb2e2-ffffffff815fb3ec: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff815e6812)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff815e6812-ffffffff815e691c: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff81614ce7)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff81614ce7-ffffffff81614df1: acpi_resource_to_address64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_resource_to_address64(struct acpi_resource *resource, struct acpi_resource_address64 *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/rsxface.c (ffffffff8162eb97)
Location: drivers/acpi/acpica/rsxface.c:332
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_resource_address_space
  - drivers/acpi/pci_root.c:get_root_bridge_busnr_callback
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff8162eb97-ffffffff8162eca1: acpi_resource_to_address64 (STB_GLOBAL)
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
