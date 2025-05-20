# Function: <code>device_find_child</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81546a50)
Location: drivers/base/core.c:1452
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81546a50-ffffffff81546af1: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815986d0)
Location: drivers/base/core.c:1452
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff815986d0-ffffffff81598771: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c6370)
Location: drivers/base/core.c:2043
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff815c6370-ffffffff815c6411: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815db120)
Location: drivers/base/core.c:2041
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff815db120-ffffffff815db1c1: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816420e0)
Location: drivers/base/core.c:2176
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816420e0-ffffffff81642183: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167d370)
Location: drivers/base/core.c:2223
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff8167d370-ffffffff8167d411: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169cd00)
Location: drivers/base/core.c:2298
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nvdimm_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff8169cd00-ffffffff8169cda0: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d5af0)
Location: drivers/base/core.c:2524
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816d5af0-ffffffff816d5b92: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f98e0)
Location: drivers/base/core.c:2561
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816f98e0-ffffffff816f9982: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b28c0)
Location: drivers/base/core.c:3062
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff817b28c0-ffffffff817b2962: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7320)
Location: drivers/base/core.c:3474
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff817c7320-ffffffff817c73c2: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aa790)
Location: drivers/base/core.c:3701
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff817aa790-ffffffff817aa832: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833950)
Location: drivers/base/core.c:3766
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81833950-ffffffff818339f2: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819750f0)
Location: drivers/base/core.c:3800
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff819750f0-ffffffff819751ac: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae2abd)
Location: drivers/base/core.c:3999
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_any_child
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81ae08c0-ffffffff81ae097c: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b309dd)
Location: drivers/base/core.c:4008
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_any_child
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81b2eae0-ffffffff81b2eb9c: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b87fdd)
Location: drivers/base/core.c:4021
Inline: True
Inline callers:
  - drivers/base/core.c:device_find_any_child
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81b862e0-ffffffff81b8639c: device_find_child (STB_GLOBAL)
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
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e3d28)
Location: drivers/base/core.c:2561
Inline: False
Direct callers:
  - drivers/bus/fsl-mc/dprc-driver.c:dprc_scan_objects
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
```
**Symbols:**

```
ffff8000108e3d28-ffff8000108e3de4: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d2858)
Location: drivers/base/core.c:2561
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
```
**Symbols:**

```
c09d2858-c09d2914: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000978e20)
Location: drivers/base/core.c:2561
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
```
**Symbols:**

```
c000000000978e20-c000000000978f40: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000578e5c)
Location: drivers/base/core.c:2561
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/bus.c:nd_ioctl
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
```
**Symbols:**

```
ffffffe000578e5c-ffffffe000578ee0: device_find_child (STB_GLOBAL)
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
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf0d0)
Location: drivers/base/core.c:2561
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816bf0d0-ffffffff816bf172: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a380)
Location: drivers/base/core.c:2561
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff8169a380-ffffffff8169a422: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ed5a0)
Location: drivers/base/core.c:2561
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff816ed5a0-ffffffff816ed642: device_find_child (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *device_find_child(struct device *parent, void *data, int (*match)(struct device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81707de0)
Location: drivers/base/core.c:2561
Inline: False
Direct callers:
  - drivers/pwm/sysfs.c:pwm_class_get_state
  - drivers/pwm/sysfs.c:pwm_unexport_child
  - drivers/tty/serial/serial_core.c:uart_resume_port
  - drivers/tty/serial/serial_core.c:uart_suspend_port
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:slave_show
  - drivers/firmware/efi/dev-path-parser.c:efi_get_device_by_path
```
**Symbols:**

```
ffffffff81707de0-ffffffff81707e82: device_find_child (STB_GLOBAL)
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
