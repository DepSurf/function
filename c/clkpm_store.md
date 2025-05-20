# Function: <code>clkpm_store</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8159aa00)
Location: drivers/pci/pcie/aspm.c:1288
Inline: False
```
**Symbols:**

```
ffffffff8159aa00-ffffffff8159ab0f: clkpm_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81639900)
Location: drivers/pci/pcie/aspm.c:1280
Inline: False
```
**Symbols:**

```
ffffffff81639900-ffffffff816399ec: clkpm_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff816607b0)
Location: drivers/pci/pcie/aspm.c:1272
Inline: False
```
**Symbols:**

```
ffffffff816607b0-ffffffff8166089c: clkpm_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff81642c90)
Location: drivers/pci/pcie/aspm.c:1272
Inline: False
```
**Symbols:**

```
ffffffff81642c90-ffffffff81642d78: clkpm_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1283
Inline: False
```
**Symbols:**

```
ffffffff816b39d0-ffffffff816b3ac5: clkpm_store (STB_LOCAL)
ffffffff81ce5cd7-ffffffff81ce5cec: clkpm_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1319
Inline: False
```
**Symbols:**

```
ffffffff817d7960-ffffffff817d7ab0: clkpm_store (STB_LOCAL)
ffffffff81eac781-ffffffff81eac796: clkpm_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1281
Inline: False
```
**Symbols:**

```
ffffffff818f8f90-ffffffff818f90e0: clkpm_store (STB_LOCAL)
ffffffff8208f53c-ffffffff8208f551: clkpm_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1298
Inline: False
```
**Symbols:**

```
ffffffff8193c320-ffffffff8193c46a: clkpm_store (STB_LOCAL)
ffffffff8210f8e8-ffffffff8210f8fc: clkpm_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aspm.c (0)
Location: drivers/pci/pcie/aspm.c:1355
Inline: False
```
**Symbols:**

```
ffffffff81986190-ffffffff819862da: clkpm_store (STB_LOCAL)
ffffffff821ed57e-ffffffff821ed592: clkpm_store.cold (STB_LOCAL)
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
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffff800010702398)
Location: drivers/pci/pcie/aspm.c:1288
Inline: False
```
**Symbols:**

```
ffff800010702398-ffff8000107024b4: clkpm_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (c0899e5c)
Location: drivers/pci/pcie/aspm.c:1288
Inline: False
```
**Symbols:**

```
c0899e5c-c0899f78: clkpm_store (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffe0004d1034)
Location: drivers/pci/pcie/aspm.c:1288
Inline: False
```
**Symbols:**

```
ffffffe0004d1034-ffffffe0004d1122: clkpm_store (STB_LOCAL)
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
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158e890)
Location: drivers/pci/pcie/aspm.c:1288
Inline: False
```
**Symbols:**

```
ffffffff8158e890-ffffffff8158e99f: clkpm_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8157d3d0)
Location: drivers/pci/pcie/aspm.c:1288
Inline: False
```
**Symbols:**

```
ffffffff8157d3d0-ffffffff8157d4df: clkpm_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff8158e750)
Location: drivers/pci/pcie/aspm.c:1288
Inline: False
```
**Symbols:**

```
ffffffff8158e750-ffffffff8158e85f: clkpm_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t clkpm_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aspm.c (ffffffff815a8c00)
Location: drivers/pci/pcie/aspm.c:1288
Inline: False
```
**Symbols:**

```
ffffffff815a8c00-ffffffff815a8d0f: clkpm_store (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
