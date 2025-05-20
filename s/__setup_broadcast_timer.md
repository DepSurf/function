# Function: <code>__setup_broadcast_timer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __setup_broadcast_timer(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff81479220)
Location: drivers/idle/intel_idle.c:792
Inline: False
```
**Symbols:**

```
ffffffff81479220-ffffffff81479243: __setup_broadcast_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __setup_broadcast_timer(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff814c7630)
Location: drivers/idle/intel_idle.c:910
Inline: False
```
**Symbols:**

```
ffffffff814c7630-ffffffff814c7653: __setup_broadcast_timer (STB_LOCAL)
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
In drivers/idle/intel_idle.c (ffffffff814e9718)
Location: drivers/idle/intel_idle.c:952
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
In drivers/idle/intel_idle.c (ffffffff814f5338)
Location: drivers/idle/intel_idle.c:953
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
In drivers/idle/intel_idle.c (ffffffff81535bb8)
Location: drivers/idle/intel_idle.c:959
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
In drivers/idle/intel_idle.c (ffffffff8156b758)
Location: drivers/idle/intel_idle.c:959
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
In drivers/idle/intel_idle.c (ffffffff815832d8)
Location: drivers/idle/intel_idle.c:959
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
In drivers/idle/intel_idle.c (ffffffff815b3a0a)
Location: drivers/idle/intel_idle.c:947
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
In drivers/idle/intel_idle.c (ffffffff815d4c4a)
Location: drivers/idle/intel_idle.c:947
Inline: True
Inline callers:
  - drivers/idle/intel_idle.c:intel_idle_cpu_online
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
In drivers/idle/intel_idle.c (ffffffff815c899a)
Location: drivers/idle/intel_idle.c:947
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
In drivers/idle/intel_idle.c (ffffffff815b1bc9)
Location: drivers/idle/intel_idle.c:947
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
In drivers/idle/intel_idle.c (ffffffff815c8f2a)
Location: drivers/idle/intel_idle.c:947
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
In drivers/idle/intel_idle.c (ffffffff815e2d8a)
Location: drivers/idle/intel_idle.c:947
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
</ul>
