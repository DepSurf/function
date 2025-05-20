# Function: <code>pirq_query_unmask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c7ad0)
Location: drivers/xen/events/events_base.c:465
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
```
**Symbols:**

```
ffffffff814c7ad0-ffffffff814c7b7c: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81518540)
Location: drivers/xen/events/events_base.c:465
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81518540-ffffffff815185ec: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81544a50)
Location: drivers/xen/events/events_base.c:464
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81544a50-ffffffff81544afc: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815588c0)
Location: drivers/xen/events/events_base.c:456
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff815588c0-ffffffff81558966: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bcc70)
Location: drivers/xen/events/events_base.c:456
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff815bcc70-ffffffff815bcd16: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f5310)
Location: drivers/xen/events/events_base.c:456
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff815f5310-ffffffff815f53bc: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81610400)
Location: drivers/xen/events/events_base.c:456
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81610400-ffffffff816104a7: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816441e0)
Location: drivers/xen/events/events_base.c:457
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff816441e0-ffffffff81644271: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81666790)
Location: drivers/xen/events/events_base.c:457
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81666790-ffffffff81666821: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716080)
Location: drivers/xen/events/events_base.c:471
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81716080-ffffffff81716121: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81733460)
Location: drivers/xen/events/events_base.c:801
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81733460-ffffffff81733503: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716fc0)
Location: drivers/xen/events/events_base.c:832
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81716fc0-ffffffff81717063: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81794670)
Location: drivers/xen/events/events_base.c:832
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81794670-ffffffff817947a6: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cd2b0)
Location: drivers/xen/events/events_base.c:832
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff818cd2b0-ffffffff818cd410: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1e880)
Location: drivers/xen/events/events_base.c:834
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81a1e880-ffffffff81a1e9e0: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a67a80)
Location: drivers/xen/events/events_base.c:826
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81a67a80-ffffffff81a67be0: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pirq_query_unmask(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81ab8af0)
Location: drivers/xen/events/events_base.c:801
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81ab8af0-ffffffff81ab8b95: pirq_query_unmask (STB_LOCAL)
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
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010830200)
Location: drivers/xen/events/events_base.c:457
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffff800010830200-ffff8000108302c0: pirq_query_unmask (STB_LOCAL)
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
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162c4c0)
Location: drivers/xen/events/events_base.c:461
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff8162c4c0-ffffffff8162c551: pirq_query_unmask (STB_LOCAL)
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
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165a5d0)
Location: drivers/xen/events/events_base.c:457
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff8165a5d0-ffffffff8165a661: pirq_query_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pirq_query_unmask(int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81674bc0)
Location: drivers/xen/events/events_base.c:457
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81674bc0-ffffffff81674c51: pirq_query_unmask (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>int irq</code>
</li>
</ul>
</details>
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
