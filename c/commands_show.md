# Function: <code>commands_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81596da0)
Location: drivers/nvdimm/core.c:246
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81598850)
Location: drivers/nvdimm/dimm_devs.c:274
Inline: False
```
**Symbols:**

```
ffffffff81596da0-ffffffff81596e7e: commands_show (STB_LOCAL)
ffffffff81598850-ffffffff8159893a: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815ebbc0)
Location: drivers/nvdimm/core.c:349
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff815ee380)
Location: drivers/nvdimm/dimm_devs.c:280
Inline: True
```
**Symbols:**

```
ffffffff815ebbc0-ffffffff815ebc73: commands_show (STB_LOCAL)
ffffffff815ee380-ffffffff815ee47f: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816187b0)
Location: drivers/nvdimm/core.c:320
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8161b3c0)
Location: drivers/nvdimm/dimm_devs.c:295
Inline: True
```
**Symbols:**

```
ffffffff816187b0-ffffffff81618863: commands_show (STB_LOCAL)
ffffffff8161b3c0-ffffffff8161b4bf: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8162c5f0)
Location: drivers/nvdimm/core.c:320
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8162f460)
Location: drivers/nvdimm/dimm_devs.c:311
Inline: True
```
**Symbols:**

```
ffffffff8162c5f0-ffffffff8162c6a4: commands_show (STB_LOCAL)
ffffffff8162f460-ffffffff8162f561: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81695270)
Location: drivers/nvdimm/core.c:320
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81697c40)
Location: drivers/nvdimm/dimm_devs.c:318
Inline: True
```
**Symbols:**

```
ffffffff81695270-ffffffff81695324: commands_show (STB_LOCAL)
ffffffff81697c40-ffffffff81697d41: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d13a0)
Location: drivers/nvdimm/core.c:320
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816d3da0)
Location: drivers/nvdimm/dimm_devs.c:319
Inline: True
```
**Symbols:**

```
ffffffff816d13a0-ffffffff816d1451: commands_show (STB_LOCAL)
ffffffff816d3da0-ffffffff816d3e94: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816f2a40)
Location: drivers/nvdimm/core.c:320
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5670)
Location: drivers/nvdimm/dimm_devs.c:307
Inline: True
```
**Symbols:**

```
ffffffff816f2a40-ffffffff816f2ae7: commands_show (STB_LOCAL)
ffffffff816f5670-ffffffff816f575a: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8172bfb0)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8172ef00)
Location: drivers/nvdimm/dimm_devs.c:304
Inline: True
```
**Symbols:**

```
ffffffff8172bfb0-ffffffff8172c051: commands_show (STB_LOCAL)
ffffffff8172eed0-ffffffff8172ef9f: commands_show (STB_LOCAL)
ffffffff81730116-ffffffff81730128: commands_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81750200)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81753220)
Location: drivers/nvdimm/dimm_devs.c:304
Inline: True
```
**Symbols:**

```
ffffffff81750200-ffffffff817502a1: commands_show (STB_LOCAL)
ffffffff81753220-ffffffff817532f0: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8180e8f0)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81811e80)
Location: drivers/nvdimm/dimm_devs.c:294
Inline: True
```
**Symbols:**

```
ffffffff8180e8f0-ffffffff8180e991: commands_show (STB_LOCAL)
ffffffff81811e80-ffffffff81811f4a: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8181d460)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81821220)
Location: drivers/nvdimm/dimm_devs.c:294
Inline: True
```
**Symbols:**

```
ffffffff8181d460-ffffffff8181d501: commands_show (STB_LOCAL)
ffffffff81821220-ffffffff818212ea: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81800890)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81804520)
Location: drivers/nvdimm/dimm_devs.c:294
Inline: False
```
**Symbols:**

```
ffffffff81800890-ffffffff81800953: commands_show (STB_LOCAL)
ffffffff81804520-ffffffff81804611: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8188ac90)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e6a0)
Location: drivers/nvdimm/dimm_devs.c:294
Inline: False
```
**Symbols:**

```
ffffffff8188ac90-ffffffff8188ad53: commands_show (STB_LOCAL)
ffffffff8188e6a0-ffffffff8188e791: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff819d43c0)
Location: drivers/nvdimm/core.c:281
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7d00)
Location: drivers/nvdimm/dimm_devs.c:274
Inline: False
```
**Symbols:**

```
ffffffff819d43c0-ffffffff819d4497: commands_show (STB_LOCAL)
ffffffff819d7d00-ffffffff819d7e09: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81b4ec10)
Location: drivers/nvdimm/core.c:281
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52ba0)
Location: drivers/nvdimm/dimm_devs.c:274
Inline: True
```
**Symbols:**

```
ffffffff81b4ec10-ffffffff81b4ecc5: commands_show (STB_LOCAL)
ffffffff81b52ba0-ffffffff81b52c8c: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81ba2060)
Location: drivers/nvdimm/core.c:281
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6050)
Location: drivers/nvdimm/dimm_devs.c:274
Inline: True
```
**Symbols:**

```
ffffffff81ba2060-ffffffff81ba2115: commands_show (STB_LOCAL)
ffffffff81ba6050-ffffffff81ba613c: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81bf61f0)
Location: drivers/nvdimm/core.c:281
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa2d0)
Location: drivers/nvdimm/dimm_devs.c:276
Inline: True
```
**Symbols:**

```
ffffffff81bf61f0-ffffffff81bf62a5: commands_show (STB_LOCAL)
ffffffff81bfa2d0-ffffffff81bfa3bc: commands_show (STB_LOCAL)
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
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffff800010950258)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffff800010953ab8)
Location: drivers/nvdimm/dimm_devs.c:304
Inline: True
```
**Symbols:**

```
ffff800010950258-ffff800010950364: commands_show (STB_LOCAL)
ffff800010953ab8-ffff800010953bd8: commands_show (STB_LOCAL)
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
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (c0000000009fc780)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (c000000000a008b0)
Location: drivers/nvdimm/dimm_devs.c:304
Inline: False
```
**Symbols:**

```
c0000000009fc780-c0000000009fc8e0: commands_show (STB_LOCAL)
c000000000a008b0-c000000000a00a08: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffe0005c0532)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c33e4)
Location: drivers/nvdimm/dimm_devs.c:304
Inline: True
```
**Symbols:**

```
ffffffe0005c0532-ffffffe0005c0612: commands_show (STB_LOCAL)
ffffffe0005c33e4-ffffffe0005c34e4: commands_show (STB_LOCAL)
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
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff817048f0)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81707910)
Location: drivers/nvdimm/dimm_devs.c:304
Inline: True
```
**Symbols:**

```
ffffffff817048f0-ffffffff81704991: commands_show (STB_LOCAL)
ffffffff81707910-ffffffff817079e0: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d8370)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff816db390)
Location: drivers/nvdimm/dimm_devs.c:304
Inline: True
```
**Symbols:**

```
ffffffff816d8370-ffffffff816d8411: commands_show (STB_LOCAL)
ffffffff816db390-ffffffff816db460: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff817436c0)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff817466e0)
Location: drivers/nvdimm/dimm_devs.c:304
Inline: True
```
**Symbols:**

```
ffffffff817436c0-ffffffff81743761: commands_show (STB_LOCAL)
ffffffff817466e0-ffffffff817467b0: commands_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t commands_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8175eb10)
Location: drivers/nvdimm/core.c:312
Inline: False
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81761b20)
Location: drivers/nvdimm/dimm_devs.c:304
Inline: True
```
**Symbols:**

```
ffffffff8175eb10-ffffffff8175ebb1: commands_show (STB_LOCAL)
ffffffff81761b20-ffffffff81761bf0: commands_show (STB_LOCAL)
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
