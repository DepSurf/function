# Function: <code>nvm_bb_to_chunk</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8169999d)
Location: drivers/lightnvm/core.c:930
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffff816d2546)
Location: drivers/lightnvm/core.c:932
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffff816f6426)
Location: drivers/lightnvm/core.c:962
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffff817ae9f0)
Location: drivers/lightnvm/core.c:961
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffffffff817ae9f0-ffffffff817aebac: nvm_bb_to_chunk.constprop.0 (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff817c3570)
Location: drivers/lightnvm/core.c:956
Inline: True
Direct callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
**Symbols:**

```
ffffffff817c3570-ffffffff817c372c: nvm_bb_to_chunk.constprop.0 (STB_LOCAL)
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
In drivers/lightnvm/core.c (ffffffff817a6f92)
Location: drivers/lightnvm/core.c:956
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108dfb50)
Location: drivers/lightnvm/core.c:962
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (c09ced9c)
Location: drivers/lightnvm/core.c:962
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (c000000000973b50)
Location: drivers/lightnvm/core.c:962
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffe000575b64)
Location: drivers/lightnvm/core.c:962
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffff816bbc16)
Location: drivers/lightnvm/core.c:962
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816ea0e6)
Location: drivers/lightnvm/core.c:962
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
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
In drivers/lightnvm/core.c (ffffffff81704926)
Location: drivers/lightnvm/core.c:962
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_get_bb_meta
```
</details>
</li>
</ul>

## Differences
