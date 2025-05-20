# Function: <code>nvdimm_firmware_visible</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
umode_t nvdimm_firmware_visible(struct kobject *kobj, struct attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81820aa0)
Location: drivers/nvdimm/dimm_devs.c:547
Inline: False
```
**Symbols:**

```
ffffffff81820aa0-ffffffff81820b1a: nvdimm_firmware_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
umode_t nvdimm_firmware_visible(struct kobject *kobj, struct attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81803da0)
Location: drivers/nvdimm/dimm_devs.c:547
Inline: False
```
**Symbols:**

```
ffffffff81803da0-ffffffff81803e1a: nvdimm_firmware_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
umode_t nvdimm_firmware_visible(struct kobject *kobj, struct attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8188dce0)
Location: drivers/nvdimm/dimm_devs.c:547
Inline: False
```
**Symbols:**

```
ffffffff8188dce0-ffffffff8188dd5a: nvdimm_firmware_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
umode_t nvdimm_firmware_visible(struct kobject *kobj, struct attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7270)
Location: drivers/nvdimm/dimm_devs.c:526
Inline: False
```
**Symbols:**

```
ffffffff819d7270-ffffffff819d72fa: nvdimm_firmware_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
umode_t nvdimm_firmware_visible(struct kobject *kobj, struct attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52010)
Location: drivers/nvdimm/dimm_devs.c:533
Inline: False
```
**Symbols:**

```
ffffffff81b52010-ffffffff81b5209a: nvdimm_firmware_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
umode_t nvdimm_firmware_visible(struct kobject *kobj, struct attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba54f0)
Location: drivers/nvdimm/dimm_devs.c:533
Inline: False
```
**Symbols:**

```
ffffffff81ba54f0-ffffffff81ba557a: nvdimm_firmware_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
umode_t nvdimm_firmware_visible(struct kobject *kobj, struct attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81bf9770)
Location: drivers/nvdimm/dimm_devs.c:535
Inline: False
```
**Symbols:**

```
ffffffff81bf9770-ffffffff81bf97fa: nvdimm_firmware_visible (STB_LOCAL)
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
