# Function: <code>nsl_validate_type_guid</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool nsl_validate_type_guid(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label, guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8189a410)
Location: drivers/nvdimm/label.c:782
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff8189a410-ffffffff8189a468: nsl_validate_type_guid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool nsl_validate_type_guid(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label, guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:826
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff81ed42fb-ffffffff81ed434d: nsl_validate_type_guid.cold (STB_LOCAL)
ffffffff819e3a60-ffffffff819e3afc: nsl_validate_type_guid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool nsl_validate_type_guid(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label, guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:826
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff8209b396-ffffffff8209b3e8: nsl_validate_type_guid.cold (STB_LOCAL)
ffffffff81b5f6c0-ffffffff81b5f75c: nsl_validate_type_guid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool nsl_validate_type_guid(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label, guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:826
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff8211c265-ffffffff8211c2b7: nsl_validate_type_guid.cold (STB_LOCAL)
ffffffff81bb2c50-ffffffff81bb2cec: nsl_validate_type_guid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool nsl_validate_type_guid(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label, guid_t *guid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:826
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:has_uuid_at_pos
```
**Symbols:**

```
ffffffff821fa0ec-ffffffff821fa13e: nsl_validate_type_guid.cold (STB_LOCAL)
ffffffff81c07140-ffffffff81c071dc: nsl_validate_type_guid (STB_GLOBAL)
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
