# Function: <code>pci_dev_rom_attr_is_visible</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
umode_t pci_dev_rom_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81637c40)
Location: drivers/pci/pci-sysfs.c:1316
Inline: False
```
**Symbols:**

```
ffffffff81637c40-ffffffff81637c79: pci_dev_rom_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
umode_t pci_dev_rom_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816a7ed0)
Location: drivers/pci/pci-sysfs.c:1316
Inline: False
```
**Symbols:**

```
ffffffff816a7ed0-ffffffff816a7f03: pci_dev_rom_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
umode_t pci_dev_rom_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff817ca9e0)
Location: drivers/pci/pci-sysfs.c:1311
Inline: False
```
**Symbols:**

```
ffffffff817ca9e0-ffffffff817caa1a: pci_dev_rom_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
umode_t pci_dev_rom_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff818e8500)
Location: drivers/pci/pci-sysfs.c:1324
Inline: False
```
**Symbols:**

```
ffffffff818e8500-ffffffff818e853a: pci_dev_rom_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
umode_t pci_dev_rom_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8192bb10)
Location: drivers/pci/pci-sysfs.c:1324
Inline: False
```
**Symbols:**

```
ffffffff8192bb10-ffffffff8192bb4a: pci_dev_rom_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
umode_t pci_dev_rom_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81974460)
Location: drivers/pci/pci-sysfs.c:1348
Inline: False
```
**Symbols:**

```
ffffffff81974460-ffffffff8197449a: pci_dev_rom_attr_is_visible (STB_LOCAL)
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
