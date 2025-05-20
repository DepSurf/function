# Function: <code>tty_cdev_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814dffa0)
Location: drivers/tty/tty_io.c:3209
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_register_driver
```
**Symbols:**

```
ffffffff814dffa0-ffffffff814e0040: tty_cdev_add.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815317d0)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff815317d0-ffffffff8153186d: tty_cdev_add.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155df10)
Location: drivers/tty/tty_io.c:3205
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff8155df10-ffffffff8155dfad: tty_cdev_add.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572e80)
Location: drivers/tty/tty_io.c:2752
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff81572e80-ffffffff81572f1d: tty_cdev_add.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d7210)
Location: drivers/tty/tty_io.c:2859
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff815d7210-ffffffff815d72ad: tty_cdev_add.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816101a0)
Location: drivers/tty/tty_io.c:2880
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff816101a0-ffffffff8161024c: tty_cdev_add.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162cfa0)
Location: drivers/tty/tty_io.c:3035
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff8162cfa0-ffffffff8162d04c: tty_cdev_add.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81660c10)
Location: drivers/tty/tty_io.c:3039
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff81660c10-ffffffff81660cab: tty_cdev_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81683260)
Location: drivers/tty/tty_io.c:3035
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff81683260-ffffffff816832fb: tty_cdev_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_cdev_add(struct tty_driver *driver, dev_t dev, unsigned int index, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817340d0)
Location: drivers/tty/tty_io.c:3038
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff817340d0-ffffffff8173416f: tty_cdev_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_cdev_add(struct tty_driver *driver, dev_t dev, unsigned int index, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81750220)
Location: drivers/tty/tty_io.c:3131
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff81750220-ffffffff817502bf: tty_cdev_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_cdev_add(struct tty_driver *driver, dev_t dev, unsigned int index, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817340a0)
Location: drivers/tty/tty_io.c:3180
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff817340a0-ffffffff8173413f: tty_cdev_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_cdev_add(struct tty_driver *driver, dev_t dev, unsigned int index, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b4a00)
Location: drivers/tty/tty_io.c:3180
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff817b4a00-ffffffff817b4a9f: tty_cdev_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_cdev_add(struct tty_driver *driver, dev_t dev, unsigned int index, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f07e0)
Location: drivers/tty/tty_io.c:3150
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff818f07e0-ffffffff818f0896: tty_cdev_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_cdev_add(struct tty_driver *driver, dev_t dev, unsigned int index, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a48970)
Location: drivers/tty/tty_io.c:3148
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff81a48970-ffffffff81a48a26: tty_cdev_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_cdev_add(struct tty_driver *driver, dev_t dev, unsigned int index, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a92bc0)
Location: drivers/tty/tty_io.c:3155
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff81a92bc0-ffffffff81a92c76: tty_cdev_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_cdev_add(struct tty_driver *driver, dev_t dev, unsigned int index, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae5610)
Location: drivers/tty/tty_io.c:3172
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff81ae5610-ffffffff81ae56c6: tty_cdev_add (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084f5b0)
Location: drivers/tty/tty_io.c:3035
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffff80001084f5b0-ffff80001084f678: tty_cdev_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_cdev_add(struct tty_driver *driver, dev_t dev, unsigned int index, unsigned int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095ad00)
Location: drivers/tty/tty_io.c:3035
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
c095ad00-c095ad9c: tty_cdev_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ef8a0)
Location: drivers/tty/tty_io.c:3035
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
c0000000008ef8a0-c0000000008ef9b4: tty_cdev_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052dca6)
Location: drivers/tty/tty_io.c:3035
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffe00052dca6-ffffffe00052dd4a: tty_cdev_add.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81648ce0)
Location: drivers/tty/tty_io.c:3035
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff81648ce0-ffffffff81648d7b: tty_cdev_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81629140)
Location: drivers/tty/tty_io.c:3035
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff81629140-ffffffff816291db: tty_cdev_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816770a0)
Location: drivers/tty/tty_io.c:3035
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff816770a0-ffffffff8167713b: tty_cdev_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816917c0)
Location: drivers/tty/tty_io.c:3035
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_register_driver
  - drivers/tty/tty_io.c:tty_register_device_attr
```
**Symbols:**

```
ffffffff816917c0-ffffffff8169185b: tty_cdev_add.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
