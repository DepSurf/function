# Function: <code>devfreq_unregister_notifier</code>

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
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8175187b)
Location: drivers/devfreq/devfreq.c:1381
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
```
**Symbols:**

```
ffffffff81751840-ffffffff81751866: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8177d64b)
Location: drivers/devfreq/devfreq.c:1416
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
```
**Symbols:**

```
ffffffff8177d610-ffffffff8177d636: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8179c1b8)
Location: drivers/devfreq/devfreq.c:1385
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
```
**Symbols:**

```
ffffffff8179c180-ffffffff8179c1a6: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81813508)
Location: drivers/devfreq/devfreq.c:1447
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
```
**Symbols:**

```
ffffffff818134d0-ffffffff818134f6: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8185d3cf)
Location: drivers/devfreq/devfreq.c:1450
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
```
**Symbols:**

```
ffffffff8185d390-ffffffff8185d3b6: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8187c61f)
Location: drivers/devfreq/devfreq.c:1597
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
```
**Symbols:**

```
ffffffff8187c5e0-ffffffff8187c606: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818c691f)
Location: drivers/devfreq/devfreq.c:1622
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
```
**Symbols:**

```
ffffffff818c68e0-ffffffff818c6906: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818f8d1f)
Location: drivers/devfreq/devfreq.c:1635
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff818f8ce0-ffffffff818f8d06: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cfecf)
Location: drivers/devfreq/devfreq.c:1892
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff819ceec0-ffffffff819ceee6: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cfbff)
Location: drivers/devfreq/devfreq.c:2118
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff819cea40-ffffffff819cea66: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819b4d3f)
Location: drivers/devfreq/devfreq.c:2136
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff819b3ba0-ffffffff819b3bc6: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81a6388f)
Location: drivers/devfreq/devfreq.c:2136
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81a62550-ffffffff81a62576: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81bd45bf)
Location: drivers/devfreq/devfreq.c:2164
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81bd35b0-ffffffff81bd35ea: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81d805ff)
Location: drivers/devfreq/devfreq.c:2166
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81d7f4d0-ffffffff81d7f50a: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81dee98f)
Location: drivers/devfreq/devfreq.c:2167
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81ded860-ffffffff81ded89a: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81ea4f0f)
Location: drivers/devfreq/devfreq.c:2206
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff81ea3c00-ffffffff81ea3c3a: devfreq_unregister_notifier (STB_GLOBAL)
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
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffff800010b85a04)
Location: drivers/devfreq/devfreq.c:1635
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffff800010b85990-ffff800010b859e4: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c0c68780)
Location: drivers/devfreq/devfreq.c:1635
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
c0c6871c-c0c6875c: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (c000000000c63820)
Location: drivers/devfreq/devfreq.c:1635
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
c000000000c637a0-c000000000c637f8: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffe00072ec88)
Location: drivers/devfreq/devfreq.c:1635
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffe00072ec28-ffffffe00072ec6c: devfreq_unregister_notifier (STB_GLOBAL)
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
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8189a04f)
Location: drivers/devfreq/devfreq.c:1635
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff8189a010-ffffffff8189a036: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8185751f)
Location: drivers/devfreq/devfreq.c:1635
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff818574e0-ffffffff81857506: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818e973f)
Location: drivers/devfreq/devfreq.c:1635
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff818e9700-ffffffff818e9726: devfreq_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devfreq_unregister_notifier(struct devfreq *devfreq, struct notifier_block *nb, unsigned int list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8190a7bf)
Location: drivers/devfreq/devfreq.c:1635
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devm_devfreq_notifier_release
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_event_handler
```
**Symbols:**

```
ffffffff8190a780-ffffffff8190a7a6: devfreq_unregister_notifier (STB_GLOBAL)
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
