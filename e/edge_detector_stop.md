# Function: <code>edge_detector_stop</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163a8a0)
Location: drivers/gpio/gpiolib-cdev.c:769
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
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
In drivers/gpio/gpiolib-cdev.c (ffffffff8161e430)
Location: drivers/gpio/gpiolib-cdev.c:769
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
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
In drivers/gpio/gpiolib-cdev.c (ffffffff8168d9f0)
Location: drivers/gpio/gpiolib-cdev.c:769
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void edge_detector_stop(struct line *line, bool hte_en);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817abf70)
Location: drivers/gpio/gpiolib-cdev.c:933
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff817abf70-ffffffff817abfe7: edge_detector_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void edge_detector_stop(struct line *line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4970)
Location: drivers/gpio/gpiolib-cdev.c:1004
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff818c4970-ffffffff818c49ed: edge_detector_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void edge_detector_stop(struct line *line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81907a40)
Location: drivers/gpio/gpiolib-cdev.c:1003
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config_unlocked
```
**Symbols:**

```
ffffffff81907a40-ffffffff81907abd: edge_detector_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void edge_detector_stop(struct line *line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f270)
Location: drivers/gpio/gpiolib-cdev.c:1092
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_free
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
```
**Symbols:**

```
ffffffff8194f270-ffffffff8194f2e8: edge_detector_stop (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool hte_en</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
