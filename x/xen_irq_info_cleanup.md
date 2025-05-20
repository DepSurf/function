# Function: <code>xen_irq_info_cleanup</code>

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
In drivers/xen/events/events_base.c (ffffffff814c84a3)
Location: drivers/xen/events/events_base.c:239
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
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
In drivers/xen/events/events_base.c (ffffffff8151940d)
Location: drivers/xen/events/events_base.c:239
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
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
In drivers/xen/events/events_base.c (ffffffff815458dd)
Location: drivers/xen/events/events_base.c:238
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
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
In drivers/xen/events/events_base.c (ffffffff81559756)
Location: drivers/xen/events/events_base.c:238
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
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
In drivers/xen/events/events_base.c (ffffffff815bdba6)
Location: drivers/xen/events/events_base.c:238
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
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
In drivers/xen/events/events_base.c (ffffffff815f61e4)
Location: drivers/xen/events/events_base.c:238
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
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
In drivers/xen/events/events_base.c (ffffffff8161129c)
Location: drivers/xen/events/events_base.c:238
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
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
In drivers/xen/events/events_base.c (ffffffff81645010)
Location: drivers/xen/events/events_base.c:239
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
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
In drivers/xen/events/events_base.c (ffffffff816675c0)
Location: drivers/xen/events/events_base.c:239
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
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
In drivers/xen/events/events_base.c (ffffffff8171734e)
Location: drivers/xen/events/events_base.c:253
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_irq_info_cleanup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817327b0)
Location: drivers/xen/events/events_base.c:377
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
**Symbols:**

```
ffffffff817327b0-ffffffff8173280a: xen_irq_info_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_irq_info_cleanup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716150)
Location: drivers/xen/events/events_base.c:394
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
**Symbols:**

```
ffffffff81716150-ffffffff817161aa: xen_irq_info_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_irq_info_cleanup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817933e0)
Location: drivers/xen/events/events_base.c:394
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
```
**Symbols:**

```
ffffffff817933e0-ffffffff8179343a: xen_irq_info_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_irq_info_cleanup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cbee0)
Location: drivers/xen/events/events_base.c:394
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
```
**Symbols:**

```
ffffffff818cbee0-ffffffff818cbf3b: xen_irq_info_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_irq_info_cleanup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1d350)
Location: drivers/xen/events/events_base.c:395
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
```
**Symbols:**

```
ffffffff81a1d350-ffffffff81a1d3ab: xen_irq_info_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_irq_info_cleanup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a66560)
Location: drivers/xen/events/events_base.c:396
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
```
**Symbols:**

```
ffffffff81a66560-ffffffff81a665bb: xen_irq_info_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_irq_info_cleanup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81ab9090)
Location: drivers/xen/events/events_base.c:399
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
```
**Symbols:**

```
ffffffff81ab9090-ffffffff81ab90eb: xen_irq_info_cleanup (STB_LOCAL)
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
In drivers/xen/events/events_base.c (ffff8000108313b8)
Location: drivers/xen/events/events_base.c:239
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162d2f0)
Location: drivers/xen/events/events_base.c:243
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165b400)
Location: drivers/xen/events/events_base.c:239
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
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
In drivers/xen/events/events_base.c (ffffffff816759f0)
Location: drivers/xen/events/events_base.c:239
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
