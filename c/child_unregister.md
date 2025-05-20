# Function: <code>child_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81596cb0)
Location: drivers/nvdimm/core.c:362
Inline: False
```
```
In drivers/nvdimm/region.c (ffffffff8159ac90)
Location: drivers/nvdimm/region.c:74
Inline: False
```
**Symbols:**

```
ffffffff81596cb0-ffffffff81596cd1: child_unregister (STB_LOCAL)
ffffffff8159ac90-ffffffff8159aca4: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ecdb0)
Location: drivers/nvdimm/bus.c:318
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff815f0cd0)
Location: drivers/nvdimm/region.c:75
Inline: False
```
**Symbols:**

```
ffffffff815ecdb0-ffffffff815ecde3: child_unregister (STB_LOCAL)
ffffffff815f0cd0-ffffffff815f0ce4: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81619ba0)
Location: drivers/nvdimm/bus.c:320
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff8161e090)
Location: drivers/nvdimm/region.c:75
Inline: False
```
**Symbols:**

```
ffffffff81619ba0-ffffffff81619bd3: child_unregister (STB_LOCAL)
ffffffff8161e090-ffffffff8161e0a4: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162db90)
Location: drivers/nvdimm/bus.c:383
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81632560)
Location: drivers/nvdimm/region.c:91
Inline: False
```
**Symbols:**

```
ffffffff8162db90-ffffffff8162dbc3: child_unregister (STB_LOCAL)
ffffffff81632560-ffffffff81632574: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81696350)
Location: drivers/nvdimm/bus.c:383
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff8169aed0)
Location: drivers/nvdimm/region.c:91
Inline: False
```
**Symbols:**

```
ffffffff81696350-ffffffff81696383: child_unregister (STB_LOCAL)
ffffffff8169aed0-ffffffff8169aee4: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d2440)
Location: drivers/nvdimm/bus.c:387
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff816d72a0)
Location: drivers/nvdimm/region.c:91
Inline: False
```
**Symbols:**

```
ffffffff816d2440-ffffffff816d2473: child_unregister (STB_LOCAL)
ffffffff816d72a0-ffffffff816d72b4: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f3b40)
Location: drivers/nvdimm/bus.c:387
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff816f9170)
Location: drivers/nvdimm/region.c:91
Inline: False
```
**Symbols:**

```
ffffffff816f3b40-ffffffff816f3bdb: child_unregister (STB_LOCAL)
ffffffff816f9170-ffffffff816f9184: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172cef0)
Location: drivers/nvdimm/bus.c:386
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81732c00)
Location: drivers/nvdimm/region.c:83
Inline: False
```
**Symbols:**

```
ffffffff8172cef0-ffffffff8172cf7c: child_unregister (STB_LOCAL)
ffffffff81732c00-ffffffff81732c14: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81750f10)
Location: drivers/nvdimm/bus.c:384
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81756820)
Location: drivers/nvdimm/region.c:83
Inline: False
```
**Symbols:**

```
ffffffff81750f10-ffffffff81750f9a: child_unregister (STB_LOCAL)
ffffffff81756820-ffffffff81756834: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8180fb40)
Location: drivers/nvdimm/bus.c:389
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81815e10)
Location: drivers/nvdimm/region.c:83
Inline: False
```
**Symbols:**

```
ffffffff8180fc00-ffffffff8180fc1f: child_unregister (STB_LOCAL)
ffffffff8180fb40-ffffffff8180fbf5: child_unregister.part.0 (STB_LOCAL)
ffffffff81815e10-ffffffff81815e24: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181ea80)
Location: drivers/nvdimm/bus.c:389
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81824fa0)
Location: drivers/nvdimm/region.c:84
Inline: False
```
**Symbols:**

```
ffffffff8181eb40-ffffffff8181eb5f: child_unregister (STB_LOCAL)
ffffffff8181ea80-ffffffff8181eb35: child_unregister.part.0 (STB_LOCAL)
ffffffff81824fa0-ffffffff81824fb4: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81801930)
Location: drivers/nvdimm/bus.c:388
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81808330)
Location: drivers/nvdimm/region.c:84
Inline: False
```
**Symbols:**

```
ffffffff81801930-ffffffff818019fd: child_unregister (STB_LOCAL)
ffffffff81808330-ffffffff81808344: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188be60)
Location: drivers/nvdimm/bus.c:392
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81892b00)
Location: drivers/nvdimm/region.c:84
Inline: False
```
**Symbols:**

```
ffffffff8188be60-ffffffff8188bee3: child_unregister (STB_LOCAL)
ffffffff81892b00-ffffffff81892b14: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff819d5280)
Location: drivers/nvdimm/bus.c:386
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff819dcdb0)
Location: drivers/nvdimm/region.c:76
Inline: False
```
**Symbols:**

```
ffffffff819d5280-ffffffff819d5316: child_unregister (STB_LOCAL)
ffffffff819dcdb0-ffffffff819dcdcc: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b4fd00)
Location: drivers/nvdimm/bus.c:386
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81b584a0)
Location: drivers/nvdimm/region.c:77
Inline: False
```
**Symbols:**

```
ffffffff81b4fd00-ffffffff81b4fd96: child_unregister (STB_LOCAL)
ffffffff81b584a0-ffffffff81b584bc: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba31d0)
Location: drivers/nvdimm/bus.c:386
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81baba10)
Location: drivers/nvdimm/region.c:77
Inline: False
```
**Symbols:**

```
ffffffff81ba31d0-ffffffff81ba3266: child_unregister (STB_LOCAL)
ffffffff81baba10-ffffffff81baba2c: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf7390)
Location: drivers/nvdimm/bus.c:386
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81bffd50)
Location: drivers/nvdimm/region.c:77
Inline: False
```
**Symbols:**

```
ffffffff81bf7390-ffffffff81bf7426: child_unregister (STB_LOCAL)
ffffffff81bffd50-ffffffff81bffd6c: child_unregister (STB_LOCAL)
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
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010951c38)
Location: drivers/nvdimm/bus.c:384
Inline: True
```
```
In drivers/nvdimm/region.c (ffff800010957ce0)
Location: drivers/nvdimm/region.c:83
Inline: False
```
**Symbols:**

```
ffff800010951c38-ffff800010951d4c: child_unregister (STB_LOCAL)
ffff800010957ce0-ffff800010957d14: child_unregister (STB_LOCAL)
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
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fe220)
Location: drivers/nvdimm/bus.c:384
Inline: True
```
```
In drivers/nvdimm/region.c (c000000000a05fd0)
Location: drivers/nvdimm/region.c:83
Inline: False
```
**Symbols:**

```
c0000000009fe220-c0000000009fe34c: child_unregister (STB_LOCAL)
c000000000a05fd0-c000000000a0600c: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c112a)
Location: drivers/nvdimm/bus.c:384
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffe0005c6bb0)
Location: drivers/nvdimm/region.c:83
Inline: False
```
**Symbols:**

```
ffffffe0005c112a-ffffffe0005c11de: child_unregister (STB_LOCAL)
ffffffe0005c6bb0-ffffffe0005c6bde: child_unregister (STB_LOCAL)
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
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81705600)
Location: drivers/nvdimm/bus.c:384
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff8170af10)
Location: drivers/nvdimm/region.c:83
Inline: False
```
**Symbols:**

```
ffffffff81705600-ffffffff8170568a: child_unregister (STB_LOCAL)
ffffffff8170af10-ffffffff8170af24: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d9080)
Location: drivers/nvdimm/bus.c:384
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff816de990)
Location: drivers/nvdimm/region.c:83
Inline: False
```
**Symbols:**

```
ffffffff816d9080-ffffffff816d910a: child_unregister (STB_LOCAL)
ffffffff816de990-ffffffff816de9a4: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817443d0)
Location: drivers/nvdimm/bus.c:384
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81749ce0)
Location: drivers/nvdimm/region.c:83
Inline: False
```
**Symbols:**

```
ffffffff817443d0-ffffffff8174445a: child_unregister (STB_LOCAL)
ffffffff81749ce0-ffffffff81749cf4: child_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int child_unregister(struct device *dev, void *data);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8175f820)
Location: drivers/nvdimm/bus.c:384
Inline: True
```
```
In drivers/nvdimm/region.c (ffffffff81765160)
Location: drivers/nvdimm/region.c:83
Inline: False
```
**Symbols:**

```
ffffffff8175f820-ffffffff8175f8aa: child_unregister (STB_LOCAL)
ffffffff81765160-ffffffff81765174: child_unregister (STB_LOCAL)
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
