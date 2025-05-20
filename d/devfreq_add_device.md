# Function: <code>devfreq_add_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff816ed110)
Location: drivers/devfreq/devfreq.c:439
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff816ed110-ffffffff816ed43c: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81752020)
Location: drivers/devfreq/devfreq.c:519
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff81752020-ffffffff81752375: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8177de10)
Location: drivers/devfreq/devfreq.c:524
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff8177de10-ffffffff8177e169: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8179c8a0)
Location: drivers/devfreq/devfreq.c:513
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff8179c8a0-ffffffff8179cbe8: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81813820)
Location: drivers/devfreq/devfreq.c:556
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff81813820-ffffffff81813d27: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8185d6e0)
Location: drivers/devfreq/devfreq.c:556
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff8185d6e0-ffffffff8185db85: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8187d000)
Location: drivers/devfreq/devfreq.c:607
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff8187d000-ffffffff8187d4ac: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff818c7ca9-ffffffff818c7d36: devfreq_add_device.cold (STB_LOCAL)
ffffffff818c7280-ffffffff818c76d0: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff818fa11b-ffffffff818fa1c0: devfreq_add_device.cold (STB_LOCAL)
ffffffff818f96f0-ffffffff818f9bad: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:731
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff819d0bb0-ffffffff819d0c4b: devfreq_add_device.cold (STB_LOCAL)
ffffffff819d0250-ffffffff819d0735: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:777
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff81c2f4b4-ffffffff81c2f54f: devfreq_add_device.cold (STB_LOCAL)
ffffffff819cfcc0-ffffffff819d0191: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:781
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff81c21779-ffffffff81c21814: devfreq_add_device.cold (STB_LOCAL)
ffffffff819b4e10-ffffffff819b5406: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:781
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff81d3330c-ffffffff81d333bb: devfreq_add_device.cold (STB_LOCAL)
ffffffff81a63980-ffffffff81a63f7c: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:778
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff81eff74f-ffffffff81eff7e6: devfreq_add_device.cold (STB_LOCAL)
ffffffff81bd46f0-ffffffff81bd4d2e: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:781
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff820aa4a1-ffffffff820aa4b6: devfreq_add_device.cold (STB_LOCAL)
ffffffff81d80760-ffffffff81d80e20: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:782
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff8212b98c-ffffffff8212b9a1: devfreq_add_device.cold (STB_LOCAL)
ffffffff81deeb10-ffffffff81def1ce: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:803
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff8220d621-ffffffff8220d636: devfreq_add_device.cold (STB_LOCAL)
ffffffff81ea5090-ffffffff81ea5783: devfreq_add_device (STB_GLOBAL)
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
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffff800010b85da8)
Location: drivers/devfreq/devfreq.c:609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffff800010b85da8-ffff800010b86268: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c0c68e04)
Location: drivers/devfreq/devfreq.c:609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
c0c68e04-c0c69300: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c000000000c64970)
Location: drivers/devfreq/devfreq.c:609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
c000000000c64970-c000000000c64f9c: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072f28a)
Location: drivers/devfreq/devfreq.c:609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffe00072f28a-ffffffe00072f6ea: devfreq_add_device (STB_GLOBAL)
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
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff8189b44b-ffffffff8189b4f0: devfreq_add_device.cold (STB_LOCAL)
ffffffff8189aa20-ffffffff8189aedd: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff8185891b-ffffffff818589c0: devfreq_add_device.cold (STB_LOCAL)
ffffffff81857ef0-ffffffff818583ad: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff818eab3b-ffffffff818eabe0: devfreq_add_device.cold (STB_LOCAL)
ffffffff818ea110-ffffffff818ea5cd: devfreq_add_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct devfreq *devfreq_add_device(struct device *dev, struct devfreq_dev_profile *profile, const char *governor_name, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (0)
Location: drivers/devfreq/devfreq.c:609
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_add_device
```
**Symbols:**

```
ffffffff8190bbbb-ffffffff8190bc60: devfreq_add_device.cold (STB_LOCAL)
ffffffff8190b190-ffffffff8190b64d: devfreq_add_device (STB_GLOBAL)
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
