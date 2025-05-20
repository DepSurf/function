# Function: <code>driver_bound</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8154b800)
Location: drivers/base/dd.c:195
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff8154b800-ffffffff8154b8da: driver_bound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8159d500)
Location: drivers/base/dd.c:240
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:device_bind_driver
```
**Symbols:**

```
ffffffff8159d500-ffffffff8159d5e0: driver_bound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815cb870)
Location: drivers/base/dd.c:235
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:device_bind_driver
```
**Symbols:**

```
ffffffff815cb870-ffffffff815cb958: driver_bound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815e0440)
Location: drivers/base/dd.c:236
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:device_bind_driver
```
**Symbols:**

```
ffffffff815e0440-ffffffff815e0528: driver_bound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81647500)
Location: drivers/base/dd.c:262
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:device_bind_driver
```
**Symbols:**

```
ffffffff81647500-ffffffff816475f6: driver_bound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816829f0)
Location: drivers/base/dd.c:259
Inline: False
Direct callers:
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff816829f0-ffffffff81682ae3: driver_bound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a2630)
Location: drivers/base/dd.c:324
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816a2630-ffffffff816a2723: driver_bound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:367
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816db400-ffffffff816db4db: driver_bound (STB_LOCAL)
ffffffff816dc309-ffffffff816dc325: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:367
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816ff3d0-ffffffff816ff4ae: driver_bound (STB_LOCAL)
ffffffff81700352-ffffffff8170036e: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:336
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817b9220-ffffffff817b9300: driver_bound (STB_LOCAL)
ffffffff817ba2ba-ffffffff817ba2d6: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:360
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817cdfd0-ffffffff817ce0b0: driver_bound (STB_LOCAL)
ffffffff81c0e33a-ffffffff81c0e356: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:374
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817b1960-ffffffff817b1a40: driver_bound (STB_LOCAL)
ffffffff81c00724-ffffffff81c00740: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:374
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff8183ac10-ffffffff8183acfc: driver_bound (STB_LOCAL)
ffffffff81d02e12-ffffffff81d02e42: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:388
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff8197d1d0-ffffffff8197d2ca: driver_bound (STB_LOCAL)
ffffffff81ecb557-ffffffff81ecb587: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:393
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff81aea590-ffffffff81aea6bd: driver_bound (STB_LOCAL)
ffffffff82098479-ffffffff8209848e: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:397
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff81b38920-ffffffff81b38a28: driver_bound (STB_LOCAL)
ffffffff821194ab-ffffffff821194c0: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:397
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff81b903e0-ffffffff81b904e8: driver_bound (STB_LOCAL)
ffffffff821f746e-ffffffff821f7483: driver_bound.cold (STB_LOCAL)
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
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108ea4b8)
Location: drivers/base/dd.c:367
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffff8000108ea4b8-ffff8000108ea5bc: driver_bound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d8578)
Location: drivers/base/dd.c:367
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
c09d8578-c09d8690: driver_bound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c0000000009815e0)
Location: drivers/base/dd.c:367
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
c0000000009815e0-c000000000981728: driver_bound (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057e32a)
Location: drivers/base/dd.c:367
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffe00057e32a-ffffffe00057e412: driver_bound (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:367
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816c4bc0-ffffffff816c4c9e: driver_bound (STB_LOCAL)
ffffffff816c5b42-ffffffff816c5b5e: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:367
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff8169fe40-ffffffff8169ff1e: driver_bound (STB_LOCAL)
ffffffff816a0dc2-ffffffff816a0dde: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:367
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816f3090-ffffffff816f316e: driver_bound (STB_LOCAL)
ffffffff816f4012-ffffffff816f402e: driver_bound.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void driver_bound(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/dd.c (0)
Location: drivers/base/dd.c:367
Inline: False
Direct callers:
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff8170d8c0-ffffffff8170d99e: driver_bound (STB_LOCAL)
ffffffff8170e83e-ffffffff8170e85a: driver_bound.cold (STB_LOCAL)
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
