# Function: <code>input_attach_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81667870)
Location: drivers/input/input.c:994
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81667870-ffffffff81667a5f: input_attach_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816c7b00)
Location: drivers/input/input.c:993
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff816c7b00-ffffffff816c7cde: input_attach_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff816f5af0)
Location: drivers/input/input.c:993
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff816f5af0-ffffffff816f5cce: input_attach_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8170b640)
Location: drivers/input/input.c:993
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff8170b640-ffffffff8170b828: input_attach_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff8177cd10)
Location: drivers/input/input.c:987
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff8177cd10-ffffffff8177cdbd: input_attach_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817bdda0)
Location: drivers/input/input.c:995
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff817bdda0-ffffffff817bde46: input_attach_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff817e5200)
Location: drivers/input/input.c:995
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff817e5200-ffffffff817e52a6: input_attach_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:991
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81825c90-ffffffff81825d2b: input_attach_handler (STB_LOCAL)
ffffffff81828059-ffffffff81828077: input_attach_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1022
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff818571c0-ffffffff8185725b: input_attach_handler (STB_LOCAL)
ffffffff818595c3-ffffffff818595e1: input_attach_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1022
Inline: True
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff819299f0-ffffffff81929a7c: input_attach_handler.isra.0 (STB_LOCAL)
ffffffff8192c181-ffffffff8192c19f: input_attach_handler.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1026
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff819303d0-ffffffff8193046b: input_attach_handler (STB_LOCAL)
ffffffff81c23157-ffffffff81c23175: input_attach_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1026
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81913630-ffffffff819136cb: input_attach_handler (STB_LOCAL)
ffffffff81c1524d-ffffffff81c1526b: input_attach_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1026
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff819b5440-ffffffff819b54db: input_attach_handler (STB_LOCAL)
ffffffff81d22ff6-ffffffff81d23014: input_attach_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1073
Inline: True
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81b15840-ffffffff81b158e6: input_attach_handler.isra.0 (STB_LOCAL)
ffffffff81eeee80-ffffffff81eeee9f: input_attach_handler.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff81ca6cd0)
Location: drivers/input/input.c:1052
Inline: True
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81ca6cd0-ffffffff81ca6d8c: input_attach_handler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff81d0e410)
Location: drivers/input/input.c:1055
Inline: True
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81d0e410-ffffffff81d0e4cc: input_attach_handler.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (ffffffff81dc4060)
Location: drivers/input/input.c:1055
Inline: True
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff81dc4060-ffffffff81dc411c: input_attach_handler.isra.0 (STB_LOCAL)
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
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffff800010a964e8)
Location: drivers/input/input.c:1022
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffff800010a964e8-ffff800010a965cc: input_attach_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c0b79114)
Location: drivers/input/input.c:1022
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
c0b79114-c0b791e8: input_attach_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (c000000000b75c20)
Location: drivers/input/input.c:1022
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
c000000000b75c20-c000000000b75d64: input_attach_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffe0006a7ee0)
Location: drivers/input/input.c:1022
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffe0006a7ee0-ffffffe0006a7f82: input_attach_handler (STB_LOCAL)
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
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1022
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff8180c1d0-ffffffff8180c26b: input_attach_handler (STB_LOCAL)
ffffffff8180e5d3-ffffffff8180e5f1: input_attach_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1022
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff817d3940-ffffffff817d39db: input_attach_handler (STB_LOCAL)
ffffffff817d5d23-ffffffff817d5d41: input_attach_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1022
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff8184b350-ffffffff8184b3eb: input_attach_handler (STB_LOCAL)
ffffffff8184d753-ffffffff8184d771: input_attach_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int input_attach_handler(struct input_dev *dev, struct input_handler *handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1022
Inline: False
Direct callers:
  - drivers/input/input.c:input_register_device
```
**Symbols:**

```
ffffffff818665b0-ffffffff8186664b: input_attach_handler (STB_LOCAL)
ffffffff8186892d-ffffffff8186894b: input_attach_handler.cold (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
