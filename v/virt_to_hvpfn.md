# Function: <code>virt_to_hvpfn</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8103f585)
Location: include/linux/hyperv.h:1772
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff810486f5)
Location: include/linux/hyperv.h:1774
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81048a55)
Location: include/linux/hyperv.h:1768
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_vtom_set_host_visibility
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int virt_to_hvpfn(void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hv/channel.c (ffffffff81850a00)
Location: drivers/hv/channel.c:40
Inline: False
Direct callers:
  - drivers/hv/channel.c:vmbus_establish_gpadl
  - drivers/hv/channel.c:vmbus_establish_gpadl
  - drivers/hv/channel.c:vmbus_establish_gpadl
```
**Symbols:**

```
ffffffff81850a00-ffffffff81850a7a: virt_to_hvpfn (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
</ul>
