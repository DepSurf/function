# Function: <code>msleep_interruptible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810ec690)
Location: kernel/time/timer.c:1687
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_close
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff810ec690-ffffffff810ec6e9: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3d20)
Location: kernel/time/timer.c:1888
Inline: False
Direct callers:
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/tty/serial/serial_core.c:uart_close
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff810f3d20-ffffffff810f3d79: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810faed0)
Location: kernel/time/timer.c:1893
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff810faed0-ffffffff810faf25: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fdf80)
Location: kernel/time/timer.c:1883
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff810fdf80-ffffffff810fdfd5: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81108830)
Location: kernel/time/timer.c:1954
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81108830-ffffffff81108893: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81113b10)
Location: kernel/time/timer.c:1965
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81113b10-ffffffff81113b6b: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81120370)
Location: kernel/time/timer.c:1964
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81120370-ffffffff811203cb: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112ac60)
Location: kernel/time/timer.c:1968
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff8112ac60-ffffffff8112acb5: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81136c00)
Location: kernel/time/timer.c:2057
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81136c00-ffffffff81136c55: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81144a60)
Location: kernel/time/timer.c:2078
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81144a60-ffffffff81144abb: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141e20)
Location: kernel/time/timer.c:2041
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81141e20-ffffffff81141e85: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81142c20)
Location: kernel/time/timer.c:2059
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81142c20-ffffffff81142c85: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81166120)
Location: kernel/time/timer.c:2045
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81166120-ffffffff81166184: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199ca0)
Location: kernel/time/timer.c:2100
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81199ca0-ffffffff81199d10: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d8340)
Location: kernel/time/timer.c:2331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
```
**Symbols:**

```
ffffffff811d8340-ffffffff811d83b0: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ec770)
Location: kernel/time/timer.c:2331
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
```
**Symbols:**

```
ffffffff811ec770-ffffffff811ec7e0: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81202790)
Location: kernel/time/timer.c:2347
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_warn
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
```
**Symbols:**

```
ffffffff81202790-ffffffff81202800: msleep_interruptible (STB_GLOBAL)
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
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019f140)
Location: kernel/time/timer.c:2057
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffff80001019f140-ffff80001019f1b4: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e9010)
Location: kernel/time/timer.c:2057
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
c03e9010-c03e907c: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001ffe90)
Location: kernel/time/timer.c:2057
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
c0000000001ffe90-c0000000001fff34: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012daf4)
Location: kernel/time/timer.c:2057
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffe00012daf4-ffffffe00012db50: msleep_interruptible (STB_GLOBAL)
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
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112f3b0)
Location: kernel/time/timer.c:2057
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff8112f3b0-ffffffff8112f405: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81121e30)
Location: kernel/time/timer.c:2057
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81121e30-ffffffff81121e85: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d0d0)
Location: kernel/time/timer.c:2057
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff8112d0d0-ffffffff8112d125: msleep_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int msleep_interruptible(unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81138e60)
Location: kernel/time/timer.c:2057
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - fs/efivarfs/file.c:efivarfs_file_read
  - drivers/tty/tty_port.c:tty_port_close_end
  - drivers/tty/serial/serial_core.c:uart_wait_until_sent
  - drivers/char/hw_random/core.c:hwrng_fillfn
```
**Symbols:**

```
ffffffff81138e60-ffffffff81138eb5: msleep_interruptible (STB_GLOBAL)
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
