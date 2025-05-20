# Function: <code>pci_dev_config_attr_is_visible</code>

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
umode_t pci_dev_config_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81637bc0)
Location: drivers/pci/pci-sysfs.c:818
Inline: False
```
**Symbols:**

```
ffffffff81637bc0-ffffffff81637bf3: pci_dev_config_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
umode_t pci_dev_config_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816a7e50)
Location: drivers/pci/pci-sysfs.c:818
Inline: False
```
**Symbols:**

```
ffffffff816a7e50-ffffffff816a7e83: pci_dev_config_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
umode_t pci_dev_config_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff817ca950)
Location: drivers/pci/pci-sysfs.c:813
Inline: False
```
**Symbols:**

```
ffffffff817ca950-ffffffff817ca98d: pci_dev_config_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
umode_t pci_dev_config_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff818e8450)
Location: drivers/pci/pci-sysfs.c:821
Inline: False
```
**Symbols:**

```
ffffffff818e8450-ffffffff818e848d: pci_dev_config_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
umode_t pci_dev_config_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8192ba60)
Location: drivers/pci/pci-sysfs.c:821
Inline: False
```
**Symbols:**

```
ffffffff8192ba60-ffffffff8192ba9d: pci_dev_config_attr_is_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
umode_t pci_dev_config_attr_is_visible(struct kobject *kobj, struct bin_attribute *a, int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff819743b0)
Location: drivers/pci/pci-sysfs.c:817
Inline: False
```
**Symbols:**

```
ffffffff819743b0-ffffffff819743ed: pci_dev_config_attr_is_visible (STB_LOCAL)
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
