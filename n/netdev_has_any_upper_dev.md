# Function: <code>netdev_has_any_upper_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81716764)
Location: net/core/dev.c:4947
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177e79a)
Location: net/core/dev.c:5291
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ac026)
Location: net/core/dev.c:5466
Inline: True
Inline callers:
  - net/core/dev.c:rollback_registered_many
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c7fc0)
Location: net/core/dev.c:5671
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff817c7fc0-ffffffff817c800c: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81841b60)
Location: net/core/dev.c:5812
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81841b60-ffffffff81841bac: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188bff0)
Location: net/core/dev.c:5942
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8188bff0-ffffffff8188c049: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ad370)
Location: net/core/dev.c:6517
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818ad370-ffffffff818ad3c9: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f8c70)
Location: net/core/dev.c:6527
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818f8c70-ffffffff818f8cc9: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192ae10)
Location: net/core/dev.c:6470
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8192ae10-ffffffff8192ae69: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819feaa0)
Location: net/core/dev.c:6861
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff819feaa0-ffffffff819feafc: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe730)
Location: net/core/dev.c:7018
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff819fe730-ffffffff819fe78c: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e4fa0)
Location: net/core/dev.c:7277
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff819e4fa0-ffffffff819e4ffc: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7267
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff81d3580c-ffffffff81d35821: netdev_has_any_upper_dev.cold (STB_LOCAL)
ffffffff81a96e80-ffffffff81a96eec: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6788
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff81f01df9-ffffffff81f01e0e: netdev_has_any_upper_dev.cold (STB_LOCAL)
ffffffff81c0dcd0-ffffffff81c0dd46: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6774
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff820ab17b-ffffffff820ab190: netdev_has_any_upper_dev.cold (STB_LOCAL)
ffffffff81dbdb50-ffffffff81dbdbc6: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6779
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff8212c824-ffffffff8212c839: netdev_has_any_upper_dev.cold (STB_LOCAL)
ffffffff81e2e3a0-ffffffff81e2e416: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6897
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff8220e563-ffffffff8220e578: netdev_has_any_upper_dev.cold (STB_LOCAL)
ffffffff81eec8c0-ffffffff81eec936: netdev_has_any_upper_dev (STB_GLOBAL)
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
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bc7738)
Location: net/core/dev.c:6470
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffff800010bc7738-ffff800010bc77ac: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce2c18)
Location: net/core/dev.c:6470
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
c0ce2c18-c0ce2c94: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca2ca0)
Location: net/core/dev.c:6470
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
c000000000ca2ca0-c000000000ca2d40: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000753c6e)
Location: net/core/dev.c:6470
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffe000753c6e-ffffffe000753cdc: netdev_has_any_upper_dev (STB_GLOBAL)
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
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cae10)
Location: net/core/dev.c:6470
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818cae10-ffffffff818cae69: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81884d50)
Location: net/core/dev.c:6470
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81884d50-ffffffff81884da9: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191be10)
Location: net/core/dev.c:6470
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8191be10-ffffffff8191be69: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool netdev_has_any_upper_dev(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193d2f0)
Location: net/core/dev.c:6470
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8193d2f0-ffffffff8193d349: netdev_has_any_upper_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
