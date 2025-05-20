# Function: <code>wait_for_initramfs</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_initramfs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff81004035)
Location: init/initramfs.c:710
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/initramfs.c:populate_rootfs
  - kernel/umh.c:call_usermodehelper_exec_async
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff81bc3925-ffffffff81bc393d: wait_for_initramfs.cold (STB_LOCAL)
ffffffff81004020-ffffffff81004056: wait_for_initramfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_initramfs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff81004086)
Location: init/initramfs.c:711
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/initramfs.c:populate_rootfs
  - kernel/umh.c:call_usermodehelper_exec_async
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff81c9499c-ffffffff81c949c8: wait_for_initramfs.cold (STB_LOCAL)
ffffffff81004070-ffffffff810040bb: wait_for_initramfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_initramfs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff81001d96)
Location: init/initramfs.c:737
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/initramfs.c:populate_rootfs
  - kernel/umh.c:call_usermodehelper_exec_async
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff81e43b54-ffffffff81e43b80: wait_for_initramfs.cold (STB_LOCAL)
ffffffff81001d80-ffffffff81001ddf: wait_for_initramfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_initramfs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff81002526)
Location: init/initramfs.c:737
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/initramfs.c:populate_rootfs
  - kernel/umh.c:call_usermodehelper_exec_async
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff8204fff7-ffffffff8205000b: wait_for_initramfs.cold (STB_LOCAL)
ffffffff81002510-ffffffff81002580: wait_for_initramfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_initramfs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff81001d06)
Location: init/initramfs.c:730
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/initramfs.c:populate_rootfs
  - kernel/umh.c:call_usermodehelper_exec_async
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff820ce4b0-ffffffff820ce4c4: wait_for_initramfs.cold (STB_LOCAL)
ffffffff81001cf0-ffffffff81001d60: wait_for_initramfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wait_for_initramfs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/initramfs.c (ffffffff81001d66)
Location: init/initramfs.c:746
Inline: True
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/initramfs.c:populate_rootfs
  - kernel/umh.c:call_usermodehelper_exec_async
  - drivers/base/firmware_loader/main.c:fw_get_filesystem_firmware
```
**Symbols:**

```
ffffffff821a8cc0-ffffffff821a8cd4: wait_for_initramfs.cold (STB_LOCAL)
ffffffff81001d50-ffffffff81001dc0: wait_for_initramfs (STB_GLOBAL)
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
