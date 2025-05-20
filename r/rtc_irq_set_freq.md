# Function: <code>rtc_irq_set_freq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, struct rtc_task *task, int freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81674980)
Location: drivers/rtc/interface.c:711
Inline: True
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81674980-ffffffff81674a40: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, struct rtc_task *task, int freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816d5180)
Location: drivers/rtc/interface.c:719
Inline: True
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff816d5180-ffffffff816d5241: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, struct rtc_task *task, int freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81704e60)
Location: drivers/rtc/interface.c:719
Inline: True
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81704e60-ffffffff81704f21: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, struct rtc_task *task, int freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8171a940)
Location: drivers/rtc/interface.c:726
Inline: True
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff8171a940-ffffffff8171aa01: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, struct rtc_task *task, int freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8178bbe0)
Location: drivers/rtc/interface.c:726
Inline: True
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff8178bbe0-ffffffff8178bca1: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, struct rtc_task *task, int freq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817cd160)
Location: drivers/rtc/interface.c:826
Inline: True
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff817cd160-ffffffff817cd26a: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f5710)
Location: drivers/rtc/interface.c:765
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff817f5710-ffffffff817f57b4: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff818363d0)
Location: drivers/rtc/interface.c:756
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff818363d0-ffffffff81836474: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81867d40)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81867d40-ffffffff81867de4: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8193b850)
Location: drivers/rtc/interface.c:778
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff8193b850-ffffffff8193b91f: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81941b90)
Location: drivers/rtc/interface.c:778
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81941b90-ffffffff81941c50: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81925320)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81925320-ffffffff819253e0: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819c82b0)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff819c82b0-ffffffff819c836d: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81b290c0)
Location: drivers/rtc/interface.c:775
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81b290c0-ffffffff81b291a3: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81cbcc40)
Location: drivers/rtc/interface.c:775
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81cbcc40-ffffffff81cbcd38: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81d24550)
Location: drivers/rtc/interface.c:775
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81d24550-ffffffff81d24648: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81dda2b0)
Location: drivers/rtc/interface.c:775
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81dda2b0-ffffffff81dda3a8: rtc_irq_set_freq (STB_GLOBAL)
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
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa99a0)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffff800010aa99a0-ffff800010aa9a90: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c0b88794)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
c0b88794-c0b888ac: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c000000000b8bab0)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
c000000000b8bab0-c000000000b8bbdc: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b506e)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffe0006b506e-ffffffe0006b511a: rtc_irq_set_freq (STB_GLOBAL)
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
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8181a9f0)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff8181a9f0-ffffffff8181aa94: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e20e0)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff817e20e0-ffffffff817e2184: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8185bed0)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff8185bed0-ffffffff8185bf74: rtc_irq_set_freq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtc_irq_set_freq(struct rtc_device *rtc, int freq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff818770c0)
Location: drivers/rtc/interface.c:764
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff818770c0-ffffffff8187717d: rtc_irq_set_freq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct rtc_task *task</code>
</li>
<li>
<b>Param reordered. </b>
<code>rtc, task, freq</code> ➡️ <code>rtc, freq</code>
</li>
</ul>
</details>
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
