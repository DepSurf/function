# Function: <code>nd_device_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ec6d0)
Location: drivers/nvdimm/bus.c:148
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff815ec6d0-ffffffff815ec71f: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816194b0)
Location: drivers/nvdimm/bus.c:148
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff816194b0-ffffffff816194ff: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162d2f0)
Location: drivers/nvdimm/bus.c:150
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff8162d2f0-ffffffff8162d33f: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81695a90)
Location: drivers/nvdimm/bus.c:151
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff81695a90-ffffffff81695ae2: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d1b40)
Location: drivers/nvdimm/bus.c:154
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff816d1b40-ffffffff816d1b92: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f31d0)
Location: drivers/nvdimm/bus.c:148
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff816f31d0-ffffffff816f3222: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172c730)
Location: drivers/nvdimm/bus.c:147
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff8172c730-ffffffff8172c785: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81750970)
Location: drivers/nvdimm/bus.c:145
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff81750970-ffffffff817509c5: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff818102bf)
Location: drivers/nvdimm/bus.c:145
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
Direct callers:
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff8180f1c0-ffffffff8180f215: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181f1ff)
Location: drivers/nvdimm/bus.c:145
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
Direct callers:
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff8181e100-ffffffff8181e155: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8180251f)
Location: drivers/nvdimm/bus.c:144
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
Direct callers:
  - drivers/nvdimm/region_devs.c:revalidate_read_only
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff81801450-ffffffff818014a5: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188c9ff)
Location: drivers/nvdimm/bus.c:143
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
Direct callers:
  - drivers/nvdimm/region_devs.c:revalidate_read_only
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff8188b8a0-ffffffff8188b8f5: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff819d5ece)
Location: drivers/nvdimm/bus.c:134
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
Direct callers:
  - drivers/nvdimm/region_devs.c:revalidate_read_only
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff819d4ca0-ffffffff819d4cfc: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b50abe)
Location: drivers/nvdimm/bus.c:134
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
Direct callers:
  - drivers/nvdimm/region_devs.c:revalidate_read_only
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff81b4f5c0-ffffffff81b4f61c: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba3f5e)
Location: drivers/nvdimm/bus.c:134
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
Direct callers:
  - drivers/nvdimm/region_devs.c:revalidate_read_only
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff81ba2b80-ffffffff81ba2bdc: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf814e)
Location: drivers/nvdimm/bus.c:134
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
Direct callers:
  - drivers/nvdimm/region_devs.c:revalidate_read_only
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff81bf6d40-ffffffff81bf6d9c: nd_device_notify (STB_GLOBAL)
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
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffff800010950878)
Location: drivers/nvdimm/bus.c:145
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffff800010950878-ffff8000109508d8: nd_device_notify (STB_GLOBAL)
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
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fd260)
Location: drivers/nvdimm/bus.c:145
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
c0000000009fd260-c0000000009fd2f8: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c09e8)
Location: drivers/nvdimm/bus.c:145
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffe0005c09e8-ffffffe0005c0a38: nd_device_notify (STB_GLOBAL)
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
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81705060)
Location: drivers/nvdimm/bus.c:145
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff81705060-ffffffff817050b5: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d8ae0)
Location: drivers/nvdimm/bus.c:145
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff816d8ae0-ffffffff816d8b35: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81743e30)
Location: drivers/nvdimm/bus.c:145
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff81743e30-ffffffff81743e85: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nd_device_notify(struct device *dev, enum nvdimm_event event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8175f280)
Location: drivers/nvdimm/bus.c:145
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_region_notify
  - drivers/nvdimm/region.c:child_notify
```
**Symbols:**

```
ffffffff8175f280-ffffffff8175f2d5: nd_device_notify (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
