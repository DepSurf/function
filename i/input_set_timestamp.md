# Function: <code>input_set_timestamp</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81856c40)
Location: drivers/input/input.c:1944
Inline: False
Direct callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff81856c40-ffffffff81856c83: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8192a33d)
Location: drivers/input/input.c:1942
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff81928e20-ffffffff81928e63: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8193167d)
Location: drivers/input/input.c:2040
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff81930380-ffffffff819303c3: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81914c9d)
Location: drivers/input/input.c:2040
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff819135e0-ffffffff81913623: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff819b6e2d)
Location: drivers/input/input.c:2040
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff819b53f0-ffffffff819b5433: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81b16b6d)
Location: drivers/input/input.c:2085
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff81b14ea0-ffffffff81b14eed: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81caa1bf)
Location: drivers/input/input.c:2069
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
```
**Symbols:**

```
ffffffff81ca5fa0-ffffffff81ca5fed: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81d1178f)
Location: drivers/input/input.c:2068
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81d0d6e0-ffffffff81d0d72d: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81dc738f)
Location: drivers/input/input.c:2068
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
Direct callers:
  - drivers/input/misc/uinput.c:uinput_write
```
**Symbols:**

```
ffffffff81dc3300-ffffffff81dc334d: input_set_timestamp (STB_GLOBAL)
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
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffff800010a95e60)
Location: drivers/input/input.c:1944
Inline: False
Direct callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffff800010a95e60-ffff800010a95eac: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c0b78b1c)
Location: drivers/input/input.c:1944
Inline: False
Direct callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
c0b78b1c-c0b78b78: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c000000000b75420)
Location: drivers/input/input.c:1944
Inline: False
Direct callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
c000000000b75420-c000000000b75494: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffe0006a784c)
Location: drivers/input/input.c:1944
Inline: False
Direct callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffe0006a784c-ffffffe0006a7896: input_set_timestamp (STB_GLOBAL)
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
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8180bc50)
Location: drivers/input/input.c:1944
Inline: False
Direct callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff8180bc50-ffffffff8180bc93: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817d33c0)
Location: drivers/input/input.c:1944
Inline: False
Direct callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff817d33c0-ffffffff817d3403: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8184add0)
Location: drivers/input/input.c:1944
Inline: False
Direct callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff8184add0-ffffffff8184ae13: input_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void input_set_timestamp(struct input_dev *dev, ktime_t timestamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81866020)
Location: drivers/input/input.c:1944
Inline: False
Direct callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff81866020-ffffffff81866063: input_set_timestamp (STB_GLOBAL)
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
