# Function: <code>__device_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815595c0)
Location: drivers/base/power/main.c:1345
Inline: False
Direct callers:
  - drivers/base/power/main.c:async_suspend
  - drivers/base/power/main.c:dpm_suspend
```
**Symbols:**

```
ffffffff815595c0-ffffffff81559930: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ab720)
Location: drivers/base/power/main.c:1351
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff815ab720-ffffffff815aba99: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815da4b0)
Location: drivers/base/power/main.c:1425
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff815da4b0-ffffffff815da83d: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815eef00)
Location: drivers/base/power/main.c:1428
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff815eef00-ffffffff815ef296: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816562b0)
Location: drivers/base/power/main.c:1519
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff816562b0-ffffffff816566ff: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1704
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff81691e70-ffffffff816922e5: __device_suspend (STB_LOCAL)
ffffffff81694472-ffffffff81694490: __device_suspend.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1706
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff816b24d0-ffffffff816b2955: __device_suspend (STB_LOCAL)
ffffffff816b4af2-ffffffff816b4b10: __device_suspend.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1692
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff816ec2a0-ffffffff816ec771: __device_suspend (STB_LOCAL)
ffffffff816ee994-ffffffff816ee9c5: __device_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1713
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff81710310-ffffffff817107e1: __device_suspend (STB_LOCAL)
ffffffff81712974-ffffffff817129a5: __device_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cb920)
Location: drivers/base/power/main.c:1591
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff817cb920-ffffffff817cbcce: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817e0390)
Location: drivers/base/power/main.c:1590
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff817e0390-ffffffff817e073e: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c4ef0)
Location: drivers/base/power/main.c:1591
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff817c4ef0-ffffffff817c52e7: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8184f2c0)
Location: drivers/base/power/main.c:1610
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff8184f2c0-ffffffff8184f6cb: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff819942f0)
Location: drivers/base/power/main.c:1606
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff819942f0-ffffffff81994702: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b04d10)
Location: drivers/base/power/main.c:1606
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff81b04d10-ffffffff81b05122: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1606
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff81b525c0-ffffffff81b52b18: __device_suspend (STB_LOCAL)
ffffffff8211990d-ffffffff82119930: __device_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1605
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff81baac70-ffffffff81bab1c8: __device_suspend (STB_LOCAL)
ffffffff821f78cf-ffffffff821f78f2: __device_suspend.cold (STB_LOCAL)
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
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff8000109009e0)
Location: drivers/base/power/main.c:1713
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffff8000109009e0-ffff800010900fe4: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09eacc8)
Location: drivers/base/power/main.c:1713
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
c09eacc8-c09eb220: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099e230)
Location: drivers/base/power/main.c:1713
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
c00000000099e230-c00000000099ea7c: __device_suspend (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1713
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff816d6470-ffffffff816d6b70: __device_suspend (STB_LOCAL)
ffffffff816d8cf4-ffffffff816d8d25: __device_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1713
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff816b0d00-ffffffff816b11c5: __device_suspend (STB_LOCAL)
ffffffff816b3334-ffffffff816b3365: __device_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1713
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff81703fd0-ffffffff817044a1: __device_suspend (STB_LOCAL)
ffffffff81706634-ffffffff81706665: __device_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __device_suspend(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/power/main.c (0)
Location: drivers/base/power/main.c:1713
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_suspend
  - drivers/base/power/main.c:async_suspend
```
**Symbols:**

```
ffffffff8171e0d0-ffffffff8171e5c1: __device_suspend (STB_LOCAL)
ffffffff81721044-ffffffff81721075: __device_suspend.cold (STB_LOCAL)
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
