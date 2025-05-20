# Function: <code>intel_scu_ipc_dev_writev</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_scu_ipc_dev_writev(struct intel_scu_ipc_dev *scu, u16 *addr, u8 *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c5330)
Location: drivers/platform/x86/intel_scu_ipc.c:392
Inline: False
Direct callers:
  - drivers/mfd/intel_msic.c:intel_msic_bulk_write
```
**Symbols:**

```
ffffffff819c5330-ffffffff819c5343: intel_scu_ipc_dev_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_scu_ipc_dev_writev(struct intel_scu_ipc_dev *scu, u16 *addr, u8 *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819c5560)
Location: drivers/platform/x86/intel_scu_ipc.c:392
Inline: False
Direct callers:
  - drivers/mfd/intel_msic.c:intel_msic_bulk_write
```
**Symbols:**

```
ffffffff819c5560-ffffffff819c5573: intel_scu_ipc_dev_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int intel_scu_ipc_dev_writev(struct intel_scu_ipc_dev *scu, u16 *addr, u8 *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff819aa530)
Location: drivers/platform/x86/intel_scu_ipc.c:392
Inline: False
```
**Symbols:**

```
ffffffff819aa530-ffffffff819aa543: intel_scu_ipc_dev_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int intel_scu_ipc_dev_writev(struct intel_scu_ipc_dev *scu, u16 *addr, u8 *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81a57f70)
Location: drivers/platform/x86/intel_scu_ipc.c:392
Inline: False
```
**Symbols:**

```
ffffffff81a57f70-ffffffff81a57f83: intel_scu_ipc_dev_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_scu_ipc_dev_writev(struct intel_scu_ipc_dev *scu, u16 *addr, u8 *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81bc7ad0)
Location: drivers/platform/x86/intel_scu_ipc.c:392
Inline: False
```
**Symbols:**

```
ffffffff81bc7ad0-ffffffff81bc7af2: intel_scu_ipc_dev_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_scu_ipc_dev_writev(struct intel_scu_ipc_dev *scu, u16 *addr, u8 *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81d706c0)
Location: drivers/platform/x86/intel_scu_ipc.c:392
Inline: False
```
**Symbols:**

```
ffffffff81d706c0-ffffffff81d706e2: intel_scu_ipc_dev_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_scu_ipc_dev_writev(struct intel_scu_ipc_dev *scu, u16 *addr, u8 *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81dde380)
Location: drivers/platform/x86/intel_scu_ipc.c:391
Inline: False
```
**Symbols:**

```
ffffffff81dde380-ffffffff81dde3a2: intel_scu_ipc_dev_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_scu_ipc_dev_writev(struct intel_scu_ipc_dev *scu, u16 *addr, u8 *data, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e94260)
Location: drivers/platform/x86/intel_scu_ipc.c:407
Inline: False
```
**Symbols:**

```
ffffffff81e94260-ffffffff81e94282: intel_scu_ipc_dev_writev (STB_GLOBAL)
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
