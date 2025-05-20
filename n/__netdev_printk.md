# Function: <code>__netdev_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817199f0)
Location: net/core/dev.c:7563
Inline: True
Direct callers:
  - net/core/dev.c:netdev_printk
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_info
```
**Symbols:**

```
ffffffff817199f0-ffffffff81719c3f: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81781ed0)
Location: net/core/dev.c:8081
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81781ed0-ffffffff8178211f: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817af7c0)
Location: net/core/dev.c:8246
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff817af7c0-ffffffff817afa0f: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ce0a0)
Location: net/core/dev.c:8447
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff817ce0a0-ffffffff817ce2bf: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81847910)
Location: net/core/dev.c:8630
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81847910-ffffffff81847b3b: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8881
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff818907b0-ffffffff81890909: __netdev_printk (STB_LOCAL)
ffffffff81898f90-ffffffff81898fe7: __netdev_printk.cold.156 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/dev.c (ffffffff818b1aff)
Location: net/core/dev.c:9514
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff818b1ac0-ffffffff818b1c19: __netdev_printk (STB_LOCAL)
ffffffff818bb465-ffffffff818bb4bc: __netdev_printk.cold.166 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81906cb9)
Location: net/core/dev.c:9619
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81906cb9-ffffffff81906dc1: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193939e)
Location: net/core/dev.c:9970
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff8193939e-ffffffff819394a6: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0e8c9)
Location: net/core/dev.c:10430
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81a0e8c9-ffffffff81a0e9a1: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c30bbd)
Location: net/core/dev.c:11139
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81c30bbd-ffffffff81c30c95: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c22ec3)
Location: net/core/dev.c:11417
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81c22ec3-ffffffff81c22f9b: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81d35988)
Location: net/core/dev.c:11424
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81d35988-ffffffff81d35a60: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81f01fab)
Location: net/core/dev.c:11206
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81f01fab-ffffffff81f02096: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:11210
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81dc34e0-ffffffff81dc36ea: __netdev_printk (STB_LOCAL)
ffffffff820ab421-ffffffff820ab44b: __netdev_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:11227
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81e32980-ffffffff81e32b8a: __netdev_printk (STB_LOCAL)
ffffffff8212ca56-ffffffff8212ca80: __netdev_printk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:11455
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff81ef0d80-ffffffff81ef0fbc: __netdev_printk (STB_LOCAL)
ffffffff8220e795-ffffffff8220e7bf: __netdev_printk.cold (STB_LOCAL)
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
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd8404)
Location: net/core/dev.c:9970
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffff800010bd8404-ffff800010bd8530: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf2d40)
Location: net/core/dev.c:9970
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
c0cf2d40-c0cf2e70: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb7dd8)
Location: net/core/dev.c:9970
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
c000000000cb7dd8-c000000000cb7f70: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007611d6)
Location: net/core/dev.c:9970
Inline: False
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffe0007611d6-ffffffe0007612f2: __netdev_printk (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d936e)
Location: net/core/dev.c:9970
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff818d936e-ffffffff818d9476: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818931ae)
Location: net/core/dev.c:9970
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff818931ae-ffffffff818932b6: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a39e)
Location: net/core/dev.c:9970
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff8192a39e-ffffffff8192a4a6: __netdev_printk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __netdev_printk(const char *level, const struct net_device *dev, struct va_format *vaf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8194ba96)
Location: net/core/dev.c:9970
Inline: True
Direct callers:
  - net/core/dev.c:netdev_info
  - net/core/dev.c:netdev_notice
  - net/core/dev.c:netdev_warn
  - net/core/dev.c:netdev_err
  - net/core/dev.c:netdev_crit
  - net/core/dev.c:netdev_alert
  - net/core/dev.c:netdev_emerg
  - net/core/dev.c:netdev_printk
```
**Symbols:**

```
ffffffff8194ba96-ffffffff8194bb9e: __netdev_printk (STB_LOCAL)
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
