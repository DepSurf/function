# Function: <code>netdev_wait_allrefs</code>

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
In net/core/dev.c (ffffffff8171edff)
Location: net/core/dev.c:6833
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff817876b2)
Location: net/core/dev.c:7342
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff817b4c72)
Location: net/core/dev.c:7512
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff817d3812)
Location: net/core/dev.c:7699
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff8184dce2)
Location: net/core/dev.c:7878
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff81898b9d)
Location: net/core/dev.c:8145
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff818baffd)
Location: net/core/dev.c:8775
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff8190696c)
Location: net/core/dev.c:8880
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff8193905c)
Location: net/core/dev.c:9218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void netdev_wait_allrefs(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9674
Inline: False
Direct callers:
  - net/core/dev.c:netdev_run_todo
```
**Symbols:**

```
ffffffff81a03590-ffffffff81a036f2: netdev_wait_allrefs (STB_LOCAL)
ffffffff81a0eeb8-ffffffff81a0eed6: netdev_wait_allrefs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void netdev_wait_allrefs(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:10300
Inline: False
Direct callers:
  - net/core/dev.c:netdev_run_todo
```
**Symbols:**

```
ffffffff81a03b00-ffffffff81a03c95: netdev_wait_allrefs (STB_LOCAL)
ffffffff81c31194-ffffffff81c311b6: netdev_wait_allrefs.cold (STB_LOCAL)
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
In net/core/dev.c (ffffffff819f60a4)
Location: net/core/dev.c:10470
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff81aa7a24)
Location: net/core/dev.c:10477
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd795c)
Location: net/core/dev.c:9218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (c0cf2a2c)
Location: net/core/dev.c:9218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (c000000000cb79d4)
Location: net/core/dev.c:9218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffe000760eee)
Location: net/core/dev.c:9218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff818d902c)
Location: net/core/dev.c:9218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff81892e6c)
Location: net/core/dev.c:9218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff8192a05c)
Location: net/core/dev.c:9218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
In net/core/dev.c (ffffffff8194b72c)
Location: net/core/dev.c:9218
Inline: True
Inline callers:
  - net/core/dev.c:netdev_run_todo
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
