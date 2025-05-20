# Function: <code>intel_scu_ipc_dev_command_with_size</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int intel_scu_ipc_dev_command_with_size(struct intel_scu_ipc_dev *scu, int cmd, int sub, const void *in, size_t inlen, size_t size, void *out, size_t outlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: drivers/platform/x86/intel_scu_ipc.c:475
Inline: False
```
**Symbols:**

```
ffffffff819c56e7-ffffffff819c5719: intel_scu_ipc_dev_command_with_size.cold (STB_LOCAL)
ffffffff819c4d40-ffffffff819c4f11: intel_scu_ipc_dev_command_with_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int intel_scu_ipc_dev_command_with_size(struct intel_scu_ipc_dev *scu, int cmd, int sub, const void *in, size_t inlen, size_t size, void *out, size_t outlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: drivers/platform/x86/intel_scu_ipc.c:475
Inline: False
```
**Symbols:**

```
ffffffff81c2d549-ffffffff81c2d57b: intel_scu_ipc_dev_command_with_size.cold (STB_LOCAL)
ffffffff819c4f70-ffffffff819c5141: intel_scu_ipc_dev_command_with_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int intel_scu_ipc_dev_command_with_size(struct intel_scu_ipc_dev *scu, int cmd, int sub, const void *in, size_t inlen, size_t size, void *out, size_t outlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: drivers/platform/x86/intel_scu_ipc.c:475
Inline: False
```
**Symbols:**

```
ffffffff81c1f7c7-ffffffff81c1f7f8: intel_scu_ipc_dev_command_with_size.cold (STB_LOCAL)
ffffffff819a9f40-ffffffff819aa10d: intel_scu_ipc_dev_command_with_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int intel_scu_ipc_dev_command_with_size(struct intel_scu_ipc_dev *scu, int cmd, int sub, const void *in, size_t inlen, size_t size, void *out, size_t outlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: drivers/platform/x86/intel_scu_ipc.c:475
Inline: False
```
**Symbols:**

```
ffffffff81d31011-ffffffff81d3104a: intel_scu_ipc_dev_command_with_size.cold (STB_LOCAL)
ffffffff81a577f0-ffffffff81a57a21: intel_scu_ipc_dev_command_with_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int intel_scu_ipc_dev_command_with_size(struct intel_scu_ipc_dev *scu, int cmd, int sub, const void *in, size_t inlen, size_t size, void *out, size_t outlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (0)
Location: drivers/platform/x86/intel_scu_ipc.c:475
Inline: False
```
**Symbols:**

```
ffffffff81efd445-ffffffff81efd47d: intel_scu_ipc_dev_command_with_size.cold (STB_LOCAL)
ffffffff81bc72e0-ffffffff81bc7526: intel_scu_ipc_dev_command_with_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_scu_ipc_dev_command_with_size(struct intel_scu_ipc_dev *scu, int cmd, int sub, const void *in, size_t inlen, size_t size, void *out, size_t outlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81d6ff60)
Location: drivers/platform/x86/intel_scu_ipc.c:475
Inline: False
```
**Symbols:**

```
ffffffff81d6ff60-ffffffff81d701e1: intel_scu_ipc_dev_command_with_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_scu_ipc_dev_command_with_size(struct intel_scu_ipc_dev *scu, int cmd, int sub, const void *in, size_t inlen, size_t size, void *out, size_t outlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81dddc20)
Location: drivers/platform/x86/intel_scu_ipc.c:474
Inline: False
```
**Symbols:**

```
ffffffff81dddc20-ffffffff81dddea1: intel_scu_ipc_dev_command_with_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_scu_ipc_dev_command_with_size(struct intel_scu_ipc_dev *scu, int cmd, int sub, const void *in, size_t inlen, size_t size, void *out, size_t outlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e93ae0)
Location: drivers/platform/x86/intel_scu_ipc.c:489
Inline: False
```
**Symbols:**

```
ffffffff81e93ae0-ffffffff81e93d6a: intel_scu_ipc_dev_command_with_size (STB_GLOBAL)
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
