# Function: <code>uevent_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81547a10)
Location: drivers/base/core.c:414
Inline: False
```
```
In drivers/base/bus.c (ffffffff8154a000)
Location: drivers/base/bus.c:649
Inline: False
```
**Symbols:**

```
ffffffff81547a10-ffffffff81547a86: uevent_store (STB_LOCAL)
ffffffff8154a000-ffffffff8154a065: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81599770)
Location: drivers/base/core.c:414
Inline: False
```
```
In drivers/base/bus.c (ffffffff8159bc40)
Location: drivers/base/bus.c:648
Inline: False
```
**Symbols:**

```
ffffffff81599770-ffffffff815997e6: uevent_store (STB_LOCAL)
ffffffff8159bc40-ffffffff8159bca5: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c70b0)
Location: drivers/base/core.c:980
Inline: False
```
```
In drivers/base/bus.c (ffffffff815ca1a0)
Location: drivers/base/bus.c:648
Inline: False
```
**Symbols:**

```
ffffffff815c70b0-ffffffff815c7126: uevent_store (STB_LOCAL)
ffffffff815ca1a0-ffffffff815ca205: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dbe00)
Location: drivers/base/core.c:981
Inline: False
```
```
In drivers/base/bus.c (ffffffff815dee60)
Location: drivers/base/bus.c:613
Inline: False
```
**Symbols:**

```
ffffffff815dbe00-ffffffff815dbe3c: uevent_store (STB_LOCAL)
ffffffff815dee60-ffffffff815dee7c: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81642e30)
Location: drivers/base/core.c:984
Inline: False
```
```
In drivers/base/bus.c (ffffffff81645e90)
Location: drivers/base/bus.c:613
Inline: False
```
**Symbols:**

```
ffffffff81642e30-ffffffff81642e6c: uevent_store (STB_LOCAL)
ffffffff81645e90-ffffffff81645eac: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167dfc0)
Location: drivers/base/core.c:1026
Inline: False
```
```
In drivers/base/bus.c (ffffffff816812d0)
Location: drivers/base/bus.c:611
Inline: False
```
**Symbols:**

```
ffffffff8167dfc0-ffffffff8167e004: uevent_store (STB_LOCAL)
ffffffff816812d0-ffffffff816812ec: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d9c0)
Location: drivers/base/core.c:1094
Inline: False
```
```
In drivers/base/bus.c (ffffffff816a0d60)
Location: drivers/base/bus.c:614
Inline: False
```
**Symbols:**

```
ffffffff8169d9c0-ffffffff8169da17: uevent_store (STB_LOCAL)
ffffffff816a0d60-ffffffff816a0d85: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1239
Inline: False
```
```
In drivers/base/bus.c (ffffffff816d9c60)
Location: drivers/base/bus.c:603
Inline: False
```
**Symbols:**

```
ffffffff816d6660-ffffffff816d6695: uevent_store (STB_LOCAL)
ffffffff816d8f88-ffffffff816d8fa3: uevent_store.cold (STB_LOCAL)
ffffffff816d9c60-ffffffff816d9c85: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1276
Inline: False
```
```
In drivers/base/bus.c (ffffffff816fdc10)
Location: drivers/base/bus.c:579
Inline: False
```
**Symbols:**

```
ffffffff816fa5c0-ffffffff816fa5f5: uevent_store (STB_LOCAL)
ffffffff816fd00e-ffffffff816fd029: uevent_store.cold (STB_LOCAL)
ffffffff816fdc10-ffffffff816fdc38: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1754
Inline: False
```
```
In drivers/base/bus.c (ffffffff817b7270)
Location: drivers/base/bus.c:580
Inline: False
```
**Symbols:**

```
ffffffff817b3110-ffffffff817b3145: uevent_store (STB_LOCAL)
ffffffff817b6961-ffffffff817b697c: uevent_store.cold (STB_LOCAL)
ffffffff817b7270-ffffffff817b729b: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:2155
Inline: False
```
```
In drivers/base/bus.c (ffffffff817cbfa0)
Location: drivers/base/bus.c:580
Inline: False
```
**Symbols:**

```
ffffffff817c83e0-ffffffff817c8415: uevent_store (STB_LOCAL)
ffffffff81c0e0af-ffffffff81c0e0ca: uevent_store.cold (STB_LOCAL)
ffffffff817cbfa0-ffffffff817cbfcb: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:2367
Inline: False
```
```
In drivers/base/bus.c (ffffffff817af910)
Location: drivers/base/bus.c:580
Inline: False
```
**Symbols:**

```
ffffffff817ab970-ffffffff817ab9a5: uevent_store (STB_LOCAL)
ffffffff81c0044d-ffffffff81c00468: uevent_store.cold (STB_LOCAL)
ffffffff817af910-ffffffff817af93b: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:2404
Inline: False
```
```
In drivers/base/bus.c (ffffffff81838b70)
Location: drivers/base/bus.c:576
Inline: False
```
**Symbols:**

```
ffffffff81834b00-ffffffff81834b35: uevent_store (STB_LOCAL)
ffffffff81d029be-ffffffff81d029d9: uevent_store.cold (STB_LOCAL)
ffffffff81838b70-ffffffff81838b9b: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:2415
Inline: False
```
```
In drivers/base/bus.c (ffffffff8197b030)
Location: drivers/base/bus.c:576
Inline: False
```
**Symbols:**

```
ffffffff81976670-ffffffff819766b1: uevent_store (STB_LOCAL)
ffffffff81ecb081-ffffffff81ecb09c: uevent_store.cold (STB_LOCAL)
ffffffff8197b030-ffffffff8197b065: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae2f70)
Location: drivers/base/core.c:2652
Inline: False
```
```
In drivers/base/bus.c (ffffffff81ae7ff0)
Location: drivers/base/bus.c:576
Inline: False
```
**Symbols:**

```
ffffffff81ae2f70-ffffffff81ae2fd5: uevent_store (STB_LOCAL)
ffffffff81ae7ff0-ffffffff81ae8025: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b30e90)
Location: drivers/base/core.c:2658
Inline: False
```
```
In drivers/base/bus.c (ffffffff81b35cc0)
Location: drivers/base/bus.c:628
Inline: False
```
**Symbols:**

```
ffffffff81b30e90-ffffffff81b30ef5: uevent_store (STB_LOCAL)
ffffffff81b35cc0-ffffffff81b35cf5: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b88490)
Location: drivers/base/core.c:2673
Inline: False
```
```
In drivers/base/bus.c (ffffffff81b8d6e0)
Location: drivers/base/bus.c:628
Inline: False
```
**Symbols:**

```
ffffffff81b88490-ffffffff81b884f5: uevent_store (STB_LOCAL)
ffffffff81b8d6e0-ffffffff81b8d715: uevent_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4e28)
Location: drivers/base/core.c:1276
Inline: False
```
```
In drivers/base/bus.c (ffff8000108e8888)
Location: drivers/base/bus.c:579
Inline: False
```
**Symbols:**

```
ffff8000108e4e28-ffff8000108e4e90: uevent_store (STB_LOCAL)
ffff8000108e8888-ffff8000108e88d8: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d382c)
Location: drivers/base/core.c:1276
Inline: False
```
```
In drivers/base/bus.c (c09d6c98)
Location: drivers/base/bus.c:579
Inline: False
```
**Symbols:**

```
c09d382c-c09d387c: uevent_store (STB_LOCAL)
c09d6c98-c09d6cc4: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097a450)
Location: drivers/base/core.c:1276
Inline: False
```
```
In drivers/base/bus.c (c00000000097f060)
Location: drivers/base/bus.c:579
Inline: False
```
**Symbols:**

```
c00000000097a450-c00000000097a4d0: uevent_store (STB_LOCAL)
c00000000097f060-c00000000097f0b0: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000579bc0)
Location: drivers/base/core.c:1276
Inline: False
```
```
In drivers/base/bus.c (ffffffe00057cb18)
Location: drivers/base/bus.c:579
Inline: False
```
**Symbols:**

```
ffffffe000579bc0-ffffffe000579c18: uevent_store (STB_LOCAL)
ffffffe00057cb18-ffffffe00057cb58: uevent_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1276
Inline: False
```
```
In drivers/base/bus.c (ffffffff816c3400)
Location: drivers/base/bus.c:579
Inline: False
```
**Symbols:**

```
ffffffff816bfdb0-ffffffff816bfde5: uevent_store (STB_LOCAL)
ffffffff816c27fe-ffffffff816c2819: uevent_store.cold (STB_LOCAL)
ffffffff816c3400-ffffffff816c3428: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1276
Inline: False
```
```
In drivers/base/bus.c (ffffffff8169e6b0)
Location: drivers/base/bus.c:579
Inline: False
```
**Symbols:**

```
ffffffff8169b060-ffffffff8169b095: uevent_store (STB_LOCAL)
ffffffff8169daae-ffffffff8169dac9: uevent_store.cold (STB_LOCAL)
ffffffff8169e6b0-ffffffff8169e6d8: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1276
Inline: False
```
```
In drivers/base/bus.c (ffffffff816f18d0)
Location: drivers/base/bus.c:579
Inline: False
```
**Symbols:**

```
ffffffff816ee280-ffffffff816ee2b5: uevent_store (STB_LOCAL)
ffffffff816f0cce-ffffffff816f0ce9: uevent_store.cold (STB_LOCAL)
ffffffff816f18d0-ffffffff816f18f8: uevent_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
ssize_t uevent_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:1276
Inline: False
```
```
In drivers/base/bus.c (ffffffff8170c110)
Location: drivers/base/bus.c:579
Inline: False
```
**Symbols:**

```
ffffffff81709340-ffffffff81709375: uevent_store (STB_LOCAL)
ffffffff8170b50e-ffffffff8170b529: uevent_store.cold (STB_LOCAL)
ffffffff8170c110-ffffffff8170c138: uevent_store (STB_LOCAL)
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
