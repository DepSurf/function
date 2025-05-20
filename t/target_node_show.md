# Function: <code>target_node_show</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff8173fc00)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
ffffffff8173fc00-ffffffff8173fc26: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81763de0)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
ffffffff81763de0-ffffffff81763e06: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8180fe10)
Location: drivers/nvdimm/bus.c:703
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81823c30)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
ffffffff8180fe10-ffffffff8180fe3c: target_node_show (STB_LOCAL)
ffffffff81823c30-ffffffff81823c56: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181ed50)
Location: drivers/nvdimm/bus.c:700
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81832a50)
Location: drivers/dax/bus.c:1170
Inline: False
```
**Symbols:**

```
ffffffff8181ed50-ffffffff8181ed7c: target_node_show (STB_LOCAL)
ffffffff81832a50-ffffffff81832a76: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81802070)
Location: drivers/nvdimm/bus.c:695
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81815c90)
Location: drivers/dax/bus.c:1171
Inline: False
```
**Symbols:**

```
ffffffff81802070-ffffffff8180209c: target_node_show (STB_LOCAL)
ffffffff81815c90-ffffffff81815cb6: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188c530)
Location: drivers/nvdimm/bus.c:689
Inline: False
```
```
In drivers/dax/bus.c (ffffffff818a02d0)
Location: drivers/dax/bus.c:1169
Inline: False
```
**Symbols:**

```
ffffffff8188c530-ffffffff8188c55c: target_node_show (STB_LOCAL)
ffffffff818a02d0-ffffffff818a02f6: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff819d59a0)
Location: drivers/nvdimm/bus.c:677
Inline: False
```
```
In drivers/dax/bus.c (ffffffff819e98c0)
Location: drivers/dax/bus.c:1199
Inline: False
```
**Symbols:**

```
ffffffff819d59a0-ffffffff819d59d5: target_node_show (STB_LOCAL)
ffffffff819e98c0-ffffffff819e98f0: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b50500)
Location: drivers/nvdimm/bus.c:690
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81b66250)
Location: drivers/dax/bus.c:1199
Inline: False
```
**Symbols:**

```
ffffffff81b50500-ffffffff81b50535: target_node_show (STB_LOCAL)
ffffffff81b66250-ffffffff81b66280: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba39d0)
Location: drivers/nvdimm/bus.c:690
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81bb9860)
Location: drivers/dax/bus.c:1229
Inline: False
```
**Symbols:**

```
ffffffff81ba39d0-ffffffff81ba3a05: target_node_show (STB_LOCAL)
ffffffff81bb9860-ffffffff81bb9890: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf7bc0)
Location: drivers/nvdimm/bus.c:690
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81c0dec0)
Location: drivers/dax/bus.c:1230
Inline: False
```
**Symbols:**

```
ffffffff81bf7bc0-ffffffff81bf7bf5: target_node_show (STB_LOCAL)
ffffffff81c0dec0-ffffffff81c0def0: target_node_show (STB_LOCAL)
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
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffff800010963ed8)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
ffff800010963ed8-ffff800010963f1c: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c0a3aac4)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
c0a3aac4-c0a3aaf4: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c000000000a1a6c0)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
c000000000a1a6c0-c000000000a1a708: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffe0005d0f7e)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
ffffffe0005d0f7e-ffffffe0005d0fbc: target_node_show (STB_LOCAL)
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
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817184d0)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
ffffffff817184d0-ffffffff817184f6: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff816f0a00)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
ffffffff816f0a00-ffffffff816f0a26: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817572a0)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
ffffffff817572a0-ffffffff817572c6: target_node_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t target_node_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81772740)
Location: drivers/dax/bus.c:289
Inline: False
```
**Symbols:**

```
ffffffff81772740-ffffffff81772766: target_node_show (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
