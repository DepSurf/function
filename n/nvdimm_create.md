# Function: <code>nvdimm_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nvdimm *nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int *dsm_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff815989b0)
Location: drivers/nvdimm/dimm_devs.c:341
Inline: False
```
**Symbols:**

```
ffffffff815989b0-ffffffff81598aae: nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct nvdimm *nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff815ee480)
Location: drivers/nvdimm/dimm_devs.c:347
Inline: False
```
**Symbols:**

```
ffffffff815ee480-ffffffff815ee589: nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct nvdimm *nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8161b4c0)
Location: drivers/nvdimm/dimm_devs.c:362
Inline: False
```
**Symbols:**

```
ffffffff8161b4c0-ffffffff8161b5c9: nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nvdimm *nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8162f570)
Location: drivers/nvdimm/dimm_devs.c:378
Inline: False
```
**Symbols:**

```
ffffffff8162f570-ffffffff8162f675: nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct nvdimm *nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81697d50)
Location: drivers/nvdimm/dimm_devs.c:397
Inline: False
```
**Symbols:**

```
ffffffff81697d50-ffffffff81697e55: nvdimm_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nvdimm *nvdimm_create(struct nvdimm_bus *nvdimm_bus, void *provider_data, const struct attribute_group **groups, long unsigned int flags, long unsigned int cmd_mask, int num_flush, struct resource *flush_wpq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816d3ea0)
Location: drivers/nvdimm/dimm_devs.c:398
Inline: False
```
**Symbols:**

```
ffffffff816d3ea0-ffffffff816d3fa5: nvdimm_create (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int cmd_mask</code>
</li>
<li>
<b>Param added. </b>
<code>int num_flush</code>
</li>
<li>
<b>Param added. </b>
<code>struct resource *flush_wpq</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *dsm_mask</code>
</li>
</ul>
</details>
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
</ul>
