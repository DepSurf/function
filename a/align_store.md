# Function: <code>align_store</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815f8b20)
Location: drivers/nvdimm/pfn_devs.c:134
Inline: False
```
**Symbols:**

```
ffffffff815f8b20-ffffffff815f8c4b: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81626da0)
Location: drivers/nvdimm/pfn_devs.c:134
Inline: False
```
**Symbols:**

```
ffffffff81626da0-ffffffff81626ecb: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8163ba40)
Location: drivers/nvdimm/pfn_devs.c:134
Inline: False
```
**Symbols:**

```
ffffffff8163ba40-ffffffff8163bb76: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816a3f20)
Location: drivers/nvdimm/pfn_devs.c:137
Inline: False
```
**Symbols:**

```
ffffffff816a3f20-ffffffff816a400d: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e00b0)
Location: drivers/nvdimm/pfn_devs.c:137
Inline: False
```
**Symbols:**

```
ffffffff816e00b0-ffffffff816e01db: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81702470)
Location: drivers/nvdimm/pfn_devs.c:137
Inline: False
```
**Symbols:**

```
ffffffff81702470-ffffffff8170259b: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8173c350)
Location: drivers/nvdimm/pfn_devs.c:129
Inline: False
```
**Symbols:**

```
ffffffff8173c350-ffffffff8173c433: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81760000)
Location: drivers/nvdimm/pfn_devs.c:131
Inline: False
```
**Symbols:**

```
ffffffff81760000-ffffffff81760122: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818150b0)
Location: drivers/nvdimm/region_devs.c:544
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8181fb00)
Location: drivers/nvdimm/pfn_devs.c:120
Inline: False
```
**Symbols:**

```
ffffffff818150b0-ffffffff818151d3: align_store (STB_LOCAL)
ffffffff8181fb00-ffffffff8181fc22: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818242a0)
Location: drivers/nvdimm/region_devs.c:544
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182ea30)
Location: drivers/nvdimm/pfn_devs.c:120
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81832f40)
Location: drivers/dax/bus.c:1124
Inline: False
```
**Symbols:**

```
ffffffff818242a0-ffffffff818243c3: align_store (STB_LOCAL)
ffffffff8182ea30-ffffffff8182eb52: align_store (STB_LOCAL)
ffffffff81832f40-ffffffff818330c8: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818074d0)
Location: drivers/nvdimm/region_devs.c:551
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81811d00)
Location: drivers/nvdimm/pfn_devs.c:120
Inline: False
```
```
In drivers/dax/bus.c (ffffffff818160c0)
Location: drivers/dax/bus.c:1125
Inline: False
```
**Symbols:**

```
ffffffff818074d0-ffffffff818075f3: align_store (STB_LOCAL)
ffffffff81811d00-ffffffff81811e22: align_store (STB_LOCAL)
ffffffff818160c0-ffffffff818162b4: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81890590)
Location: drivers/nvdimm/region_devs.c:551
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189c330)
Location: drivers/nvdimm/pfn_devs.c:120
Inline: False
```
```
In drivers/dax/bus.c (ffffffff818a06f0)
Location: drivers/dax/bus.c:1123
Inline: False
```
**Symbols:**

```
ffffffff81890590-ffffffff818906b3: align_store (STB_LOCAL)
ffffffff8189c330-ffffffff8189c44f: align_store (STB_LOCAL)
ffffffff818a06f0-ffffffff818a08e1: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819da4c0)
Location: drivers/nvdimm/region_devs.c:506
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff819e5bc0)
Location: drivers/nvdimm/pfn_devs.c:119
Inline: False
```
```
In drivers/dax/bus.c (ffffffff819e9d20)
Location: drivers/dax/bus.c:1153
Inline: False
```
**Symbols:**

```
ffffffff819da4c0-ffffffff819da604: align_store (STB_LOCAL)
ffffffff819e5bc0-ffffffff819e5cf1: align_store (STB_LOCAL)
ffffffff819e9d20-ffffffff819e9f16: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b55830)
Location: drivers/nvdimm/region_devs.c:553
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81b61b00)
Location: drivers/nvdimm/pfn_devs.c:121
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81b66730)
Location: drivers/dax/bus.c:1153
Inline: False
```
**Symbols:**

```
ffffffff81b55830-ffffffff81b5596d: align_store (STB_LOCAL)
ffffffff81b61b00-ffffffff81b61c31: align_store (STB_LOCAL)
ffffffff81b66730-ffffffff81b66926: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81ba8d80)
Location: drivers/nvdimm/region_devs.c:553
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb5100)
Location: drivers/nvdimm/pfn_devs.c:121
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81bb9b20)
Location: drivers/dax/bus.c:1183
Inline: False
```
**Symbols:**

```
ffffffff81ba8d80-ffffffff81ba8ebd: align_store (STB_LOCAL)
ffffffff81bb5100-ffffffff81bb5231: align_store (STB_LOCAL)
ffffffff81bb9b20-ffffffff81bb9d16: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bfd0c0)
Location: drivers/nvdimm/region_devs.c:554
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c09680)
Location: drivers/nvdimm/pfn_devs.c:121
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81c0e180)
Location: drivers/dax/bus.c:1184
Inline: False
```
**Symbols:**

```
ffffffff81bfd0c0-ffffffff81bfd1fd: align_store (STB_LOCAL)
ffffffff81c09680-ffffffff81c097b1: align_store (STB_LOCAL)
ffffffff81c0e180-ffffffff81c0e376: align_store (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (c000000000a16740)
Location: drivers/nvdimm/pfn_devs.c:131
Inline: False
```
**Symbols:**

```
c000000000a16740-c000000000a16908: align_store (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff817146f0)
Location: drivers/nvdimm/pfn_devs.c:131
Inline: False
```
**Symbols:**

```
ffffffff817146f0-ffffffff81714812: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e8170)
Location: drivers/nvdimm/pfn_devs.c:131
Inline: False
```
**Symbols:**

```
ffffffff816e8170-ffffffff816e8292: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff817534c0)
Location: drivers/nvdimm/pfn_devs.c:131
Inline: False
```
**Symbols:**

```
ffffffff817534c0-ffffffff817535e2: align_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t align_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8176e930)
Location: drivers/nvdimm/pfn_devs.c:131
Inline: False
```
**Symbols:**

```
ffffffff8176e930-ffffffff8176ea52: align_store (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
