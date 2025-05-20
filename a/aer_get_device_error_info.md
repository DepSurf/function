# Function: <code>aer_get_device_error_info</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8154bae0)
Location: drivers/pci/pcie/aer.c:1086
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8154bae0-ffffffff8154bc3e: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157b470)
Location: drivers/pci/pcie/aer.c:1086
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8157b470-ffffffff8157b5ce: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8159ced0)
Location: drivers/pci/pcie/aer.c:1086
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8159ced0-ffffffff8159d02e: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8163cb50)
Location: drivers/pci/pcie/aer.c:1012
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff8163cb50-ffffffff8163ccae: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81663ab0)
Location: drivers/pci/pcie/aer.c:1040
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81663ab0-ffffffff81663c1d: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81645f60)
Location: drivers/pci/pcie/aer.c:1040
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81645f60-ffffffff816460c0: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff816b72e0)
Location: drivers/pci/pcie/aer.c:1042
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff816b72e0-ffffffff816b7440: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff817dafd0)
Location: drivers/pci/pcie/aer.c:1047
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/aer.c:aer_isr
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff817dafd0-ffffffff817db148: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff818fced0)
Location: drivers/pci/pcie/aer.c:1058
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff818fced0-ffffffff818fd048: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81940350)
Location: drivers/pci/pcie/aer.c:1061
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81940350-ffffffff819404c8: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81989540)
Location: drivers/pci/pcie/aer.c:1209
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_process_error
```
**Symbols:**

```
ffffffff81989540-ffffffff819896b8: aer_get_device_error_info (STB_GLOBAL)
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
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffff800010704e90)
Location: drivers/pci/pcie/aer.c:1086
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffff800010704e90-ffff80001070500c: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (c089c190)
Location: drivers/pci/pcie/aer.c:1086
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
c089c190-c089c31c: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffe0004d2fbc)
Location: drivers/pci/pcie/aer.c:1086
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffe0004d2fbc-ffffffe0004d3124: aer_get_device_error_info (STB_GLOBAL)
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
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815909a0)
Location: drivers/pci/pcie/aer.c:1086
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff815909a0-ffffffff81590afe: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8157f8a0)
Location: drivers/pci/pcie/aer.c:1086
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff8157f8a0-ffffffff8157f9fe: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81590c20)
Location: drivers/pci/pcie/aer.c:1086
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff81590c20-ffffffff81590d7e: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int aer_get_device_error_info(struct pci_dev *dev, struct aer_err_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff815ab0d0)
Location: drivers/pci/pcie/aer.c:1086
Inline: False
Direct callers:
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/aer.c:aer_process_err_devices
  - drivers/pci/pcie/dpc.c:dpc_handler
```
**Symbols:**

```
ffffffff815ab0d0-ffffffff815ab22e: aer_get_device_error_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
