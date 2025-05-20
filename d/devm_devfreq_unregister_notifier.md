# Function: <code>devm_devfreq_unregister_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81751fe0)
Location: drivers/devfreq/devfreq.c:1460
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81751fe0-ffffffff81752018: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8177ddd0)
Location: drivers/devfreq/devfreq.c:1495
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff8177ddd0-ffffffff8177de08: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8179ccf0)
Location: drivers/devfreq/devfreq.c:1464
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff8179ccf0-ffffffff8179cd19: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81813e30)
Location: drivers/devfreq/devfreq.c:1526
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81813e30-ffffffff81813e59: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8185dc90)
Location: drivers/devfreq/devfreq.c:1529
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff8185dc90-ffffffff8185dcb9: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8187d5b0)
Location: drivers/devfreq/devfreq.c:1676
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff8187d5b0-ffffffff8187d5d9: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818c7c96)
Location: drivers/devfreq/devfreq.c:1701
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff818c7c96-ffffffff818c7ca9: devm_devfreq_unregister_notifier.cold (STB_LOCAL)
ffffffff818c7250-ffffffff818c7279: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818f96c0)
Location: drivers/devfreq/devfreq.c:1714
Inline: True
```
**Symbols:**

```
ffffffff818f96c0-ffffffff818f96e9: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cf4f0)
Location: drivers/devfreq/devfreq.c:1971
Inline: True
```
**Symbols:**

```
ffffffff819cf4f0-ffffffff819cf519: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cf180)
Location: drivers/devfreq/devfreq.c:2197
Inline: True
```
**Symbols:**

```
ffffffff819cf180-ffffffff819cf1a9: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819b42e0)
Location: drivers/devfreq/devfreq.c:2215
Inline: True
```
**Symbols:**

```
ffffffff819b42e0-ffffffff819b4309: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81a61d40)
Location: drivers/devfreq/devfreq.c:2215
Inline: False
```
**Symbols:**

```
ffffffff81a61d40-ffffffff81a61d69: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81bd2bb0)
Location: drivers/devfreq/devfreq.c:2243
Inline: False
```
**Symbols:**

```
ffffffff81bd2bb0-ffffffff81bd2bf5: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d7e9f0)
Location: drivers/devfreq/devfreq.c:2245
Inline: False
```
**Symbols:**

```
ffffffff81d7e9f0-ffffffff81d7ea35: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81decd80)
Location: drivers/devfreq/devfreq.c:2246
Inline: False
```
**Symbols:**

```
ffffffff81decd80-ffffffff81decdc5: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea3120)
Location: drivers/devfreq/devfreq.c:2285
Inline: False
```
**Symbols:**

```
ffffffff81ea3120-ffffffff81ea3165: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffff800010b863c0)
Location: drivers/devfreq/devfreq.c:1714
Inline: True
```
**Symbols:**

```
ffff800010b863c0-ffff800010b86418: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c0c69648)
Location: drivers/devfreq/devfreq.c:1714
Inline: True
```
**Symbols:**

```
c0c69648-c0c69698: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c000000000c626f0)
Location: drivers/devfreq/devfreq.c:1714
Inline: False
```
**Symbols:**

```
c000000000c626f0-c000000000c62748: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072f238)
Location: drivers/devfreq/devfreq.c:1714
Inline: True
```
**Symbols:**

```
ffffffe00072f238-ffffffe00072f28a: devm_devfreq_unregister_notifier (STB_GLOBAL)
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
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8189a9f0)
Location: drivers/devfreq/devfreq.c:1714
Inline: True
```
**Symbols:**

```
ffffffff8189a9f0-ffffffff8189aa19: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81857ec0)
Location: drivers/devfreq/devfreq.c:1714
Inline: True
```
**Symbols:**

```
ffffffff81857ec0-ffffffff81857ee9: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818ea0e0)
Location: drivers/devfreq/devfreq.c:1714
Inline: True
```
**Symbols:**

```
ffffffff818ea0e0-ffffffff818ea109: devm_devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_devfreq_unregister_notifier(struct device *dev, struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8190b160)
Location: drivers/devfreq/devfreq.c:1714
Inline: True
```
**Symbols:**

```
ffffffff8190b160-ffffffff8190b189: devm_devfreq_unregister_notifier (STB_GLOBAL)
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
