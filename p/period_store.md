# Function: <code>period_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8142d650)
Location: drivers/pwm/sysfs.c:52
Inline: False
```
**Symbols:**

```
ffffffff8142d650-ffffffff8142d6d2: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff814788b0)
Location: drivers/pwm/sysfs.c:56
Inline: False
```
**Symbols:**

```
ffffffff814788b0-ffffffff81478962: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81499c40)
Location: drivers/pwm/sysfs.c:56
Inline: False
```
**Symbols:**

```
ffffffff81499c40-ffffffff81499cf2: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff814a3890)
Location: drivers/pwm/sysfs.c:56
Inline: False
```
**Symbols:**

```
ffffffff814a3890-ffffffff814a3942: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff814e2600)
Location: drivers/pwm/sysfs.c:56
Inline: False
```
**Symbols:**

```
ffffffff814e2600-ffffffff814e26b2: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81511e10)
Location: drivers/pwm/sysfs.c:56
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff817e0060)
Location: drivers/ptp/ptp_sysfs.c:109
Inline: False
```
**Symbols:**

```
ffffffff81511e10-ffffffff81511ebc: period_store (STB_LOCAL)
ffffffff817e0060-ffffffff817e0149: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81527540)
Location: drivers/pwm/sysfs.c:56
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8180b630)
Location: drivers/ptp/ptp_sysfs.c:109
Inline: False
```
**Symbols:**

```
ffffffff81527540-ffffffff815275ec: period_store (STB_LOCAL)
ffffffff8180b630-ffffffff8180b719: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81556530)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8184d310)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffffffff81556530-ffffffff815565db: period_store (STB_LOCAL)
ffffffff8184d310-ffffffff8184d3e8: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81577b50)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8187ed50)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffffffff81577b50-ffffffff81577bfb: period_store (STB_LOCAL)
ffffffff8187ed50-ffffffff8187ee28: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8161c820)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8194d250)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffffffff8161c820-ffffffff8161c8d3: period_store (STB_LOCAL)
ffffffff8194d250-ffffffff8194d326: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81643320)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81952c60)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffffffff81643320-ffffffff816433cd: period_store (STB_LOCAL)
ffffffff81952c60-ffffffff81952d36: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81626140)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81936ad0)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffffffff81626140-ffffffff816261ed: period_store (STB_LOCAL)
ffffffff81936ad0-ffffffff81936ba8: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81695930)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff819da580)
Location: drivers/ptp/ptp_sysfs.c:97
Inline: False
```
**Symbols:**

```
ffffffff81695930-ffffffff816959dd: period_store (STB_LOCAL)
ffffffff819da580-ffffffff819da65b: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff817b66b0)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81b3daf0)
Location: drivers/ptp/ptp_sysfs.c:97
Inline: False
```
**Symbols:**

```
ffffffff817b66b0-ffffffff817b6787: period_store (STB_LOCAL)
ffffffff81b3daf0-ffffffff81b3dbea: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff818d0c70)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81cd3c50)
Location: drivers/ptp/ptp_sysfs.c:97
Inline: False
```
**Symbols:**

```
ffffffff818d0c70-ffffffff818d0d47: period_store (STB_LOCAL)
ffffffff81cd3c50-ffffffff81cd3d4a: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81913c00)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81d3b860)
Location: drivers/ptp/ptp_sysfs.c:108
Inline: False
```
**Symbols:**

```
ffffffff81913c00-ffffffff81913cd7: period_store (STB_LOCAL)
ffffffff81d3b860-ffffffff81d3b95a: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8195bb40)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81df2190)
Location: drivers/ptp/ptp_sysfs.c:112
Inline: False
```
**Symbols:**

```
ffffffff8195bb40-ffffffff8195bc17: period_store (STB_LOCAL)
ffffffff81df2190-ffffffff81df228a: period_store (STB_LOCAL)
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
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffff8000106d9688)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffff800010ac8a18)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffff8000106d9688-ffff8000106d9754: period_store (STB_LOCAL)
ffff800010ac8a18-ffff800010ac8b30: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (c0876008)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (c0ba838c)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
c0876008-c08760c4: period_store (STB_LOCAL)
c0ba838c-c0ba8488: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (c000000000850fc0)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (c000000000baa3d0)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
c000000000850fc0-c0000000008510b8: period_store (STB_LOCAL)
c000000000baa3d0-c000000000baa534: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffe0004b2780)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffe0006c6d06)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffffffe0004b2780-ffffffe0004b2818: period_store (STB_LOCAL)
ffffffe0006c6d06-ffffffe0006c6de8: period_store (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8156c960)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff818272c0)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffffffff8156c960-ffffffff8156ca0b: period_store (STB_LOCAL)
ffffffff818272c0-ffffffff81827398: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t period_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_sysfs.c (ffffffff817ee950)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffffffff817ee950-ffffffff817eea28: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff8156b8a0)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff81874200)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffffffff8156b8a0-ffffffff8156b94b: period_store (STB_LOCAL)
ffffffff81874200-ffffffff818742d8: period_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
ssize_t period_store(struct device *child, struct device_attribute *attr, const char *buf, size_t size);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/sysfs.c (ffffffff81585da0)
Location: drivers/pwm/sysfs.c:48
Inline: False
```
```
In drivers/ptp/ptp_sysfs.c (ffffffff8188fbb0)
Location: drivers/ptp/ptp_sysfs.c:96
Inline: False
```
**Symbols:**

```
ffffffff81585da0-ffffffff81585e4b: period_store (STB_LOCAL)
ffffffff8188fbb0-ffffffff8188fc88: period_store (STB_LOCAL)
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
<details>
<summary>Changed between <code>generic</code> and <code>azure</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>size_t count</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *child</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
