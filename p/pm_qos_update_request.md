# Function: <code>pm_qos_update_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810cc600)
Location: kernel/power/qos.c:474
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffff810cc600-ffffffff810cc6c6: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d1110)
Location: kernel/power/qos.c:474
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffff810d1110-ffffffff810d11db: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d7b80)
Location: kernel/power/qos.c:474
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffff810d7b80-ffffffff810d7c3b: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810d6bc0)
Location: kernel/power/qos.c:474
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_write
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff810d6bc0-ffffffff810d6c7a: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810deb50)
Location: kernel/power/qos.c:474
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_write
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff810deb50-ffffffff810dec12: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810e7360)
Location: kernel/power/qos.c:475
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_write
  - drivers/i2c/busses/i2c-designware-baytrail.c:baytrail_i2c_acquire
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff810e7360-ffffffff810e7423: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810f2790)
Location: kernel/power/qos.c:464
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffff810f2790-ffffffff810f2853: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fac40)
Location: kernel/power/qos.c:465
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_block_punit_i2c_access
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffff810fac40-ffffffff810fad03: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff81106ad0)
Location: kernel/power/qos.c:417
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffff81106ad0-ffffffff81106b93: pm_qos_update_request (STB_GLOBAL)
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
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016d628)
Location: kernel/power/qos.c:417
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffff80001016d628-ffff80001016d72c: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b867c)
Location: kernel/power/qos.c:417
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_write
  - drivers/tty/serial/omap-serial.c:serial_omap_uart_qos_work
```
**Symbols:**

```
c03b867c-c03b8788: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c4df0)
Location: kernel/power/qos.c:417
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
c0000000001c4df0-c0000000001c4f68: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010ce6a)
Location: kernel/power/qos.c:417
Inline: True
Direct callers:
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffe00010ce6a-ffffffe00010cf60: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810ffde0)
Location: kernel/power/qos.c:417
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffff810ffde0-ffffffff810ffea3: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810effd0)
Location: kernel/power/qos.c:417
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffff810effd0-ffffffff810f0093: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810fcfa0)
Location: kernel/power/qos.c:417
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffff810fcfa0-ffffffff810fd063: pm_qos_update_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pm_qos_update_request(struct pm_qos_request *req, s32 new_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff811081f0)
Location: kernel/power/qos.c:417
Inline: True
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - kernel/power/qos.c:pm_qos_power_write
```
**Symbols:**

```
ffffffff811081f0-ffffffff811082cf: pm_qos_update_request (STB_GLOBAL)
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
