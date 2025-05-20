# Function: <code>region_badblocks_show</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81630cb0)
Location: drivers/nvdimm/region_devs.c:512
Inline: False
```
**Symbols:**

```
ffffffff81630cb0-ffffffff81630d03: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81699720)
Location: drivers/nvdimm/region_devs.c:512
Inline: False
```
**Symbols:**

```
ffffffff81699720-ffffffff81699773: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d59c0)
Location: drivers/nvdimm/region_devs.c:544
Inline: False
```
**Symbols:**

```
ffffffff816d59c0-ffffffff816d5a05: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f7720)
Location: drivers/nvdimm/region_devs.c:564
Inline: False
```
**Symbols:**

```
ffffffff816f7720-ffffffff816f778e: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:562
Inline: False
```
**Symbols:**

```
ffffffff81730ed0-ffffffff81730f3b: region_badblocks_show (STB_LOCAL)
ffffffff817329b1-ffffffff817329bb: region_badblocks_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81754fc0)
Location: drivers/nvdimm/region_devs.c:562
Inline: False
```
**Symbols:**

```
ffffffff81754fc0-ffffffff8175502e: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81813de0)
Location: drivers/nvdimm/region_devs.c:584
Inline: False
```
**Symbols:**

```
ffffffff81813de0-ffffffff81813e4b: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81822fd0)
Location: drivers/nvdimm/region_devs.c:584
Inline: False
```
**Symbols:**

```
ffffffff81822fd0-ffffffff8182303b: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81806130)
Location: drivers/nvdimm/region_devs.c:591
Inline: False
```
**Symbols:**

```
ffffffff81806130-ffffffff8180619b: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81890420)
Location: drivers/nvdimm/region_devs.c:591
Inline: False
```
**Symbols:**

```
ffffffff81890420-ffffffff8189048b: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819da100)
Location: drivers/nvdimm/region_devs.c:546
Inline: False
```
**Symbols:**

```
ffffffff819da100-ffffffff819da175: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b553c0)
Location: drivers/nvdimm/region_devs.c:591
Inline: False
```
**Symbols:**

```
ffffffff81b553c0-ffffffff81b55435: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81ba8910)
Location: drivers/nvdimm/region_devs.c:591
Inline: False
```
**Symbols:**

```
ffffffff81ba8910-ffffffff81ba8985: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bfcab0)
Location: drivers/nvdimm/region_devs.c:592
Inline: False
```
**Symbols:**

```
ffffffff81bfcab0-ffffffff81bfcb25: region_badblocks_show (STB_LOCAL)
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
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff800010956048)
Location: drivers/nvdimm/region_devs.c:562
Inline: False
```
**Symbols:**

```
ffff800010956048-ffff8000109560d4: region_badblocks_show (STB_LOCAL)
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
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a03ce0)
Location: drivers/nvdimm/region_devs.c:562
Inline: False
```
**Symbols:**

```
c000000000a03ce0-c000000000a03d88: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c548c)
Location: drivers/nvdimm/region_devs.c:562
Inline: False
```
**Symbols:**

```
ffffffe0005c548c-ffffffe0005c5504: region_badblocks_show (STB_LOCAL)
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
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817096b0)
Location: drivers/nvdimm/region_devs.c:562
Inline: False
```
**Symbols:**

```
ffffffff817096b0-ffffffff8170971e: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816dd130)
Location: drivers/nvdimm/region_devs.c:562
Inline: False
```
**Symbols:**

```
ffffffff816dd130-ffffffff816dd19e: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81748480)
Location: drivers/nvdimm/region_devs.c:562
Inline: False
```
**Symbols:**

```
ffffffff81748480-ffffffff817484ee: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t region_badblocks_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81763900)
Location: drivers/nvdimm/region_devs.c:562
Inline: False
```
**Symbols:**

```
ffffffff81763900-ffffffff8176396e: region_badblocks_show (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
