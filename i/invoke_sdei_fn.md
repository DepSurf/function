# Function: <code>invoke_sdei_fn</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int invoke_sdei_fn(long unsigned int function_id, long unsigned int arg0, long unsigned int arg1, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, u64 *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/arm_sdei.c (ffff800010b4b4e8)
Location: drivers/firmware/arm_sdei.c:139
Inline: False
Direct callers:
  - drivers/firmware/arm_sdei.c:sdei_probe
  - drivers/firmware/arm_sdei.c:sdei_register_ghes
  - drivers/firmware/arm_sdei.c:sdei_device_thaw
  - drivers/firmware/arm_sdei.c:sdei_event_register
  - drivers/firmware/arm_sdei.c:sdei_event_register
  - drivers/firmware/arm_sdei.c:_local_event_register
  - drivers/firmware/arm_sdei.c:_local_event_unregister
  - drivers/firmware/arm_sdei.c:sdei_event_disable
  - drivers/firmware/arm_sdei.c:_ipi_event_disable
  - drivers/firmware/arm_sdei.c:sdei_event_enable
  - drivers/firmware/arm_sdei.c:_local_event_enable
  - drivers/firmware/arm_sdei.c:sdei_platform_reset
  - drivers/firmware/arm_sdei.c:_ipi_private_reset
  - drivers/firmware/arm_sdei.c:sdei_unmask_local_cpu
  - drivers/firmware/arm_sdei.c:sdei_mask_local_cpu
  - drivers/firmware/arm_sdei.c:sdei_api_event_context
```
**Symbols:**

```
ffff800010b4b4e8-ffff800010b4b618: invoke_sdei_fn (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
