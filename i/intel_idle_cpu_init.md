# Function: <code>intel_idle_cpu_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int intel_idle_cpu_init(int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff814792b0)
Location: drivers/idle/intel_idle.c:1186
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:cpu_hotplug_notify
```
**Symbols:**

```
ffffffff814792b0-ffffffff8147935c: intel_idle_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int intel_idle_cpu_init(int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff814c7660)
Location: drivers/idle/intel_idle.c:1376
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:cpu_hotplug_notify
```
**Symbols:**

```
ffffffff814c7660-ffffffff814c771b: intel_idle_cpu_init (STB_LOCAL)
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
In drivers/idle/intel_idle.c (ffffffff814e9743)
Location: drivers/idle/intel_idle.c:1388
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff814f5363)
Location: drivers/idle/intel_idle.c:1390
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff81535be3)
Location: drivers/idle/intel_idle.c:1402
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff8156b783)
Location: drivers/idle/intel_idle.c:1402
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff81583303)
Location: drivers/idle/intel_idle.c:1399
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff815b3a39)
Location: drivers/idle/intel_idle.c:1388
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff815d4c79)
Location: drivers/idle/intel_idle.c:1388
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int intel_idle_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff8167e930)
Location: drivers/idle/intel_idle.c:1540
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
**Symbols:**

```
ffffffff8167e930-ffffffff8167ea18: intel_idle_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int intel_idle_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff8169d630)
Location: drivers/idle/intel_idle.c:1605
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
```
**Symbols:**

```
ffffffff8169d630-ffffffff8169d718: intel_idle_cpu_init (STB_LOCAL)
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
In drivers/idle/intel_idle.c (ffffffff8168040d)
Location: drivers/idle/intel_idle.c:1606
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff816f5196)
Location: drivers/idle/intel_idle.c:1639
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff81821ad0)
Location: drivers/idle/intel_idle.c:1909
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff819527d0)
Location: drivers/idle/intel_idle.c:1975
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff81998bd0)
Location: drivers/idle/intel_idle.c:2006
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff819e1320)
Location: drivers/idle/intel_idle.c:2117
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff815c89c9)
Location: drivers/idle/intel_idle.c:1388
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff815b1bf7)
Location: drivers/idle/intel_idle.c:1388
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff815c8f59)
Location: drivers/idle/intel_idle.c:1388
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff815e2db9)
Location: drivers/idle/intel_idle.c:1388
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
