# Function: <code>get_set_conduit_method</code>

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
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int get_set_conduit_method(struct device_node *np);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/psci/psci.c (ffff800010b5a1f8)
Location: drivers/firmware/psci/psci.c:231
Inline: False
Direct callers:
  - drivers/firmware/psci/psci.c:psci_0_1_init
  - drivers/firmware/psci/psci.c:psci_0_2_init
```
```
In drivers/firmware/xilinx/zynqmp.c (ffff800010b639c8)
Location: drivers/firmware/xilinx/zynqmp.c:255
Inline: True
Inline callers:
  - drivers/firmware/xilinx/zynqmp.c:zynqmp_firmware_probe
```
**Symbols:**

```
ffff800010b5a1f8-ffff800010b5a2ec: get_set_conduit_method (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_set_conduit_method(struct device_node *np);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/psci/psci.c (c0c3b2a4)
Location: drivers/firmware/psci/psci.c:231
Inline: False
Direct callers:
  - drivers/firmware/psci/psci.c:psci_0_1_init
  - drivers/firmware/psci/psci.c:psci_0_2_init
```
**Symbols:**

```
c0c3b2a4-c0c3b3bc: get_set_conduit_method (STB_LOCAL)
```
</details>
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
