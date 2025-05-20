# Function: <code>__platform_get_irq</code>

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
int __platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff81701a10)
Location: drivers/base/platform.c:84
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_irq_count
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq
```
**Symbols:**

```
ffffffff81701a10-ffffffff81701b5a: __platform_get_irq (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffff8000108edb60)
Location: drivers/base/platform.c:84
Inline: True
Direct callers:
  - drivers/base/platform.c:platform_irq_count
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq
```
**Symbols:**

```
ffff8000108edb60-ffff8000108edd24: __platform_get_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c09dbaec)
Location: drivers/base/platform.c:84
Inline: True
Direct callers:
  - drivers/base/platform.c:platform_irq_count
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq
```
**Symbols:**

```
c09dbaec-c09dbbe4: __platform_get_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (c000000000986120)
Location: drivers/base/platform.c:84
Inline: True
Direct callers:
  - drivers/base/platform.c:platform_irq_count
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq
```
**Symbols:**

```
c000000000986120-c000000000986278: __platform_get_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffe000580dda)
Location: drivers/base/platform.c:84
Inline: True
Direct callers:
  - drivers/base/platform.c:platform_irq_count
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq
```
**Symbols:**

```
ffffffe000580dda-ffffffe000580eb0: __platform_get_irq (STB_LOCAL)
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
int __platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816c7160)
Location: drivers/base/platform.c:84
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_irq_count
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq
```
**Symbols:**

```
ffffffff816c7160-ffffffff816c72aa: __platform_get_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816a2460)
Location: drivers/base/platform.c:84
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_irq_count
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq
```
**Symbols:**

```
ffffffff816a2460-ffffffff816a25aa: __platform_get_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff816f56d0)
Location: drivers/base/platform.c:84
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_irq_count
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq
```
**Symbols:**

```
ffffffff816f56d0-ffffffff816f581a: __platform_get_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __platform_get_irq(struct platform_device *dev, unsigned int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform.c (ffffffff8170ff60)
Location: drivers/base/platform.c:84
Inline: False
Direct callers:
  - drivers/base/platform.c:platform_irq_count
  - drivers/base/platform.c:platform_get_irq_optional
  - drivers/base/platform.c:platform_get_irq
```
**Symbols:**

```
ffffffff8170ff60-ffffffff817100aa: __platform_get_irq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
