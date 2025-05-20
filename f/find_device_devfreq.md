# Function: <code>find_device_devfreq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *find_device_devfreq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff816ec9e0)
Location: drivers/devfreq/devfreq.c:52
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff816ec9e0-ffffffff816eca78: find_device_devfreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *find_device_devfreq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff817518a0)
Location: drivers/devfreq/devfreq.c:53
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff817518a0-ffffffff8175193a: find_device_devfreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *find_device_devfreq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8177d670)
Location: drivers/devfreq/devfreq.c:53
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff8177d670-ffffffff8177d70e: find_device_devfreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *find_device_devfreq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8179c1e0)
Location: drivers/devfreq/devfreq.c:53
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff8179c1e0-ffffffff8179c269: find_device_devfreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *find_device_devfreq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81813530)
Location: drivers/devfreq/devfreq.c:56
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff81813530-ffffffff818135b9: find_device_devfreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *find_device_devfreq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8185d3f0)
Location: drivers/devfreq/devfreq.c:56
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_dev_release
```
**Symbols:**

```
ffffffff8185d3f0-ffffffff8185d478: find_device_devfreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct devfreq *find_device_devfreq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff8187ca80)
Location: drivers/devfreq/devfreq.c:54
Inline: True
```
**Symbols:**

```
ffffffff8187ca80-ffffffff8187cb08: find_device_devfreq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct devfreq *find_device_devfreq(struct device *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff818c7c51)
Location: drivers/devfreq/devfreq.c:54
Inline: True
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff818c6f10-ffffffff818c6f82: find_device_devfreq (STB_LOCAL)
ffffffff818c7c51-ffffffff818c7c70: find_device_devfreq.cold (STB_LOCAL)
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
In drivers/devfreq/devfreq.c (ffffffff818f974b)
Location: drivers/devfreq/devfreq.c:54
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819d02ab)
Location: drivers/devfreq/devfreq.c:59
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cfd1e)
Location: drivers/devfreq/devfreq.c:66
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff819b4e6b)
Location: drivers/devfreq/devfreq.c:67
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81a639db)
Location: drivers/devfreq/devfreq.c:67
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81bd475b)
Location: drivers/devfreq/devfreq.c:67
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81d807ca)
Location: drivers/devfreq/devfreq.c:67
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81deeb7a)
Location: drivers/devfreq/devfreq.c:67
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81ea50fa)
Location: drivers/devfreq/devfreq.c:67
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffff800010b85e08)
Location: drivers/devfreq/devfreq.c:54
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (c0c68e6c)
Location: drivers/devfreq/devfreq.c:54
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (c000000000c649f0)
Location: drivers/devfreq/devfreq.c:54
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffe00072f2d6)
Location: drivers/devfreq/devfreq.c:54
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff8189aa7b)
Location: drivers/devfreq/devfreq.c:54
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81857f4b)
Location: drivers/devfreq/devfreq.c:54
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff818ea16b)
Location: drivers/devfreq/devfreq.c:54
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff8190b1eb)
Location: drivers/devfreq/devfreq.c:54
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
</ul>
