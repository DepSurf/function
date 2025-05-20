# Function: <code>sector_size_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8159b500)
Location: drivers/nvdimm/namespace_devs.c:1171
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff815a1410)
Location: drivers/nvdimm/btt_devs.c:59
Inline: False
```
**Symbols:**

```
ffffffff8159b500-ffffffff8159b535: sector_size_show (STB_LOCAL)
ffffffff815a1410-ffffffff815a1453: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f1640)
Location: drivers/nvdimm/namespace_devs.c:1181
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff815f7830)
Location: drivers/nvdimm/btt_devs.c:59
Inline: False
```
**Symbols:**

```
ffffffff815f1640-ffffffff815f1675: sector_size_show (STB_LOCAL)
ffffffff815f7830-ffffffff815f7873: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8161edc0)
Location: drivers/nvdimm/namespace_devs.c:1289
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81625aa0)
Location: drivers/nvdimm/btt_devs.c:59
Inline: False
```
**Symbols:**

```
ffffffff8161edc0-ffffffff8161edf5: sector_size_show (STB_LOCAL)
ffffffff81625aa0-ffffffff81625ae3: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81633a30)
Location: drivers/nvdimm/namespace_devs.c:1310
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8163aae0)
Location: drivers/nvdimm/btt_devs.c:59
Inline: False
```
**Symbols:**

```
ffffffff81633a30-ffffffff81633a89: sector_size_show (STB_LOCAL)
ffffffff8163aae0-ffffffff8163ab23: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169c3b0)
Location: drivers/nvdimm/namespace_devs.c:1310
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816a36e0)
Location: drivers/nvdimm/btt_devs.c:59
Inline: False
```
**Symbols:**

```
ffffffff8169c3b0-ffffffff8169c409: sector_size_show (STB_LOCAL)
ffffffff816a36e0-ffffffff816a3723: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816d8ed0)
Location: drivers/nvdimm/namespace_devs.c:1309
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816df850)
Location: drivers/nvdimm/btt_devs.c:59
Inline: False
```
**Symbols:**

```
ffffffff816d8ed0-ffffffff816d8f28: sector_size_show (STB_LOCAL)
ffffffff816df850-ffffffff816df893: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fb1a0)
Location: drivers/nvdimm/namespace_devs.c:1332
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81701c00)
Location: drivers/nvdimm/btt_devs.c:59
Inline: False
```
**Symbols:**

```
ffffffff816fb1a0-ffffffff816fb1f8: sector_size_show (STB_LOCAL)
ffffffff81701c00-ffffffff81701c43: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81734c00)
Location: drivers/nvdimm/namespace_devs.c:1339
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:51
Inline: False
```
**Symbols:**

```
ffffffff81734c00-ffffffff81734c58: sector_size_show (STB_LOCAL)
ffffffff8173baa0-ffffffff8173bad0: sector_size_show (STB_LOCAL)
ffffffff8173c0fb-ffffffff8173c115: sector_size_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81758990)
Location: drivers/nvdimm/namespace_devs.c:1339
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8175f790)
Location: drivers/nvdimm/btt_devs.c:51
Inline: False
```
**Symbols:**

```
ffffffff81758990-ffffffff817589e8: sector_size_show (STB_LOCAL)
ffffffff8175f790-ffffffff8175f7d3: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81816ea0)
Location: drivers/nvdimm/namespace_devs.c:1319
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8181f220)
Location: drivers/nvdimm/btt_devs.c:40
Inline: False
```
**Symbols:**

```
ffffffff81816ea0-ffffffff81816ef8: sector_size_show (STB_LOCAL)
ffffffff8181f220-ffffffff8181f24c: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81825ff0)
Location: drivers/nvdimm/namespace_devs.c:1319
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8182e160)
Location: drivers/nvdimm/btt_devs.c:40
Inline: False
```
**Symbols:**

```
ffffffff81825ff0-ffffffff81826048: sector_size_show (STB_LOCAL)
ffffffff8182e160-ffffffff8182e18c: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81809370)
Location: drivers/nvdimm/namespace_devs.c:1319
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81811430)
Location: drivers/nvdimm/btt_devs.c:40
Inline: False
```
**Symbols:**

```
ffffffff81809370-ffffffff818093c8: sector_size_show (STB_LOCAL)
ffffffff81811430-ffffffff8181145c: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff818938a0)
Location: drivers/nvdimm/namespace_devs.c:1319
Inline: False
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8189bbc0)
Location: drivers/nvdimm/btt_devs.c:40
Inline: False
```
**Symbols:**

```
ffffffff818938a0-ffffffff818938f8: sector_size_show (STB_LOCAL)
ffffffff8189bbc0-ffffffff8189bbec: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff819de350)
Location: drivers/nvdimm/namespace_devs.c:1093
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff819e53b0)
Location: drivers/nvdimm/btt_devs.c:39
Inline: False
```
**Symbols:**

```
ffffffff819de350-ffffffff819de399: sector_size_show (STB_LOCAL)
ffffffff819e53b0-ffffffff819e53e6: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b59c50)
Location: drivers/nvdimm/namespace_devs.c:1085
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81b61220)
Location: drivers/nvdimm/btt_devs.c:39
Inline: False
```
**Symbols:**

```
ffffffff81b59c50-ffffffff81b59c99: sector_size_show (STB_LOCAL)
ffffffff81b61220-ffffffff81b61256: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81bad1d0)
Location: drivers/nvdimm/namespace_devs.c:1085
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81bb47a0)
Location: drivers/nvdimm/btt_devs.c:39
Inline: False
```
**Symbols:**

```
ffffffff81bad1d0-ffffffff81bad219: sector_size_show (STB_LOCAL)
ffffffff81bb47a0-ffffffff81bb47d6: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c01510)
Location: drivers/nvdimm/namespace_devs.c:1094
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81c08cf0)
Location: drivers/nvdimm/btt_devs.c:39
Inline: False
```
**Symbols:**

```
ffffffff81c01510-ffffffff81c01559: sector_size_show (STB_LOCAL)
ffffffff81c08cf0-ffffffff81c08d26: sector_size_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095a048)
Location: drivers/nvdimm/namespace_devs.c:1339
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffff800010960fc0)
Location: drivers/nvdimm/btt_devs.c:51
Inline: False
```
**Symbols:**

```
ffff80001095a048-ffff80001095a0d4: sector_size_show (STB_LOCAL)
ffff800010960fc0-ffff800010961034: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a09c90)
Location: drivers/nvdimm/namespace_devs.c:1339
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (c000000000a14480)
Location: drivers/nvdimm/btt_devs.c:51
Inline: False
```
**Symbols:**

```
c000000000a09c90-c000000000a09d38: sector_size_show (STB_LOCAL)
c000000000a14480-c000000000a144cc: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c8bde)
Location: drivers/nvdimm/namespace_devs.c:1339
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffe0005ce942)
Location: drivers/nvdimm/btt_devs.c:51
Inline: False
```
**Symbols:**

```
ffffffe0005c8bde-ffffffe0005c8c66: sector_size_show (STB_LOCAL)
ffffffe0005ce942-ffffffe0005ce996: sector_size_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8170d080)
Location: drivers/nvdimm/namespace_devs.c:1339
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81713e80)
Location: drivers/nvdimm/btt_devs.c:51
Inline: False
```
**Symbols:**

```
ffffffff8170d080-ffffffff8170d0d8: sector_size_show (STB_LOCAL)
ffffffff81713e80-ffffffff81713ec3: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816e0b00)
Location: drivers/nvdimm/namespace_devs.c:1339
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff816e7900)
Location: drivers/nvdimm/btt_devs.c:51
Inline: False
```
**Symbols:**

```
ffffffff816e0b00-ffffffff816e0b58: sector_size_show (STB_LOCAL)
ffffffff816e7900-ffffffff816e7943: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8174be50)
Location: drivers/nvdimm/namespace_devs.c:1339
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81752c50)
Location: drivers/nvdimm/btt_devs.c:51
Inline: False
```
**Symbols:**

```
ffffffff8174be50-ffffffff8174bea8: sector_size_show (STB_LOCAL)
ffffffff81752c50-ffffffff81752c93: sector_size_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t sector_size_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff817672d0)
Location: drivers/nvdimm/namespace_devs.c:1339
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (ffffffff8176e0c0)
Location: drivers/nvdimm/btt_devs.c:51
Inline: False
```
**Symbols:**

```
ffffffff817672d0-ffffffff81767328: sector_size_show (STB_LOCAL)
ffffffff8176e0c0-ffffffff8176e103: sector_size_show (STB_LOCAL)
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
