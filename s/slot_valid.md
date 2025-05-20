# Function: <code>slot_valid</code>

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
In drivers/nvdimm/label.c (ffffffff8159f648)
Location: drivers/nvdimm/label.c:271
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_active
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
In drivers/nvdimm/label.c (ffffffff815f58e0)
Location: drivers/nvdimm/label.c:271
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
In drivers/nvdimm/label.c (ffffffff816235a0)
Location: drivers/nvdimm/label.c:271
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81637240)
Location: drivers/nvdimm/label.c:336
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff81637240-ffffffff816372f1: slot_valid.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8169fba0)
Location: drivers/nvdimm/label.c:338
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff8169fba0-ffffffff8169fc51: slot_valid.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dbeb0)
Location: drivers/nvdimm/label.c:347
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff816dbeb0-ffffffff816dbf54: slot_valid.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816fdea0)
Location: drivers/nvdimm/label.c:355
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff816fdea0-ffffffff816fdf44: slot_valid.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81737ba0)
Location: drivers/nvdimm/label.c:349
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff81737ba0-ffffffff81737c42: slot_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175cb06)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff8175b890-ffffffff8175b913: slot_valid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181c3f0)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff8181b0c0-ffffffff8181b144: slot_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182b440)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff8182a120-ffffffff8182a1a4: slot_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180e756)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff8180d400-ffffffff8180d484: slot_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81898d45)
Location: drivers/nvdimm/label.c:376
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff81897970-ffffffff81897a06: slot_valid.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool slot_valid(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label, u32 slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff819e1794)
Location: drivers/nvdimm/label.c:384
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff819e1760-ffffffff819e183d: slot_valid (STB_LOCAL)
ffffffff81ed3cbf-ffffffff81ed3d8b: slot_valid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool slot_valid(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label, u32 slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81b5d3bd)
Location: drivers/nvdimm/label.c:384
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff81b5d370-ffffffff81b5d468: slot_valid (STB_LOCAL)
ffffffff8209ae0b-ffffffff8209aed7: slot_valid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool slot_valid(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label, u32 slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81bb097d)
Location: drivers/nvdimm/label.c:384
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff81bb0930-ffffffff81bb0a28: slot_valid (STB_LOCAL)
ffffffff8211bd1f-ffffffff8211bdeb: slot_valid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool slot_valid(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label, u32 slot);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81c04e3d)
Location: drivers/nvdimm/label.c:384
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff81c04df0-ffffffff81c04ee8: slot_valid (STB_LOCAL)
ffffffff821f9ba6-ffffffff821f9c72: slot_valid.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095e28c)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffff80001095cf50-ffff80001095d00c: slot_valid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a10130)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
c000000000a0e6a0-c000000000a0e7a8: slot_valid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cc230)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffe0005cb194-ffffffe0005cb21e: slot_valid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff817111f6)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff8170ff80-ffffffff81710003: slot_valid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e4c76)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff816e3a00-ffffffff816e3a83: slot_valid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8174ffc6)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff8174ed50-ffffffff8174edd3: slot_valid.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176b446)
Location: drivers/nvdimm/label.c:349
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/label.c:nd_label_active
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
**Symbols:**

```
ffffffff8176a1d0-ffffffff8176a253: slot_valid.isra.0.part.0 (STB_LOCAL)
```
</details>
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
