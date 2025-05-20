# Function: <code>serio_bind_driver</code>

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
In drivers/input/serio/serio.c (ffffffff816645ff)
Location: drivers/input/serio/serio.c:106
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff816c483f)
Location: drivers/input/serio/serio.c:106
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff816f27ff)
Location: drivers/input/serio/serio.c:106
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff81707f2b)
Location: drivers/input/serio/serio.c:106
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff8177911b)
Location: drivers/input/serio/serio.c:106
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff817b9d99)
Location: drivers/input/serio/serio.c:106
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff817e13e9)
Location: drivers/input/serio/serio.c:102
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff81821c68)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff818530d8)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int serio_bind_driver(struct serio *serio, struct serio_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:90
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff819246b0-ffffffff81924758: serio_bind_driver (STB_LOCAL)
ffffffff819254b4-ffffffff819254f0: serio_bind_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int serio_bind_driver(struct serio *serio, struct serio_driver *drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:90
Inline: False
Direct callers:
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8192c460-ffffffff8192c508: serio_bind_driver (STB_LOCAL)
ffffffff81c2297f-ffffffff81c229bb: serio_bind_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff819101f6)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff819b10e6)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81b0fbb6)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81ca00d6)
Location: drivers/input/serio/serio.c:87
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81d07416)
Location: drivers/input/serio/serio.c:87
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81dbd046)
Location: drivers/input/serio/serio.c:87
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffff800010a93690)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (c0b76724)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (c000000000b6f94c)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffe0006a59c0)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff818081b8)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff817cf898)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff81847268)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
In drivers/input/serio/serio.c (ffffffff81862518)
Location: drivers/input/serio/serio.c:90
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:drvctl_store
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
</ul>
