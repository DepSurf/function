# Function: <code>input_dev_ensure_poller</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-poller.c (ffffffff8185a715)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input-poller.c (ffffffff8192d345)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
Direct callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
```
**Symbols:**

```
ffffffff8192d484-ffffffff8192d4b3: input_dev_ensure_poller.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input-poller.c (ffffffff81934805)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
Direct callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
```
**Symbols:**

```
ffffffff81c23397-ffffffff81c233c6: input_dev_ensure_poller.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input-poller.c (ffffffff81917b55)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
Direct callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
```
**Symbols:**

```
ffffffff81c15445-ffffffff81c15474: input_dev_ensure_poller.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input-poller.c (ffffffff819b9dc5)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
Direct callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
```
**Symbols:**

```
ffffffff81d23332-ffffffff81d23361: input_dev_ensure_poller.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/input/input-poller.c (ffffffff81b19a95)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
Direct callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
```
**Symbols:**

```
ffffffff81eef113-ffffffff81eef14a: input_dev_ensure_poller.part.0 (STB_LOCAL)
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
In drivers/input/input-poller.c (ffffffff81cab565)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
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
In drivers/input/input-poller.c (ffffffff81d12b45)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
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
In drivers/input/input-poller.c (ffffffff81dc8745)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
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
In drivers/input/input-poller.c (ffff800010a9a874)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
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
In drivers/input/input-poller.c (c0b7c438)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
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
In drivers/input/input-poller.c (c000000000b7a920)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
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
In drivers/input/input-poller.c (ffffffe0006ab0e4)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
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
In drivers/input/input-poller.c (ffffffff8180f725)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
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
In drivers/input/input-poller.c (ffffffff817d6e75)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
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
In drivers/input/input-poller.c (ffffffff8184e8a5)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
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
In drivers/input/input-poller.c (ffffffff81869a75)
Location: drivers/input/input-poller.c:94
Inline: True
Inline callers:
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_max_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_min_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
  - drivers/input/input-poller.c:input_set_poll_interval
```
</details>
</li>
</ul>

## Differences
