# Function: <code>get_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff814424b9)
Location: drivers/pci/slot.c:208
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff8148e364)
Location: drivers/pci/slot.c:208
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff814afb54)
Location: drivers/pci/slot.c:208
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff814ba1c9)
Location: drivers/pci/slot.c:208
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff814fa5c9)
Location: drivers/pci/slot.c:208
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff8152b079)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: drivers/pci/hotplug/shpchp.h:208
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff81540dc9)
Location: drivers/pci/slot.c:208
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81553135)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff815707d9)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81583065)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff815918b9)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815a4a45)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff8163fb68)
Location: drivers/pci/slot.c:173
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8164d695)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff81665f98)
Location: drivers/pci/slot.c:173
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81671855)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff81648538)
Location: drivers/pci/slot.c:173
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81653d65)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff816b9f38)
Location: drivers/pci/slot.c:173
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff816c5b65)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff817de878)
Location: drivers/pci/slot.c:174
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff817eb9f5)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff819014e8)
Location: drivers/pci/slot.c:174
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81911f45)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff81944aa8)
Location: drivers/pci/slot.c:174
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff819555d5)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff8198dda8)
Location: drivers/pci/slot.c:174
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8199ea95)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffff8000106f7580)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d6e0)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (c089164c)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (c0000000008764b4)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffe0004c954c)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004d9e0e)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff81585749)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598255)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff81574519)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815873e5)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff81585609)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598795)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/slot.c (ffffffff8159fab9)
Location: drivers/pci/slot.c:209
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815b2bd5)
Location: drivers/pci/hotplug/shpchp.h:210
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:get_adapter_status
  - drivers/pci/hotplug/shpchp_core.c:get_latch_status
  - drivers/pci/hotplug/shpchp_core.c:get_attention_status
  - drivers/pci/hotplug/shpchp_core.c:get_power_status
  - drivers/pci/hotplug/shpchp_core.c:disable_slot
  - drivers/pci/hotplug/shpchp_core.c:enable_slot
  - drivers/pci/hotplug/shpchp_core.c:set_attention_status
```
</details>
</li>
</ul>

## Differences
