# Function: <code>watchdog_cdev_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff816ecad6)
Location: drivers/watchdog/watchdog_dev.c:809
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
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
In drivers/watchdog/watchdog_dev.c (ffffffff8171db76)
Location: drivers/watchdog/watchdog_dev.c:899
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff81735da6)
Location: drivers/watchdog/watchdog_dev.c:907
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817a7b26)
Location: drivers/watchdog/watchdog_dev.c:910
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817ef590)
Location: drivers/watchdog/watchdog_dev.c:930
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8181b456)
Location: drivers/watchdog/watchdog_dev.c:930
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8185d6a0)
Location: drivers/watchdog/watchdog_dev.c:956
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:960
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8188e610-ffffffff8188e884: watchdog_cdev_register (STB_LOCAL)
ffffffff8188f49f-ffffffff8188f546: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:981
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8195d210-ffffffff8195d484: watchdog_cdev_register (STB_LOCAL)
ffffffff8195e141-ffffffff8195e1e8: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:982
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81963bc0-ffffffff81963e31: watchdog_cdev_register (STB_LOCAL)
ffffffff81c25edd-ffffffff81c25f84: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:982
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81947fe0-ffffffff81948251: watchdog_cdev_register (STB_LOCAL)
ffffffff81c18062-ffffffff81c18109: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:988
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff819ecf80-ffffffff819ed200: watchdog_cdev_register (STB_LOCAL)
ffffffff81d27435-ffffffff81d274f1: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:993
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81b53870-ffffffff81b53b0c: watchdog_cdev_register (STB_LOCAL)
ffffffff81ef32c5-ffffffff81ef3384: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:1001
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81cec720-ffffffff81ceca5f: watchdog_cdev_register (STB_LOCAL)
ffffffff820a7d5e-ffffffff820a7d72: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:1022
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81d55440-ffffffff81d5577f: watchdog_cdev_register (STB_LOCAL)
ffffffff8212913c-ffffffff82129150: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:1022
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81e0c310-ffffffff81e0c687: watchdog_cdev_register (STB_LOCAL)
ffffffff8220ab25-ffffffff8220ab39: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffff800010ae0a5c)
Location: drivers/watchdog/watchdog_dev.c:960
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c0bc0cb8)
Location: drivers/watchdog/watchdog_dev.c:960
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
c0bc0cb8-c0bc0f98: watchdog_cdev_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (c000000000bc7090)
Location: drivers/watchdog/watchdog_dev.c:960
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
c000000000bc7090-c000000000bc7480: watchdog_cdev_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d7d80)
Location: drivers/watchdog/watchdog_dev.c:960
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:960
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81834490-ffffffff81834704: watchdog_cdev_register (STB_LOCAL)
ffffffff8183531f-ffffffff818353c6: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:960
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff817fbb20-ffffffff817fbd94: watchdog_cdev_register (STB_LOCAL)
ffffffff817fc9af-ffffffff817fca56: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:960
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff81883ac0-ffffffff81883d34: watchdog_cdev_register (STB_LOCAL)
ffffffff8188494f-ffffffff818849f6: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int watchdog_cdev_register(struct watchdog_device *wdd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (0)
Location: drivers/watchdog/watchdog_dev.c:960
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_register
```
**Symbols:**

```
ffffffff8189f580-ffffffff8189f7f4: watchdog_cdev_register (STB_LOCAL)
ffffffff818a040f-ffffffff818a04b6: watchdog_cdev_register.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
