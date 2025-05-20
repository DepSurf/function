# Function: <code>firmware_request_builtin</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool firmware_request_builtin(struct firmware *fw, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff819a1a95)
Location: drivers/base/firmware_loader/builtin/main.c:47
Inline: True
Inline callers:
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff819a1a00-ffffffff819a1a89: firmware_request_builtin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool firmware_request_builtin(struct firmware *fw, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81b13905)
Location: drivers/base/firmware_loader/builtin/main.c:47
Inline: True
Inline callers:
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff81b13860-ffffffff81b138e9: firmware_request_builtin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool firmware_request_builtin(struct firmware *fw, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81b62635)
Location: drivers/base/firmware_loader/builtin/main.c:47
Inline: True
Inline callers:
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff81b62590-ffffffff81b62619: firmware_request_builtin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool firmware_request_builtin(struct firmware *fw, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/builtin/main.c (ffffffff81bb6145)
Location: drivers/base/firmware_loader/builtin/main.c:47
Inline: True
Inline callers:
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
  - drivers/base/firmware_loader/builtin/main.c:firmware_request_builtin_buf
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob
  - arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers
  - drivers/base/firmware_loader/main.c:device_uncache_fw_images_work
```
**Symbols:**

```
ffffffff81bb60a0-ffffffff81bb6129: firmware_request_builtin (STB_GLOBAL)
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
