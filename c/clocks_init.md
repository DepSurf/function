# Function: <code>clocks_init</code>

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
In drivers/mfd/twl-core.c (ffffffff81587c90)
Location: drivers/mfd/twl-core.c:1006
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (ffffffff815dcced)
Location: drivers/mfd/twl-core.c:1004
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (ffffffff816099bd)
Location: drivers/mfd/twl-core.c:1003
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (ffffffff8161db12)
Location: drivers/mfd/twl-core.c:1003
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (ffffffff81686358)
Location: drivers/mfd/twl-core.c:1003
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (ffffffff816c2246)
Location: drivers/mfd/twl-core.c:1003
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (ffffffff816e3686)
Location: drivers/mfd/twl-core.c:1003
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (ffffffff8171d219)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff817414ec)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void clocks_init(struct device *dev, struct twl4030_clock_init_data *clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:990
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff817fe6b0-ffffffff817fe7e6: clocks_init (STB_LOCAL)
ffffffff817ff4a9-ffffffff817ff4d4: clocks_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void clocks_init(struct device *dev, struct twl4030_clock_init_data *clock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/twl-core.c (0)
Location: drivers/mfd/twl-core.c:990
Inline: False
Direct callers:
  - drivers/mfd/twl-core.c:twl_probe
```
**Symbols:**

```
ffffffff8180fae0-ffffffff8180fc16: clocks_init (STB_LOCAL)
ffffffff81c130b4-ffffffff81c130df: clocks_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff817f4beb)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff8187dc4b)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff819c616a)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81b3cb38)
Location: drivers/mfd/twl-core.c:687
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81b8ff13)
Location: drivers/mfd/twl-core.c:625
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff81be3e36)
Location: drivers/mfd/twl-core.c:627
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (ffff80001093cd0c)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (c0a25794)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (c0000000009e4a0c)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (ffffffe0005b0fc0)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/twl-core.c (ffffffff817349ac)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
In drivers/mfd/twl-core.c (ffffffff8174fdec)
Location: drivers/mfd/twl-core.c:990
Inline: True
Inline callers:
  - drivers/mfd/twl-core.c:twl_probe
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
</ul>
