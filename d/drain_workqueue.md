# Function: <code>drain_workqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81099390)
Location: kernel/workqueue.c:2638
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81099390-ffffffff810994b1: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109c900)
Location: kernel/workqueue.c:2736
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff8109c900-ffffffff8109ca38: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1a60)
Location: kernel/workqueue.c:2741
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff810a1a60-ffffffff810a1b98: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109eca0)
Location: kernel/workqueue.c:2740
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff8109eca0-ffffffff8109edca: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a54e0)
Location: kernel/workqueue.c:2755
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff810a54e0-ffffffff810a560a: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ab870)
Location: kernel/workqueue.c:2805
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - drivers/pci/hotplug/pciehp_core.c:release_slot
```
**Symbols:**

```
ffffffff810ab870-ffffffff810ab98e: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b47f0)
Location: kernel/workqueue.c:2828
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff810b47f0-ffffffff810b490e: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2924
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff810bef6d-ffffffff810bef89: drain_workqueue.cold (STB_LOCAL)
ffffffff810ba3f0-ffffffff810ba4ff: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2933
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - drivers/acpi/ec.c:__acpi_ec_flush_work
```
**Symbols:**

```
ffffffff810c5486-ffffffff810c54a2: drain_workqueue.cold (STB_LOCAL)
ffffffff810c0870-ffffffff810c097f: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2930
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
```
**Symbols:**

```
ffffffff810cd067-ffffffff810cd083: drain_workqueue.cold (STB_LOCAL)
ffffffff810c7fe0-ffffffff810c80ef: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2936
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
```
**Symbols:**

```
ffffffff81bdbebc-ffffffff81bdbed8: drain_workqueue.cold (STB_LOCAL)
ffffffff810c3100-ffffffff810c320f: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2937
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
```
**Symbols:**

```
ffffffff81bcdfd5-ffffffff81bcdff8: drain_workqueue.cold (STB_LOCAL)
ffffffff810c4f30-ffffffff810c503f: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2976
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81ca5159-ffffffff81ca517c: drain_workqueue.cold (STB_LOCAL)
ffffffff810d7b20-ffffffff810d7c2f: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2959
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff81e54aab-ffffffff81e54acd: drain_workqueue.cold (STB_LOCAL)
ffffffff810f2360-ffffffff810f246a: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811131a0)
Location: kernel/workqueue.c:2959
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff811131a0-ffffffff811132d3: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111f530)
Location: kernel/workqueue.c:3275
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff8111f530-ffffffff8111f663: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811297e0)
Location: kernel/workqueue.c:3296
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffff811297e0-ffffffff81129913: drain_workqueue (STB_GLOBAL)
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
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011d268)
Location: kernel/workqueue.c:2933
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - drivers/acpi/ec.c:__acpi_ec_flush_work
```
**Symbols:**

```
ffff80001011d268-ffff80001011d408: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c037344c)
Location: kernel/workqueue.c:2933
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
c037344c-c0373598: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000167540)
Location: kernel/workqueue.c:2933
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
c000000000167540-c000000000167764: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d7766)
Location: kernel/workqueue.c:2933
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
```
**Symbols:**

```
ffffffe0000d7766-ffffffe0000d78d0: drain_workqueue (STB_GLOBAL)
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
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2933
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - drivers/acpi/ec.c:__acpi_ec_flush_work
```
**Symbols:**

```
ffffffff810bf7f6-ffffffff810bf812: drain_workqueue.cold (STB_LOCAL)
ffffffff810babe0-ffffffff810bacef: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2933
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - drivers/acpi/ec.c:__acpi_ec_flush_work
```
**Symbols:**

```
ffffffff810ae016-ffffffff810ae032: drain_workqueue.cold (STB_LOCAL)
ffffffff810a9520-ffffffff810a9629: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2933
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - drivers/acpi/ec.c:__acpi_ec_flush_work
```
**Symbols:**

```
ffffffff810bed56-ffffffff810bed72: drain_workqueue.cold (STB_LOCAL)
ffffffff810ba140-ffffffff810ba24f: drain_workqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void drain_workqueue(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2933
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - drivers/acpi/ec.c:__acpi_ec_flush_work
```
**Symbols:**

```
ffffffff810c70de-ffffffff810c70f5: drain_workqueue.cold (STB_LOCAL)
ffffffff810c3140-ffffffff810c3254: drain_workqueue (STB_GLOBAL)
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
