# Function: <code>input_cleanse_bitmasks</code>

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
In drivers/input/input.c (ffffffff81667abb)
Location: drivers/input/input.c:2003
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff816c93e5)
Location: drivers/input/input.c:2002
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff816f73c5)
Location: drivers/input/input.c:2002
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff8170cea9)
Location: drivers/input/input.c:2002
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff8177e0e9)
Location: drivers/input/input.c:1996
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff817bf20b)
Location: drivers/input/input.c:2003
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff817e666b)
Location: drivers/input/input.c:2003
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff818272a3)
Location: drivers/input/input.c:1999
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff818587d3)
Location: drivers/input/input.c:2072
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void input_cleanse_bitmasks(struct input_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81928a70)
Location: drivers/input/input.c:2070
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81928a70-ffffffff81928b49: input_cleanse_bitmasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void input_cleanse_bitmasks(struct input_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8192ffa0)
Location: drivers/input/input.c:2168
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff8192ffa0-ffffffff81930079: input_cleanse_bitmasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void input_cleanse_bitmasks(struct input_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81913200)
Location: drivers/input/input.c:2168
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81913200-ffffffff819132d9: input_cleanse_bitmasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void input_cleanse_bitmasks(struct input_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff819b50a0)
Location: drivers/input/input.c:2168
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff819b50a0-ffffffff819b5179: input_cleanse_bitmasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void input_cleanse_bitmasks(struct input_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81b14450)
Location: drivers/input/input.c:2218
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81b14450-ffffffff81b14535: input_cleanse_bitmasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void input_cleanse_bitmasks(struct input_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81ca6000)
Location: drivers/input/input.c:2202
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81ca6000-ffffffff81ca60e5: input_cleanse_bitmasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void input_cleanse_bitmasks(struct input_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81d0d740)
Location: drivers/input/input.c:2201
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81d0d740-ffffffff81d0d825: input_cleanse_bitmasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void input_cleanse_bitmasks(struct input_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81dc3360)
Location: drivers/input/input.c:2201
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81dc3360-ffffffff81dc3445: input_cleanse_bitmasks (STB_LOCAL)
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
In drivers/input/input.c (ffff800010a97510)
Location: drivers/input/input.c:2072
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (c0b7a620)
Location: drivers/input/input.c:2072
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (c000000000b78098)
Location: drivers/input/input.c:2072
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffe0006a8a72)
Location: drivers/input/input.c:2072
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff8180d7e3)
Location: drivers/input/input.c:2072
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff817d4f53)
Location: drivers/input/input.c:2072
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff8184c963)
Location: drivers/input/input.c:2072
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
In drivers/input/input.c (ffffffff81867c53)
Location: drivers/input/input.c:2072
Inline: True
Inline callers:
  - drivers/input/input.c:input_register_device
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
