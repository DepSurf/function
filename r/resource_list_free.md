# Function: <code>resource_list_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81086440)
Location: kernel/resource.c:1528
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
```
**Symbols:**

```
ffffffff81086440-ffffffff8108649b: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81089480)
Location: kernel/resource.c:1605
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
```
**Symbols:**

```
ffffffff81089480-ffffffff810894e6: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e3d0)
Location: kernel/resource.c:1605
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff8108e3d0-ffffffff8108e436: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b3f0)
Location: kernel/resource.c:1605
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff8108b3f0-ffffffff8108b457: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810920d0)
Location: kernel/resource.c:1623
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810920d0-ffffffff81092137: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81095ac0)
Location: kernel/resource.c:1605
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff81095ac0-ffffffff81095b27: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109de40)
Location: kernel/resource.c:1614
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff8109de40-ffffffff8109dea7: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2390)
Location: kernel/resource.c:1637
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810a2390-ffffffff810a23ed: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8960)
Location: kernel/resource.c:1637
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810a8960-ffffffff810a89bd: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b00e0)
Location: kernel/resource.c:1642
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_dev_consumes_res
  - drivers/acpi/resource.c:acpi_dev_consumes_res
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810b00e0-ffffffff810b013d: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ab800)
Location: kernel/resource.c:1715
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_dev_consumes_res
  - drivers/acpi/resource.c:acpi_dev_consumes_res
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810ab800-ffffffff810ab85d: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aca00)
Location: kernel/resource.c:1768
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810aca00-ffffffff810aca5d: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810be580)
Location: kernel/resource.c:1768
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810be580-ffffffff810be5dd: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d5710)
Location: kernel/resource.c:1767
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810d5710-ffffffff810d5775: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f46b0)
Location: kernel/resource.c:1761
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810f46b0-ffffffff810f4715: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81100ae0)
Location: kernel/resource.c:1761
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff81100ae0-ffffffff81100b45: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110a410)
Location: kernel/resource.c:1815
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff8110a410-ffffffff8110a475: resource_list_free (STB_GLOBAL)
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
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff8000100ffdc8)
Location: kernel/resource.c:1637
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffff8000100ffdc8-ffff8000100ffe3c: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035cae4)
Location: kernel/resource.c:1637
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
```
**Symbols:**

```
c035cae4-c035cb40: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000147580)
Location: kernel/resource.c:1637
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
```
**Symbols:**

```
c000000000147580-c00000000014763c: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c7ace)
Location: kernel/resource.c:1637
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
```
**Symbols:**

```
ffffffe0000c7ace-ffffffe0000c7b2a: resource_list_free (STB_GLOBAL)
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
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2280)
Location: kernel/resource.c:1637
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810a2280-ffffffff810a22dd: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81090c60)
Location: kernel/resource.c:1637
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff81090c60-ffffffff81090cbd: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2230)
Location: kernel/resource.c:1637
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810a2230-ffffffff810a228d: resource_list_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void resource_list_free(struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aa290)
Location: kernel/resource.c:1637
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_free_resource_list
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/acpi_watchdog.c:acpi_watchdog_init
```
**Symbols:**

```
ffffffff810aa290-ffffffff810aa2ed: resource_list_free (STB_GLOBAL)
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
