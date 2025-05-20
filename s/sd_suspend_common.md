# Function: <code>sd_suspend_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff815bc8f0)
Location: drivers/scsi/sd.c:3266
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff815bc8f0-ffffffff815bc9d9: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816155e0)
Location: drivers/scsi/sd.c:3246
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff816155e0-ffffffff816156c9: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81645010)
Location: drivers/scsi/sd.c:3342
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81645010-ffffffff816450f9: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81658820)
Location: drivers/scsi/sd.c:3516
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81658820-ffffffff81658945: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c1e60)
Location: drivers/scsi/sd.c:3560
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff816c1e60-ffffffff816c1f85: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816fe4c0)
Location: drivers/scsi/sd.c:3534
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff816fe4c0-ffffffff816fe5e5: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81721090)
Location: drivers/scsi/sd.c:3572
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81721090-ffffffff817211b5: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175c760)
Location: drivers/scsi/sd.c:3537
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff8175c760-ffffffff8175c888: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81780630)
Location: drivers/scsi/sd.c:3549
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81780630-ffffffff81780758: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81846a60)
Location: drivers/scsi/sd.c:3587
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81846a60-ffffffff81846b81: sd_suspend_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81858590)
Location: drivers/scsi/sd.c:3632
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81858590-ffffffff818586b1: sd_suspend_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8183b510)
Location: drivers/scsi/sd.c:3649
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff8183b510-ffffffff8183b631: sd_suspend_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c7cc0)
Location: drivers/scsi/sd.c:3621
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff818c7cc0-ffffffff818c7de1: sd_suspend_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a14ad0)
Location: drivers/scsi/sd.c:3649
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81a14ad0-ffffffff81a14c17: sd_suspend_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b94f60)
Location: drivers/scsi/sd.c:3697
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81b94f60-ffffffff81b950a7: sd_suspend_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81beb4d0)
Location: drivers/scsi/sd.c:3819
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81beb4d0-ffffffff81beb616: sd_suspend_common.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c40b80)
Location: drivers/scsi/sd.c:3900
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81c40b80-ffffffff81c40cc9: sd_suspend_common.isra.0 (STB_LOCAL)
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
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff800010986d30)
Location: drivers/scsi/sd.c:3549
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffff800010986d30-ffff800010986e74: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a59034)
Location: drivers/scsi/sd.c:3549
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
c0a59034-c0a59154: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a46360)
Location: drivers/scsi/sd.c:3549
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
c000000000a46360-c000000000a46524: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005eb208)
Location: drivers/scsi/sd.c:3549
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffe0005eb208-ffffffe0005eb2fa: sd_suspend_common (STB_LOCAL)
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
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81734d20)
Location: drivers/scsi/sd.c:3549
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff81734d20-ffffffff81734e48: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817169c0)
Location: drivers/scsi/sd.c:3549
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff817169c0-ffffffff81716ae8: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817754b0)
Location: drivers/scsi/sd.c:3549
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff817754b0-ffffffff817755d8: sd_suspend_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sd_suspend_common(struct device *dev, bool ignore_stop_errors);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8178f290)
Location: drivers/scsi/sd.c:3549
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_suspend_runtime
  - drivers/scsi/sd.c:sd_suspend_system
```
**Symbols:**

```
ffffffff8178f290-ffffffff8178f3b8: sd_suspend_common (STB_LOCAL)
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
