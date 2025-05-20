# Function: <code>persistence_domain_show</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81699b40)
Location: drivers/nvdimm/region_devs.c:531
Inline: True
```
**Symbols:**

```
ffffffff81699b40-ffffffff81699bea: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d5dd0)
Location: drivers/nvdimm/region_devs.c:563
Inline: True
```
**Symbols:**

```
ffffffff816d5dd0-ffffffff816d5e7a: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f7af0)
Location: drivers/nvdimm/region_devs.c:590
Inline: True
```
**Symbols:**

```
ffffffff816f7af0-ffffffff816f7b9a: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81731263)
Location: drivers/nvdimm/region_devs.c:588
Inline: True
```
**Symbols:**

```
ffffffff817311f0-ffffffff81731284: persistence_domain_show (STB_LOCAL)
ffffffff81732a04-ffffffff81732a1e: persistence_domain_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81755300)
Location: drivers/nvdimm/region_devs.c:588
Inline: True
```
**Symbols:**

```
ffffffff81755300-ffffffff817553aa: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81814d00)
Location: drivers/nvdimm/region_devs.c:610
Inline: False
```
**Symbols:**

```
ffffffff81814d00-ffffffff81814d90: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818240f0)
Location: drivers/nvdimm/region_devs.c:610
Inline: False
```
**Symbols:**

```
ffffffff818240f0-ffffffff81824180: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81807060)
Location: drivers/nvdimm/region_devs.c:617
Inline: False
```
**Symbols:**

```
ffffffff81807060-ffffffff818070f0: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81890030)
Location: drivers/nvdimm/region_devs.c:617
Inline: False
```
**Symbols:**

```
ffffffff81890030-ffffffff818900c0: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819d9c20)
Location: drivers/nvdimm/region_devs.c:572
Inline: False
```
**Symbols:**

```
ffffffff819d9c20-ffffffff819d9cc3: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b54de0)
Location: drivers/nvdimm/region_devs.c:617
Inline: False
```
**Symbols:**

```
ffffffff81b54de0-ffffffff81b54e83: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81ba8330)
Location: drivers/nvdimm/region_devs.c:617
Inline: False
```
**Symbols:**

```
ffffffff81ba8330-ffffffff81ba83d3: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bfc4d0)
Location: drivers/nvdimm/region_devs.c:618
Inline: False
```
**Symbols:**

```
ffffffff81bfc4d0-ffffffff81bfc573: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff800010956418)
Location: drivers/nvdimm/region_devs.c:588
Inline: True
```
**Symbols:**

```
ffff800010956418-ffff8000109564d4: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a040c0)
Location: drivers/nvdimm/region_devs.c:588
Inline: True
```
**Symbols:**

```
c000000000a040c0-c000000000a041ac: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c578a)
Location: drivers/nvdimm/region_devs.c:588
Inline: True
```
**Symbols:**

```
ffffffe0005c578a-ffffffe0005c587c: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817099f0)
Location: drivers/nvdimm/region_devs.c:588
Inline: True
```
**Symbols:**

```
ffffffff817099f0-ffffffff81709a9a: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816dd470)
Location: drivers/nvdimm/region_devs.c:588
Inline: True
```
**Symbols:**

```
ffffffff816dd470-ffffffff816dd51a: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817487c0)
Location: drivers/nvdimm/region_devs.c:588
Inline: True
```
**Symbols:**

```
ffffffff817487c0-ffffffff8174886a: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t persistence_domain_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81763c40)
Location: drivers/nvdimm/region_devs.c:588
Inline: True
```
**Symbols:**

```
ffffffff81763c40-ffffffff81763cea: persistence_domain_show (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
