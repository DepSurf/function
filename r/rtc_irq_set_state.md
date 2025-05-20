# Function: <code>rtc_irq_set_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, struct rtc_task *task, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81673f00)
Location: drivers/rtc/interface.c:677
Inline: False
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_release
```
**Symbols:**

```
ffffffff81673f00-ffffffff81673fa0: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, struct rtc_task *task, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff816d46e0)
Location: drivers/rtc/interface.c:685
Inline: False
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_release
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff816d46e0-ffffffff816d4780: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, struct rtc_task *task, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817043c0)
Location: drivers/rtc/interface.c:685
Inline: False
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_release
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff817043c0-ffffffff81704460: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, struct rtc_task *task, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81719fa0)
Location: drivers/rtc/interface.c:692
Inline: False
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_release
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81719fa0-ffffffff8171a040: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, struct rtc_task *task, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8178b210)
Location: drivers/rtc/interface.c:692
Inline: False
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_release
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff8178b210-ffffffff8178b2b0: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, struct rtc_task *task, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817cca30)
Location: drivers/rtc/interface.c:790
Inline: False
Direct callers:
  - drivers/rtc/rtc-dev.c:rtc_dev_release
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
  - drivers/rtc/rtc-dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff817cca30-ffffffff817ccb1c: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f5690)
Location: drivers/rtc/interface.c:743
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff817f5690-ffffffff817f570c: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81836350)
Location: drivers/rtc/interface.c:734
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81836350-ffffffff818363cc: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81867cc0)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81867cc0-ffffffff81867d3c: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8193b790)
Location: drivers/rtc/interface.c:756
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff8193b790-ffffffff8193b841: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81941af0)
Location: drivers/rtc/interface.c:756
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81941af0-ffffffff81941b90: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81925280)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81925280-ffffffff81925320: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819c8210)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff819c8210-ffffffff819c82ad: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81b29000)
Location: drivers/rtc/interface.c:753
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81b29000-ffffffff81b290b7: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81cbcb70)
Location: drivers/rtc/interface.c:753
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81cbcb70-ffffffff81cbcc27: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81d24480)
Location: drivers/rtc/interface.c:753
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81d24480-ffffffff81d24537: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81dda1e0)
Location: drivers/rtc/interface.c:753
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81dda1e0-ffffffff81dda297: rtc_irq_set_state (STB_GLOBAL)
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
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa98e0)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffff800010aa98e0-ffff800010aa99a0: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c0b886a8)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
c0b886a8-c0b88794: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (c000000000b8b9b0)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
c000000000b8b9b0-c000000000b8baa4: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b4fd4)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffe0006b4fd4-ffffffe0006b506e: rtc_irq_set_state (STB_GLOBAL)
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
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8181a970)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff8181a970-ffffffff8181a9ec: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e2060)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff817e2060-ffffffff817e20dc: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8185be50)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff8185be50-ffffffff8185becc: rtc_irq_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rtc_irq_set_state(struct rtc_device *rtc, int enabled);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81877030)
Location: drivers/rtc/interface.c:742
Inline: False
Direct callers:
  - drivers/rtc/dev.c:rtc_dev_release
  - drivers/rtc/dev.c:rtc_dev_ioctl
  - drivers/rtc/dev.c:rtc_dev_ioctl
```
**Symbols:**

```
ffffffff81877030-ffffffff818770bc: rtc_irq_set_state (STB_GLOBAL)
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
<code>rtc, task, enabled</code> ➡️ <code>rtc, enabled</code>
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
