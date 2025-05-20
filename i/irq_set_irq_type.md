# Function: <code>irq_set_irq_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810dda90)
Location: kernel/irq/chip.c:70
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/mfd/tps65912-irq.c:tps65912_irq_init
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff810dda90-ffffffff810ddb16: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e32a0)
Location: kernel/irq/chip.c:70
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff810e32a0-ffffffff810e3327: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9b60)
Location: kernel/irq/chip.c:70
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff810e9b60-ffffffff810e9be4: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9080)
Location: kernel/irq/chip.c:70
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff810e9080-ffffffff810e9104: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f14e0)
Location: kernel/irq/chip.c:70
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff810f14e0-ffffffff810f1564: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f9920)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff810f9920-ffffffff810f99a4: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811050d0)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff811050d0-ffffffff81105154: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110e3b0)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff8110e3b0-ffffffff8110e436: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111a670)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff8111a670-ffffffff8111a6f6: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811266f0)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff811266f0-ffffffff81126776: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122320)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff81122320-ffffffff811223a6: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811226a0)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff811226a0-ffffffff81122726: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81142c50)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff81142c50-ffffffff81142cd6: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81166910)
Location: kernel/irq/chip.c:65
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff81166910-ffffffff811669a8: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119abd0)
Location: kernel/irq/chip.c:65
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff8119abd0-ffffffff8119ac68: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ac930)
Location: kernel/irq/chip.c:65
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff811ac930-ffffffff811ac9c8: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bc530)
Location: kernel/irq/chip.c:65
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff811bc530-ffffffff811bc5c8: irq_set_irq_type (STB_GLOBAL)
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
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017dd10)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffff80001017dd10-ffff80001017ddac: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03ce51c)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpio-htc-egpio.c:egpio_probe
  - drivers/mfd/asic3.c:asic3_probe
  - drivers/mfd/t7l66xb.c:t7l66xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
  - drivers/staging/emxx_udc/emxx_udc.c:nbu2ss_drv_probe
```
**Symbols:**

```
c03ce51c-c03ce5b4: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d8630)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_device
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic_u3msi.c:u3msi_setup_msi_irqs
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
c0000000001d8630-c0000000001d86e8: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe0001168d6)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffe0001168d6-ffffffe00011693a: irq_set_irq_type (STB_GLOBAL)
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
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81112c50)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff81112c50-ffffffff81112cd6: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81103970)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff81103970-ffffffff811039f6: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81110b40)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff81110b40-ffffffff81110bc6: irq_set_irq_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_set_irq_type(unsigned int irq, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111c0c0)
Location: kernel/irq/chip.c:68
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/mfd/ezx-pcap.c:ezx_pcap_probe
```
**Symbols:**

```
ffffffff8111c0c0-ffffffff8111c146: irq_set_irq_type (STB_GLOBAL)
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
