# Function: <code>__nvdimm_create</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5840)
Location: drivers/nvdimm/dimm_devs.c:534
Inline: False
```
**Symbols:**

```
ffffffff816f5840-ffffffff816f5a0f: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8172f010)
Location: drivers/nvdimm/dimm_devs.c:531
Inline: False
```
**Symbols:**

```
ffffffff8172f010-ffffffff8172f218: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff817533b0)
Location: drivers/nvdimm/dimm_devs.c:459
Inline: False
```
**Symbols:**

```
ffffffff817533b0-ffffffff81753648: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81811f50)
Location: drivers/nvdimm/dimm_devs.c:466
Inline: False
```
**Symbols:**

```
ffffffff81811f50-ffffffff818121e8: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops, const struct nvdimm_fw_ops *fw_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81820b20)
Location: drivers/nvdimm/dimm_devs.c:594
Inline: False
```
**Symbols:**

```
ffffffff81820b20-ffffffff81820dc3: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops, const struct nvdimm_fw_ops *fw_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81803e20)
Location: drivers/nvdimm/dimm_devs.c:594
Inline: False
```
**Symbols:**

```
ffffffff81803e20-ffffffff818040c3: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops, const struct nvdimm_fw_ops *fw_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:594
Inline: False
```
**Symbols:**

```
ffffffff81d0aeda-ffffffff81d0af20: __nvdimm_create.cold (STB_LOCAL)
ffffffff8188ead0-ffffffff8188eda0: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops, const struct nvdimm_fw_ops *fw_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:575
Inline: False
```
**Symbols:**

```
ffffffff81ed338c-ffffffff81ed33b6: __nvdimm_create.cold (STB_LOCAL)
ffffffff819d7fa0-ffffffff819d8273: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops, const struct nvdimm_fw_ops *fw_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:582
Inline: False
```
**Symbols:**

```
ffffffff8209a675-ffffffff8209a69f: __nvdimm_create.cold (STB_LOCAL)
ffffffff81b52e50-ffffffff81b53128: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops, const struct nvdimm_fw_ops *fw_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:582
Inline: False
```
**Symbols:**

```
ffffffff8211b74d-ffffffff8211b777: __nvdimm_create.cold (STB_LOCAL)
ffffffff81ba62f0-ffffffff81ba65c7: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops, const struct nvdimm_fw_ops *fw_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:584
Inline: False
```
**Symbols:**

```
ffffffff821f95d4-ffffffff821f95fe: __nvdimm_create.cold (STB_LOCAL)
ffffffff81bfa570-ffffffff81bfa876: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff800010953cd0)
Location: drivers/nvdimm/dimm_devs.c:459
Inline: False
```
**Symbols:**

```
ffff800010953cd0-ffff800010953f4c: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a010b0)
Location: drivers/nvdimm/dimm_devs.c:459
Inline: False
```
**Symbols:**

```
c000000000a010b0-c000000000a01410: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c35a2)
Location: drivers/nvdimm/dimm_devs.c:459
Inline: False
```
**Symbols:**

```
ffffffe0005c35a2-ffffffe0005c37d0: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81707aa0)
Location: drivers/nvdimm/dimm_devs.c:459
Inline: False
```
**Symbols:**

```
ffffffff81707aa0-ffffffff81707d38: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816db520)
Location: drivers/nvdimm/dimm_devs.c:459
Inline: False
Direct callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_register_dimms
```
**Symbols:**

```
ffffffff816db520-ffffffff816db7b8: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81746870)
Location: drivers/nvdimm/dimm_devs.c:459
Inline: False
```
**Symbols:**

```
ffffffff81746870-ffffffff81746b08: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nvdimm *__nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq, const char *dimm_id, const struct nvdimm_security_ops *sec_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81761cb0)
Location: drivers/nvdimm/dimm_devs.c:459
Inline: False
```
**Symbols:**

```
ffffffff81761cb0-ffffffff81761f48: __nvdimm_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct nvdimm_fw_ops *fw_ops</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
