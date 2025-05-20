# Function: <code>gpiod_free_commit</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d8140)
Location: drivers/gpio/gpiolib.c:2246
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
```
**Symbols:**

```
ffffffff814d8140-ffffffff814d8217: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815076f0)
Location: drivers/gpio/gpiolib.c:2360
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
```
**Symbols:**

```
ffffffff815076f0-ffffffff815077c7: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151bf70)
Location: drivers/gpio/gpiolib.c:2388
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_hog
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff8151bf70-ffffffff8151c05e: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154a250)
Location: drivers/gpio/gpiolib.c:2452
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff8154a250-ffffffff8154a33a: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156b460)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff8156b460-ffffffff8156b54a: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160f260)
Location: drivers/gpio/gpiolib.c:3151
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:lineevent_release
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib.c:linehandle_release
```
**Symbols:**

```
ffffffff8160f260-ffffffff8160f390: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81635d40)
Location: drivers/gpio/gpiolib.c:1955
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81635d40-ffffffff81635e95: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81619100)
Location: drivers/gpio/gpiolib.c:1932
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81619100-ffffffff8161924d: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1954
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
  - drivers/gpio/gpiolib.c:gpiochip_remove
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff816883c0-ffffffff8168851b: gpiod_free_commit (STB_LOCAL)
ffffffff81ce16ac-ffffffff81ce16c1: gpiod_free_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2015
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff817a40f0-ffffffff817a4237: gpiod_free_commit (STB_LOCAL)
ffffffff81ea7cde-ffffffff81ea7cf3: gpiod_free_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2085
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff818bbb70-ffffffff818bbcb7: gpiod_free_commit (STB_LOCAL)
ffffffff8208e4ec-ffffffff8208e501: gpiod_free_commit.cold (STB_LOCAL)
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
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2122
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff818ff0b0-ffffffff818ff1e5: gpiod_free_commit.isra.0 (STB_LOCAL)
ffffffff8210e7c1-ffffffff8210e7d6: gpiod_free_commit.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2305
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_put_array
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff81946450-ffffffff81946582: gpiod_free_commit (STB_LOCAL)
ffffffff821ec406-ffffffff821ec41b: gpiod_free_commit.cold (STB_LOCAL)
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
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c1080)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffff8000106c1080-ffff8000106c12d4: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085ed70)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
c085ed70-c085ee90: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083bd00)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
c00000000083bd00-c00000000083beac: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a5ce2)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_free_hogs
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffe0004a5ce2-ffffffe0004a5de6: gpiod_free_commit (STB_LOCAL)
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
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560c20)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff81560c20-ffffffff81560d0a: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81551a70)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff81551a70-ffffffff81551b5a: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155f790)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff8155f790-ffffffff8155f87a: gpiod_free_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool gpiod_free_commit(struct gpio_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81579610)
Location: drivers/gpio/gpiolib.c:2784
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_request_own_desc
```
**Symbols:**

```
ffffffff81579610-ffffffff815796da: gpiod_free_commit (STB_LOCAL)
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
