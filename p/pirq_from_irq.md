# Function: <code>pirq_from_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c7a60)
Location: drivers/xen/events/events_base.c:287
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff814c7a60-ffffffff814c7a90: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815184d0)
Location: drivers/xen/events/events_base.c:287
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff815184d0-ffffffff81518500: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815449e0)
Location: drivers/xen/events/events_base.c:286
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff815449e0-ffffffff81544a10: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81558850)
Location: drivers/xen/events/events_base.c:286
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff81558850-ffffffff81558880: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bcc00)
Location: drivers/xen/events/events_base.c:286
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff815bcc00-ffffffff815bcc30: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f52a0)
Location: drivers/xen/events/events_base.c:286
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff815f52a0-ffffffff815f52d0: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81610390)
Location: drivers/xen/events/events_base.c:286
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff81610390-ffffffff816103c0: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81644110)
Location: drivers/xen/events/events_base.c:287
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff81644110-ffffffff81644140: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816666c0)
Location: drivers/xen/events/events_base.c:287
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff816666c0-ffffffff816666f0: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81715eb5)
Location: drivers/xen/events/events_base.c:301
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
**Symbols:**

```
ffffffff81715f00-ffffffff81715f43: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81732f15)
Location: drivers/xen/events/events_base.c:431
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
**Symbols:**

```
ffffffff81732f60-ffffffff81732fa4: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817169c5)
Location: drivers/xen/events/events_base.c:448
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
```
**Symbols:**

```
ffffffff81716ab0-ffffffff81716af4: pirq_from_irq (STB_LOCAL)
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
In drivers/xen/events/events_base.c (ffffffff81793a25)
Location: drivers/xen/events/events_base.c:448
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
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
In drivers/xen/events/events_base.c (ffffffff818cc4f5)
Location: drivers/xen/events/events_base.c:448
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
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
In drivers/xen/events/events_base.c (ffffffff81a1dac5)
Location: drivers/xen/events/events_base.c:449
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
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
In drivers/xen/events/events_base.c (ffffffff81a66cc5)
Location: drivers/xen/events/events_base.c:450
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
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
In drivers/xen/events/events_base.c (ffffffff81ab9ef4)
Location: drivers/xen/events/events_base.c:456
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:do_eoi_pirq
  - drivers/xen/events/events_base.c:pirq_query_unmask
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
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
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108300c8)
Location: drivers/xen/events/events_base.c:287
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
```
**Symbols:**

```
ffff8000108300c8-ffff80001083011c: pirq_from_irq (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162c3f0)
Location: drivers/xen/events/events_base.c:291
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff8162c3f0-ffffffff8162c420: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165a500)
Location: drivers/xen/events/events_base.c:287
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff8165a500-ffffffff8165a530: pirq_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int pirq_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81674af0)
Location: drivers/xen/events/events_base.c:287
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_pirq_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:eoi_pirq
  - drivers/xen/events/events_base.c:pirq_check_eoi_map
```
**Symbols:**

```
ffffffff81674af0-ffffffff81674b20: pirq_from_irq (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
