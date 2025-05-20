# Function: <code>qi_submit_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81534970)
Location: drivers/iommu/dmar.c:1192
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/intel-svm.c:intel_mm_release
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel_irq_remapping.c:modify_irte
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81534970-ffffffff81534d47: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81589230)
Location: drivers/iommu/dmar.c:1208
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/intel_irq_remapping.c:modify_irte
```
**Symbols:**

```
ffffffff81589230-ffffffff8158959b: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b68f0)
Location: drivers/iommu/dmar.c:1209
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/intel_irq_remapping.c:modify_irte
```
**Symbols:**

```
ffffffff815b68f0-ffffffff815b6c5b: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cc750)
Location: drivers/iommu/dmar.c:1218
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/intel_irq_remapping.c:modify_irte
```
**Symbols:**

```
ffffffff815cc750-ffffffff815ccaab: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81633540)
Location: drivers/iommu/dmar.c:1221
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
  - drivers/iommu/intel_irq_remapping.c:modify_irte
```
**Symbols:**

```
ffffffff81633540-ffffffff8163389b: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1221
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel-svm.c:intel_svm_unbind_mm
  - drivers/iommu/intel-svm.c:intel_svm_bind_mm
  - drivers/iommu/intel-svm.c:intel_mm_release
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8166f471-ffffffff8166f4cf: qi_submit_sync.cold.28 (STB_LOCAL)
ffffffff8166e6f0-ffffffff8166ea00: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1228
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8168d9d1-ffffffff8168da36: qi_submit_sync.cold.27 (STB_LOCAL)
ffffffff8168cb20-ffffffff8168cf09: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1217
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff816c5401-ffffffff816c5462: qi_submit_sync.cold (STB_LOCAL)
ffffffff816c4560-ffffffff816c493b: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1227
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff816e8338-ffffffff816e8399: qi_submit_sync.cold (STB_LOCAL)
ffffffff816e74b0-ffffffff816e788b: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int qi_submit_sync(struct intel_iommu *iommu, struct qi_desc *desc, unsigned int count, long unsigned int options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179dd30)
Location: drivers/iommu/intel/dmar.c:1235
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_flush_pasid_cache
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_context
  - drivers/iommu/intel/dmar.c:qi_global_iec
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8179dd30-ffffffff8179e0e4: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int qi_submit_sync(struct intel_iommu *iommu, struct qi_desc *desc, unsigned int count, long unsigned int options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff817aba90)
Location: drivers/iommu/intel/dmar.c:1274
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_flush_pasid_cache
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_context
  - drivers/iommu/intel/dmar.c:qi_global_iec
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff817aba90-ffffffff817abe44: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int qi_submit_sync(struct intel_iommu *iommu, struct qi_desc *desc, unsigned int count, long unsigned int options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8178e8f0)
Location: drivers/iommu/intel/dmar.c:1341
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_flush_pasid_cache
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_context
  - drivers/iommu/intel/dmar.c:qi_global_iec
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8178e8f0-ffffffff8178ed15: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int qi_submit_sync(struct intel_iommu *iommu, struct qi_desc *desc, unsigned int count, long unsigned int options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81816180)
Location: drivers/iommu/intel/dmar.c:1340
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_flush_pasid_cache
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_context
  - drivers/iommu/intel/dmar.c:qi_global_iec
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81816180-ffffffff818165a5: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int qi_submit_sync(struct intel_iommu *iommu, struct qi_desc *desc, unsigned int count, long unsigned int options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81957060)
Location: drivers/iommu/intel/dmar.c:1336
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_flush_pasid_cache
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_context
  - drivers/iommu/intel/dmar.c:qi_global_iec
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81957060-ffffffff81957501: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int qi_submit_sync(struct intel_iommu *iommu, struct qi_desc *desc, unsigned int count, long unsigned int options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abdf60)
Location: drivers/iommu/intel/dmar.c:1325
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_flush_pasid_cache
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_context
  - drivers/iommu/intel/dmar.c:qi_global_iec
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81abdf60-ffffffff81abe40e: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int qi_submit_sync(struct intel_iommu *iommu, struct qi_desc *desc, unsigned int count, long unsigned int options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b0a8f0)
Location: drivers/iommu/intel/dmar.c:1346
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_flush_pasid_cache
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_context
  - drivers/iommu/intel/dmar.c:qi_global_iec
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_svm_drain_prq
  - drivers/iommu/intel/irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff81b0a8f0-ffffffff81b0ad9e: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int qi_submit_sync(struct intel_iommu *iommu, struct qi_desc *desc, unsigned int count, long unsigned int options);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5e940)
Location: drivers/iommu/intel/dmar.c:1346
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:qi_flush_pasid_cache
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb_pasid
  - drivers/iommu/intel/dmar.c:qi_flush_piotlb
  - drivers/iommu/intel/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_iotlb
  - drivers/iommu/intel/dmar.c:qi_flush_context
  - drivers/iommu/intel/dmar.c:qi_global_iec
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_dirty_tracking
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/svm.c:intel_svm_page_response
  - drivers/iommu/intel/svm.c:intel_drain_pasid_prq
```
**Symbols:**

```
ffffffff81b5e940-ffffffff81b5edee: qi_submit_sync (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1227
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff816ade18-ffffffff816ade79: qi_submit_sync.cold (STB_LOCAL)
ffffffff816acf90-ffffffff816ad36b: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1227
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff8168b778-ffffffff8168b7d9: qi_submit_sync.cold (STB_LOCAL)
ffffffff8168a8f0-ffffffff8168accb: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1227
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff816dbff8-ffffffff816dc059: qi_submit_sync.cold (STB_LOCAL)
ffffffff816db170-ffffffff816db54b: qi_submit_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int qi_submit_sync(struct qi_desc *desc, struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1227
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:qi_flush_dev_iotlb
  - drivers/iommu/dmar.c:qi_flush_iotlb
  - drivers/iommu/dmar.c:qi_flush_context
  - drivers/iommu/dmar.c:qi_global_iec
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-svm.c:prq_event_thread
  - drivers/iommu/intel_irq_remapping.c:intel_free_irq_resources
```
**Symbols:**

```
ffffffff816f65c8-ffffffff816f6629: qi_submit_sync.cold (STB_LOCAL)
ffffffff816f5740-ffffffff816f5b1c: qi_submit_sync (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int count</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int options</code>
</li>
<li>
<b>Param reordered. </b>
<code>desc, iommu</code> ➡️ <code>iommu, desc, count, options</code>
</li>
</ul>
</details>
</li>
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
<b>Arch</b>
<ul>
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
