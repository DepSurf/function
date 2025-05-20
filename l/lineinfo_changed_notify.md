# Function: <code>lineinfo_changed_notify</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lineinfo_changed_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160dac0)
Location: drivers/gpio/gpiolib.c:1377
Inline: True
```
**Symbols:**

```
ffffffff8160dac0-ffffffff8160dbd3: lineinfo_changed_notify.part.0 (STB_LOCAL)
ffffffff8160e300-ffffffff8160e333: lineinfo_changed_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lineinfo_changed_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a140)
Location: drivers/gpio/gpiolib-cdev.c:2153
Inline: True
```
**Symbols:**

```
ffffffff8163a140-ffffffff8163a23f: lineinfo_changed_notify.part.0 (STB_LOCAL)
ffffffff8163a640-ffffffff8163a679: lineinfo_changed_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lineinfo_changed_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161dd90)
Location: drivers/gpio/gpiolib-cdev.c:2154
Inline: True
```
**Symbols:**

```
ffffffff8161dd90-ffffffff8161de8f: lineinfo_changed_notify.part.0 (STB_LOCAL)
ffffffff8161e1a0-ffffffff8161e1d9: lineinfo_changed_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lineinfo_changed_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d4b0)
Location: drivers/gpio/gpiolib-cdev.c:2154
Inline: True
```
**Symbols:**

```
ffffffff8168d4b0-ffffffff8168d5ac: lineinfo_changed_notify.part.0 (STB_LOCAL)
ffffffff8168d8c0-ffffffff8168d8f9: lineinfo_changed_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lineinfo_changed_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aaaa0)
Location: drivers/gpio/gpiolib-cdev.c:2349
Inline: False
```
**Symbols:**

```
ffffffff817aaaa0-ffffffff817aabe7: lineinfo_changed_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lineinfo_changed_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c36b0)
Location: drivers/gpio/gpiolib-cdev.c:2503
Inline: False
```
**Symbols:**

```
ffffffff818c36b0-ffffffff818c37f9: lineinfo_changed_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lineinfo_changed_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81906780)
Location: drivers/gpio/gpiolib-cdev.c:2500
Inline: False
```
**Symbols:**

```
ffffffff81906780-ffffffff819068c9: lineinfo_changed_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lineinfo_changed_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950b20)
Location: drivers/gpio/gpiolib-cdev.c:2552
Inline: False
```
**Symbols:**

```
ffffffff81950b20-ffffffff81950c73: lineinfo_changed_notify (STB_LOCAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
