# Function: <code>to_slot</code>

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
In drivers/nvdimm/label.c (ffffffff8159ea66)
Location: drivers/nvdimm/label.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_label
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
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
In drivers/nvdimm/label.c (ffffffff815f6824)
Location: drivers/nvdimm/label.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:del_label
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
In drivers/nvdimm/label.c (ffffffff81624813)
Location: drivers/nvdimm/label.c:210
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
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
In drivers/nvdimm/label.c (ffffffff81639566)
Location: drivers/nvdimm/label.c:260
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
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
In drivers/nvdimm/label.c (ffffffff816a1c36)
Location: drivers/nvdimm/label.c:262
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dcf41)
Location: drivers/nvdimm/label.c:271
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8154e205)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81556b65)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff816ff291)
Location: drivers/nvdimm/label.c:279
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8157e065)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81586ba5)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff8173902a)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8159faa5)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815a8575)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff8175cd7a)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81648425)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81651215)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff8181c67b)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8166d4d5)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81673c45)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff8182b6cb)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8164fa65)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81656175)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff8180e9eb)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff816c17b5)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff816c8165)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff81898fcb)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:reap_victim
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff817e70a5)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff819e2f5d)
Location: drivers/nvdimm/label.c:281
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8190c0e5)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81b5ebbd)
Location: drivers/nvdimm/label.c:281
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8194f765)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81bb2171)
Location: drivers/nvdimm/label.c:281
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81998b95)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
```
```
In drivers/nvdimm/label.c (ffffffff81c06661)
Location: drivers/nvdimm/label.c:281
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffff800010707fa4)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffff8000107115c4)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffff80001095e664)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (c000000000880828)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (c000000000a10590)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffe0004d5884)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffe0005cc4f8)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815932b5)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159bd85)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff8171146a)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81582445)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8158af15)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff816e4eea)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815937f5)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8159c2c5)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff8175023a)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
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
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff815adc75)
Location: drivers/pci/hotplug/cpci_hotplug.h:66
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_latch_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:get_power_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:enable_slot
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff815b66f5)
Location: drivers/pci/hotplug/acpiphp.h:46
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:get_adapter_status
  - drivers/pci/hotplug/acpiphp_core.c:get_latch_status
  - drivers/pci/hotplug/acpiphp_core.c:get_power_status
  - drivers/pci/hotplug/acpiphp_core.c:disable_slot
  - drivers/pci/hotplug/acpiphp_core.c:enable_slot
```
```
In drivers/nvdimm/label.c (ffffffff8176b6ba)
Location: drivers/nvdimm/label.c:273
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
</details>
</li>
</ul>

## Differences
