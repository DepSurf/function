# Function: <code>security_show</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5580)
Location: drivers/nvdimm/dimm_devs.c:373
Inline: True
```
**Symbols:**

```
ffffffff816f5580-ffffffff816f5661: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8172eea5)
Location: drivers/nvdimm/dimm_devs.c:370
Inline: True
```
**Symbols:**

```
ffffffff817300fc-ffffffff81730116: security_show.cold (STB_LOCAL)
ffffffff8172ee00-ffffffff8172eecb: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81753140)
Location: drivers/nvdimm/dimm_devs.c:370
Inline: True
```
**Symbols:**

```
ffffffff81753140-ffffffff8175321d: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81811c80)
Location: drivers/nvdimm/dimm_devs.c:361
Inline: False
```
**Symbols:**

```
ffffffff81811c80-ffffffff81811d42: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81820f30)
Location: drivers/nvdimm/dimm_devs.c:373
Inline: False
```
**Symbols:**

```
ffffffff81820f30-ffffffff81820ff2: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81804230)
Location: drivers/nvdimm/dimm_devs.c:373
Inline: False
```
**Symbols:**

```
ffffffff81804230-ffffffff818042f2: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8188dd60)
Location: drivers/nvdimm/dimm_devs.c:373
Inline: False
```
**Symbols:**

```
ffffffff8188dd60-ffffffff8188de22: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7300)
Location: drivers/nvdimm/dimm_devs.c:352
Inline: False
```
**Symbols:**

```
ffffffff819d7300-ffffffff819d73e3: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81b520b0)
Location: drivers/nvdimm/dimm_devs.c:352
Inline: False
```
**Symbols:**

```
ffffffff81b520b0-ffffffff81b52193: security_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba58a0)
Location: drivers/nvdimm/dimm_devs.c:352
Inline: False
```
**Symbols:**

```
ffffffff81ba58a0-ffffffff81ba5983: security_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81bf9b20)
Location: drivers/nvdimm/dimm_devs.c:354
Inline: False
```
**Symbols:**

```
ffffffff81bf9b20-ffffffff81bf9c03: security_show (STB_LOCAL)
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
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff8000109539d0)
Location: drivers/nvdimm/dimm_devs.c:370
Inline: True
```
**Symbols:**

```
ffff8000109539d0-ffff800010953ab8: security_show (STB_WEAK)
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
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a00f70)
Location: drivers/nvdimm/dimm_devs.c:370
Inline: True
```
**Symbols:**

```
c000000000a00f70-c000000000a010a8: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c3250)
Location: drivers/nvdimm/dimm_devs.c:370
Inline: True
```
**Symbols:**

```
ffffffe0005c3250-ffffffe0005c33e4: security_show (STB_WEAK)
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
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81707830)
Location: drivers/nvdimm/dimm_devs.c:370
Inline: True
```
**Symbols:**

```
ffffffff81707830-ffffffff8170790d: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816db2b0)
Location: drivers/nvdimm/dimm_devs.c:370
Inline: True
```
**Symbols:**

```
ffffffff816db2b0-ffffffff816db38d: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81746600)
Location: drivers/nvdimm/dimm_devs.c:370
Inline: True
```
**Symbols:**

```
ffffffff81746600-ffffffff817466dd: security_show (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t security_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81761a40)
Location: drivers/nvdimm/dimm_devs.c:370
Inline: True
```
**Symbols:**

```
ffffffff81761a40-ffffffff81761b1d: security_show (STB_WEAK)
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
