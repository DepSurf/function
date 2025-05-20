# Function: <code>namespace_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff815a11f0)
Location: drivers/nvdimm/btt_devs.c:125
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815a1d20)
Location: drivers/nvdimm/pfn_devs.c:145
Inline: False
```
**Symbols:**

```
ffffffff815a11f0-ffffffff815a12b8: namespace_store (STB_LOCAL)
ffffffff815a1d20-ffffffff815a1deb: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff815f7610)
Location: drivers/nvdimm/btt_devs.c:125
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff815f7f90)
Location: drivers/nvdimm/pfn_devs.c:191
Inline: False
```
**Symbols:**

```
ffffffff815f7610-ffffffff815f76db: namespace_store (STB_LOCAL)
ffffffff815f7f90-ffffffff815f804c: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81625880)
Location: drivers/nvdimm/btt_devs.c:125
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81626200)
Location: drivers/nvdimm/pfn_devs.c:191
Inline: False
```
**Symbols:**

```
ffffffff81625880-ffffffff8162594b: namespace_store (STB_LOCAL)
ffffffff81626200-ffffffff816262bc: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8163a8d0)
Location: drivers/nvdimm/btt_devs.c:125
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8163b3c0)
Location: drivers/nvdimm/pfn_devs.c:191
Inline: False
```
**Symbols:**

```
ffffffff8163a8d0-ffffffff8163a995: namespace_store (STB_LOCAL)
ffffffff8163b3c0-ffffffff8163b476: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816a34d0)
Location: drivers/nvdimm/btt_devs.c:125
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816a4130)
Location: drivers/nvdimm/pfn_devs.c:195
Inline: False
```
**Symbols:**

```
ffffffff816a34d0-ffffffff816a3595: namespace_store (STB_LOCAL)
ffffffff816a4130-ffffffff816a41e6: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816df650)
Location: drivers/nvdimm/btt_devs.c:125
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e02f0)
Location: drivers/nvdimm/pfn_devs.c:195
Inline: False
```
**Symbols:**

```
ffffffff816df650-ffffffff816df708: namespace_store (STB_LOCAL)
ffffffff816e02f0-ffffffff816e0399: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81701a00)
Location: drivers/nvdimm/btt_devs.c:125
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff817026b0)
Location: drivers/nvdimm/pfn_devs.c:195
Inline: False
```
**Symbols:**

```
ffffffff81701a00-ffffffff81701ab8: namespace_store (STB_LOCAL)
ffffffff817026b0-ffffffff81702759: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:117
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8173c550)
Location: drivers/nvdimm/pfn_devs.c:187
Inline: False
```
**Symbols:**

```
ffffffff8173b8b0-ffffffff8173b963: namespace_store (STB_LOCAL)
ffffffff8173c0dd-ffffffff8173c0e7: namespace_store.cold (STB_LOCAL)
ffffffff8173c550-ffffffff8173c5fc: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8175f580)
Location: drivers/nvdimm/btt_devs.c:117
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81760240)
Location: drivers/nvdimm/pfn_devs.c:190
Inline: False
```
**Symbols:**

```
ffffffff8175f580-ffffffff8175f63d: namespace_store (STB_LOCAL)
ffffffff81760240-ffffffff817602ec: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8181f4c0)
Location: drivers/nvdimm/btt_devs.c:106
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8181fd40)
Location: drivers/nvdimm/pfn_devs.c:179
Inline: False
```
**Symbols:**

```
ffffffff8181f4c0-ffffffff8181f57a: namespace_store (STB_LOCAL)
ffffffff8181fd40-ffffffff8181fdec: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8182e400)
Location: drivers/nvdimm/btt_devs.c:106
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182ec70)
Location: drivers/nvdimm/pfn_devs.c:179
Inline: False
```
**Symbols:**

```
ffffffff8182e400-ffffffff8182e4ba: namespace_store (STB_LOCAL)
ffffffff8182ec70-ffffffff8182ed1c: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff818116d0)
Location: drivers/nvdimm/btt_devs.c:106
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81811f40)
Location: drivers/nvdimm/pfn_devs.c:179
Inline: False
```
**Symbols:**

```
ffffffff818116d0-ffffffff8181178a: namespace_store (STB_LOCAL)
ffffffff81811f40-ffffffff81811fec: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8189b9c0)
Location: drivers/nvdimm/btt_devs.c:106
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189c560)
Location: drivers/nvdimm/pfn_devs.c:179
Inline: False
```
**Symbols:**

```
ffffffff8189b9c0-ffffffff8189ba77: namespace_store (STB_LOCAL)
ffffffff8189c560-ffffffff8189c609: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff819e5180)
Location: drivers/nvdimm/btt_devs.c:105
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff819e5e30)
Location: drivers/nvdimm/pfn_devs.c:178
Inline: False
```
**Symbols:**

```
ffffffff819e5180-ffffffff819e5247: namespace_store (STB_LOCAL)
ffffffff819e5e30-ffffffff819e5eeb: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81b60fc0)
Location: drivers/nvdimm/btt_devs.c:105
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81b61da0)
Location: drivers/nvdimm/pfn_devs.c:180
Inline: False
```
**Symbols:**

```
ffffffff81b60fc0-ffffffff81b61087: namespace_store (STB_LOCAL)
ffffffff81b61da0-ffffffff81b61e5b: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81bb4540)
Location: drivers/nvdimm/btt_devs.c:105
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb53a0)
Location: drivers/nvdimm/pfn_devs.c:180
Inline: False
```
**Symbols:**

```
ffffffff81bb4540-ffffffff81bb4607: namespace_store (STB_LOCAL)
ffffffff81bb53a0-ffffffff81bb545b: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81c08a90)
Location: drivers/nvdimm/btt_devs.c:105
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c09920)
Location: drivers/nvdimm/pfn_devs.c:180
Inline: False
```
**Symbols:**

```
ffffffff81c08a90-ffffffff81c08b57: namespace_store (STB_LOCAL)
ffffffff81c09920-ffffffff81c099db: namespace_store (STB_LOCAL)
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
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffff800010960d58)
Location: drivers/nvdimm/btt_devs.c:117
Inline: False
```
**Symbols:**

```
ffff800010960d58-ffff800010960e3c: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (c000000000a14140)
Location: drivers/nvdimm/btt_devs.c:117
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a15360)
Location: drivers/nvdimm/pfn_devs.c:190
Inline: False
```
**Symbols:**

```
c000000000a14140-c000000000a14284: namespace_store (STB_LOCAL)
c000000000a15360-c000000000a154b4: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffe0005ce702)
Location: drivers/nvdimm/btt_devs.c:117
Inline: False
```
**Symbols:**

```
ffffffe0005ce702-ffffffe0005ce7dc: namespace_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81713c70)
Location: drivers/nvdimm/btt_devs.c:117
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81714930)
Location: drivers/nvdimm/pfn_devs.c:190
Inline: False
```
**Symbols:**

```
ffffffff81713c70-ffffffff81713d2d: namespace_store (STB_LOCAL)
ffffffff81714930-ffffffff817149dc: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816e76f0)
Location: drivers/nvdimm/btt_devs.c:117
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e83b0)
Location: drivers/nvdimm/pfn_devs.c:190
Inline: False
```
**Symbols:**

```
ffffffff816e76f0-ffffffff816e77ad: namespace_store (STB_LOCAL)
ffffffff816e83b0-ffffffff816e845c: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81752a40)
Location: drivers/nvdimm/btt_devs.c:117
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81753700)
Location: drivers/nvdimm/pfn_devs.c:190
Inline: False
```
**Symbols:**

```
ffffffff81752a40-ffffffff81752afd: namespace_store (STB_LOCAL)
ffffffff81753700-ffffffff817537ac: namespace_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t namespace_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8176deb0)
Location: drivers/nvdimm/btt_devs.c:117
Inline: False
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176eb70)
Location: drivers/nvdimm/pfn_devs.c:190
Inline: False
```
**Symbols:**

```
ffffffff8176deb0-ffffffff8176df6d: namespace_store (STB_LOCAL)
ffffffff8176eb70-ffffffff8176ec1c: namespace_store (STB_LOCAL)
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
