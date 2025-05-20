# Function: <code>input_ff_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffff8166b190)
Location: drivers/input/ff-core.c:310
Inline: False
```
**Symbols:**

```
ffffffff8166b190-ffffffff8166b2fe: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffff816cb470)
Location: drivers/input/ff-core.c:310
Inline: False
```
**Symbols:**

```
ffffffff816cb470-ffffffff816cb5c7: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffff816f9420)
Location: drivers/input/ff-core.c:310
Inline: False
```
**Symbols:**

```
ffffffff816f9420-ffffffff816f9577: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffff8170ef70)
Location: drivers/input/ff-core.c:310
Inline: False
```
**Symbols:**

```
ffffffff8170ef70-ffffffff8170f0c7: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffff817801c0)
Location: drivers/input/ff-core.c:317
Inline: False
```
**Symbols:**

```
ffffffff817801c0-ffffffff81780317: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffff817c12c0)
Location: drivers/input/ff-core.c:317
Inline: False
```
**Symbols:**

```
ffffffff817c12c0-ffffffff817c1419: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffff817e87b0)
Location: drivers/input/ff-core.c:317
Inline: False
```
**Symbols:**

```
ffffffff817e87b0-ffffffff817e8909: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
```
**Symbols:**

```
ffffffff818295ef-ffffffff81829629: input_ff_create.cold (STB_LOCAL)
ffffffff818294c0-ffffffff818295ef: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
```
**Symbols:**

```
ffffffff8185af7f-ffffffff8185afb9: input_ff_create.cold (STB_LOCAL)
ffffffff8185ae50-ffffffff8185af7f: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff8192dc8f-ffffffff8192dccb: input_ff_create.cold (STB_LOCAL)
ffffffff8192d670-ffffffff8192d7aa: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81c2346f-ffffffff81c234ab: input_ff_create.cold (STB_LOCAL)
ffffffff81934a40-ffffffff81934b7a: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81c15529-ffffffff81c15565: input_ff_create.cold (STB_LOCAL)
ffffffff81917d80-ffffffff81917ebe: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81d23416-ffffffff81d23452: input_ff_create.cold (STB_LOCAL)
ffffffff819b9ff0-ffffffff819ba12e: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81eef21d-ffffffff81eef24f: input_ff_create.cold (STB_LOCAL)
ffffffff81b1a000-ffffffff81b1a13f: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffff81cabc90)
Location: drivers/input/ff-core.c:302
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81cabc90-ffffffff81cabdd0: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffff81d13270)
Location: drivers/input/ff-core.c:302
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81d13270-ffffffff81d133b0: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffff81dc8ea0)
Location: drivers/input/ff-core.c:302
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_create_device
```
**Symbols:**

```
ffffffff81dc8ea0-ffffffff81dc8fe0: input_ff_create (STB_GLOBAL)
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
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffff800010a9ab20)
Location: drivers/input/ff-core.c:305
Inline: False
```
**Symbols:**

```
ffff800010a9ab20-ffff800010a9acc4: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (c0b7cb10)
Location: drivers/input/ff-core.c:305
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
**Symbols:**

```
c0b7cb10-c0b7cc90: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (c000000000b7b5c0)
Location: drivers/input/ff-core.c:305
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
**Symbols:**

```
c000000000b7b5c0-c000000000b7b7a8: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/ff-core.c (ffffffe0006ab626)
Location: drivers/input/ff-core.c:305
Inline: False
Direct callers:
  - drivers/input/misc/uinput.c:uinput_ioctl_handler
```
**Symbols:**

```
ffffffe0006ab626-ffffffe0006ab7aa: input_ff_create (STB_GLOBAL)
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
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
```
**Symbols:**

```
ffffffff8180ff8f-ffffffff8180ffc9: input_ff_create.cold (STB_LOCAL)
ffffffff8180fe60-ffffffff8180ff8f: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
```
**Symbols:**

```
ffffffff817d76df-ffffffff817d7719: input_ff_create.cold (STB_LOCAL)
ffffffff817d75b0-ffffffff817d76df: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
```
**Symbols:**

```
ffffffff8184f10f-ffffffff8184f149: input_ff_create.cold (STB_LOCAL)
ffffffff8184efe0-ffffffff8184f10f: input_ff_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int input_ff_create(struct input_dev *dev, unsigned int max_effects);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/ff-core.c (0)
Location: drivers/input/ff-core.c:305
Inline: False
```
**Symbols:**

```
ffffffff8186a2bf-ffffffff8186a2f9: input_ff_create.cold (STB_LOCAL)
ffffffff8186a190-ffffffff8186a2bf: input_ff_create (STB_GLOBAL)
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
