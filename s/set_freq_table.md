# Function: <code>set_freq_table</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff81813bda)
Location: drivers/devfreq/devfreq.c:119
Inline: True
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
In drivers/devfreq/devfreq.c (ffffffff8185da0c)
Location: drivers/devfreq/devfreq.c:119
Inline: True
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
In drivers/devfreq/devfreq.c (ffffffff8187d350)
Location: drivers/devfreq/devfreq.c:117
Inline: True
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
In drivers/devfreq/devfreq.c (ffffffff818c75ae)
Location: drivers/devfreq/devfreq.c:117
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff818f9a73)
Location: drivers/devfreq/devfreq.c:117
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_freq_table(struct devfreq *devfreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819ce2d0)
Location: drivers/devfreq/devfreq.c:170
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff819ce2d0-ffffffff819ce3de: set_freq_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_freq_table(struct devfreq *devfreq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/devfreq.c (ffffffff819cdca0)
Location: drivers/devfreq/devfreq.c:177
Inline: False
Direct callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
**Symbols:**

```
ffffffff819cdca0-ffffffff819cddae: set_freq_table (STB_LOCAL)
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
In drivers/devfreq/devfreq.c (ffffffff819b51e3)
Location: drivers/devfreq/devfreq.c:178
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81a63d53)
Location: drivers/devfreq/devfreq.c:178
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81bd4acf)
Location: drivers/devfreq/devfreq.c:179
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81d80c78)
Location: drivers/devfreq/devfreq.c:179
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81def028)
Location: drivers/devfreq/devfreq.c:179
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81ea55db)
Location: drivers/devfreq/devfreq.c:179
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffff800010b860ec)
Location: drivers/devfreq/devfreq.c:117
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (c0c69164)
Location: drivers/devfreq/devfreq.c:117
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (c000000000c64d9c)
Location: drivers/devfreq/devfreq.c:117
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffe00072f58e)
Location: drivers/devfreq/devfreq.c:117
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff8189ada3)
Location: drivers/devfreq/devfreq.c:117
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff81858273)
Location: drivers/devfreq/devfreq.c:117
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff818ea493)
Location: drivers/devfreq/devfreq.c:117
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
In drivers/devfreq/devfreq.c (ffffffff8190b513)
Location: drivers/devfreq/devfreq.c:117
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
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
