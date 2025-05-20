# Function: <code>elants_i2c_event</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81701480)
Location: drivers/input/touchscreen/elants_i2c.c:840
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81701480-ffffffff8170171a: elants_i2c_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81716cc0)
Location: drivers/input/touchscreen/elants_i2c.c:840
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81716cc0-ffffffff81716f4b: elants_i2c_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81787e90)
Location: drivers/input/touchscreen/elants_i2c.c:841
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81787e90-ffffffff8178811b: elants_i2c_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8f20)
Location: drivers/input/touchscreen/elants_i2c.c:840
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff817c8f20-ffffffff817c91a7: elants_i2c_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff817f05c0)
Location: drivers/input/touchscreen/elants_i2c.c:841
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff817f05c0-ffffffff817f0847: elants_i2c_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:836
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81830920-ffffffff81830b61: elants_i2c_event (STB_LOCAL)
ffffffff81831659-ffffffff818316a9: elants_i2c_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:836
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81862250-ffffffff81862491: elants_i2c_event (STB_LOCAL)
ffffffff81862f89-ffffffff81862fd9: elants_i2c_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:908
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81934e40-ffffffff81934e7f: elants_i2c_event (STB_LOCAL)
ffffffff81935d32-ffffffff81935d7a: elants_i2c_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:916
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff8193beb0-ffffffff8193beef: elants_i2c_event (STB_LOCAL)
ffffffff81c23974-ffffffff81c239bc: elants_i2c_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:1003
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff8191f3e0-ffffffff8191f41f: elants_i2c_event (STB_LOCAL)
ffffffff81c1593a-ffffffff81c15982: elants_i2c_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:1047
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff819c2190-ffffffff819c21cf: elants_i2c_event (STB_LOCAL)
ffffffff81d242db-ffffffff81d24323: elants_i2c_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:1047
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81b22540-ffffffff81b22593: elants_i2c_event (STB_LOCAL)
ffffffff81ef0129-ffffffff81ef0171: elants_i2c_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb4a70)
Location: drivers/input/touchscreen/elants_i2c.c:1047
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81cb4a70-ffffffff81cb4b25: elants_i2c_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1c0d0)
Location: drivers/input/touchscreen/elants_i2c.c:1047
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81d1c0d0-ffffffff81d1c185: elants_i2c_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf, size_t packet_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd1e20)
Location: drivers/input/touchscreen/elants_i2c.c:1047
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81dd1e20-ffffffff81dd1ed5: elants_i2c_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:836
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff818563e0-ffffffff81856621: elants_i2c_event (STB_LOCAL)
ffffffff81857119-ffffffff81857169: elants_i2c_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void elants_i2c_event(struct elants_data *ts, u8 *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (0)
Location: drivers/input/touchscreen/elants_i2c.c:836
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_irq
```
**Symbols:**

```
ffffffff81871510-ffffffff81871751: elants_i2c_event (STB_LOCAL)
ffffffff81872249-ffffffff81872299: elants_i2c_event.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t packet_size</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
