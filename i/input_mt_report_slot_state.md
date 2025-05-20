# Function: <code>input_mt_report_slot_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8166ab40)
Location: drivers/input/input-mt.c:135
Inline: True
```
**Symbols:**

```
ffffffff8166ab40-ffffffff8166abcf: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff816cae30)
Location: drivers/input/input-mt.c:135
Inline: True
```
**Symbols:**

```
ffffffff816cae30-ffffffff816caebf: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff816f8df0)
Location: drivers/input/input-mt.c:135
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff816f8df0-ffffffff816f8e7f: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8170e930)
Location: drivers/input/input-mt.c:135
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff8170e930-ffffffff8170e9c3: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8177fb70)
Location: drivers/input/input-mt.c:135
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff8177fb70-ffffffff8177fc03: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff817c0c70)
Location: drivers/input/input-mt.c:137
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff817c0c70-ffffffff817c0d0d: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff817e8160)
Location: drivers/input/input-mt.c:137
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff817e8160-ffffffff817e81fd: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81828c80)
Location: drivers/input/input-mt.c:134
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff81828c80-ffffffff81828d20: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8185a1f0)
Location: drivers/input/input-mt.c:134
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff8185a1f0-ffffffff8185a290: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8192ca80)
Location: drivers/input/input-mt.c:134
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
```
**Symbols:**

```
ffffffff8192ca80-ffffffff8192cb20: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81933f50)
Location: drivers/input/input-mt.c:134
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
```
**Symbols:**

```
ffffffff81933f50-ffffffff81933ff0: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81917280)
Location: drivers/input/input-mt.c:134
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
```
**Symbols:**

```
ffffffff81917280-ffffffff81917320: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff819b94f0)
Location: drivers/input/input-mt.c:134
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
```
**Symbols:**

```
ffffffff819b94f0-ffffffff819b9590: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81b190f0)
Location: drivers/input/input-mt.c:134
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
```
**Symbols:**

```
ffffffff81b190f0-ffffffff81b1919f: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81caaa60)
Location: drivers/input/input-mt.c:135
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
```
**Symbols:**

```
ffffffff81caaa60-ffffffff81caab0f: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81d12040)
Location: drivers/input/input-mt.c:135
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
```
**Symbols:**

```
ffffffff81d12040-ffffffff81d120ef: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81dc7c40)
Location: drivers/input/input-mt.c:135
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_mt_event
```
**Symbols:**

```
ffffffff81dc7c40-ffffffff81dc7cef: input_mt_report_slot_state (STB_GLOBAL)
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
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffff800010a9a1d0)
Location: drivers/input/input-mt.c:134
Inline: True
```
**Symbols:**

```
ffff800010a9a1d0-ffff800010a9a2a4: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (c0b7be3c)
Location: drivers/input/input-mt.c:134
Inline: True
```
**Symbols:**

```
c0b7be3c-c0b7bee0: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (c000000000b7a1f0)
Location: drivers/input/input-mt.c:134
Inline: True
```
**Symbols:**

```
c000000000b7a1f0-c000000000b7a30c: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffe0006aab68)
Location: drivers/input/input-mt.c:134
Inline: True
```
**Symbols:**

```
ffffffe0006aab68-ffffffe0006aac10: input_mt_report_slot_state (STB_GLOBAL)
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
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8180f200)
Location: drivers/input/input-mt.c:134
Inline: True
```
**Symbols:**

```
ffffffff8180f200-ffffffff8180f2a0: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff817d6950)
Location: drivers/input/input-mt.c:134
Inline: True
```
**Symbols:**

```
ffffffff817d6950-ffffffff817d69f0: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8184e380)
Location: drivers/input/input-mt.c:134
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff8184e380-ffffffff8184e420: input_mt_report_slot_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool input_mt_report_slot_state(struct input_dev *dev, unsigned int tool_type, bool active);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81869550)
Location: drivers/input/input-mt.c:134
Inline: True
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_event
```
**Symbols:**

```
ffffffff81869550-ffffffff818695f0: input_mt_report_slot_state (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
