# Function: <code>wq_select_unbound_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b898)
Location: kernel/workqueue.c:1333
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810a07c8)
Location: kernel/workqueue.c:1335
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff8109d9ab)
Location: kernel/workqueue.c:1335
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810a40de)
Location: kernel/workqueue.c:1337
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810ac09a)
Location: kernel/workqueue.c:1335
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810b4f7a)
Location: kernel/workqueue.c:1355
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810badad)
Location: kernel/workqueue.c:1366
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810c1022)
Location: kernel/workqueue.c:1367
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int wq_select_unbound_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1364
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810c7460-ffffffff810c7506: wq_select_unbound_cpu (STB_LOCAL)
ffffffff810cd04f-ffffffff810cd067: wq_select_unbound_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int wq_select_unbound_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1370
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810c2570-ffffffff810c2616: wq_select_unbound_cpu (STB_LOCAL)
ffffffff81bdbea4-ffffffff81bdbebc: wq_select_unbound_cpu.cold (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810c5c05)
Location: kernel/workqueue.c:1371
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810d887d)
Location: kernel/workqueue.c:1401
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int wq_select_unbound_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1390
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810f0570-ffffffff810f0652: wq_select_unbound_cpu (STB_LOCAL)
ffffffff81e5497a-ffffffff81e549bc: wq_select_unbound_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int wq_select_unbound_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1390
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff81112230-ffffffff81112337: wq_select_unbound_cpu (STB_LOCAL)
ffffffff82056511-ffffffff8205653b: wq_select_unbound_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int wq_select_unbound_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1588
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff8111e6b0-ffffffff8111e7b7: wq_select_unbound_cpu (STB_LOCAL)
ffffffff820d4a83-ffffffff820d4aad: wq_select_unbound_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int wq_select_unbound_cpu(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1682
Inline: False
```
**Symbols:**

```
ffffffff811273c0-ffffffff811274af: wq_select_unbound_cpu (STB_LOCAL)
ffffffff821af945-ffffffff821af96f: wq_select_unbound_cpu.cold (STB_LOCAL)
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
In kernel/workqueue.c (ffff80001011ee48)
Location: kernel/workqueue.c:1367
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (c0372108)
Location: kernel/workqueue.c:1367
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (c0000000001654f0)
Location: kernel/workqueue.c:1367
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffe0000d82b6)
Location: kernel/workqueue.c:1367
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810bb392)
Location: kernel/workqueue.c:1367
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810a9e82)
Location: kernel/workqueue.c:1367
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810ba8f2)
Location: kernel/workqueue.c:1367
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff810c2364)
Location: kernel/workqueue.c:1367
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
