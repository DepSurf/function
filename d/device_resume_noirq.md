# Function: <code>device_resume_noirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81558a50)
Location: drivers/base/power/main.c:474
Inline: False
Direct callers:
  - drivers/base/power/main.c:async_resume_noirq
  - drivers/base/power/main.c:dpm_resume_noirq
```
**Symbols:**

```
ffffffff81558a50-ffffffff81558bdc: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815aab90)
Location: drivers/base/power/main.c:476
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff815aab90-ffffffff815aad11: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815d9990)
Location: drivers/base/power/main.c:534
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff815d9990-ffffffff815d9b2d: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff815ee380)
Location: drivers/base/power/main.c:542
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff815ee380-ffffffff815ee524: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81656080)
Location: drivers/base/power/main.c:564
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81656080-ffffffff8165625d: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81691690)
Location: drivers/base/power/main.c:615
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81691690-ffffffff816918ea: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b1c80)
Location: drivers/base/power/main.c:616
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff816b1c80-ffffffff816b1eda: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816ebb20)
Location: drivers/base/power/main.c:608
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff816ebb20-ffffffff816ebd6f: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8170fbc0)
Location: drivers/base/power/main.c:636
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff8170fbc0-ffffffff8170fdf9: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817cbcd0)
Location: drivers/base/power/main.c:594
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff817cbcd0-ffffffff817cbef5: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817e0740)
Location: drivers/base/power/main.c:593
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff817e0740-ffffffff817e0965: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff817c4340)
Location: drivers/base/power/main.c:594
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff817c4340-ffffffff817c4565: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8184e720)
Location: drivers/base/power/main.c:591
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff8184e720-ffffffff8184e945: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81994710)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81994710-ffffffff81994970: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b051d0)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81b051d0-ffffffff81b05430: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81b52bc0)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81b52bc0-ffffffff81b52e20: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81bab890)
Location: drivers/base/power/main.c:590
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_noirq_resume_devices
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81bab890-ffffffff81babbee: device_resume_noirq (STB_LOCAL)
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
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffff800010900228)
Location: drivers/base/power/main.c:636
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffff800010900228-ffff800010900488: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c09ea480)
Location: drivers/base/power/main.c:636
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
c09ea480-c09ea6c8: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (c00000000099d930)
Location: drivers/base/power/main.c:636
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
c00000000099d930-c00000000099dc20: device_resume_noirq (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816d5b80)
Location: drivers/base/power/main.c:636
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff816d5b80-ffffffff816d5e64: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b05b0)
Location: drivers/base/power/main.c:636
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff816b05b0-ffffffff816b07e9: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81703880)
Location: drivers/base/power/main.c:636
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff81703880-ffffffff81703ab9: device_resume_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_resume_noirq(struct device *dev, pm_message_t state, bool async);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff8171e5d0)
Location: drivers/base/power/main.c:636
Inline: False
Direct callers:
  - drivers/base/power/main.c:dpm_resume_noirq
  - drivers/base/power/main.c:async_resume_noirq
```
**Symbols:**

```
ffffffff8171e5d0-ffffffff8171e809: device_resume_noirq (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
