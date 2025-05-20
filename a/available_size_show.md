# Function: <code>available_size_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8159aae0)
Location: drivers/nvdimm/region_devs.c:221
Inline: False
```
**Symbols:**

```
ffffffff8159aae0-ffffffff8159ab47: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff815f0ac0)
Location: drivers/nvdimm/region_devs.c:309
Inline: False
```
**Symbols:**

```
ffffffff815f0ac0-ffffffff815f0b27: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8161da80)
Location: drivers/nvdimm/region_devs.c:323
Inline: False
```
**Symbols:**

```
ffffffff8161da80-ffffffff8161dae7: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81631f00)
Location: drivers/nvdimm/region_devs.c:384
Inline: False
```
**Symbols:**

```
ffffffff81631f00-ffffffff81631f67: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8169a860)
Location: drivers/nvdimm/region_devs.c:384
Inline: False
```
**Symbols:**

```
ffffffff8169a860-ffffffff8169a8c7: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d6b10)
Location: drivers/nvdimm/region_devs.c:416
Inline: False
```
**Symbols:**

```
ffffffff816d6b10-ffffffff816d6b77: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f88f0)
Location: drivers/nvdimm/region_devs.c:421
Inline: False
```
**Symbols:**

```
ffffffff816f88f0-ffffffff816f8957: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:415
Inline: False
```
**Symbols:**

```
ffffffff81731fa0-ffffffff81732022: available_size_show (STB_LOCAL)
ffffffff81732ac7-ffffffff81732ad1: available_size_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81756120)
Location: drivers/nvdimm/region_devs.c:415
Inline: False
```
**Symbols:**

```
ffffffff81756120-ffffffff817561a5: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818156a0)
Location: drivers/nvdimm/region_devs.c:389
Inline: False
```
**Symbols:**

```
ffffffff818156a0-ffffffff81815722: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81824890)
Location: drivers/nvdimm/region_devs.c:389
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81833dd0)
Location: drivers/dax/bus.c:258
Inline: False
```
**Symbols:**

```
ffffffff81824890-ffffffff81824912: available_size_show (STB_LOCAL)
ffffffff81833dd0-ffffffff81833e46: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81807c20)
Location: drivers/nvdimm/region_devs.c:389
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81816fc0)
Location: drivers/dax/bus.c:259
Inline: False
```
**Symbols:**

```
ffffffff81807c20-ffffffff81807ca2: available_size_show (STB_LOCAL)
ffffffff81816fc0-ffffffff81817037: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff818923c0)
Location: drivers/nvdimm/region_devs.c:389
Inline: False
```
```
In drivers/dax/bus.c (ffffffff818a1610)
Location: drivers/dax/bus.c:257
Inline: False
```
**Symbols:**

```
ffffffff818923c0-ffffffff81892442: available_size_show (STB_LOCAL)
ffffffff818a1610-ffffffff818a1687: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff819dc600)
Location: drivers/nvdimm/region_devs.c:344
Inline: False
```
```
In drivers/dax/bus.c (ffffffff819ead30)
Location: drivers/dax/bus.c:279
Inline: False
```
**Symbols:**

```
ffffffff819dc600-ffffffff819dc689: available_size_show (STB_LOCAL)
ffffffff819ead30-ffffffff819eadb3: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b57c00)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81b67850)
Location: drivers/dax/bus.c:279
Inline: False
```
**Symbols:**

```
ffffffff81b57c00-ffffffff81b57c89: available_size_show (STB_LOCAL)
ffffffff81b67850-ffffffff81b678d3: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bab170)
Location: drivers/nvdimm/region_devs.c:391
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81bbaef0)
Location: drivers/dax/bus.c:293
Inline: False
```
**Symbols:**

```
ffffffff81bab170-ffffffff81bab1f9: available_size_show (STB_LOCAL)
ffffffff81bbaef0-ffffffff81bbaf73: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bff4b0)
Location: drivers/nvdimm/region_devs.c:392
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81c0f630)
Location: drivers/dax/bus.c:293
Inline: False
```
**Symbols:**

```
ffffffff81bff4b0-ffffffff81bff539: available_size_show (STB_LOCAL)
ffffffff81c0f630-ffffffff81c0f6b3: available_size_show (STB_LOCAL)
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
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff8000109574f8)
Location: drivers/nvdimm/region_devs.c:415
Inline: False
```
**Symbols:**

```
ffff8000109574f8-ffff80001095759c: available_size_show (STB_LOCAL)
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
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a05500)
Location: drivers/nvdimm/region_devs.c:415
Inline: False
```
**Symbols:**

```
c000000000a05500-c000000000a055c4: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c6506)
Location: drivers/nvdimm/region_devs.c:415
Inline: False
```
**Symbols:**

```
ffffffe0005c6506-ffffffe0005c65a2: available_size_show (STB_LOCAL)
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
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8170a810)
Location: drivers/nvdimm/region_devs.c:415
Inline: False
```
**Symbols:**

```
ffffffff8170a810-ffffffff8170a895: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816de290)
Location: drivers/nvdimm/region_devs.c:415
Inline: False
```
**Symbols:**

```
ffffffff816de290-ffffffff816de315: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817495e0)
Location: drivers/nvdimm/region_devs.c:415
Inline: False
```
**Symbols:**

```
ffffffff817495e0-ffffffff81749665: available_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t available_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81764a60)
Location: drivers/nvdimm/region_devs.c:415
Inline: False
```
**Symbols:**

```
ffffffff81764a60-ffffffff81764ae5: available_size_show (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
