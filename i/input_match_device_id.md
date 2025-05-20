# Function: <code>input_match_device_id</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8177cba0)
Location: drivers/input/input.c:936
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff8177cba0-ffffffff8177cd08: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817bdc40)
Location: drivers/input/input.c:944
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff817bdc40-ffffffff817bdda0: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817e50a0)
Location: drivers/input/input.c:944
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff817e50a0-ffffffff817e5200: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81825b10)
Location: drivers/input/input.c:940
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff81825b10-ffffffff81825c82: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81857040)
Location: drivers/input/input.c:971
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff81857040-ffffffff818571b2: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff819287e0)
Location: drivers/input/input.c:971
Inline: False
```
**Symbols:**

```
ffffffff819287e0-ffffffff81928950: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8192fd10)
Location: drivers/input/input.c:975
Inline: False
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff8192fd10-ffffffff8192fe80: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81913090)
Location: drivers/input/input.c:975
Inline: False
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff81913090-ffffffff81913200: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff819b4f30)
Location: drivers/input/input.c:975
Inline: False
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff819b4f30-ffffffff819b50a0: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81b142d0)
Location: drivers/input/input.c:1022
Inline: False
```
**Symbols:**

```
ffffffff81b142d0-ffffffff81b1444c: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81ca5340)
Location: drivers/input/input.c:1001
Inline: False
```
**Symbols:**

```
ffffffff81ca5340-ffffffff81ca54bc: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81d0ca80)
Location: drivers/input/input.c:1004
Inline: False
```
**Symbols:**

```
ffffffff81d0ca80-ffffffff81d0cbfc: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81dc2710)
Location: drivers/input/input.c:1004
Inline: False
```
**Symbols:**

```
ffffffff81dc2710-ffffffff81dc288c: input_match_device_id (STB_GLOBAL)
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
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffff800010a96398)
Location: drivers/input/input.c:971
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffff800010a96398-ffff800010a964e8: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c0b78f9c)
Location: drivers/input/input.c:971
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
c0b78f9c-c0b79114: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c000000000b75a60)
Location: drivers/input/input.c:971
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
c000000000b75a60-c000000000b75c1c: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffe0006a7d9a)
Location: drivers/input/input.c:971
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffe0006a7d9a-ffffffe0006a7ee0: input_match_device_id (STB_GLOBAL)
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
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8180c050)
Location: drivers/input/input.c:971
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff8180c050-ffffffff8180c1c2: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817d37c0)
Location: drivers/input/input.c:971
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff817d37c0-ffffffff817d3932: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8184b1d0)
Location: drivers/input/input.c:971
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff8184b1d0-ffffffff8184b342: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool input_match_device_id(const struct input_dev *dev, const struct input_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81866430)
Location: drivers/input/input.c:971
Inline: True
Direct callers:
  - drivers/input/input.c:input_attach_handler
```
**Symbols:**

```
ffffffff81866430-ffffffff818665a2: input_match_device_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
