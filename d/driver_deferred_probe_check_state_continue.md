# Function: <code>driver_deferred_probe_check_state_continue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int driver_deferred_probe_check_state_continue(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816dbaf0)
Location: drivers/base/dd.c:290
Inline: False
```
**Symbols:**

```
ffffffff816dbaf0-ffffffff816dbb24: driver_deferred_probe_check_state_continue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int driver_deferred_probe_check_state_continue(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816ffb00)
Location: drivers/base/dd.c:290
Inline: False
```
**Symbols:**

```
ffffffff816ffb00-ffffffff816ffb34: driver_deferred_probe_check_state_continue (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int driver_deferred_probe_check_state_continue(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108eacd0)
Location: drivers/base/dd.c:290
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
**Symbols:**

```
ffff8000108eacd0-ffff8000108ead20: driver_deferred_probe_check_state_continue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int driver_deferred_probe_check_state_continue(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d8e08)
Location: drivers/base/dd.c:290
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
**Symbols:**

```
c09d8e08-c09d8e5c: driver_deferred_probe_check_state_continue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int driver_deferred_probe_check_state_continue(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c000000000982060)
Location: drivers/base/dd.c:290
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
**Symbols:**

```
c000000000982060-c0000000009820c4: driver_deferred_probe_check_state_continue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int driver_deferred_probe_check_state_continue(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057ea3c)
Location: drivers/base/dd.c:290
Inline: False
Direct callers:
  - drivers/pinctrl/devicetree.c:pinctrl_dt_to_map
```
**Symbols:**

```
ffffffe00057ea3c-ffffffe00057ea84: driver_deferred_probe_check_state_continue (STB_GLOBAL)
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
int driver_deferred_probe_check_state_continue(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c52f0)
Location: drivers/base/dd.c:290
Inline: False
```
**Symbols:**

```
ffffffff816c52f0-ffffffff816c5324: driver_deferred_probe_check_state_continue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int driver_deferred_probe_check_state_continue(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a0570)
Location: drivers/base/dd.c:290
Inline: False
```
**Symbols:**

```
ffffffff816a0570-ffffffff816a05a4: driver_deferred_probe_check_state_continue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int driver_deferred_probe_check_state_continue(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f37c0)
Location: drivers/base/dd.c:290
Inline: False
```
**Symbols:**

```
ffffffff816f37c0-ffffffff816f37f4: driver_deferred_probe_check_state_continue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int driver_deferred_probe_check_state_continue(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170dff0)
Location: drivers/base/dd.c:290
Inline: False
```
**Symbols:**

```
ffffffff8170dff0-ffffffff8170e024: driver_deferred_probe_check_state_continue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
