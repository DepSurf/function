# Function: <code>__store_smt_control</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109de65)
Location: kernel/cpu.c:2128
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
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
In kernel/cpu.c (ffffffff810a43b5)
Location: kernel/cpu.c:2144
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
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
In kernel/cpu.c (ffffffff810ab660)
Location: kernel/cpu.c:2275
Inline: True
Direct callers:
  - kernel/cpu.c:store_smt_control
```
**Symbols:**

```
ffffffff810ab660-ffffffff810ab74d: __store_smt_control.constprop.0 (STB_LOCAL)
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
In kernel/cpu.c (ffffffff810a6ee0)
Location: kernel/cpu.c:2286
Inline: True
Direct callers:
  - kernel/cpu.c:store_smt_control
```
**Symbols:**

```
ffffffff810a6ee0-ffffffff810a6fcd: __store_smt_control.constprop.0 (STB_LOCAL)
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
In kernel/cpu.c (ffffffff810a7fc1)
Location: kernel/cpu.c:2403
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
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
In kernel/cpu.c (ffffffff810b9a71)
Location: kernel/cpu.c:2431
Inline: True
Inline callers:
  - kernel/cpu.c:control_store
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
In kernel/cpu.c (ffffffff810d04fd)
Location: kernel/cpu.c:2453
Inline: True
Inline callers:
  - kernel/cpu.c:control_store
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
In kernel/cpu.c (ffffffff810eed9d)
Location: kernel/cpu.c:2479
Inline: True
Inline callers:
  - kernel/cpu.c:control_store
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
In kernel/cpu.c (ffffffff810fad4d)
Location: kernel/cpu.c:2864
Inline: True
Inline callers:
  - kernel/cpu.c:control_store
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
In kernel/cpu.c (ffffffff8110416f)
Location: kernel/cpu.c:2925
Inline: True
Inline callers:
  - kernel/cpu.c:control_store
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
In kernel/cpu.c (0)
Location: kernel/cpu.c:2186
Inline: True
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
In kernel/cpu.c (0)
Location: kernel/cpu.c:2186
Inline: True
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
In kernel/cpu.c (0)
Location: kernel/cpu.c:2186
Inline: True
```
</details>
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
In kernel/cpu.c (ffffffff8109dcd5)
Location: kernel/cpu.c:2144
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
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
In kernel/cpu.c (ffffffff8108c6f5)
Location: kernel/cpu.c:2144
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
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
In kernel/cpu.c (ffffffff8109dc85)
Location: kernel/cpu.c:2144
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
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
In kernel/cpu.c (ffffffff810a5b75)
Location: kernel/cpu.c:2144
Inline: True
Inline callers:
  - kernel/cpu.c:store_smt_control
```
</details>
</li>
</ul>

## Differences
