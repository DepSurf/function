# Function: <code>devres_release_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815502a0)
Location: drivers/base/devres.c:508
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_probe_device
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff815502a0-ffffffff815502f8: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a20a0)
Location: drivers/base/devres.c:508
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff815a20a0-ffffffff815a20f8: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815d0810)
Location: drivers/base/devres.c:509
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff815d0810-ffffffff815d0868: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e5200)
Location: drivers/base/devres.c:509
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff815e5200-ffffffff815e5247: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164c4f0)
Location: drivers/base/devres.c:509
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff8164c4f0-ffffffff8164c539: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81687ae0)
Location: drivers/base/devres.c:513
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:driver_probe_device
```
**Symbols:**

```
ffffffff81687ae0-ffffffff81687b28: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a77c0)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816a77c0-ffffffff816a7808: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devres.c (0)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816e09d6-ffffffff816e09ee: devres_release_all.cold (STB_LOCAL)
ffffffff816e0930-ffffffff816e0977: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704b50)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff81704b50-ffffffff81704b9b: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817bf160)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817bf160-ffffffff817bf1ad: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d4070)
Location: drivers/base/devres.c:537
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817d4070-ffffffff817d40bd: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b7a80)
Location: drivers/base/devres.c:537
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817b7a80-ffffffff817b7acd: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81841380)
Location: drivers/base/devres.c:512
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff81841380-ffffffff81841447: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81984910)
Location: drivers/base/devres.c:512
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_unbind_cleanup
```
**Symbols:**

```
ffffffff81984910-ffffffff819849e1: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af2ad0)
Location: drivers/base/devres.c:517
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_unbind_cleanup
```
**Symbols:**

```
ffffffff81af2ad0-ffffffff81af2ba1: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b40cf0)
Location: drivers/base/devres.c:517
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_unbind_cleanup
```
**Symbols:**

```
ffffffff81b40cf0-ffffffff81b40dc1: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b98b90)
Location: drivers/base/devres.c:517
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_unbind_cleanup
```
**Symbols:**

```
ffffffff81b98b90-ffffffff81b98c61: devres_release_all (STB_GLOBAL)
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
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f0f28)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffff8000108f0f28-ffff8000108f0fe4: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09de0bc)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
c09de0bc-c09de11c: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c00000000098a2d0)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
c00000000098a2d0-c00000000098a344: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582f5c)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffe000582f5c-ffffffe000582fb0: devres_release_all (STB_GLOBAL)
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
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816ca2a0)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816ca2a0-ffffffff816ca2eb: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a55d0)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816a55d0-ffffffff816a561b: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f8810)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff816f8810-ffffffff816f885b: devres_release_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devres_release_all(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817130b0)
Location: drivers/base/devres.c:521
Inline: False
Direct callers:
  - drivers/base/core.c:device_release
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/base/dd.c:really_probe
```
**Symbols:**

```
ffffffff817130b0-ffffffff817130fb: devres_release_all (STB_GLOBAL)
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
