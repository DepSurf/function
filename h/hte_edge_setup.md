# Function: <code>hte_edge_setup</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hte_edge_setup(struct line *line, u64 eflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff817ac110)
Location: drivers/gpio/gpiolib-cdev.c:833
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff817ac110-ffffffff817ac1d2: hte_edge_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hte_edge_setup(struct line *line, u64 eflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c50b0)
Location: drivers/gpio/gpiolib-cdev.c:734
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff818c50b0-ffffffff818c5172: hte_edge_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hte_edge_setup(struct line *line, u64 eflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff81908180)
Location: drivers/gpio/gpiolib-cdev.c:733
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff81908180-ffffffff81908242: hte_edge_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hte_edge_setup(struct line *line, u64 eflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f990)
Location: drivers/gpio/gpiolib-cdev.c:822
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
  - drivers/gpio/gpiolib-cdev.c:edge_detector_setup
```
**Symbols:**

```
ffffffff8194f990-ffffffff8194fa53: hte_edge_setup (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
