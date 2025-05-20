# Function: <code>led_parse_fwnode_props</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818e4064)
Location: drivers/leds/led-core.c:368
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void led_parse_fwnode_props(struct device *dev, struct fwnode_handle *fwnode, struct led_properties *props);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-core.c (0)
Location: drivers/leds/led-core.c:368
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff819b7020-ffffffff819b712e: led_parse_fwnode_props (STB_LOCAL)
ffffffff819b7833-ffffffff819b789f: led_parse_fwnode_props.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void led_parse_fwnode_props(struct device *dev, struct fwnode_handle *fwnode, struct led_properties *props);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-core.c (0)
Location: drivers/leds/led-core.c:370
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff819b9500-ffffffff819b960e: led_parse_fwnode_props (STB_LOCAL)
ffffffff81c2b340-ffffffff81c2b3ac: led_parse_fwnode_props.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void led_parse_fwnode_props(struct device *dev, struct fwnode_handle *fwnode, struct led_properties *props);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-core.c (0)
Location: drivers/leds/led-core.c:364
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff8199dcf0-ffffffff8199ddfe: led_parse_fwnode_props (STB_LOCAL)
ffffffff81c1d6d1-ffffffff81c1d73d: led_parse_fwnode_props.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void led_parse_fwnode_props(struct device *dev, struct fwnode_handle *fwnode, struct led_properties *props);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-core.c (0)
Location: drivers/leds/led-core.c:364
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff81a4a810-ffffffff81a4a91e: led_parse_fwnode_props (STB_LOCAL)
ffffffff81d2e940-ffffffff81d2e9ac: led_parse_fwnode_props.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void led_parse_fwnode_props(struct device *dev, struct fwnode_handle *fwnode, struct led_properties *props);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-core.c (0)
Location: drivers/leds/led-core.c:364
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff81bb8d60-ffffffff81bb8ea5: led_parse_fwnode_props (STB_LOCAL)
ffffffff81efadb6-ffffffff81efae22: led_parse_fwnode_props.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void led_parse_fwnode_props(struct device *dev, struct fwnode_handle *fwnode, struct led_properties *props);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81d5df80)
Location: drivers/leds/led-core.c:364
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff81d5df80-ffffffff81d5e103: led_parse_fwnode_props (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void led_parse_fwnode_props(struct device *dev, struct fwnode_handle *fwnode, struct led_properties *props);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81dc8b60)
Location: drivers/leds/led-core.c:419
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff81dc8b60-ffffffff81dc8ce3: led_parse_fwnode_props (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void led_parse_fwnode_props(struct device *dev, struct fwnode_handle *fwnode, struct led_properties *props);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81e81620)
Location: drivers/leds/led-core.c:424
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_compose_name
```
**Symbols:**

```
ffffffff81e81620-ffffffff81e817a3: led_parse_fwnode_props (STB_LOCAL)
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
In drivers/leds/led-core.c (ffff800010b486f8)
Location: drivers/leds/led-core.c:368
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (c0c3212c)
Location: drivers/leds/led-core.c:368
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (c000000000c3cd6c)
Location: drivers/leds/led-core.c:368
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
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
In drivers/leds/led-core.c (ffffffe00071c40e)
Location: drivers/leds/led-core.c:368
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81887a24)
Location: drivers/leds/led-core.c:368
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8183f3a4)
Location: drivers/leds/led-core.c:368
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818d8ec4)
Location: drivers/leds/led-core.c:368
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818f59e4)
Location: drivers/leds/led-core.c:368
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_compose_name
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
